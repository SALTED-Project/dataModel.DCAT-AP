<!-- 10-Header -->  
[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  
エンティティデータセット  
============<!-- /10-Header -->  
<!-- 15-License -->  
[オープンライセンス](https://github.com/smart-data-models//dataModel.DCAT-AP/blob/master/Dataset/LICENSE.md)  
[文書が自動的に生成されます](https://docs.google.com/presentation/d/e/2PACX-1vTs-Ng5dIAwkg91oTTUdt8ua7woBXhPnwavZ0FxgR8BsAI_Ek3C5q97Nd94HS8KhP-r_quD4H0fgyt3/pub?start=false&loop=false&delayms=3000#slide=id.gb715ace035_0_60)  
<!-- /15-License -->  
<!-- 20-Description -->  
グローバルな記述です：**DCAT-AP 2.0 仕様に準拠したデータセットスキーマ**。  
バージョン：0.0.2  
<!-- /20-Description -->  
<!-- 30-PropertiesList -->  

## プロパティ一覧  

<sup><sub>[*] 属性に型がない場合は、複数の型や異なるフォーマット/パターンを持つ可能性があるためです</sub></sup>。  
- `accessRights[string]`: プロパティです。モデル:'foaf:Agent'.このプロパティは、Datasetがオープンデータであるか、アクセス制限があるか、非公開であるかを示す情報を指す。3つのメンバー（:public, :restricted, :non-public）を持つ統制語彙が、EUの出版局によって作成・維持される予定です。列挙：'public, restricted, non-public'  . Model: [foaf:Agent](foaf:Agent)- `alternateName[string]`: このアイテムの別称  - `conformsTo[string]`: プロパティです。Model:'dct:conformsTo'.このプロパティは、実装規則または他の仕様を参照する。  . Model: [dct:conformsTo](dct:conformsTo)- `contactPoint[array]`: プロパティです。モデル：'vcard:Kind'。DCAT-AP 2.0.1の'contact point'必須プロパティに対応する。このプロパティには、データセットに関するコメントを送信するために使用できる連絡先情報が含まれています。  . Model: [vcard:Kind](vcard:Kind)- `creator[string]`: プロパティです。モデル：'dct:creator'.このプロパティは、カタログの制作を主に担当するエンティティを指す  . Model: [dct:creator](dct:creator)- `dataProvider[string]`: 調和されたデータエンティティの提供者を識別する一連の文字。  - `datasetDescription[array]`: プロパティです。このプロパティには、データセットのフリーテキストによる説明が含まれる。DCAT-AP 2.0.1の'description'必須プロパティと対応している。このプロパティは、説明文の並行言語版のために繰り返すことができる。  - `datasetDistribution[array]`: プロパティです。このプロパティは、データセットと利用可能なディストリビューションを結びつける。DCAT-AP 2.0.1の'dataset distribution'必須プロパティに対応する。モデル：'dcat:distribution'  . Model: [dcat:distribution](dcat:distribution)- `datasetSource[array]`: プロパティです。モデル：'rdfs:Resource'。DCAT-AP 2.0.1のプロパティ'source'と対応する。このプロパティは、記述されたDatasetが由来する関連Datasetを指す。  . Model: [rdfs:Resource](rdfs:Resource)- `datasetType[string]`: プロパティです。モデル：'dct:type'.このプロパティは、データセットのタイプを示す。DCAT 2.0.1のプロパティ'Type'に相当する。値の制御語彙は確立されていない。  . Model: [dct:type](dct:type)- `dateCreated[string]`: エンティティの作成タイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  - `dateModified[string]`: エンティティの最終更新のタイムスタンプ。これは通常、ストレージプラットフォームによって割り当てられる。  - `description[string]`: このアイテムの説明  - `documentation[array]`: プロパティです。モデル:'foaf:Document'.このプロパティは、このデータセットに関するページまたはドキュメントを参照します。  . Model: [foaf:Document](foaf:Document)- `frequency[string]`: プロパティです。モデル：'dct:Frequency'.このプロパティは、Datasetが更新される頻度について言及する。  . Model: [dct:Frequency](dct:Frequency)- `hasVersion[array]`: プロパティです。このプロパティは、説明されているデータセットのバージョン、エディション、または適応である関連データセットを指します。  - `id[*]`: エンティティの一意な識別子  - `identifier[array]`: プロパティです。Model:'dct:identifier'.このプロパティには、データセットの主な識別子（例：カタログのコンテキストにおけるURIまたはその他の一意の識別子）が含まれます。  . Model: [dct:identifier](dct:identifier)- `isReferencedBy[array]`: プロパティです。Model:'dct:isVersionOf'.このプロパティは、記述されたDatasetがバージョン、エディション、またはアダプテーションである関連Datasetを参照する。  . Model: [dct:isVersionOf](dct:isVersionOf)- `isVersionOf[array]`: プロパティです。Model:'dct:identifier'.このプロパティには、データセットの主な識別子（例：カタログのコンテキストにおけるURIまたはその他の一意の識別子）が含まれます。  . Model: [dct:identifier](dct:identifier)- `keyword[array]`: Property（プロパティ）。このプロパティには、データセットを説明するキーワードまたはタグが含まれます。モデル:'dcat:keyword'  . Model: [dcat:keyword](dcat:keyword)- `landingPage[array]`: プロパティです。Model:'dcat:landingPage'.このプロパティは、データセット、その配布物、および追加情報へのアクセスを提供するウェブページを指します。このプロパティは、アグリゲーターなどの第三者のサイト上のページではなく、元のデータ提供者のランディングページを指すことを意図しています。  . Model: [dcat:landingPage](dcat:landingPage)- `language[array]`: プロパティです。Model:'dct:LinguisticSystem'といいます。このプロパティは、Datasetの言語を参照します。データセットに複数の言語がある場合は、このプロパティを繰り返すことができます。  . Model: [dct:LinguisticSystem](dct:LinguisticSystem)- `name[string]`: この項目の名称です。  - `otherIdentifier[array]`: プロパティです。Model:'dct:identifier'.このプロパティは、MAST/ADS、DataCite、DOI、EZID、W3IDなど、データセットの二次識別子を指します。  . Model: [dct:identifier](dct:identifier)- `owner[array]`: 所有者の固有IDを参照するJSONエンコードされた文字列を含むリストです。  - `provenance[array]`: プロパティです。Model:'dct:ProvenanceStatement'.このプロパティには、Datasetの血統に関するステートメントが含まれます。  . Model: [dct:ProvenanceStatement](dct:ProvenanceStatement)- `publisher[string]`: プロパティです。Model:'foaf:Agent'.このプロパティは、データセットを利用可能にする責任を負うエンティティ（組織）を指す  . Model: [foaf:Agent](foaf:Agent)- `qualifiedAttribution[array]`: プロパティです。モデル:'prov:qualifiedAttribution'.このプロパティは、データセットを参照、引用、またはその他の方法で指し示す、出版物などの関連リソースに関するものです。  . Model: [prov:qualifiedAttribution](prov:qualifiedAttribution)- `qualifiedRelation[array]`: プロパティです。Model:'dcat:Relationship'.このプロパティは、データセットを参照、引用、またはその他の方法で指し示す、出版物などの関連リソースに関するものです  . Model: [dcat:Relationship](dcat:Relationship)- `relatedResource[array]`: プロパティです。モデル:'rdfs:Resource'.このプロパティは、関連するリソースを参照する  . Model: [rdfs:Resource](rdfs:Resource)- `releaseDate[string]`: プロパティです。Model:'dct:issued'.このプロパティには、Datasetの正式な発行（例：Publish）日が含まれます。  . Model: [dct:issued](dct:issued)- `sample[array]`: プロパティです。モデル:'rdfs:Resource'.このプロパティは、データセットのサンプル配布を指す  . Model: [rdfs:Resource](rdfs:Resource)- `seeAlso[*]`: アイテムに関する追加リソースを指す URI のリスト。  - `source[string]`: エンティティデータの元のソースをURLとして与える一連の文字。ソースプロバイダの完全修飾ドメイン名、またはソースオブジェクトのURLであることが推奨されます。  - `spatial[array]`: ジオプロパティです。モデル:'dct:Location'.このプロパティは、Datasetがカバーする地理的な領域を指す  . Model: [dct:Location](dct:Location)- `spatialResolution[array]`: プロパティです。Model:'dcat:spatialResolutionIn Meters'.このプロパティは、データセットで解決可能な最小の空間的分離を指し、メートル単位で測定される  . Model: [dcat:spatialResolutionIn Meters](dcat:spatialResolutionIn Meters)- `temporal[array]`: プロパティ。このプロパティは、Datasetがカバーする時間的な期間を指す。モデル:'dct:PeriodOfTime'  . Model: [dct:PeriodOfTime](dct:PeriodOfTime)- `temporalResolution[array]`: プロパティです。モデル：'dcat:temporalResolution'.このプロパティは、データセットで解決可能な最小時間帯を指す。  . Model: [dcat:temporalResolution](dcat:temporalResolution)- `theme[array]`: プロパティです。モデル：'dcat:theme'.このプロパティは、Datasetのカテゴリを参照します。データセットは、複数のテーマと関連付けることができます。  . Model: [dcat:theme](dcat:theme)- `title[array]`: プロパティです。このプロパティには、データセットに付けられた名前が含まれる。DCAT-AP 2.0.1の'Title'必須プロパティに対応する。このプロパティは、名前の並行言語バージョンに対して繰り返すことができる。  - `type[string]`: 特性です。NGSIタイプです。Datasetでなければならない  - `updateDate[string]`: プロパティです。Model:'dct:modified'.このプロパティには、Datasetが変更または修正された最新の日付が含まれます。  . Model: [dct:modified](dct:modified)- `version[string]`: プロパティです。モデル:'owl:versionInfo'.このプロパティには、データセットのバージョン番号または他のバージョン指定が含まれる  . Model: [owl:versionInfo](owl:versionInfo)- `versionNotes[array]`: プロパティです。Model:'adms:versionNotes'.このプロパティには、このバージョンとデータセットの以前のバージョンとの相違点の説明が含まれる。このプロパティは、バージョンノートの並行言語バージョンに対して繰り返すことができる。  . Model: [adms:versionNotes](adms:versionNotes)- `wasGeneratedBy[array]`: プロパティです。Model:'prov:wasGeneratedBy'です。このプロパティには、このバージョンとデータセットの以前のバージョンとの相違点の説明が含まれる。このプロパティは、バージョンノートの並行言語版のために繰り返すことができます。  . Model: [prov:wasGeneratedBy](prov:wasGeneratedBy)<!-- /30-PropertiesList -->  
<!-- 35-RequiredProperties -->  
必須プロパティ  
- `datasetDescription`  - `id`  - `title`  - `type`  <!-- /35-RequiredProperties -->  
<!-- 40-RequiredProperties -->  
Adapted from [DCAT-AP version 2.0.1](https://joinup.ec.europa.eu/sites/default/files/distribution/access_url/2020-06/e4823478-4458-4546-9a85-3609867ad089/DCAT_AP_2.0.1.pdf).  
<!-- /40-RequiredProperties -->  
<!-- 50-DataModelHeader -->  
## プロパティのデータモデル記述  
アルファベット順（クリックで詳細表示）  
<!-- /50-DataModelHeader -->  
<!-- 60-ModelYaml -->  
<details><summary><strong>full yaml details</strong></summary>    
```yaml  
Dataset:    
  description: Dataset Schema meeting DCAT-AP 2.0 specification    
  properties:    
    accessRights:    
      description: 'Property. Model:''foaf:Agent''. This property refers to information that indicates whether the Dataset is open data, has access restrictions or is not public. A controlled vocabulary with three members (:public, :restricted, :non-public) will be created and maintained by the Publications Office of the EU. Enum:''public, restricted, non-public'''    
      enum:    
        - public    
        - restricted    
        - non-public    
      type: string    
      x-ngsi:    
        model: foaf:Agent    
        type: Property    
    alternateName:    
      description: An alternative name for this item    
      type: string    
      x-ngsi:    
        type: Property    
    conformsTo:    
      description: 'Property. Model:''dct:conformsTo''. This property refers to an implementing rule nor other specification.'    
      type: string    
      x-ngsi:    
        model: dct:conformsTo    
        type: Property    
    contactPoint:    
      description: 'Property. Model:''vcard:Kind''. It corresponds with the ''contact point'' mandatory property of DCAT-AP 2.0.1. This property contains contact information that can be used for sending comments about the Dataset.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: vcard:Kind    
        type: Property    
    creator:    
      description: 'Property. Model:''dct:creator''. This property refers to the entity primarily responsible for producing the catalogue'    
      type: string    
      x-ngsi:    
        model: dct:creator    
        type: Property    
    dataProvider:    
      description: A sequence of characters identifying the provider of the harmonised data entity.    
      type: string    
      x-ngsi:    
        type: Property    
    datasetDescription:    
      description: Property. This property contains a free-text account of the Dataset. It corresponds with the 'description' mandatory property of DCAT-AP 2.0.1. This property can be repeated for parallel language versions of the description.    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
    datasetDistribution:    
      description: 'Property. This property links the Dataset to an available Distributions. It corresponds with the ''dataset distribution'' mandatory property of DCAT-AP 2.0.1. Model:''dcat:distribution'''    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:distribution    
        type: Property    
    datasetSource:    
      description: 'Property. Model:''rdfs:Resource''. It corresponds with the property ''source'' from DCAT-AP 2.0.1. This property refers to a related Dataset from which the described Dataset is derived.'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: rdfs:Resource    
        type: Property    
    datasetType:    
      description: 'Property. Model:''dct:type''. This property refers to the type of the Dataset. It corresponds to the property ''Type'' of the DCAT 2.0.1. A controlled vocabulary for the values has not been established.'    
      type: string    
      x-ngsi:    
        model: dct:type    
        type: Property    
    dateCreated:    
      description: Entity creation timestamp. This will usually be allocated by the storage platform.    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    dateModified:    
      description: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.    
      format: date-time    
      type: string    
      x-ngsi:    
        type: Property    
    description:    
      description: A description of this item    
      type: string    
      x-ngsi:    
        type: Property    
    documentation:    
      description: 'Property. Model:''foaf:Document''. This property refers to a page or document about this Dataset'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: foaf:Document    
        type: Property    
    frequency:    
      description: 'Property. Model:''dct:Frequency''. This property refers to the frequency at which the Dataset is updated.'    
      type: string    
      x-ngsi:    
        model: dct:Frequency    
        type: Property    
    hasVersion:    
      description: 'Property. This property refers to a related Dataset that is a version, edition, or adaptation of the described Dataset.'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
    id:    
      anyOf: &dataset_-_properties_-_owner_-_items_-_anyof    
        - description: Property. Identifier format of any NGSI entity    
          maxLength: 256    
          minLength: 1    
          pattern: ^[\w\-\.\{\}\$\+\*\[\]`|~^@!,:\\]+$    
          type: string    
        - description: Property. Identifier format of any NGSI entity    
          format: uri    
          type: string    
      description: Unique identifier of the entity    
      x-ngsi:    
        type: Property    
    identifier:    
      description: 'Property. Model:''dct:identifier''. This property contains the main identifier for the Dataset, e.g. the URI or other unique identifier in the context of the Catalogue'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:identifier    
        type: Property    
    isReferencedBy:    
      description: 'Property. Model:''dct:isVersionOf''. This property refers to a related Dataset of which the described Dataset is a version, edition, or adaptation'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:isVersionOf    
        type: Property    
    isVersionOf:    
      description: 'Property. Model:''dct:identifier''. This property contains the main identifier for the Dataset, e.g. the URI or other unique identifier in the context of the Catalogue'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:identifier    
        type: Property    
    keyword:    
      description: 'Property. This property contains a keyword or tag, describing the Dataset. Model:''dcat:keyword'''    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:keyword    
        type: Property    
    landingPage:    
      description: 'Property. Model:''dcat:landingPage''. This property refers to a web page that provides access to the Dataset, its Distributions and/or additional information. It is intended to point to a landing page at the original data provider, not to a page on a site of a third party, such as an aggregator.'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:landingPage    
        type: Property    
    language:    
      description: 'Property. Model:''dct:LinguisticSystem''. This property refers to a language of the Dataset. This property can be repeated if there are multiple languages in the Dataset.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:LinguisticSystem    
        type: Property    
    name:    
      description: The name of this item.    
      type: string    
      x-ngsi:    
        type: Property    
    otherIdentifier:    
      description: 'Property. Model:''dct:identifier''. This property refers to a secondary identifier of the Dataset, such as MAST/ADS, DataCite, DOI, EZID or W3ID.'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:identifier    
        type: Property    
    owner:    
      description: A List containing a JSON encoded sequence of characters referencing the unique Ids of the owner(s)    
      items:    
        anyOf: *dataset_-_properties_-_owner_-_items_-_anyof    
        description: Property. Unique identifier of the entity    
      type: array    
      x-ngsi:    
        type: Property    
    provenance:    
      description: 'Property. Model:''dct:ProvenanceStatement''. This property contains a statement about the lineage of a Dataset.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:ProvenanceStatement    
        type: Property    
    publisher:    
      description: 'Property. Model:''foaf:Agent''. This property refers to an entity (organisation) responsible for making the Dataset available'    
      type: string    
      x-ngsi:    
        model: foaf:Agent    
        type: Property    
    qualifiedAttribution:    
      description: 'Property. Model:''prov:qualifiedAttribution''. This property is about a related resource, such as a publication, that references, cites, or otherwise points to the dataset.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: prov:qualifiedAttribution    
        type: Property    
    qualifiedRelation:    
      description: 'Property. Model:''dcat:Relationship''. This property is about a related resource, such as a publication, that references, cites, or otherwise points to the dataset'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:Relationship    
        type: Property    
    relatedResource:    
      description: 'Property. Model:''rdfs:Resource''. This property refers to a related resource'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: rdfs:Resource    
        type: Property    
    releaseDate:    
      description: 'Property. Model:''dct:issued''. This property contains the date of formal issuance (e.g., publication) of the Dataset.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: dct:issued    
        type: Property    
    sample:    
      description: 'Property. Model:''rdfs:Resource''. This property refers to a sample distribution of the dataset'    
      items:    
        format: uri    
        type: string    
      type: array    
      x-ngsi:    
        model: rdfs:Resource    
        type: Property    
    seeAlso:    
      description: list of uri pointing to additional resources about the item    
      oneOf:    
        - items:    
            format: uri    
            type: string    
          minItems: 1    
          type: array    
        - format: uri    
          type: string    
      x-ngsi:    
        type: Property    
    source:    
      description: 'A sequence of characters giving the original source of the entity data as a URL. Recommended to be the fully qualified domain name of the source provider, or the URL to the source object.'    
      type: string    
      x-ngsi:    
        type: Property    
    spatial:    
      description: 'Geoproperty. Model:''dct:Location''. This property refers to a geographic region that is covered by the Dataset'    
      items:    
        description: 'GeoProperty. Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon'    
        oneOf:    
          - description: GeoProperty. Geojson reference to the item. Point    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  type: number    
                minItems: 2    
                type: array    
              type:    
                enum:    
                  - Point    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON Point    
            type: object    
          - description: GeoProperty. Geojson reference to the item. LineString    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                minItems: 2    
                type: array    
              type:    
                enum:    
                  - LineString    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON LineString    
            type: object    
          - description: GeoProperty. Geojson reference to the item. Polygon    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 4    
                  type: array    
                type: array    
              type:    
                enum:    
                  - Polygon    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON Polygon    
            type: object    
          - description: GeoProperty. Geojson reference to the item. MultiPoint    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  items:    
                    type: number    
                  minItems: 2    
                  type: array    
                type: array    
              type:    
                enum:    
                  - MultiPoint    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON MultiPoint    
            type: object    
          - description: GeoProperty. Geojson reference to the item. MultiLineString    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  items:    
                    items:    
                      type: number    
                    minItems: 2    
                    type: array    
                  minItems: 2    
                  type: array    
                type: array    
              type:    
                enum:    
                  - MultiLineString    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON MultiLineString    
            type: object    
          - description: GeoProperty. Geojson reference to the item. MultiLineString    
            properties:    
              bbox:    
                items:    
                  type: number    
                minItems: 4    
                type: array    
              coordinates:    
                items:    
                  items:    
                    items:    
                      items:    
                        type: number    
                      minItems: 2    
                      type: array    
                    minItems: 4    
                    type: array    
                  type: array    
                type: array    
              type:    
                enum:    
                  - MultiPolygon    
                type: string    
            required:    
              - type    
              - coordinates    
            title: GeoJSON MultiPolygon    
            type: object    
      type: array    
      x-ngsi:    
        model: dct:Location    
    spatialResolution:    
      description: 'Property. Model:''dcat:spatialResolutionIn Meters''. This property refers to the minimum spatial separation resolvable in a dataset, measured in meters'    
      items:    
        type: number    
      type: array    
      x-ngsi:    
        model: 'dcat:spatialResolutionIn Meters'    
        type: Property    
    temporal:    
      description: 'Property. This property refers to a temporal period that the Dataset covers. Model:''dct:PeriodOfTime'''    
      items:    
        format: date-time    
        type: string    
      type: array    
      x-ngsi:    
        model: dct:PeriodOfTime    
        type: Property    
    temporalResolution:    
      description: 'Property. Model:''dcat:temporalResolution''. This property refers to the minimum time period resolvable in the dataset.'    
      items:    
        type: number    
      type: array    
      x-ngsi:    
        model: dcat:temporalResolution    
        type: Property    
    theme:    
      description: 'Property. Model:''dcat:theme''. This property refers to a category of the Dataset. A Dataset may be associated with multiple themes'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: dcat:theme    
        type: Property    
    title:    
      description: Property. This property contains a name given to the Dataset. It corresponds with the 'Title' mandatory property of DCAT-AP 2.0.1. This property can be repeated for parallel language versions of the name.    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        type: Property    
    type:    
      description: Property. NGSI type. It has to be Dataset    
      enum:    
        - Dataset    
      type: string    
      x-ngsi:    
        type: Property    
    updateDate:    
      description: 'Property. Model:''dct:modified''. This property contains the most recent date on which the Dataset was changed or modified.'    
      format: date-time    
      type: string    
      x-ngsi:    
        model: dct:modified    
        type: Property    
    version:    
      description: 'Property. Model:''owl:versionInfo''. This property contains a version number or other version designation of the Dataset'    
      type: string    
      x-ngsi:    
        model: owl:versionInfo    
        type: Property    
    versionNotes:    
      description: 'Property. Model:''adms:versionNotes''. This property contains a description of the differences between this version and a previous version of the Dataset. This property can be repeated for parallel language versions of the version notes.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: adms:versionNotes    
        type: Property    
    wasGeneratedBy:    
      description: 'Property. Model:''prov:wasGeneratedBy''. This property contains a description of the differences between this version and a previous version of the Dataset. This property can be repeated for parallel language versions of the version notes.'    
      items:    
        type: string    
      type: array    
      x-ngsi:    
        model: prov:wasGeneratedBy    
        type: Property    
  required:    
    - id    
    - type    
    - datasetDescription    
    - title    
  type: object    
  x-derived-from: ""    
  x-disclaimer: 'Redistribution and use in source and binary forms, with or without modification, are permitted  provided that the license conditions are met. Copyleft (c) 2022 Contributors to Smart Data Models Program'    
  x-license-url: https://github.com/smart-data-models/dataModel.DCAT-AP/blob/master/Dataset/LICENSE.md    
  x-model-schema: https://github.com/smart-data-models/dataModel.DCAT-AP/blob/master/Dataset/schema.json    
  x-model-tags: ""    
  x-version: 0.0.2    
```  
</details>    
<!-- /60-ModelYaml -->  
<!-- 70-MiddleNotes -->  
<!-- /70-MiddleNotes -->  
<!-- 80-Examples -->  
## ペイロードの例  
#### データセット NGSI-v2 キー値 例  
ここでは、DatasetをJSON-LD形式でkey-valuesとした例を示す。これは、`options=keyValues`を使用した場合にNGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Dataset:id:VESI:23278568",  
  "dateCreated": "1985-07-20T10:08:50Z",  
  "dateModified": "2015-07-13T03:09:32Z",  
  "source": "urn:ngsi-ld:Dataset:items:YSWN:41266715",  
  "name": "First table field check. Agency writer size. Meeting nice nothing after ever.",  
  "alternateName": "Apply popular what suddenly environmental at system. Situation son future example task. Machine year positive security better.",  
  "description": "Own fast suffer your. Spend per police. Less skill much run letter shoulder know office. Discuss of director enter process world possible out.",  
  "dataProvider": "Investment five beat become resource individual assume. Yard seat memory bed forget heart crime.",  
  "owner": [  
    "urn:ngsi-ld:Dataset:items:QZHN:39684072",  
    "urn:ngsi-ld:Dataset:items:LADQ:07842317"  
  ],  
  "seeAlso": [  
    "urn:ngsi-ld:Dataset:items:JGFW:76050330",  
    "urn:ngsi-ld:Dataset:items:XUMS:21710022"  
  ],  
  "type": "Dataset",  
  "datasetDescription": [  
    "Sit worry pay during TV increase family. Social drop organization method. Fact treatment throw detail.",  
    "Experience similar officer social us item lay prepare. Price year close better."  
  ],  
  "title": [  
    "Class skill deal there no language himself. After rule mouth tell economy risk. Glass personal person center.",  
    "Air step occur crime. Fear read scientist vote light. Phone sign what lot garden century big."  
  ],  
  "contactPoint": [  
    "Minute write his experience similar right.",  
    "Experience away remain."  
  ],  
  "datasetDistribution": [  
    "urn:ngsi-ld:Dataset:items:KJVK:30944451",  
    "urn:ngsi-ld:Dataset:items:MMWU:84196227"  
  ],  
  "keyword": [  
    "Free analysis reduce. Owner Republican institution six science a usually. Value land executive design.",  
    "Bag recently might far plan nearly scene example. Trouble official dream author job claim join different. Success full debate here check attorney size."  
  ],  
  "publisher": "Statement which consumer product thought total. Nothing concern picture involve paper nor kid.",  
  "spatial": [  
    {  
      "type": "Point",  
      "coordinates": [  
        9.922458,  
        109.478534  
      ]  
    }  
  ],  
  "temporal": [  
    "2017-04-03T02:35:57Z",  
    "1978-06-15T04:39:05Z"  
  ],  
  "theme": [  
    "Win catch job number find number. Leader reason top arrive night. Movement expect security high hair whom three yeah.",  
    "Respond character continue gun. Grow best choice group manage over find."  
  ],  
  "accessRights": "non-public",  
  "creator": "Wall true factor several nothing. Mission want kind design. Who cause health father director either cause.",  
  "documentation": [  
    "urn:ngsi-ld:Dataset:items:EDTJ:28919577",  
    "urn:ngsi-ld:Dataset:items:GKJO:30040605"  
  ],  
  "frequency": "Case fine feel that. Government executive issue police chance believe.",  
  "hasVersion": [  
    "urn:ngsi-ld:Dataset:items:SQSB:90831182",  
    "urn:ngsi-ld:Dataset:items:FFVZ:69502935"  
  ],  
  "identifier": [  
    "urn:ngsi-ld:Dataset:items:MBNQ:57176010",  
    "urn:ngsi-ld:Dataset:items:DDDJ:93242038"  
  ],  
  "isReferencedBy": [  
    "urn:ngsi-ld:Dataset:items:YQRP:33454193",  
    "urn:ngsi-ld:Dataset:items:RBND:48628164"  
  ],  
  "isVersionOf": [  
    "urn:ngsi-ld:Dataset:items:AMAC:16896252",  
    "urn:ngsi-ld:Dataset:items:IPSO:04920226"  
  ],  
  "landingPage": [  
    "urn:ngsi-ld:Dataset:items:UMBA:72418275",  
    "urn:ngsi-ld:Dataset:items:GUKW:86586813"  
  ],  
  "language": [  
    "Environment site ability night player. Head able American example call again.",  
    "Receive my risk leave matter prepare. Worker admit draw others remember establish necessary one."  
  ],  
  "otherIdentifier": [  
    "urn:ngsi-ld:Dataset:items:ZNYR:18053145",  
    "urn:ngsi-ld:Dataset:items:ICBO:96194869"  
  ],  
  "provenance": [  
    "Air success movie nation attention. Fight do natural brother street.",  
    "Future against sing especially answer sea. Difference effect company."  
  ],  
  "qualifiedAttribution": [  
    "Central born manage evidence data. Answer doctor visit ready physical fact. Quite allow however certain lose heart.",  
    "Home interesting range ever. Magazine the instead particularly. Late have collection."  
  ],  
  "qualifiedRelation": [  
    "urn:ngsi-ld:Dataset:items:ITFK:67369057",  
    "urn:ngsi-ld:Dataset:items:ZJWX:10596189"  
  ],  
  "relatedResource": [  
    "urn:ngsi-ld:Dataset:items:FXEY:35067714",  
    "urn:ngsi-ld:Dataset:items:YYOL:47950545"  
  ],  
  "releaseDate": "1983-07-16T12:51:26Z",  
  "sample": [  
    "urn:ngsi-ld:Dataset:items:QJPZ:50290394",  
    "urn:ngsi-ld:Dataset:items:ZSSA:73451152"  
  ],  
  "spatialResolution": [  
    864.6,  
    864.6  
  ],  
  "temporalResolution": [  
    864.6,  
    864.6  
  ],  
  "datasetType": "Else memory if. Whose group through despite cause. Sense peace economy travel.",  
  "updateDate": "2017-12-27T03:37:52Z",  
  "version": "Financial role together range. Nice government first policy daughter need kind. Employee source nature add rest human station. Ability management test during foot that course nothing.",  
  "versionNotes": [  
    "Sort language ball floor. Your majority feeling fact by four two.",  
    "Natural explain before something first drug contain start. Party prevent live."  
  ],  
  "wasGeneratedBy": [  
    "Theory type successful together. Raise study modern miss dog Democrat quickly.",  
    "Every manage political record word group food break. Picture suddenly drug rule bring determine some forward. Beyond chair recently and."  
  ]  
}  
```  
</details>  
#### データセット NGSI-v2 正規化例  
JSON-LD形式のDatasetを正規化した例を示します。これは、オプションを使用しない場合、NGSI-v2と互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
  "id": "urn:ngsi-ld:Dataset:id:HUZY:68185655",  
  "type": "Dataset",  
  "dateCreated": {  
    "type": "DateTime",  
    "value": "2021-07-01T10:27:49Z"  
  },  
  "dateModified": {  
    "type": "DateTime",  
    "value": "2021-07-01T10:27:59Z"  
  },  
  "source": {  
    "type": "Text",  
    "value": ""  
  },  
  "name": {  
    "type": "Text",  
    "value": "list of open data portals by MELODA.org project"  
  },  
  "alternateName": {  
    "type": "Text",  
    "value": ""  
  },  
  "description": {  
    "type": "Text",  
    "value": "Analysis based on actual review of the features of the open data portals"  
  },  
  "dataProvider": {  
    "type": "Text",  
    "value": "meloda.org"  
  },  
  "owner": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:UHNW:18835438",  
      "urn:ngsi-ld:Dataset:items:JIFN:75588835"  
    ]  
  },  
  "seeAlso": {  
    "type": "array",  
    "value": [  
      "https://meloda.org"  
    ]  
  },  
  "datasetDescription": {  
    "type": "array",  
    "value": [  
      "List of open data portals",  
      "Listado de portales open data"  
    ]  
  },  
  "title": {  
    "type": "array",  
    "value": [  
      "Open Data list",  
      "Lista open data"  
    ]  
  },  
  "contactPoint": {  
    "type": "array",  
    "value": [  
      ""  
    ]  
  },  
  "datasetDistribution": {  
    "type": "array",  
    "value": [  
      ""  
    ]  
  },  
  "keyword": {  
    "type": "array",  
    "value": [  
      "opendata",  
      "portal"  
    ]  
  },  
  "publisher": {  
    "type": "Text",  
    "value": "urjc"  
  },  
  "spatial": {  
    "type": "geo:json",  
    "value": {  
      "type": "Point",  
      "coordinates": [  
        22.1394715,  
        -7.100602  
      ]  
    }  
  },  
  "temporal": {  
    "type": "array",  
    "value": [  
      "2021-01-01T00:00:00Z",  
      "2021-12-31T23:59:59Z"  
    ]  
  },  
  "theme": {  
    "type": "array",  
    "value": [  
      "data management",  
      "open data"  
    ]  
  },  
  "accessRights": {  
    "type": "Text",  
    "value": "public"  
  },  
  "creator": {  
    "type": "Text",  
    "value": "Diego Garcia, Marta Ortiz de Urbina, Carmen de Pablos"  
  },  
  "documentation": {  
    "type": "array",  
    "value": [  
      "",  
      ""  
    ]  
  },  
  "frequency": {  
    "type": "array",  
    "value": "two years"  
  },  
  "hasVersion": {  
    "type": "Text",  
    "value": [  
      "",  
      ""  
    ]  
  },  
  "identifier": {  
    "type": "array",  
    "value": [  
      "",  
      ""  
    ]  
  },  
  "isReferencedBy": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:HJNK:88711880",  
      "urn:ngsi-ld:Dataset:items:MDEO:95193079"  
    ]  
  },  
  "isVersionOf": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:RBWE:31388012",  
      "urn:ngsi-ld:Dataset:items:GATZ:02632837"  
    ]  
  },  
  "landingPage": {  
    "type": "array",  
    "value": [  
      "htps://meloda.org"  
    ]  
  },  
  "language": {  
    "type": "array",  
    "value": [  
      "EN",  
      "ES"  
    ]  
  },  
  "otherIdentifier": {  
    "type": "array",  
    "value": [  
      "",  
      ""  
    ]  
  },  
  "provenance": {  
    "type": "array",  
    "value": [  
      "",  
      ""  
    ]  
  },  
  "qualifiedAttribution": {  
    "type": "array",  
    "value": [  
      ""  
    ]  
  },  
  "qualifiedRelation": {  
    "type": "array",  
    "value": [  
      ""  
    ]  
  },  
  "relatedResource": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:LGBY:74926949",  
      "urn:ngsi-ld:Dataset:items:ZAUC:79968579"  
    ]  
  },  
  "releaseDate": {  
    "type": "DateTime",  
    "value": "2021-10-01T15:46:46Z"  
  },  
  "sample": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:MLHW:64299003",  
      "urn:ngsi-ld:Dataset:items:GNXL:59256807"  
    ]  
  },  
  "datasetSource": {  
    "type": "array",  
    "value": [  
      "urn:ngsi-ld:Dataset:items:QTKR:65814062",  
      "urn:ngsi-ld:Dataset:items:SVUY:57639613"  
    ]  
  },  
  "spatialResolution": {  
    "type": "array",  
    "value": [  
      864.6  
    ]  
  },  
  "temporalResolution": {  
    "type": "array",  
    "value": [  
      730  
    ]  
  },  
  "datasetType": {  
    "type": "Text",  
    "value": ""  
  },  
  "updateDate": {  
    "type": "DateTime",  
    "value": "2021-07-01T03:37:52Z"  
  },  
  "version": {  
    "type": "Text",  
    "value": "3.0"  
  },  
  "versionNotes": {  
    "type": "array",  
    "value": [  
      "With temporal evolution"  
    ]  
  },  
  "wasGeneratedBy": {  
    "type": "Text",  
    "value": [  
      "meloda Team"  
    ]  
  }  
}  
```  
</details>  
#### データセット NGSI-LD キー値 例  
ここでは、DatasetをJSON-LD形式でkey-valuesとした例を示します。これは、`options=keyValues`を使用した場合にNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Dataset:id:VESI:23278568",  
    "type": "Dataset",  
    "accessRights": "non-public",  
    "alternateName": "Apply popular what suddenly environmental at system. Situation son future example task. Machine year positive security better.",  
    "contactPoint": [  
        "Minute write his experience similar right.",  
        "Experience away remain."  
    ],  
    "creator": "Wall true factor several nothing. Mission want kind design. Who cause health father director either cause.",  
    "dataProvider": "Investment five beat become resource individual assume. Yard seat memory bed forget heart crime.",  
    "datasetDescription": [  
        "Sit worry pay during TV increase family. Social drop organization method. Fact treatment throw detail.",  
        "Experience similar officer social us item lay prepare. Price year close better."  
    ],  
    "datasetDistribution": [  
        "urn:ngsi-ld:Dataset:items:KJVK:30944451",  
        "urn:ngsi-ld:Dataset:items:MMWU:84196227"  
    ],  
    "datasetType": "Else memory if. Whose group through despite cause. Sense peace economy travel.",  
    "dateCreated": "1985-07-20T10:08:50Z",  
    "dateModified": "2015-07-13T03:09:32Z",  
    "description": "Own fast suffer your. Spend per police. Less skill much run letter shoulder know office. Discuss of director enter process world possible out.",  
    "documentation": [  
        "urn:ngsi-ld:Dataset:items:EDTJ:28919577",  
        "urn:ngsi-ld:Dataset:items:GKJO:30040605"  
    ],  
    "frequency": "Case fine feel that. Government executive issue police chance believe.",  
    "hasVersion": [  
        "urn:ngsi-ld:Dataset:items:SQSB:90831182",  
        "urn:ngsi-ld:Dataset:items:FFVZ:69502935"  
    ],  
    "identifier": [  
        "urn:ngsi-ld:Dataset:items:MBNQ:57176010",  
        "urn:ngsi-ld:Dataset:items:DDDJ:93242038"  
    ],  
    "isReferencedBy": [  
        "urn:ngsi-ld:Dataset:items:YQRP:33454193",  
        "urn:ngsi-ld:Dataset:items:RBND:48628164"  
    ],  
    "isVersionOf": [  
        "urn:ngsi-ld:Dataset:items:AMAC:16896252",  
        "urn:ngsi-ld:Dataset:items:IPSO:04920226"  
    ],  
    "keyword": [  
        "Free analysis reduce. Owner Republican institution six science a usually. Value land executive design.",  
        "Bag recently might far plan nearly scene example. Trouble official dream author job claim join different. Success full debate here check attorney size."  
    ],  
    "landingPage": [  
        "urn:ngsi-ld:Dataset:items:UMBA:72418275",  
        "urn:ngsi-ld:Dataset:items:GUKW:86586813"  
    ],  
    "language": [  
        "Environment site ability night player. Head able American example call again.",  
        "Receive my risk leave matter prepare. Worker admit draw others remember establish necessary one."  
    ],  
    "name": "First table field check. Agency writer size. Meeting nice nothing after ever.",  
    "otherIdentifier": [  
        "urn:ngsi-ld:Dataset:items:ZNYR:18053145",  
        "urn:ngsi-ld:Dataset:items:ICBO:96194869"  
    ],  
    "owner": [  
        "urn:ngsi-ld:Dataset:items:QZHN:39684072",  
        "urn:ngsi-ld:Dataset:items:LADQ:07842317"  
    ],  
    "provenance": [  
        "Air success movie nation attention. Fight do natural brother street.",  
        "Future against sing especially answer sea. Difference effect company."  
    ],  
    "publisher": "Statement which consumer product thought total. Nothing concern picture involve paper nor kid.",  
    "qualifiedAttribution": [  
        "Central born manage evidence data. Answer doctor visit ready physical fact. Quite allow however certain lose heart.",  
        "Home interesting range ever. Magazine the instead particularly. Late have collection."  
    ],  
    "qualifiedRelation": [  
        "urn:ngsi-ld:Dataset:items:ITFK:67369057",  
        "urn:ngsi-ld:Dataset:items:ZJWX:10596189"  
    ],  
    "relatedResource": [  
        "urn:ngsi-ld:Dataset:items:FXEY:35067714",  
        "urn:ngsi-ld:Dataset:items:YYOL:47950545"  
    ],  
    "releaseDate": "1983-07-16T12:51:26Z",  
    "sample": [  
        "urn:ngsi-ld:Dataset:items:QJPZ:50290394",  
        "urn:ngsi-ld:Dataset:items:ZSSA:73451152"  
    ],  
    "seeAlso": [  
        "urn:ngsi-ld:Dataset:items:JGFW:76050330",  
        "urn:ngsi-ld:Dataset:items:XUMS:21710022"  
    ],  
    "source": "urn:ngsi-ld:Dataset:items:YSWN:41266715",  
    "spatial": [  
        {  
            "type": "Point",  
            "coordinates": [  
                9.922458,  
                109.478534  
            ]  
        }  
    ],  
    "spatialResolution": [  
        864.6,  
        864.6  
    ],  
    "temporal": [  
        "2017-04-03T02:35:57Z",  
        "1978-06-15T04:39:05Z"  
    ],  
    "temporalResolution": [  
        864.6,  
        864.6  
    ],  
    "theme": [  
        "Win catch job number find number. Leader reason top arrive night. Movement expect security high hair whom three yeah.",  
        "Respond character continue gun. Grow best choice group manage over find."  
    ],  
    "title": [  
        "Class skill deal there no language himself. After rule mouth tell economy risk. Glass personal person center.",  
        "Air step occur crime. Fear read scientist vote light. Phone sign what lot garden century big."  
    ],  
    "updateDate": "2017-12-27T03:37:52Z",  
    "version": "Financial role together range. Nice government first policy daughter need kind. Employee source nature add rest human station. Ability management test during foot that course nothing.",  
    "versionNotes": [  
        "Sort language ball floor. Your majority feeling fact by four two.",  
        "Natural explain before something first drug contain start. Party prevent live."  
    ],  
    "wasGeneratedBy": [  
        "Theory type successful together. Raise study modern miss dog Democrat quickly.",  
        "Every manage political record word group food break. Picture suddenly drug rule bring determine some forward. Beyond chair recently and."  
    ],  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
    ]  
}  
```  
</details>  
#### データセット NGSI-LD 正規化例  
ここでは、JSON-LD形式のDatasetを正規化した例を示す。これは、オプションを使用しない場合のNGSI-LDと互換性があり、個々のエンティティのコンテキストデータを返します。  
<details><summary><strong>show/hide example</strong></summary>    
```json  
{  
    "id": "urn:ngsi-ld:Dataset:id:HUZY:68185655",  
    "type": "Dataset",  
    "accessRights": {  
        "type": "Property",  
        "value": "public"  
    },  
    "alternateName": {  
        "type": "Property",  
        "value": ""  
    },  
    "contactPoint": {  
        "type": "Property",  
        "value": [  
            ""  
        ]  
    },  
    "creator": {  
        "type": "Property",  
        "value": "Diego Garcia, Marta Ortiz de Urbina, Carmen de Pablos"  
    },  
    "dataProvider": {  
        "type": "Property",  
        "value": "meloda.org"  
    },  
    "datasetDescription": {  
        "type": "Property",  
        "value": [  
            "List of open data portals",  
            "Listado de portales open data"  
        ]  
    },  
    "datasetDistribution": {  
        "type": "Property",  
        "value": [  
            ""  
        ]  
    },  
    "datasetSource": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:QTKR:65814062",  
            "urn:ngsi-ld:Dataset:items:SVUY:57639613"  
        ]  
    },  
    "datasetType": {  
        "type": "Property",  
        "value": ""  
    },  
    "dateCreated": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-07-01T10:27:49Z"  
        }  
    },  
    "dateModified": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-07-01T10:27:59Z"  
        }  
    },  
    "description": {  
        "type": "Property",  
        "value": "Analysis based on actual review of the features of the open data portals"  
    },  
    "documentation": {  
        "type": "Property",  
        "value": [  
            "",  
            ""  
        ]  
    },  
    "frequency": {  
        "type": "Property",  
        "value": "two years"  
    },  
    "hasVersion": {  
        "type": "Property",  
        "value": [  
            "",  
            ""  
        ]  
    },  
    "identifier": {  
        "type": "Property",  
        "value": [  
            "",  
            ""  
        ]  
    },  
    "isReferencedBy": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:HJNK:88711880",  
            "urn:ngsi-ld:Dataset:items:MDEO:95193079"  
        ]  
    },  
    "isVersionOf": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:RBWE:31388012",  
            "urn:ngsi-ld:Dataset:items:GATZ:02632837"  
        ]  
    },  
    "keyword": {  
        "type": "Property",  
        "value": [  
            "opendata",  
            "portal"  
        ]  
    },  
    "landingPage": {  
        "type": "Property",  
        "value": [  
            "htps://meloda.org"  
        ]  
    },  
    "language": {  
        "type": "Property",  
        "value": [  
            "EN",  
            "ES"  
        ]  
    },  
    "name": {  
        "type": "Property",  
        "value": "list of open data portals by MELODA.org project"  
    },  
    "otherIdentifier": {  
        "type": "Property",  
        "value": [  
            "",  
            ""  
        ]  
    },  
    "owner": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:UHNW:18835438",  
            "urn:ngsi-ld:Dataset:items:JIFN:75588835"  
        ]  
    },  
    "provenance": {  
        "type": "Property",  
        "value": [  
            "",  
            ""  
        ]  
    },  
    "publisher": {  
        "type": "Property",  
        "value": "urjc"  
    },  
    "qualifiedAttribution": {  
        "type": "Property",  
        "value": [  
            ""  
        ]  
    },  
    "qualifiedRelation": {  
        "type": "Property",  
        "value": [  
            ""  
        ]  
    },  
    "relatedResource": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:LGBY:74926949",  
            "urn:ngsi-ld:Dataset:items:ZAUC:79968579"  
        ]  
    },  
    "releaseDate": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-10-01T15:46:46Z"  
        }  
    },  
    "sample": {  
        "type": "Property",  
        "value": [  
            "urn:ngsi-ld:Dataset:items:MLHW:64299003",  
            "urn:ngsi-ld:Dataset:items:GNXL:59256807"  
        ]  
    },  
    "seeAlso": {  
        "type": "Property",  
        "value": [  
            "https://meloda.org"  
        ]  
    },  
    "source": {  
        "type": "Property",  
        "value": ""  
    },  
    "spatial": {  
        "type": "Property",  
        "value": {  
            "type": "Point",  
            "coordinates": [  
                22.1394715,  
                -7.100602  
            ]  
        }  
    },  
    "spatialResolution": {  
        "type": "Property",  
        "value": [  
            864.6  
        ]  
    },  
    "temporal": {  
        "type": "Property",  
        "value": [  
            {  
                "@type": "DateTime",  
                "@value": "2021-01-01T00:00:00Z"  
            },  
            {  
                "@type": "DateTime",  
                "@value": "2021-12-31T23:59:59Z"  
            }  
        ]  
    },  
    "temporalResolution": {  
        "type": "Property",  
        "value": [  
            730  
        ]  
    },  
    "theme": {  
        "type": "Property",  
        "value": [  
            "data management",  
            "open data"  
        ]  
    },  
    "title": {  
        "type": "Property",  
        "value": [  
            "Open Data list",  
            "Lista open data"  
        ]  
    },  
    "updateDate": {  
        "type": "Property",  
        "value": {  
            "@type": "DateTime",  
            "@value": "2021-07-01T03:37:52Z"  
        }  
    },  
    "version": {  
        "type": "Property",  
        "value": "3.0"  
    },  
    "versionNotes": {  
        "type": "Property",  
        "value": [  
            "With temporal evolution"  
        ]  
    },  
    "wasGeneratedBy": {  
        "type": "Property",  
        "value": [  
            "meloda Team"  
        ]  
    },  
    "@context": [  
        "https://raw.githubusercontent.com/smart-data-models/dataModel.DCAT-AP/master/context.jsonld"  
    ]  
}  
```  
</details><!-- /80-Examples -->  
<!-- 90-FooterNotes -->  
<!-- /90-FooterNotes -->  
<!-- 95-Units -->  
マグニチュード単位の扱いについては、[FAQ 10](https://smartdatamodels.org/index.php/faqs/)を参照してください。  
<!-- /95-Units -->  
<!-- 97-LastFooter -->  
---  
[Smart Data Models](https://smartdatamodels.org) +++ [Contribution Manual](https://bit.ly/contribution_manual) +++ [About](https://bit.ly/Introduction_SDM)<!-- /97-LastFooter -->  
