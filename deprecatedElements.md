### product
| Term name | alm:product |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/product  |
| Status | deprecated |
| Date deprecated | 2023-06-13 |
| Replaced by | [productType](http://purl.org/almescore/productType) |

### references
| Term name | dct:references |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/references |
| Status | deprecated |
| Date deprecated | 2023-06-13 |
| Replaced by | [dcat:accessURL](https://github.com/Filipi-Soares/almes/blob/main/README.md#accessURL) |
| Comment | Deprecated only in the Almes Core schema, but still in use in the Dublin Core. |

### verbatimName
| Term name | alm:verbatimName |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/verbatimName  |
| Status | deprecated |
| Date deprecated | 2023-06-13 |
| Replaced by | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#title">dc:title</a> |

### dataType
| Term name | sdo:dataType |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/DataType |
| Status | deprecated |
| Date deprecated | 2023-06-13 |
| Comment | Deprecated only in the Almes Core schema, but still in use in Schema.org). |

### frequency
| Term name | sdo:frequency |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/frequency |
| Status | deprecated |
| Date deprecated | 2023-06-13 |
| Replaced by | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accrualPeriodicity">dct:accrualPeriodicity</a> |
| Comment | Deprecated only in the Almes Core schema, but still in use in Schema.org. 

### Data
| Term name | alm:Data |
| ------------- | ------------- |
| Type of Term  | Class  |
| Status | deprecated |
| Date deprecated | 2024-10-14 |
| URI  | https://w3id.org/AlmesCore#data |
| Definition  | A unit of data in a dataset.  |
| Replaced by | <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#accrualPeriodicity">alm:Observation</a> |

### metadataID
| Term name | alm:metadataID |
| ------------- | ------------- |
| Type of Term  | Property  |
| Status | deprecated |
| Date deprecated | 2024-10-14 |
| URI  | https://w3id.org/AlmesCore#metadataid |
| Definition  | The identifier of the metadata record, indicated by <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#identifier">dct:identifier</a>. |
| Comment | This metadata field should be used as a foreign key in a database when the metadata and data are stored in separate tables.|
| Domain | <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#data">Data</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI | 
