---
title: "Agriculture and Livestock Metadata Elements Set (Almes Core)"
description: "Structured metadata schema for agricultural datasets, supporting FAIR data principles."
keywords: "metadata, agriculture, price index, linked data, JSON-LD, SHACL, semantic web"
robots: "index, follow"
layout: default
---

<!-- SEO Meta Tags -->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="title" content="Agriculture and Livestock Metadata Elements Set (Almes Core)">
<meta name="description" content="Structured metadata schema for agricultural datasets, supporting FAIR data principles.">
<meta name="keywords" content="metadata, agriculture, price index, linked data, JSON-LD, SHACL, semantic web">
<meta name="robots" content="index, follow">
<meta name="author" content="Almes Core Management Group">
<meta name="language" content="en">
<meta name="copyright" content="Creative Commons Attribution 4.0 (CC BY 4.0)">
<meta name="og:type" content="website">
<meta name="og:title" content="Agriculture and Livestock Metadata Elements Set (Almes Core)">
<meta name="og:description" content="Structured metadata schema for agricultural datasets, supporting FAIR data principles.">
<meta name="og:image" content="https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/images/logo.jpeg"> <!-- Add if you have a logo -->
<meta name="og:url" content="https://almescore.github.io/Almes-Core/">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Agriculture and Livestock Metadata Elements Set (Almes Core)">
<meta name="twitter:description" content="Structured metadata schema for agricultural datasets, supporting FAIR data principles.">
<meta name="twitter:image" content="https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/images/logo.jpeg"> <!-- Add if you have a logo -->

# Almes Core Reference Guide

| Property | Value |
| ------------- | ------------- |
| Title  | Agriculture and Livestock Metadata Elements Set (Almes Core)  |
| Creator  | Almes Core Management Group  |
| Namespace  | [https://w3id.org/AlmesCore#](https://w3id.org/AlmesCore#) |
| RDF namespace | [https://w3id.org/AlmesCore/rdf#](https://w3id.org/AlmesCore/rdf#) |
| AgroPortal URI | [https://agroportal.lirmm.fr/ontologies/ALM](https://agroportal.lirmm.fr/ontologies/ALM) |
| Latest Version | [https://almescore.github.io/Almes-Core/](https://almescore.github.io/Almes-Core/) |
| Version History | [https://github.com/AlmesCore/Almes-Core](https://github.com/AlmesCore/Almes-Core) |
| Version number | 2.0.1
| Last updated | 2024-14-10 |
| Document Status | valid |
| Description | This document presents the latest version of the Agriculture and Livestock Metadata Element Set (Almes Core), curated by the Almes Core Data Management Group. It encompasses comprehensive definitions of classes, properties, vocabulary encoding schemes, and syntax encoding schemes. The current core focuses on providing a detailed description of agricultural price index datasets.  |
| Contributors | <a href="https://orcid.org/0000-0002-0674-7960"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Filipi Miranda Soares</a>, <a href="https://orcid.org/0000-0002-2744-6104"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Fernando Elias Corrêa</a>, <a href="https://orcid.org/0000-0002-4801-2225"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Dilvan de Abreu Moreira</a>, <a href="https://orcid.org/0000-0003-4177-1322"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Debora Pignatari Drucker</a>, <a href="https://orcid.org/0000-0001-6218-6849"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Kelly Rosa Braghetto</a>, <a href="https://orcid.org/0000-0003-1810-1742"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Alexandre Cláudio Botazzo Delbem</a>, <a href="https://orcid.org/0000-0001-7432-7653"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Luís Ferreira Pires</a>, <a href="https://orcid.org/0000-0002-1164-1351"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Luiz Olavo Bonino da Silva Santos</a>, and <a href="https://orcid.org/0000-0003-2283-1123"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Antonio Mauro Saraiva</a>. |
| License | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Serializations | <a href="https://almescore.github.io/Almes-Core/">HTML</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm-shacl.ttl">SHACL</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm.json">RDF/JSON-LD</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm.plantuml">PlantUML</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm.xml">OWL</a> |

### Recommended citation: 

Soares, F., Corrêa, F. E., Moreira, D. de A., Pignatari Drucker, D., Braghetto, K. R., Botazzo Delbem, A. C., Ferreira Pires, L., Bonino da Silva Santos, L. O., & Saraiva, A. M. (2024). Agriculture and Livestock Metadata Elements Set (Almes Core) [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.12711290](https://doi.org/10.5281/zenodo.12711290)

### Related publication:

Soares, F. M., Corrêa, F. E., Pires, L. F., da Silva Santos, L. O. B., Drucker, D. P., Braghetto, K. R., de Abreu Moreira, D., Delbem, A. C. B., da Silva, R. F., da Silva Lopes, C. O., & Saraiva, A. M. (2022). Building a Community-Based FAIR Metadata Schema for Brazilian Agriculture and Livestock Trading Data. In SEMPDW 2022 (CEUR workshop proceedings; Vol. 3235). [https://ceur-ws.org/Vol-3235/paper26.pdf
](https://ceur-ws.org/Vol-3235/paper26.pdf
)




# Table of Contents

1. [Overview](#overview)
   - [Normative namespaces](#normative-namespaces)
   - [Vocabulary Encoding Schemes](#vocabulary-encoding-schemes)
2. [Simple Almes Core](#simple-almes-core)
   - [Conceptual Model](#conceptual-model)
     - [Classes](#classes)
     - [Relationships Between Classes](#relationships-between-classes)
   - [Class Descriptions](#class-descriptions)
     - [1. Resource](#1-resource)
     - [2. Dataset](#2-dataset)
     - [3. Observation](#3-observation)
   - [Key Relationships](#key-relationships)
   - [Use Case Example](#use-case-example)
   - [Index of Terms](#index-of-terms)
3. [Extended Almes Core (RDF)](#extended-almes-core)
   - [Conceptual Model](#conceptual-model-1)
   - [Index of Terms](#index-of-terms-1)

# Overview

The Agriculture and Livestock Metadata Elements Set (Almes Core) is a structured metadata schema designed to enhance the FAIRness (Findability, Accessibility, Interoperability, and Reusability) of agricultural price index datasets. Developed and maintained by the Almes Core Management Group, the schema provides a standardized vocabulary for describing datasets related to agriculture, commodities, and price indexes.

The name "Almes Core" was chosen to reflect the schema’s broad and extensible design, allowing for future expansion into other agricultural domains beyond price index data.

## Normative namespaces

Namespaces and prefixes used in normative parts of this recommendation.

| Prefix | Namespace |
| ------------- | ------------- |
| alm | [https://w3id.org/AlmesCore#](https://w3id.org/AlmesCore#) |
| alm | [https://w3id.org/AlmesCore/rdf#](https://w3id.org/AlmesCore/rdf#)
| dc  | [http://purl.org/dc/elements/1.1/](http://purl.org/dc/elements/1.1/)  |
| sdo  | [https://schema.org/](https://schema.org/)  |
| dcat | [http://www.w3.org/ns/dcat#](http://www.w3.org/ns/dcat#) |
| dct | [http://purl.org/dc/terms/](http://purl.org/dc/terms/) |
| foaf| [http://xmlns.com/foaf/0.1/](http://xmlns.com/foaf/0.1/) |
| gn | [http://www.geonames.org/ontology#](http://www.geonames.org/ontology#) |

## Vocabulary Encoding Schemes

| Name | Namespace |
| ------------- | ------------- |
| Agrovoc | [http://aims.fao.org/aos/agrovoc](http://aims.fao.org/aos/agrovoc) |
| Agrotermos  | [https://sistemas.sede.embrapa.br/agrotermos/](https://sistemas.sede.embrapa.br/agrotermos/)  |
| APTO  | [https://w3id.org/APTO#](https://w3id.org/APTO#) |

# Simple Almes Core #

## Conceptual Model

![Conceptual Model Diagram](https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/images/almesCoreUML.png)

This conceptual model represents the metadata schema for managing and documenting resources, datasets, and observations, primarily within the domain of agriculture and economic statistical operations. The model defines a set of classes and properties to describe how data is structured, with a particular focus on datasets and observations of product prices.

### Classes

The model consists of three main classes:

1. **Resource**
2. **Dataset**
3. **Observation**

### Relationships Between Classes

- **Resource** is a general class that describes any entity that is published or curated by a single agent, such as a dataset, report, or other informational resources.
- **Dataset** is a subclass of Resource, representing structured data collections. A **Dataset** contains one or more **Observations**, which capture recorded data about specific agricultural products, including price, date, and currency.
- The relationship between **Dataset** and **Observation** is expressed through the `alm:hasObservation` property, indicating that a dataset can have multiple observations associated with it.

---

## Class Descriptions

### 1. **Resource**

**Definition**: A general class representing any resource published or curated by a single agent.

- **URI**: `https://www.w3.org/ns/dcat#Resource`
- **Properties**:
  - `dct:identifier (xsd:anyURI)`: An unambiguous reference to the resource within a given context.
  - `dc:title (rdfs:Literal)`: The title or name of the resource.
  - `dct:description (rdfs:Literal)`: A description of the resource, which may include an abstract, table of contents, or free-text account.
  - `dc:publisher (rdfs:Literal)`: The entity responsible for publishing the resource (e.g., person, organization, or service).
  - `dc:creator (rdfs:Literal)`: The entity primarily responsible for creating the resource.
  - `dct:modified (xsd:date)`: The date the resource was last modified.
  - `dct:hasVersion (rdfs:Literal)`: Version information about the resource.
  - `dct:language (rdfs:Literal)`: The language of the resource, represented as a controlled vocabulary (ISO 639).
  - `dct:license (xsd:anyURI)`: A legal document granting permission to use the resource.
  - `dc:rights (rdfs:Literal)`: Information about rights held over the resource.

---

### 2. **Dataset**

**Definition**: A structured collection of data, often used in economic and agricultural contexts to represent measurements and observations about products, prices, and other factors.

- **URI**: `https://www.w3.org/ns/dcat#Dataset`
- **Inherits from**: `dcat:Resource`
- **Properties**:
  - `alm:productgroup (rdfs:Literal)`: A group of products resulting from agriculture or livestock, aggregated based on biological traits.
  - `alm:producttype (rdfs:Literal)`: The type of agricultural or livestock product represented in the dataset (e.g., soy, corn, cattle).
  - `alm:theme (rdfs:Literal)`: The main subject or topic of the dataset (e.g., price index, agricultural production).
  - `dcat:accessURL (xsd:anyURI)`: A URL providing access to the dataset (e.g., a landing page or SPARQL endpoint).
  - `dct:accrualPeriodicity (rdfs:Literal)`: The frequency at which items are added to the dataset.
  - `sdo:referenceQuantity (rdfs:Literal)`: The reference quantity for which a certain price applies (e.g., 1 EUR per 4 kWh of electricity).
  - `sdo:location (rdfs:Literal)`: The geographical location associated with the dataset.
  - `alm:statisticalMethod (xsd:anyURI)`: Summary of the statistical methods used to process the dataset.
  - `alm:descriptiveStatistics (rdfs:Literal)`: Descriptive statistics summarizing the dataset, such as mean, variance, and trends.
  - `sdo:startDate (xsd:date)`: The start date of the dataset (typically for time series data).
  - `sdo:endDate (xsd:date)`: The end date of the dataset. If the dataset is still active, this field remains empty.
  - **`alm:hasObservation`**: A key property linking a dataset to multiple **Observation** entities that capture detailed information such as price, date, and currency for agricultural products.

---

### 3. **Observation**

**Definition**: An observation is a specific recorded data point, typically used to represent the price of an agricultural product at a specific point in time, along with other relevant attributes.

- **URI**: `https://w3id.org/AlmesCore#data`
- **Properties**:
  - `dc:date (xsd:date)`: The date or time period when the observation was made.
  - `sdo:price (xsd:float)`: The price of the product, represented as a floating-point number.
  - `sdo:currency (xsd:string)`: The currency in which the price is expressed, typically following ISO 4217 standards (e.g., "USD" for US dollars).

---

## Key Relationships

### `alm:hasObservation`

- **Definition**: A property that associates a **Dataset** with one or more **Observation** instances.
- **Domain**: `Dataset`
- **Range**: `Observation`
- **Cardinality**: A dataset may have zero or more observations. Each observation contains specific details such as price, date, and currency.
  
### Example of Relationship:

- A **Dataset** could be a time series of agricultural product prices.
- Each **Observation** in the dataset would represent the price of a specific product (e.g., soy) on a particular date, expressed in a given currency (e.g., BRL for Brazilian Real).

---

### Use Case Example

Consider an economic statistical operation that tracks the price of various agricultural products over time. In this scenario:
1. **Resource**: Represents the overall collection of datasets published by an organization responsible for managing agricultural statistics.
2. **Dataset**: Could represent the time series data for the price of different products, such as grains or livestock, categorized by product type and theme (e.g., Price Index for Domestic Agriculture).
3. **Observation**: Individual data points within the dataset, capturing the price of a product at a given time and in a specific currency.

---

## Index of Terms

[**Resource**](https://almescore.github.io/Almes-Core/#resource)
- [identifier](https://almescore.github.io/Almes-Core/#identifier)
- [title](https://almescore.github.io/Almes-Core/#title)
- [description](https://almescore.github.io/Almes-Core/#description)
- [publisher](https://almescore.github.io/Almes-Core/#publisher)
- [creator](https://almescore.github.io/Almes-Core/#creator)
- [modified](https://almescore.github.io/Almes-Core/#modified)
- [version](https://almescore.github.io/Almes-Core/#version)
- [language](https://almescore.github.io/Almes-Core/#language)
- [license](https://almescore.github.io/Almes-Core/#license)
- [rights](https://almescore.github.io/Almes-Core/#rights)

[**Dataset**](https://almescore.github.io/Almes-Core/#dataset)
- [productGroup](https://almescore.github.io/Almes-Core/#productgroup)
- [productType](https://almescore.github.io/Almes-Core/#producttype)
- [theme](https://almescore.github.io/Almes-Core/#theme)
- [accrualPeriodicity](https://almescore.github.io/Almes-Core/#accrualperiodicity)
- [referenceQuantity](https://almescore.github.io/Almes-Core/#referencequantity)
- [location](https://almescore.github.io/Almes-Core/#location)
- [accessURL](https://almescore.github.io/Almes-Core/#accessurl)
- [statisticalMethod](https://almescore.github.io/Almes-Core/#statisticalmethod)
- [descriptiveStatistics](https://almescore.github.io/Almes-Core/#descriptivestatistics)
- [startDate](https://almescore.github.io/Almes-Core/#startdate)
- [endDate](https://almescore.github.io/Almes-Core/#enddate)
- [hasObservation](https://almescore.github.io/Almes-Core/#hasobservation)

[**Observation**](https://almescore.github.io/Almes-Core/#observation)
- [date](https://almescore.github.io/Almes-Core/#date)
- [price](https://almescore.github.io/Almes-Core/#price)
- [currency](https://almescore.github.io/Almes-Core/#currency)
  
# Simple Almes Core

## Resource

| Term name | dcat:Resource |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Resource  |
| Label (PT-BR) | Recurso  |
| URI  | https://www.w3.org/ns/dcat#Resource  |
| Definition  | Resource published or curated by a single agent.  |

### identifier

| Term name | dct:identifier |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | identifier  |
| Label (PT-BR) | identificador  |
| URI  | http://purl.org/dc/terms/identifier  |
| Definition  | An unambiguous reference to the resource within a given context.  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### title

| Term name | dc:title |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | title  |
| Label (PT-BR) | título  |
| URI  | http://purl.org/dc/elements/1.1/title  |
| Definition | A name given to the resource.   |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | 	http://www.w3.org/2000/01/rdf-schema#Literal |

### description

| Term name | dct:description |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | description  |
| Label (PT-BR) | descrição  |
| URI  | http://purl.org/dc/terms/description |
| Definition | 	Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | 	http://www.w3.org/2000/01/rdf-schema#Literal |

### publisher

| Term name | dc:publisher |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | publisher  |
| Label (PT-BR) | editor  |
| URI  | http://purl.org/dc/elements/1.1/publisher  |
| Definition | An entity responsible for making the resource available. |
| Comment | Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### creator

| Term name | dc:creator |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | creator  |
| Label (PT-BR) | criador  |
| URI  | http://purl.org/dc/elements/1.1/creator  |
| Definition | 	An entity primarily responsible for making the resource. |
| Comments| Examples of a Creator include a person, an organization, or a service. Typically, the name of a Creator should be used to indicate the entity. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### modified

| Term name | dct:modified |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | modified  |
| Label (PT-BR) | última atualização  |
| URI  | http://purl.org/dc/terms/modified |
| Definition | Date on which the resource was changed. |
| Comment | Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#date |

### version

| Term name | dct:hasVersion |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | version  |
| Label (PT-BR) | versão  |
| URI  | http://purl.org/dc/terms/hasVersion |
| Definition | The version indicator (name or identifier) of a resource. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### language

| Term name | dct:language |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | language  |
| Label (PT-BR) | idioma  |
| URI  | http://purl.org/dc/terms/language  |
| Definition | A language of the resource. |
| Comment | Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as <a href="https://www.loc.gov/standards/iso639-2/php/code_list-txt.php">ISO 639-2</a> or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### license

| Term name | dct:license |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | license  |
| Label (PT-BR) | licença de uso  |
| URI  | http://purl.org/dc/terms/license |
| Definition | A legal document giving official permission to do something with the resource. |
| Comment | Recommended practice is to identify the license document with a URI. If this is not possible or feasible, a literal value that identifies the license may be provided. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### rights

| Term name | dc:rights |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | rights  |
| Label (PT-BR) | direitos  |
| URI  | http://purl.org/dc/elements/1.1/rights |
| Definition | Information about rights held in and over the resource. |
| Comment | Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

## Dataset

| Term name | dcat:Dataset |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Dataset  |
| Label (PT-BR) | Dataset  |
| URI  | https://www.w3.org/ns/dcat#Dataset  |
| Definition  | Data encoded in a defined structure.  |

### productGroup

| Term name | alm:productgroup |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product group  |
| Label (PT-BR) | grupo do produto  |
| URI  | https://w3id.org/AlmesCore#productgroup |
| Definition  | A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.  |
| Comment | The best recommended practice is to use a controlled vocabulary, such as the Agricultural Product Types Ontology (APTO). Example: grain, vegetables, meat. |
| Broader Match | <a href="https://schema.org/ProductGroup">sdo:productGroup</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### productType

| Term name | alm:producttype |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product type  |
| Label (PT-BR) | produto  |
| URI  | https://w3id.org/AlmesCore#producttype |
| Definition | Name of the agricultural or livestock product type targeted by the commercial operation.  |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle. |
| Broader Match | <a href="https://schema.org/Product">sdo:product</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### theme

| Term name | alm:theme |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | theme  |
| Label (PT-BR) | tema  |
| URI  | https://w3id.org/AlmesCore#theme |
| Definition | Indicates the main subject or topic investigated in the economic statistical operation. Themes help categorize the dataset for easier discovery and analysis. |
| Comment | The recommended best practice is to use a controlled vocabulary for consistency and accuracy. Examples of possible themes include Price Index, Domestic Material Consumption Indicator, Agricultural Production, Export and Import Data, Inflation Rate, Employment Statistics, and Energy Consumption. |
| References | https://metadados.ibge.gov.br/consulta/estatisticos/temas |
| Broader Match | <a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### accessURL

| Term name | dcat:accessURL |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | access URL  |
| Label (PT-BR) | disponível em  |
| URI  | https://www.w3.org/ns/dcat#accessURL |
| Definition | A URL of the resource that gives access to a distribution of the dataset. E.g. landing page, feed, SPARQL endpoint. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### accrualPeriodicity

| Term name | dct:accrualPeriodicity |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | periodicity  |
| Label (PT-BR) | periodicidade  |
| URI  | http://purl.org/dc/terms/accrualPeriodicity |
| Definition | The frequency with which items are added to a collection. |
| Comment | Recommended practice is to use a value from the Collection Description Frequency Vocabulary <a href="https://www.dublincore.org/specifications/dublin-core/collection-description/frequency/">(DCMI-COLLFREQ)</a>. 
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### referenceQuantity

| Term name | sdo:referenceQuantity |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | reference quantity  |
| Label (PT-BR) | quantidade de referência  |
| URI  | https://schema.org/referenceQuantity |
| Definition | The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### location

| Term name | sdo:location |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | location  |
| Label (PT-BR) | localização  |
| URI  | https://schema.org/location |
| Definition | The location of, for example, where an event is happening, where an organization is located, or where an action takes place. |
| Comment | Recommended practice is to use a value from a controlled vocabulary such as <a href="https://www.geonames.org/">Geonames.org</a>. 
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### statisticalMethod

| Term name | alm:statisticalMethod |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | statistical method  |
| Label (PT-BR) | método estatístico  |
| URI  | https://w3id.org/AlmesCore#statisticalmethod |
| Definition | Summary of the methods used for the process of obtaining data. |
| Comment| Recommended best practice is to indicate the published resource URI in an open access format. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### descriptiveStatistics

| Term name | alm:descriptiveStatistics |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | descriptive statistics  |
| Label (PT-BR) | estatística descritiva  |
| URI  | https://w3id.org/AlmesCore#descriptivestatistics |
| Definition | Summarizes and describes the main features of a dataset. When used in the context of a time series, it includes metrics such as mean, variance, and trends over time. |
| Comment|  Recommended best practice is to use a controlled vocabulary. Example: ``time series``, ``mean``, ``Range``, ``trend analysis``, ``seasonal snalysis``, etc. |
| Related Match | <a href="https://rdf-vocabulary.ddialliance.org/discovery.html#descriptivestatistics">ddi:DescriptiveStatistics</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### startDate

| Term name | sdo:startDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | start date  |
| Label (PT-BR) | data de início  |
| URI  | https://schema.org/startDate |
| Definition  | The start date and time of the item (in ISO 8601 date format).  |
| Comment|  In Almes Core, it is used to inform the start date of a price index time series. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### endDate

| Term name | sdo:endDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | end date  |
| Label (PT-BR) | data de fim  |
| URI  | https://schema.org/endDate |
| Definition  | The end date and time of the item (in ISO 8601 date format).  |
| Comment|  In Almes Core, it is used to inform the end date of a price index time series. In case the price index is still active, this field should be left blank. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### hasObservation

| Term name | alm:hasObservation |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | has observation  |
| Label (PT-BR) | tem observação  |
| URI  | https://w3id.org/AlmesCore#hasObservation |
| Definition  | Associates an entity (represented by an ``dct:identifier``) to a specific recorded price ``Observation`` related to an agricultural product.  |
| Comment | This metadata field should be used to create a blank node in an RDF representation, including the properties ``dc:date``, ``sdo:price``, and ``sdo:currency``.|
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset">Dataset</a> |
| Range | alm:Observation | 


## Observation

| Term name | alm:Data |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Observation  |
| Label (PT-BR) | Observação  |
| URI  | https://w3id.org/AlmesCore#Observation |
| Definition  | A recorded observation of an agricultural product price on a specific date. The observation captures key attributes such as the price, date of observation, and the applicable currency, which provide a snapshot of the economic value of the product at a given time. |

### date

| Term name | dc:date |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | date  |
| Label (PT-BR) | data  |
| URI  | http://purl.org/dc/elements/1.1/date  |
| Definition | A point or period of time associated with an event in the lifecycle of the resource. |
| Comment 1 | Date may be used to express temporal information at any level of granularity. Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [ISO 8601-1] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [W3CDTF] or the Extended Date/Time Format Specification [EDTF]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character. Either the start or end date may be missing. |
| Comment 2 | In case the date is a range, [sdo:startDate](https://almescore.github.io/Almes-Core/#startdate) and [sdo:ednDate](https://almescore.github.io/Almes-Core/#enddate) should be used instead to indicate the beginning and the end of the period. |
| Domain | <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### price

| Term name | sdo:price |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | price  |
| Label (PT-BR) | preço  |
| URI  | https://schema.org/price |
| Definition | The offer price of a product. |
| Comment | The price should be indicated as a float number with two decimal digits. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#observation">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#float | 


### currency

| Term name | sdo:currency |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | currency  |
| Label (PT-BR) | moeda  |
| URI  | https://schema.org/currency |
| Definition | The currency in which the monetary amount is expressed. |
| Comment | Use standard formats: ISO 4217 currency format, e.g. "USD"; Ticker symbol for cryptocurrencies, e.g. "BTC"; well known names for Local Exchange Trading Systems (LETS) and other currency types, e.g. "Ithaca HOUR". |
| Domain | <a href="https://almescore.github.io/Almes-Core/#observation">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#string | 

# Extended Almes Core

Extended Almes Core was created to support the use of the metadata schema in RDF, within the namespace `https://w3id.org/AlmesCore/rdf#`.

The `publisher` and `creator` properties describe the entities responsible for publishing the Datasets. To provide more detailed information about these entities beyond just their names, these properties can be instantiated using the `Agent` class, which includes attributes such as name, homepage, and email. Using the `Agent` class is optional in the Simple Almes Core, and mandatory in the Extended Almes Core.

The `productGroup` and `productType` properties may have subproperties `productGroupURI`, `productGroupName`, and `productTypeURI`, `productTypeName`, respectively. The use of this subproperties is not mandatory, but highly recommended. 

As mentioned before, in the Simple Almes Core, `location` may provide only the name of the location in textual form. In Extended Almes Core, `location` should be instantiated using the `GeoNamesFeature` class, which has two properties: `geoNamesName`, to give the location name as it appears on the GeoNames ontology, and `geoNamesID`, to provide the URI of the concept representing a location within the GeoNames ontology.


## Conceptual Model

![Conceptual Model Diagram](https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/images/almesCoreextended.png)

## Index of Terms

[**Resource**](https://almescore.github.io/Almes-Core/#resource-1)
- [identifier](https://almescore.github.io/Almes-Core/#identifier-1)
- [title](https://almescore.github.io/Almes-Core/#title-1)
- [description](https://almescore.github.io/Almes-Core/#description-1)
- [publisher](https://almescore.github.io/Almes-Core/#publisher-1)
- [creator](https://almescore.github.io/Almes-Core/#creator-1)
- [modified](https://almescore.github.io/Almes-Core/#modified-1)
- [version](https://almescore.github.io/Almes-Core/#version-1)
- [language](https://almescore.github.io/Almes-Core/#language-1)
- [license](https://almescore.github.io/Almes-Core/#license-1)
- [rights](https://almescore.github.io/Almes-Core/#rights-1)

[**Dataset**](https://almescore.github.io/Almes-Core/#dataset-1)
- [productGroup](https://almescore.github.io/Almes-Core/#productgroup-1)
- [productGroupURI](https://almescore.github.io/Almes-Core/#productgroupuri-1)
- [productGroupName](https://almescore.github.io/Almes-Core/#productgroupname-1)
- [productType](https://almescore.github.io/Almes-Core/#producttype-1)
- [productTypeURI](https://almescore.github.io/Almes-Core/#producttypeuri-1)
- [productTypeName](https://almescore.github.io/Almes-Core/#producttypename-1)
- [theme](https://almescore.github.io/Almes-Core/#theme-1)
- [accrualPeriodicity](https://almescore.github.io/Almes-Core/#accrualperiodicity-1)
- [referenceQuantity](https://almescore.github.io/Almes-Core/#referencequantity-1)
- [location](https://almescore.github.io/Almes-Core/#location-1)
- [accessURL](https://almescore.github.io/Almes-Core/#accessurl-1)
- [statisticalMethod](https://almescore.github.io/Almes-Core/#statisticalmethod-1)
- [descriptiveStatistics](https://almescore.github.io/Almes-Core/#descriptivestatistics-1)
- [startDate](https://almescore.github.io/Almes-Core/#startdate-1)
- [endDate](https://almescore.github.io/Almes-Core/#enddate-1)
- [hasObservation](https://almescore.github.io/Almes-Core/#hasobservation-1)

[**Agent**](https://almescore.github.io/Almes-Core/#agent-1)
- [name](https://almescore.github.io/Almes-Core/#name-1)
- [homepage](https://almescore.github.io/Almes-Core/#homepage-1)
- [e-mail](https://almescore.github.io/Almes-Core/#e-mail-1)

[**GeoNamesFeature**](https://almescore.github.io/Almes-Core/#geonamesfeature-1)
- [geoNamesName](https://almescore.github.io/Almes-Core/#geonamesname-1)
- [geoNamesID](https://almescore.github.io/Almes-Core/#geonamesid-1)

[**Observation**](https://almescore.github.io/Almes-Core/#observation-1)
- [date](https://almescore.github.io/Almes-Core/#date-1)
- [price](https://almescore.github.io/Almes-Core/#price-1)
- [currency](https://almescore.github.io/Almes-Core/#currency-1)

## Resource

| Term name | dcat:Resource |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Resource  |
| Label (PT-BR) | Recurso  |
| URI  | https://www.w3.org/ns/dcat#Resource  |
| Definition  | Resource published or curated by a single agent.  |

### identifier

| Term name | dct:identifier |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | identifier  |
| Label (PT-BR) | identificador  |
| URI  | http://purl.org/dc/terms/identifier  |
| Definition  | An unambiguous reference to the resource within a given context.  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### title

| Term name | dc:title |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | title  |
| Label (PT-BR) | título  |
| URI  | http://purl.org/dc/elements/1.1/title  |
| Definition | A name given to the resource.   |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | 	http://www.w3.org/2000/01/rdf-schema#Literal |

### description

| Term name | dct:description |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | description  |
| Label (PT-BR) | descrição  |
| URI  | http://purl.org/dc/terms/description |
| Definition | 	Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | 	http://www.w3.org/2000/01/rdf-schema#Literal |

### publisher

| Term name | dc:publisher |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | publisher  |
| Label (PT-BR) | editor  |
| URI  | http://purl.org/dc/elements/1.1/publisher  |
| Definition | An entity responsible for making the resource available. |
| Comment | Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | 	<a href="https://almescore.github.io/Almes-Core/#agent-1">Agent</a> |

### creator

| Term name | dc:creator |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | creator  |
| Label (PT-BR) | criador  |
| URI  | http://purl.org/dc/elements/1.1/creator  |
| Definition | 	An entity primarily responsible for making the resource. |
| Comments| Examples of a Creator include a person, an organization, or a service. Typically, the name of a Creator should be used to indicate the entity. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | 	<a href="https://almescore.github.io/Almes-Core/#agent-1">Agent</a> |

### modified

| Term name | dct:modified |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | modified  |
| Label (PT-BR) | última atualização  |
| URI  | http://purl.org/dc/terms/modified |
| Definition | Date on which the resource was changed. |
| Comment | Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#date |

### version

| Term name | dct:hasVersion |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | version  |
| Label (PT-BR) | versão  |
| URI  | http://purl.org/dc/terms/hasVersion |
| Definition | The version indicator (name or identifier) of a resource. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### language

| Term name | dct:language |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | language  |
| Label (PT-BR) | idioma  |
| URI  | http://purl.org/dc/terms/language  |
| Definition | A language of the resource. |
| Comment | Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as <a href="https://www.loc.gov/standards/iso639-2/php/code_list-txt.php">ISO 639-2</a> or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### license

| Term name | dct:license |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | license  |
| Label (PT-BR) | licença de uso  |
| URI  | http://purl.org/dc/terms/license |
| Definition | A legal document giving official permission to do something with the resource. |
| Comment | Recommended practice is to identify the license document with a URI. If this is not possible or feasible, a literal value that identifies the license may be provided. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### rights

| Term name | dc:rights |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | rights  |
| Label (PT-BR) | direitos  |
| URI  | http://purl.org/dc/elements/1.1/rights |
| Definition | Information about rights held in and over the resource. |
| Comment | Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#resource-1">Resource</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

## Dataset

| Term name | dcat:Dataset |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Dataset  |
| Label (PT-BR) | Dataset  |
| URI  | https://www.w3.org/ns/dcat#Dataset  |
| Definition  | Data encoded in a defined structure.  |

### productGroup

| Term name | alm:productgroup |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product group  |
| Label (PT-BR) | grupo do produto  |
| URI  | https://w3id.org/AlmesCore/rdf#productgroup |
| Definition  | A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.  |
| Comment | The best recommended practice is to use a controlled vocabulary, such as the Agricultural Product Types Ontology (APTO). Example: grain, vegetables, meat. |
| Broader Match | <a href="https://schema.org/ProductGroup">sdo:productGroup</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### productGroupURI

| Term name | alm:productgroupuri |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product group URI |
| Label (PT-BR) | URI do grupo do produto  |
| URI  | https://w3id.org/AlmesCore/rdf#productgroupuri |
| Definition  | A URI of a term from any controlled vocabulary describing a <a href="https://almescore.github.io/Almes-Core/#productgroup-1">productGroup</a>. |
| Comment | Example: https://agrovoc.fao.org/browse/agrovoc/en/page/c_3346 |
| Subproperty of | <a href="https://almescore.github.io/Almes-Core/#productgroupuri-1">productGroup</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### productGroupName

| Term name | alm:productgroupname |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product group name |
| Label (PT-BR) | nome do grupo do produto  |
| URI  | https://w3id.org/AlmesCore/rdf#productgroupname |
| Definition  | The name of a <a href="https://almescore.github.io/Almes-Core/#productgroup-1">productGroup</a> in a controlled vocabulary. |
| Comment | Examples: grain, vegetables, meat. |
| Subproperty of | <a href="https://almescore.github.io/Almes-Core/#productgroupuri-1">productGroup</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### productType

| Term name | alm:producttype |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product type  |
| Label (PT-BR) | produto  |
| URI  | https://w3id.org/AlmesCore/rdf#producttype |
| Definition | Name of the agricultural or livestock product type targeted by the commercial operation.  |
| Comment | The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle. |
| Broader Match | <a href="https://schema.org/Product">sdo:product</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### productTypeURI

| Term name | alm:producttypeuri |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product type URI  |
| Label (PT-BR) | URI do tipo de produto  |
| URI  | https://w3id.org/AlmesCore/rdf#producttypeuri |
| Definition | A URI of a term from any controlled vocabulary describing a <a href="https://almescore.github.io/Almes-Core/#producttype-1">productType</a>. |
| Comment | Example: http://aims.fao.org/aos/agrovoc/c_a77edd1d |
| Subproperty of | <a href="https://almescore.github.io/Almes-Core/#producttype-1">productType</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### productTypeName

| Term name | alm:producttypename |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | product type name  |
| Label (PT-BR) | nome do tipo de produto  |
| URI  | https://w3id.org/AlmesCore/rdf#producttypename |
| Definition | The name of a <a href="https://almescore.github.io/Almes-Core/#producttype-1">productType</a> in a controlled vocabulary. |
| Comment | Examples: cassava flour, honey, beef. |
| Subproperty of | <a href="https://almescore.github.io/Almes-Core/#producttype-1">productType</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### theme

| Term name | alm:theme |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | theme  |
| Label (PT-BR) | tema  |
| URI  | https://w3id.org/AlmesCore/rdf#theme |
| Definition | Indicates the main subject or topic investigated in the economic statistical operation. Themes help categorize the dataset for easier discovery and analysis. |
| Comment | The recommended best practice is to use a controlled vocabulary for consistency and accuracy. Examples of possible themes include Price Index, Domestic Material Consumption Indicator, Agricultural Production, Export and Import Data, Inflation Rate, Employment Statistics, and Energy Consumption. |
| References | https://metadados.ibge.gov.br/consulta/estatisticos/temas |
| Broader Match | <a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### accessURL

| Term name | dcat:accessURL |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | access URL  |
| Label (PT-BR) | disponível em  |
| URI  | https://www.w3.org/ns/dcat#accessURL |
| Definition | A URL of the resource that gives access to a distribution of the dataset. E.g. landing page, feed, SPARQL endpoint. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### accrualPeriodicity

| Term name | dct:accrualPeriodicity |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | periodicity  |
| Label (PT-BR) | periodicidade  |
| URI  | http://purl.org/dc/terms/accrualPeriodicity |
| Definition | The frequency with which items are added to a collection. |
| Comment | Recommended practice is to use a value from the Collection Description Frequency Vocabulary <a href="https://www.dublincore.org/specifications/dublin-core/collection-description/frequency/">(DCMI-COLLFREQ)</a>. 
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### referenceQuantity

| Term name | sdo:referenceQuantity |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | reference quantity  |
| Label (PT-BR) | quantidade de referência  |
| URI  | https://schema.org/referenceQuantity |
| Definition | The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### location

| Term name | sdo:location |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | location  |
| Label (PT-BR) | localização  |
| URI  | https://schema.org/location |
| Definition | The location of, for example, where an event is happening, where an organization is located, or where an action takes place. |
| Comment | Recommended practice is to use a value from a controlled vocabulary such as <a href="https://www.geonames.org/">Geonames.org</a>. 
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | [GeoNamesFeature](https://almescore.github.io/Almes-Core/#geonamesfeature-1) |

### statisticalMethod

| Term name | alm:statisticalMethod |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | statistical method  |
| Label (PT-BR) | método estatístico  |
| URI  | https://w3id.org/AlmesCore/rdf#statisticalmethod |
| Definition | Summary of the methods used for the process of obtaining data. |
| Comment| Recommended best practice is to indicate the published resource URI in an open access format. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI |

### descriptiveStatistics

| Term name | alm:descriptiveStatistics |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | descriptive statistics  |
| Label (PT-BR) | estatística descritiva  |
| URI  | https://w3id.org/AlmesCore/rdf#descriptivestatistics |
| Definition | Summarizes and describes the main features of a dataset. When used in the context of a time series, it includes metrics such as mean, variance, and trends over time. |
| Comment|  Recommended best practice is to use a controlled vocabulary. Example: ``time series``, ``mean``, ``Range``, ``trend analysis``, ``seasonal snalysis``, etc. |
| Related Match | <a href="https://rdf-vocabulary.ddialliance.org/discovery.html#descriptivestatistics">ddi:DescriptiveStatistics</a> |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### startDate

| Term name | sdo:startDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | start date  |
| Label (PT-BR) | data de início  |
| URI  | https://schema.org/startDate |
| Definition  | The start date and time of the item (in ISO 8601 date format).  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### endDate

| Term name | sdo:endDate |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | end date  |
| Label (PT-BR) | data de fim  |
| URI  | https://schema.org/endDate |
| Definition  | The end date and time of the item (in ISO 8601 date format).  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### hasObservation

| Term name | alm:hasObservation |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | has observation  |
| Label (PT-BR) | tem observação  |
| URI  | https://w3id.org/AlmesCore/rdf#hasObservation |
| Definition  | Associates an entity (represented by an ``dct:identifier``) to a specific recorded price ``Observation`` related to an agricultural product.  |
| Comment | This metadata field should be used to create a blank node in an RDF representation, including the properties ``dc:date``, ``sdo:price``, and ``sdo:currency``.|
| Domain | <a href="https://almescore.github.io/Almes-Core/#dataset-1">Dataset</a> |
| Range | alm:Observation | 

## Agent

| Term name | foaf:Agent |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Agent  |
| Label (PT-BR) | Agente  |
| URI  | http://xmlns.com/foaf/0.1/#term_Agent |
| Definition  | An agent (eg. person, group, software or physical artifact).  |
 
### name

| Term name | foaf:name |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | name  |
| Label (PT-BR) | nome  |
| URI  | http://xmlns.com/foaf/0.1/#term_name |
| Definition  | A name for some thing.  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#agent-1">Agent</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal |

### homepage

| Term name | foaf:homepage |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | homepage  |
| Label (PT-BR) | homepage  |
| URI  | http://xmlns.com/foaf/0.1/#term_homepage |
| Definition  | A homepage for some thing.  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#agent-1">Agent</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI | 

### e-mail

| Term name | foaf:mbox |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | e-mail  |
| Label (PT-BR) | e-mail  |
| URI  | http://xmlns.com/foaf/0.1/#term_mbox |
| Definition  | A personal mailbox, ie. an Internet mailbox associated with exactly one owner, the first owner of this mailbox. This is a 'static inverse functional property', in that there is (across time and change) at most one individual that ever has any particular value for foaf:mbox.  |
| Domain | <a href="https://almescore.github.io/Almes-Core/#agent-1">Agent</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal | 

## GeoNamesFeature

| Term name | gn:Feature |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | GeoNames Feature  |
| Label (PT-BR) | Característica Geográfica  |
| URI  | http://www.geonames.org/ontology#Feature |
| Definition  | A geographical feature. It can be any feature that has a geographical extent, such as a country, city, mountain, river, etc.  |

### geoNamesName

| Term name | gn:name |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | geoNames name  |
| Label (PT-BR) | nome geoNames |
| URI  | http://www.geonames.org/ontology#name |
| Definition  | The name of a geographical feature.  |
| Comments | Examples: ``New York``, ``Mount Everest``, ``Nile River``.
| Domain | <a href="https://almescore.github.io/Almes-Core/#geonamesfeature-1">GeoNamesFeature</a> |
| Range | http://www.w3.org/2000/01/rdf-schema#Literal | 

### geoNamesID

| Term name | gn:geonamesID |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | geonames ID  |
| Label (PT-BR) | identificador geoNames |
| URI  | http://www.geonames.org/ontology#geonamesID |
| Definition  | The ID of a geographical feature.  |
| Comments | Examples: ``http://sws.geonames.org/5128581/``, ``http://sws.geonames.org/6252001/``, ``http://sws.geonames.org/2347283/``.
| Domain | <a href="https://almescore.github.io/Almes-Core/#geonamesfeature-1">GeoNamesFeature</a> |
| Range | http://www.w3.org/2001/XMLSchema#anyURI | 


## Observation

| Term name | alm:Observation |
| ------------- | ------------- |
| Type of Term  | Class  |
| Label (EN) | Observation  |
| Label (PT-BR) | Observação  |
| URI  | https://w3id.org/AlmesCore/rdf#Observation |
| Definition  | A recorded observation of an agricultural product price on a specific date. The observation captures key attributes such as the price, date of observation, and the applicable currency, which provide a snapshot of the economic value of the product at a given time. |

### date

| Term name | dc:date |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | date  |
| Label (PT-BR) | data  |
| URI  | http://purl.org/dc/elements/1.1/date  |
| Definition | A point or period of time associated with an event in the lifecycle of the resource. |
| Comment 1 | Date may be used to express temporal information at any level of granularity. Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [ISO 8601-1] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [W3CDTF] or the Extended Date/Time Format Specification [EDTF]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a '/' (slash) character. Either the start or end date may be missing. |
| Comment 2 | In case the date is a range, [sdo:startDate](https://almescore.github.io/Almes-Core/#startdate-1) and [sdo:ednDate](https://almescore.github.io/Almes-Core/#enddate-1) should be used instead to indicate the beginning and the end of the period. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#observation-1">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#date | 

### price

| Term name | sdo:price |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | price  |
| Label (PT-BR) | preço  |
| URI  | https://schema.org/price |
| Definition | The offer price of a product. |
| Comment | The price should be indicated as a float number with two decimal digits. |
| Domain | <a href="https://almescore.github.io/Almes-Core/#observation-1">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#float | 


### currency

| Term name | sdo:currency |
| ------------- | ------------- |
| Type of Term  | Property  |
| Label (EN) | currency  |
| Label (PT-BR) | moeda  |
| URI  | https://schema.org/currency |
| Definition | The currency in which the monetary amount is expressed. |
| Comment | Use standard formats: ISO 4217 currency format, e.g. "USD"; Ticker symbol for cryptocurrencies, e.g. "BTC"; well known names for Local Exchange Trading Systems (LETS) and other currency types, e.g. "Ithaca HOUR". |
| Domain | <a href="https://almescore.github.io/Almes-Core/#observation-1">Observation</a> |
| Range | http://www.w3.org/2001/XMLSchema#string | 

## 🔍 Embedded Metadata

To improve search engine discoverability, this page contains **structured metadata (JSON-LD)**

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "CreativeWork",
  "name": "Agriculture and Livestock Metadata Elements Set (Almes Core)",
  "creator": {
    "@type": "Organization",
    "name": "Almes Core Management Group"
  },
  "identifier": "https://w3id.org/AlmesCore#",
  "url": "https://almescore.github.io/Almes-Core/",
  "version": "2.0.1",
  "dateModified": "2024-10-15",
  "description": "This document presents the latest version of the Agriculture and Livestock Metadata Element Set (Almes Core), curated by the Almes Core Data Management Group. It encompasses comprehensive definitions of classes, properties, vocabulary encoding schemes, and syntax encoding schemes. The current core focuses on providing a detailed description of agricultural price index datasets.",
  "keywords": [
    "Agriculture",
    "metadata schema",
    "commodities",
    "price index"
  ],
  "license": "https://creativecommons.org/licenses/by/4.0/",
  "status": "valid",
  "distribution": [
    {
      "@type": "DataDownload",
      "encodingFormat": "text/html",
      "contentUrl": "https://almescore.github.io/Almes-Core/"
    },
    {
      "@type": "DataDownload",
      "encodingFormat": "text/turtle",
      "contentUrl": "https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm-shacl.ttl"
    },
    {
      "@type": "DataDownload",
      "encodingFormat": "application/ld+json",
      "contentUrl": "https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm.json"
    },
    {
      "@type": "DataDownload",
      "encodingFormat": "application/plantuml",
      "contentUrl": "https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/alm.plantuml"
    }
  ],
  "isAccessibleForFree": true,
  "contributor": [
    {
      "@type": "Person",
      "name": "Filipi Miranda Soares",
      "sameAs": "https://orcid.org/0000-0002-0674-7960"
    },
    {
      "@type": "Person",
      "name": "Fernando Elias Corrêa",
      "sameAs": "https://orcid.org/0000-0002-2744-6104"
    },
    {
      "@type": "Person",
      "name": "Dilvan de Abreu Moreira",
      "sameAs": "https://orcid.org/0000-0002-4801-2225"
    }
  ],
  "hasPart": {
    "@type": "CreativeWork",
    "name": "Version History",
    "url": "https://github.com/AlmesCore/Almes-Core"
  }
}
</script>
