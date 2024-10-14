# Conceptual Model Documentation

## Overview
![Conceptual Model Diagram](https://github.com/AlmesCore/Almes-Core/blob/main/images/almesCoreUML.png)

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

## Use Case Example

Consider an economic statistical operation that tracks the price of various agricultural products over time. In this scenario:
1. **Resource**: Represents the overall collection of datasets published by an organization responsible for managing agricultural statistics.
2. **Dataset**: Could represent the time series data for the price of different products, such as grains or livestock, categorized by product type and theme (e.g., Price Index for Domestic Agriculture).
3. **Observation**: Individual data points within the dataset, capturing the price of a product at a given time and in a specific currency.

---

## Conclusion

This conceptual model provides a flexible yet structured approach to managing data related to agricultural products and their pricing. The model enables organizations to link observations with datasets and resources, ensuring consistency, traceability, and meaningful analysis across various domains such as economic forecasting, agricultural monitoring, and statistical reporting.

