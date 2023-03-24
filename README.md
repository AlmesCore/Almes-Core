# Almes Core Reference Guide
Preliminary repository for the Almes Core vocabulary
| Property | Value |
| ------------- | ------------- |
| Title  | Agriculture and Livestock Metadata Elements Set (Almes Core)  |
| Creator  | C4AI AgriBio Data Managment Team  |
| Identifier  | http://purl.org/almescore |
| Latest Version | http://purl.org/almescore |
| Version History | uri here |
| Document Status | draft |
| Description | Este documento é a versão mais atualizada da especificação de todos os termos de metadados mantidos pelo C4AI AgriBio Data Managment Team, incluindo classes, propriedades, esquemas de codificação de vocabulário, e esquemas de codificação de sintaxe |
| Namespace | http://purl.org/almescore |
| Namespace abbreviation | alm: |

# Normative namespaces
Namespaces and prefixes used in normative parts of this recommendation are shown in the following table.
| Prefix | Namespace |
| ------------- | ------------- |
| alm | http://purl.org/almescore |
| dc  | http://purl.org/dc/elements/1.1/  |
| scm  | https://schema.org/docs/schemas.html  |
| dcat | http://www.w3.org/ns/dcat# |
| dct | http://purl.org/dc/terms/ |

# Index of Terms

## productGroup

| Term name | productGroup |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/productGroup  |
| Definition  | A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.  |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: grain, vegetables, meat. |
| Broader Match | https://schema.org/ProductGroup |

## theme
| Term name | theme |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  |  http://purl.org/almescore/theme |
| Definition | Indicates the main theme investigated in the economic statistical operation. |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: agriculture, livestock, forest production, fishing, aquaculture. |
| Exact Match | https://metadados.ibge.gov.br/consulta/estatisticos/temas |
| Broader Match | http://www.w3.org/ns/dcat#theme

## product
| Term name | product |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/product  |
| Definition | Name of the agricultural or livestock product targeted by the commercial operation.                                                    |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle. |
| Broader Match | https://schema.org/Product |

## verbatimName
| Term name | verbatimName |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/verbatimName  |
| Comment | Deprecated. Replaced by <a href="https://github.com/Filipi-Soares/almes/blob/main/README.md#title">dc:title</a> |

## title
| Term name | dc:title |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/elements/1.1/title  |
| Definition | A name given to the resource.                                                    |

## editor
| Term name | editor |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/publisher  |

## creator
| Term name | creator |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/creator  |

## references
| Term name | references |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/references |

## dataType
| Term name | dataType |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/DataType |

## frequency
| Term name | frequency |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/frequency |

## quantitativeValue
| Term name | quantitativeValue |
| ------------- | ------------- |
| Type of Term  | Class  |
| URI  | https://schema.org/frequency |

## unitText
| Term name | unitText |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/unitText |

## currency
| Term name | currency |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/unitText |

## location
| Term name | currency |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/location |

## startDate
| Term name | startDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/startDate |

## endDate
| Term name | endDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | https://schema.org/endDate |

## modified
| Term name | modified |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/modified |

## license
| Term name | license |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/dc/terms/license |

## statisticalMethod
| Term name | statisticalMethod |
| ------------- | ------------- |
| Type of Term  | Property  |
| URI  | http://purl.org/almescore/statisticalMethod |


