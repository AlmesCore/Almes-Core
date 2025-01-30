<h1 id="almes-core-reference-guide">Almes Core Reference Guide</h1>
<table>
<thead>
<tr>
<th>Property</th>
<th>Value</th>
</tr>
</thead>
<tbody>
<tr>
<td>Title</td>
<td>Agriculture and Livestock Metadata Elements Set (Almes Core)</td>
</tr>
<tr>
<td>Creator</td>
<td>Almes Core Management Group</td>
</tr>
<tr>
<td>Identifier</td>
<td><a href="https://w3id.org/AlmesCore#">https://w3id.org/AlmesCore#</a></td>
</tr>
<tr>
<td>Latest Version</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/edit/main/core2024-07-08.md">https://github.com/AlmesCore/Almes-Core/edit/main/core2024-07-08.md</a></td>
</tr>
<tr>
<td>Version History</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/deprecatedElements.md">https://github.com/AlmesCore/Almes-Core/blob/main/deprecatedElements.md</a></td>
</tr>
<tr>
<td>Version number</td>
<td>2.0.1</td>
</tr>
<tr>
<td>Last updated</td>
<td>2024-14-10</td>
</tr>
<tr>
<td>Document Status</td>
<td>valid</td>
</tr>
<tr>
<td>Description</td>
<td>This document presents the latest version of the Agriculture and Livestock Metadata Element Set (Almes Core), curated by the Almes Core Data Management Group. It encompasses comprehensive definitions of classes, properties, vocabulary encoding schemes, and syntax encoding schemes. The current core focuses on providing a detailed description of agricultural price index datasets.</td>
</tr>
<tr>
<td>Contributors</td>
<td><a href="https://orcid.org/0000-0002-0674-7960"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Filipi Miranda Soares</a>, <a href="https://orcid.org/0000-0002-2744-6104"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Fernando Elias Corrêa</a>, <a href="https://orcid.org/0000-0002-4801-2225"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Dilvan de Abreu Moreira</a>, <a href="https://orcid.org/0000-0003-4177-1322"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Debora Pignatari Drucker</a>, <a href="https://orcid.org/0000-0001-6218-6849"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Kelly Rosa Braghetto</a>, <a href="https://orcid.org/0000-0003-1810-1742"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Alexandre Cláudio Botazzo Delbem</a>, <a href="https://orcid.org/0000-0001-7432-7653"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Luís Ferreira Pires</a>, <a href="https://orcid.org/0000-0002-1164-1351"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Luiz Olavo Bonino da Silva Santos</a>, and <a href="https://orcid.org/0000-0003-2283-1123"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" alt="ORCID iD icon"> Antonio Mauro Saraiva</a>.</td>
</tr>
<tr>
<td>License</td>
<td><a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></td>
</tr>
<tr>
<td>Serializations</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#almes-core-reference-guide">HTML</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/almes-core-schema-shacl.ttl">SHACL</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/main/almes-core-schema.json">RDF/JSON-LD</a>, <a href="https://raw.githubusercontent.com/AlmesCore/Almes-Core/refs/heads/main/Serializations/almes-core-schema.plantuml">PlantUML</a></td>
</tr>
</tbody>
</table>
<h3 id="recommended-citation-">Recommended citation:</h3>
<p>Soares, F., Corrêa, F. E., Moreira, D. de A., Pignatari Drucker, D., Braghetto, K. R., Botazzo Delbem, A. C., Ferreira Pires, L., Bonino da Silva Santos, L. O., &amp; Saraiva, A. M. (2024). Agriculture and Livestock Metadata Elements Set (Almes Core) [Data set]. Zenodo. <a href="https://doi.org/10.5281/zenodo.12711290">https://doi.org/10.5281/zenodo.12711290</a></p>
<h3 id="related-publication-">Related publication:</h3>
<p>Soares, F. M., Corrêa, F. E., Pires, L. F., da Silva Santos, L. O. B., Drucker, D. P., Braghetto, K. R., de Abreu Moreira, D., Delbem, A. C. B., da Silva, R. F., da Silva Lopes, C. O., &amp; Saraiva, A. M. (2022). Building a Community-Based FAIR Metadata Schema for Brazilian Agriculture and Livestock Trading Data. In SEMPDW 2022 (CEUR workshop proceedings; Vol. 3235). <a href="https://ceur-ws.org/Vol-3235/paper26.pdf">https://ceur-ws.org/Vol-3235/paper26.pdf</a></p>
<h1 id="table-of-contents">Table of Contents</h1>
<ol>
<li><a href="#overview">Overview</a><ul>
<li><a href="#normative-namespaces">Normative namespaces</a></li>
<li><a href="#vocabulary-encoding-schemes">Vocabulary Encoding Schemes</a></li>
</ul>
</li>
<li><a href="#simple-almes-core">Simple Almes Core</a><ul>
<li><a href="#conceptual-model">Conceptual Model</a><ul>
<li><a href="#classes">Classes</a></li>
<li><a href="#relationships-between-classes">Relationships Between Classes</a></li>
</ul>
</li>
<li><a href="#class-descriptions">Class Descriptions</a><ul>
<li><a href="#1-resource">1. Resource</a></li>
<li><a href="#2-dataset">2. Dataset</a></li>
<li><a href="#3-observation">3. Observation</a></li>
</ul>
</li>
<li><a href="#key-relationships">Key Relationships</a></li>
<li><a href="#use-case-example">Use Case Example</a></li>
<li><a href="#index-of-terms">Index of Terms</a></li>
</ul>
</li>
<li><a href="#extended-almes-core">Extended Almes Core</a><ul>
<li><a href="#conceptual-model-1">Conceptual Model</a></li>
<li><a href="#index-of-terms-1">Index of Terms</a></li>
</ul>
</li>
</ol>
<h1 id="overview">Overview</h1>
<h2 id="normative-namespaces">Normative namespaces</h2>
<p>Namespaces and prefixes used in normative parts of this recommendation.
| Prefix | Namespace |
| ------------- | ------------- |
| alm | <a href="https://w3id.org/AlmesCore#">https://w3id.org/AlmesCore#</a> |
| dc  | <a href="http://purl.org/dc/elements/1.1/">http://purl.org/dc/elements/1.1/</a>  |
| sdo  | <a href="https://schema.org/">https://schema.org/</a>  |
| dcat | <a href="http://www.w3.org/ns/dcat#">http://www.w3.org/ns/dcat#</a> |
| dct | <a href="http://purl.org/dc/terms/">http://purl.org/dc/terms/</a> |
| foaf| <a href="http://xmlns.com/foaf/0.1/">http://xmlns.com/foaf/0.1/</a> |
| gn | <a href="http://www.geonames.org/ontology#">http://www.geonames.org/ontology#</a> |</p>
<h2 id="vocabulary-encoding-schemes">Vocabulary Encoding Schemes</h2>
<table>
<thead>
<tr>
<th>Name</th>
<th>Namespace</th>
</tr>
</thead>
<tbody>
<tr>
<td>Agrovoc</td>
<td><a href="http://aims.fao.org/aos/agrovoc">http://aims.fao.org/aos/agrovoc</a></td>
</tr>
<tr>
<td>Agrotermos</td>
<td><a href="https://sistemas.sede.embrapa.br/agrotermos/">https://sistemas.sede.embrapa.br/agrotermos/</a></td>
</tr>
<tr>
<td>APTO</td>
<td><a href="https://w3id.org/apto">https://w3id.org/apto</a></td>
</tr>
</tbody>
</table>
<h1 id="simple-almes-core">Simple Almes Core</h1>
<h2 id="conceptual-model">Conceptual Model</h2>
<p><img src="https://github.com/AlmesCore/Almes-Core/blob/main/images/almesCoreUML.png" alt="Conceptual Model Diagram"></p>
<p>This conceptual model represents the metadata schema for managing and documenting resources, datasets, and observations, primarily within the domain of agriculture and economic statistical operations. The model defines a set of classes and properties to describe how data is structured, with a particular focus on datasets and observations of product prices.</p>
<h3 id="classes">Classes</h3>
<p>The model consists of three main classes:</p>
<ol>
<li><strong>Resource</strong></li>
<li><strong>Dataset</strong></li>
<li><strong>Observation</strong></li>
</ol>
<h3 id="relationships-between-classes">Relationships Between Classes</h3>
<ul>
<li><strong>Resource</strong> is a general class that describes any entity that is published or curated by a single agent, such as a dataset, report, or other informational resources.</li>
<li><strong>Dataset</strong> is a subclass of Resource, representing structured data collections. A <strong>Dataset</strong> contains one or more <strong>Observations</strong>, which capture recorded data about specific agricultural products, including price, date, and currency.</li>
<li>The relationship between <strong>Dataset</strong> and <strong>Observation</strong> is expressed through the <code>alm:hasObservation</code> property, indicating that a dataset can have multiple observations associated with it.</li>
</ul>
<hr>
<h2 id="class-descriptions">Class Descriptions</h2>
<h3 id="1-resource-">1. <strong>Resource</strong></h3>
<p><strong>Definition</strong>: A general class representing any resource published or curated by a single agent.</p>
<ul>
<li><strong>URI</strong>: <code>https://www.w3.org/ns/dcat#Resource</code></li>
<li><strong>Properties</strong>:<ul>
<li><code>dct:identifier (xsd:anyURI)</code>: An unambiguous reference to the resource within a given context.</li>
<li><code>dc:title (rdfs:Literal)</code>: The title or name of the resource.</li>
<li><code>dct:description (rdfs:Literal)</code>: A description of the resource, which may include an abstract, table of contents, or free-text account.</li>
<li><code>dc:publisher (rdfs:Literal)</code>: The entity responsible for publishing the resource (e.g., person, organization, or service).</li>
<li><code>dc:creator (rdfs:Literal)</code>: The entity primarily responsible for creating the resource.</li>
<li><code>dct:modified (xsd:date)</code>: The date the resource was last modified.</li>
<li><code>dct:hasVersion (rdfs:Literal)</code>: Version information about the resource.</li>
<li><code>dct:language (rdfs:Literal)</code>: The language of the resource, represented as a controlled vocabulary (ISO 639).</li>
<li><code>dct:license (xsd:anyURI)</code>: A legal document granting permission to use the resource.</li>
<li><code>dc:rights (rdfs:Literal)</code>: Information about rights held over the resource.</li>
</ul>
</li>
</ul>
<hr>
<h3 id="2-dataset-">2. <strong>Dataset</strong></h3>
<p><strong>Definition</strong>: A structured collection of data, often used in economic and agricultural contexts to represent measurements and observations about products, prices, and other factors.</p>
<ul>
<li><strong>URI</strong>: <code>https://www.w3.org/ns/dcat#Dataset</code></li>
<li><strong>Inherits from</strong>: <code>dcat:Resource</code></li>
<li><strong>Properties</strong>:<ul>
<li><code>alm:productgroup (rdfs:Literal)</code>: A group of products resulting from agriculture or livestock, aggregated based on biological traits.</li>
<li><code>alm:producttype (rdfs:Literal)</code>: The type of agricultural or livestock product represented in the dataset (e.g., soy, corn, cattle).</li>
<li><code>alm:theme (rdfs:Literal)</code>: The main subject or topic of the dataset (e.g., price index, agricultural production).</li>
<li><code>dcat:accessURL (xsd:anyURI)</code>: A URL providing access to the dataset (e.g., a landing page or SPARQL endpoint).</li>
<li><code>dct:accrualPeriodicity (rdfs:Literal)</code>: The frequency at which items are added to the dataset.</li>
<li><code>sdo:referenceQuantity (rdfs:Literal)</code>: The reference quantity for which a certain price applies (e.g., 1 EUR per 4 kWh of electricity).</li>
<li><code>sdo:location (rdfs:Literal)</code>: The geographical location associated with the dataset.</li>
<li><code>alm:statisticalMethod (xsd:anyURI)</code>: Summary of the statistical methods used to process the dataset.</li>
<li><code>alm:descriptiveStatistics (rdfs:Literal)</code>: Descriptive statistics summarizing the dataset, such as mean, variance, and trends.</li>
<li><code>sdo:startDate (xsd:date)</code>: The start date of the dataset (typically for time series data).</li>
<li><code>sdo:endDate (xsd:date)</code>: The end date of the dataset. If the dataset is still active, this field remains empty.</li>
<li><strong><code>alm:hasObservation</code></strong>: A key property linking a dataset to multiple <strong>Observation</strong> entities that capture detailed information such as price, date, and currency for agricultural products.</li>
</ul>
</li>
</ul>
<hr>
<h3 id="3-observation-">3. <strong>Observation</strong></h3>
<p><strong>Definition</strong>: An observation is a specific recorded data point, typically used to represent the price of an agricultural product at a specific point in time, along with other relevant attributes.</p>
<ul>
<li><strong>URI</strong>: <code>https://w3id.org/AlmesCore#data</code></li>
<li><strong>Properties</strong>:<ul>
<li><code>dc:date (xsd:date)</code>: The date or time period when the observation was made.</li>
<li><code>sdo:price (xsd:float)</code>: The price of the product, represented as a floating-point number.</li>
<li><code>sdo:currency (xsd:string)</code>: The currency in which the price is expressed, typically following ISO 4217 standards (e.g., &quot;USD&quot; for US dollars).</li>
</ul>
</li>
</ul>
<hr>
<h2 id="key-relationships">Key Relationships</h2>
<h3 id="-alm-hasobservation-"><code>alm:hasObservation</code></h3>
<ul>
<li><strong>Definition</strong>: A property that associates a <strong>Dataset</strong> with one or more <strong>Observation</strong> instances.</li>
<li><strong>Domain</strong>: <code>Dataset</code></li>
<li><strong>Range</strong>: <code>Observation</code></li>
<li><strong>Cardinality</strong>: A dataset may have zero or more observations. Each observation contains specific details such as price, date, and currency.</li>
</ul>
<h3 id="example-of-relationship-">Example of Relationship:</h3>
<ul>
<li>A <strong>Dataset</strong> could be a time series of agricultural product prices.</li>
<li>Each <strong>Observation</strong> in the dataset would represent the price of a specific product (e.g., soy) on a particular date, expressed in a given currency (e.g., BRL for Brazilian Real).</li>
</ul>
<hr>
<h3 id="use-case-example">Use Case Example</h3>
<p>Consider an economic statistical operation that tracks the price of various agricultural products over time. In this scenario:</p>
<ol>
<li><strong>Resource</strong>: Represents the overall collection of datasets published by an organization responsible for managing agricultural statistics.</li>
<li><strong>Dataset</strong>: Could represent the time series data for the price of different products, such as grains or livestock, categorized by product type and theme (e.g., Price Index for Domestic Agriculture).</li>
<li><strong>Observation</strong>: Individual data points within the dataset, capturing the price of a product at a given time and in a specific currency.</li>
</ol>
<hr>
<h2 id="index-of-terms">Index of Terms</h2>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource"><strong>Resource</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#identifier">identifier</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#title">title</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#description">description</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#publisher">publisher</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#creator">creator</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#modified">modified</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#version">version</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#language">language</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#license">license</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#rights">rights</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset"><strong>Dataset</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#theme">theme</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#accrualperiodicity">accrualPeriodicity</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#referencequantity">referenceQuantity</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#location">location</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#accessurl">accessURL</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#statisticalmethod">statisticalMethod</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#descriptivestatistics">descriptiveStatistics</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#startdate">startDate</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#enddate">endDate</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#hasobservation">hasObservation</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation"><strong>Observation</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#date">date</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#price">price</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#currency">currency</a></li>
</ul>
<h1 id="simple-almes-core">Simple Almes Core</h1>
<h3 id="-resource-"><strong>Resource</strong></h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:Resource</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Resource</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Recurso</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#Resource">https://www.w3.org/ns/dcat#Resource</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Resource published or curated by a single agent.</td>
</tr>
</tbody>
</table>
<h3 id="identifier">identifier</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:identifier</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>identifier</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>identificador</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/identifier">http://purl.org/dc/terms/identifier</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An unambiguous reference to the resource within a given context.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="title">title</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:title</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>title</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>título</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/title">http://purl.org/dc/elements/1.1/title</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A name given to the resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="description">description</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>description</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>descrição</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/description">http://purl.org/dc/terms/description</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="publisher">publisher</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:publisher</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>publisher</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>editor</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/publisher">http://purl.org/dc/elements/1.1/publisher</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An entity responsible for making the resource available.</td>
</tr>
<tr>
<td>Comment</td>
<td>Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="creator">creator</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:creator</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>creator</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>criador</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/creator">http://purl.org/dc/elements/1.1/creator</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An entity primarily responsible for making the resource.</td>
</tr>
<tr>
<td>Comments</td>
<td>Examples of a Creator include a person, an organization, or a service. Typically, the name of a Creator should be used to indicate the entity.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="modified">modified</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:modified</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>modified</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>última atualização</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/modified">http://purl.org/dc/terms/modified</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Date on which the resource was changed.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="version">version</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:hasVersion</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>version</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>versão</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/hasVersion">http://purl.org/dc/terms/hasVersion</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The version indicator (name or identifier) of a resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="language">language</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:language</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>language</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>idioma</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/language">http://purl.org/dc/terms/language</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A language of the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as <a href="https://www.loc.gov/standards/iso639-2/php/code_list-txt.php">ISO 639-2</a> or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="license">license</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:license</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>license</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>licença de uso</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/license">http://purl.org/dc/terms/license</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A legal document giving official permission to do something with the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to identify the license document with a URI. If this is not possible or feasible, a literal value that identifies the license may be provided.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="rights">rights</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:rights</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>rights</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>direitos</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/rights">http://purl.org/dc/elements/1.1/rights</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Information about rights held in and over the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h2 id="dataset">Dataset</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:Dataset</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Dataset</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Dataset</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#Dataset">https://www.w3.org/ns/dcat#Dataset</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Data encoded in a defined structure.</td>
</tr>
</tbody>
</table>
<h3 id="productgroup">productGroup</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:productgroup</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product group</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>grupo do produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#productgroup">https://w3id.org/AlmesCore#productgroup</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.</td>
</tr>
<tr>
<td>Comment</td>
<td>The best recommended practice is to use a controlled vocabulary, such as the Agricultural Product Types Ontology (APTO). Example: grain, vegetables, meat.</td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="https://schema.org/ProductGroup">sdo:productGroup</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="producttype">productType</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:producttype</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product type</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#producttype">https://w3id.org/AlmesCore#producttype</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Name of the agricultural or livestock product type targeted by the commercial operation.</td>
</tr>
<tr>
<td>Comment</td>
<td>The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle.</td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="https://schema.org/Product">sdo:product</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="theme">theme</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:theme</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>theme</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>tema</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#theme">https://w3id.org/AlmesCore#theme</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Indicates the main subject or topic investigated in the economic statistical operation. Themes help categorize the dataset for easier discovery and analysis.</td>
</tr>
<tr>
<td>Comment</td>
<td>The recommended best practice is to use a controlled vocabulary for consistency and accuracy. Examples of possible themes include Price Index, Domestic Material Consumption Indicator, Agricultural Production, Export and Import Data, Inflation Rate, Employment Statistics, and Energy Consumption.</td>
</tr>
<tr>
<td>References</td>
<td><a href="https://metadados.ibge.gov.br/consulta/estatisticos/temas">https://metadados.ibge.gov.br/consulta/estatisticos/temas</a></td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="accessurl">accessURL</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:accessURL</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>access URL</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>disponível em</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#accessURL">https://www.w3.org/ns/dcat#accessURL</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A URL of the resource that gives access to a distribution of the dataset. E.g. landing page, feed, SPARQL endpoint.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="accrualperiodicity">accrualPeriodicity</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:accrualPeriodicity</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>periodicity</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>periodicidade</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/accrualPeriodicity">http://purl.org/dc/terms/accrualPeriodicity</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The frequency with which items are added to a collection.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use a value from the Collection Description Frequency Vocabulary <a href="https://www.dublincore.org/specifications/dublin-core/collection-description/frequency/">(DCMI-COLLFREQ)</a>. </td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="referencequantity">referenceQuantity</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:referenceQuantity</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>reference quantity</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>quantidade de referência</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/referenceQuantity">https://schema.org/referenceQuantity</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="location">location</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:location</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>location</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>localização</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/location">https://schema.org/location</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The location of, for example, where an event is happening, where an organization is located, or where an action takes place.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use a value from a controlled vocabulary such as <a href="https://www.geonames.org/">Geonames.org</a>. </td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="statisticalmethod">statisticalMethod</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:statisticalMethod</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>statistical method</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>método estatístico</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#statisticalmethod">https://w3id.org/AlmesCore#statisticalmethod</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Summary of the methods used for the process of obtaining data.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended best practice is to indicate the published resource URI in an open access format.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="descriptivestatistics">descriptiveStatistics</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:descriptiveStatistics</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>descriptive statistics</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>estatística descritiva</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#descriptivestatistics">https://w3id.org/AlmesCore#descriptivestatistics</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Summarizes and describes the main features of a dataset. When used in the context of a time series, it includes metrics such as mean, variance, and trends over time.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended best practice is to use a controlled vocabulary. Example: <code>time series</code>, <code>mean</code>, <code>Range</code>, <code>trend analysis</code>, <code>seasonal snalysis</code>, etc.</td>
</tr>
<tr>
<td>Related Match</td>
<td><a href="https://rdf-vocabulary.ddialliance.org/discovery.html#descriptivestatistics">ddi:DescriptiveStatistics</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="startdate">startDate</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:startDate</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>start date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data de início</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/startDate">https://schema.org/startDate</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The start date and time of the item (in ISO 8601 date format).</td>
</tr>
<tr>
<td>Comment</td>
<td>In Almes Core, it is used to inform the start date of a price index time series.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="enddate">endDate</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:endDate</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>end date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data de fim</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/endDate">https://schema.org/endDate</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The end date and time of the item (in ISO 8601 date format).</td>
</tr>
<tr>
<td>Comment</td>
<td>In Almes Core, it is used to inform the end date of a price index time series. In case the price index is still active, this field should be left blank.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="hasobservation">hasObservation</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:hasObservation</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>has observation</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>tem observação</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#hasObservation">https://w3id.org/AlmesCore#hasObservation</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Associates an entity (represented by an <code>dct:identifier</code>) to a specific recorded price <code>Observation</code> related to an agricultural product.</td>
</tr>
<tr>
<td>Comment</td>
<td>This metadata field should be used to create a blank node in an RDF representation, including the properties <code>dc:date</code>, <code>sdo:price</code>, and <code>sdo:currency</code>.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td>alm:Observation</td>
</tr>
</tbody>
</table>
<h2 id="observation">Observation</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:Data</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Observation</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Observação</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#Observation">https://w3id.org/AlmesCore#Observation</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A recorded observation of an agricultural product price on a specific date. The observation captures key attributes such as the price, date of observation, and the applicable currency, which provide a snapshot of the economic value of the product at a given time.</td>
</tr>
</tbody>
</table>
<h3 id="date">date</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:date</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/date">http://purl.org/dc/elements/1.1/date</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A point or period of time associated with an event in the lifecycle of the resource.</td>
</tr>
<tr>
<td>Comment 1</td>
<td>Date may be used to express temporal information at any level of granularity. Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [ISO 8601-1] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [W3CDTF] or the Extended Date/Time Format Specification [EDTF]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a &#39;/&#39; (slash) character. Either the start or end date may be missing.</td>
</tr>
<tr>
<td>Comment 2</td>
<td>In case the date is a range, <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#startdate">sdo:startDate</a> and <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#enddate">sdo:ednDate</a> should be used instead to indicate the beginning and the end of the period.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="price">price</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:price</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>price</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>preço</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/price">https://schema.org/price</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The offer price of a product.</td>
</tr>
<tr>
<td>Comment</td>
<td>The price should be indicated as a float number with two decimal digits.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#float">http://www.w3.org/2001/XMLSchema#float</a></td>
</tr>
</tbody>
</table>
<h3 id="currency">currency</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:currency</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>currency</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>moeda</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/currency">https://schema.org/currency</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The currency in which the monetary amount is expressed.</td>
</tr>
<tr>
<td>Comment</td>
<td>Use standard formats: ISO 4217 currency format, e.g. &quot;USD&quot;; Ticker symbol for cryptocurrencies, e.g. &quot;BTC&quot;; well known names for Local Exchange Trading Systems (LETS) and other currency types, e.g. &quot;Ithaca HOUR&quot;.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#string">http://www.w3.org/2001/XMLSchema#string</a></td>
</tr>
</tbody>
</table>
<h1 id="extended-almes-core">Extended Almes Core</h1>
<h2 id="conceptual-model">Conceptual Model</h2>
<p><img src="https://github.com/AlmesCore/Almes-Core/blob/main/images/almesCoreextended.png" alt="Conceptual Model Diagram"></p>
<h2 id="index-of-terms">Index of Terms</h2>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource"><strong>Resource</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#identifier">identifier</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#title">title</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#description">description</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#publisher-1">publisher</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#creator-1">creator</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#modified">modified</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#version">version</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#language">language</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#license">license</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#rights">rights</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset"><strong>Dataset</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroupuri">productGroupURI</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroupname">productGroupName</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttypeuri">productTypeURI</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttypename">productTypeName</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#theme">theme</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#accrualperiodicity">accrualPeriodicity</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#referencequantity">referenceQuantity</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#location-1">location</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#accessurl">accessURL</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#statisticalmethod">statisticalMethod</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#descriptivestatistics">descriptiveStatistics</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#startdate">startDate</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#enddate">endDate</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#hasobservation">hasObservation</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent"><strong>Agent</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#name">name</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#homepage">homepage</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#e-mail">e-mail</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesfeature"><strong>GeoNamesFeature</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesname">geoNamesName</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesid">geoNamesID</a></li>
</ul>
<p><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation"><strong>Observation</strong></a></p>
<ul>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#date">date</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#price">price</a></li>
<li><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#currency">currency</a></li>
</ul>
<h2 id="resource">Resource</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:Resource</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Resource</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Recurso</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#Resource">https://www.w3.org/ns/dcat#Resource</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Resource published or curated by a single agent.</td>
</tr>
</tbody>
</table>
<h3 id="identifier">identifier</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:identifier</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>identifier</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>identificador</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/identifier">http://purl.org/dc/terms/identifier</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An unambiguous reference to the resource within a given context.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="title">title</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:title</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>title</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>título</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/title">http://purl.org/dc/elements/1.1/title</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A name given to the resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="description">description</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:description</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>description</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>descrição</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/description">http://purl.org/dc/terms/description</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Description may include but is not limited to: an abstract, a table of contents, a graphical representation, or a free-text account of the resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="publisher">publisher</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:publisher</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>publisher</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>editor</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/publisher">http://purl.org/dc/elements/1.1/publisher</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An entity responsible for making the resource available.</td>
</tr>
<tr>
<td>Comment</td>
<td>Examples of a Publisher include a person, an organization, or a service. Typically, the name of a Publisher should be used to indicate the entity.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent">Agent</a></td>
</tr>
</tbody>
</table>
<h3 id="creator">creator</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:creator</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>creator</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>criador</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/creator">http://purl.org/dc/elements/1.1/creator</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An entity primarily responsible for making the resource.</td>
</tr>
<tr>
<td>Comments</td>
<td>Examples of a Creator include a person, an organization, or a service. Typically, the name of a Creator should be used to indicate the entity.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent">Agent</a></td>
</tr>
</tbody>
</table>
<h3 id="modified">modified</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:modified</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>modified</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>última atualização</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/modified">http://purl.org/dc/terms/modified</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Date on which the resource was changed.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to describe the date, date/time, or period of time as recommended for the property Date, of which this is a subproperty.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="version">version</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:hasVersion</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>version</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>versão</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/hasVersion">http://purl.org/dc/terms/hasVersion</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The version indicator (name or identifier) of a resource.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="language">language</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:language</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>language</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>idioma</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/language">http://purl.org/dc/terms/language</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A language of the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use either a non-literal value representing a language from a controlled vocabulary such as <a href="https://www.loc.gov/standards/iso639-2/php/code_list-txt.php">ISO 639-2</a> or ISO 639-3, or a literal value consisting of an IETF Best Current Practice 47 <a href="https://www.rfc-editor.org/info/bcp47">(IETF-BCP47)</a> language tag.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="license">license</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:license</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>license</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>licença de uso</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/license">http://purl.org/dc/terms/license</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A legal document giving official permission to do something with the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to identify the license document with a URI. If this is not possible or feasible, a literal value that identifies the license may be provided.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="rights">rights</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:rights</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>rights</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>direitos</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/rights">http://purl.org/dc/elements/1.1/rights</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Information about rights held in and over the resource.</td>
</tr>
<tr>
<td>Comment</td>
<td>Typically, rights information includes a statement about various property rights associated with the resource, including intellectual property rights.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#resource">Resource</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h2 id="dataset">Dataset</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:Dataset</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Dataset</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Dataset</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#Dataset">https://www.w3.org/ns/dcat#Dataset</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Data encoded in a defined structure.</td>
</tr>
</tbody>
</table>
<h3 id="productgroup">productGroup</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:productgroup</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product group</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>grupo do produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#productgroup">https://w3id.org/AlmesCore#productgroup</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A ProductGroup represents a group of products resulting from agriculture or livestock activities that vary only in certain well-described ways, being aggregated according to common biological traits.</td>
</tr>
<tr>
<td>Comment</td>
<td>The best recommended practice is to use a controlled vocabulary, such as the Agricultural Product Types Ontology (APTO). Example: grain, vegetables, meat.</td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="https://schema.org/ProductGroup">sdo:productGroup</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="productgroupuri">productGroupURI</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:productgroupuri</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product group URI</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>URI do grupo do produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#productgroupuri">https://w3id.org/AlmesCore#productgroupuri</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A URI of a term from any controlled vocabulary describing a <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a>.</td>
</tr>
<tr>
<td>Comment</td>
<td>Example: <a href="https://agrovoc.fao.org/browse/agrovoc/en/page/c_3346">https://agrovoc.fao.org/browse/agrovoc/en/page/c_3346</a></td>
</tr>
<tr>
<td>Subproperty of</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="productgroupname">productGroupName</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:productgroupname</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product group name</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>nome do grupo do produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#productgroupname">https://w3id.org/AlmesCore#productgroupname</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The name of a <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a> in a controlled vocabulary.</td>
</tr>
<tr>
<td>Comment</td>
<td>Examples: grain, vegetables, meat.</td>
</tr>
<tr>
<td>Subproperty of</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#productgroup">productGroup</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="producttype">productType</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:producttype</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product type</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#producttype">https://w3id.org/AlmesCore#producttype</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Name of the agricultural or livestock product type targeted by the commercial operation.</td>
</tr>
<tr>
<td>Comment</td>
<td>The best recommended practice is to use a controlled vocabulary. Example: soy, corn, fed cattle.</td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="https://schema.org/Product">sdo:product</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="producttypeuri">productTypeURI</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:producttypeuri</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product type URI</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>URI do tipo de produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#producttypeuri">https://w3id.org/AlmesCore#producttypeuri</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A URI of a term from any controlled vocabulary describing a <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a>.</td>
</tr>
<tr>
<td>Comment</td>
<td>Example: <a href="http://aims.fao.org/aos/agrovoc/c_a77edd1d">http://aims.fao.org/aos/agrovoc/c_a77edd1d</a></td>
</tr>
<tr>
<td>Subproperty of</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="producttypename">productTypeName</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:producttypename</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>product type name</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>nome do tipo de produto</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#producttypename">https://w3id.org/AlmesCore#producttypename</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The name of a <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a> in a controlled vocabulary.</td>
</tr>
<tr>
<td>Comment</td>
<td>Examples: cassava flour, honey, beef.</td>
</tr>
<tr>
<td>Subproperty of</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#producttype">productType</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="theme">theme</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:theme</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>theme</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>tema</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#theme">https://w3id.org/AlmesCore#theme</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Indicates the main subject or topic investigated in the economic statistical operation. Themes help categorize the dataset for easier discovery and analysis.</td>
</tr>
<tr>
<td>Comment</td>
<td>The recommended best practice is to use a controlled vocabulary for consistency and accuracy. Examples of possible themes include Price Index, Domestic Material Consumption Indicator, Agricultural Production, Export and Import Data, Inflation Rate, Employment Statistics, and Energy Consumption.</td>
</tr>
<tr>
<td>References</td>
<td><a href="https://metadados.ibge.gov.br/consulta/estatisticos/temas">https://metadados.ibge.gov.br/consulta/estatisticos/temas</a></td>
</tr>
<tr>
<td>Broader Match</td>
<td><a href="http://www.w3.org/ns/dcat#theme">dcat:theme</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="accessurl">accessURL</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dcat:accessURL</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>access URL</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>disponível em</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://www.w3.org/ns/dcat#accessURL">https://www.w3.org/ns/dcat#accessURL</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A URL of the resource that gives access to a distribution of the dataset. E.g. landing page, feed, SPARQL endpoint.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="accrualperiodicity">accrualPeriodicity</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dct:accrualPeriodicity</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>periodicity</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>periodicidade</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/terms/accrualPeriodicity">http://purl.org/dc/terms/accrualPeriodicity</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The frequency with which items are added to a collection.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use a value from the Collection Description Frequency Vocabulary <a href="https://www.dublincore.org/specifications/dublin-core/collection-description/frequency/">(DCMI-COLLFREQ)</a>. </td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="referencequantity">referenceQuantity</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:referenceQuantity</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>reference quantity</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>quantidade de referência</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/referenceQuantity">https://schema.org/referenceQuantity</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The reference quantity for which a certain price applies, e.g. 1 EUR per 4 kWh of electricity. This property is a replacement for unitOfMeasurement for the advanced cases where the price does not relate to a standard unit.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="location">location</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:location</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>location</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>localização</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/location">https://schema.org/location</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The location of, for example, where an event is happening, where an organization is located, or where an action takes place.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended practice is to use a value from a controlled vocabulary such as <a href="https://www.geonames.org/">Geonames.org</a>. </td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesfeature">GeoNamesFeature</a></td>
</tr>
</tbody>
</table>
<h3 id="statisticalmethod">statisticalMethod</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:statisticalMethod</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>statistical method</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>método estatístico</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#statisticalmethod">https://w3id.org/AlmesCore#statisticalmethod</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Summary of the methods used for the process of obtaining data.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended best practice is to indicate the published resource URI in an open access format.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="descriptivestatistics">descriptiveStatistics</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:descriptiveStatistics</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>descriptive statistics</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>estatística descritiva</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#descriptivestatistics">https://w3id.org/AlmesCore#descriptivestatistics</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Summarizes and describes the main features of a dataset. When used in the context of a time series, it includes metrics such as mean, variance, and trends over time.</td>
</tr>
<tr>
<td>Comment</td>
<td>Recommended best practice is to use a controlled vocabulary. Example: <code>time series</code>, <code>mean</code>, <code>Range</code>, <code>trend analysis</code>, <code>seasonal snalysis</code>, etc.</td>
</tr>
<tr>
<td>Related Match</td>
<td><a href="https://rdf-vocabulary.ddialliance.org/discovery.html#descriptivestatistics">ddi:DescriptiveStatistics</a></td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="startdate">startDate</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:startDate</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>start date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data de início</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/startDate">https://schema.org/startDate</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The start date and time of the item (in ISO 8601 date format).</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="enddate">endDate</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:endDate</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>end date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data de fim</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/endDate">https://schema.org/endDate</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The end date and time of the item (in ISO 8601 date format).</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="hasobservation">hasObservation</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:hasObservation</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>has observation</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>tem observação</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#hasObservation">https://w3id.org/AlmesCore#hasObservation</a></td>
</tr>
<tr>
<td>Definition</td>
<td>Associates an entity (represented by an <code>dct:identifier</code>) to a specific recorded price <code>Observation</code> related to an agricultural product.</td>
</tr>
<tr>
<td>Comment</td>
<td>This metadata field should be used to create a blank node in an RDF representation, including the properties <code>dc:date</code>, <code>sdo:price</code>, and <code>sdo:currency</code>.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#dataset">Dataset</a></td>
</tr>
<tr>
<td>Range</td>
<td>alm:Observation</td>
</tr>
</tbody>
</table>
<h2 id="agent">Agent</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>foaf:Agent</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Agent</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Agente</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://xmlns.com/foaf/0.1/#term_Agent">http://xmlns.com/foaf/0.1/#term_Agent</a></td>
</tr>
<tr>
<td>Definition</td>
<td>An agent (eg. person, group, software or physical artifact).</td>
</tr>
</tbody>
</table>
<h3 id="name">name</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>foaf:name</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>name</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>nome</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://xmlns.com/foaf/0.1/#term_name">http://xmlns.com/foaf/0.1/#term_name</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A name for some thing.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent">Agent</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="homepage">homepage</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>foaf:homepage</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>homepage</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>homepage</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://xmlns.com/foaf/0.1/#term_homepage">http://xmlns.com/foaf/0.1/#term_homepage</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A homepage for some thing.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent">Agent</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h3 id="e-mail">e-mail</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>foaf:mbox</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>e-mail</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>e-mail</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://xmlns.com/foaf/0.1/#term_mbox">http://xmlns.com/foaf/0.1/#term_mbox</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A personal mailbox, ie. an Internet mailbox associated with exactly one owner, the first owner of this mailbox. This is a &#39;static inverse functional property&#39;, in that there is (across time and change) at most one individual that ever has any particular value for foaf:mbox.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#agent">Agent</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h2 id="geonamesfeature">GeoNamesFeature</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>gn:Feature</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>GeoNames Feature</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Característica Geográfica</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://www.geonames.org/ontology#Feature">http://www.geonames.org/ontology#Feature</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A geographical feature. It can be any feature that has a geographical extent, such as a country, city, mountain, river, etc.</td>
</tr>
</tbody>
</table>
<h3 id="geonamesname">geoNamesName</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>gn:name</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>geoNames name</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>nome geoNames</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://www.geonames.org/ontology#name">http://www.geonames.org/ontology#name</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The name of a geographical feature.</td>
</tr>
<tr>
<td>Comments</td>
<td>Examples: <code>New York</code>, <code>Mount Everest</code>, <code>Nile River</code>.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesfeature">GeoNamesFeature</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2000/01/rdf-schema#Literal">http://www.w3.org/2000/01/rdf-schema#Literal</a></td>
</tr>
</tbody>
</table>
<h3 id="geonamesid">geoNamesID</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>gn:geonamesID</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>geonames ID</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>identificador geoNames</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://www.geonames.org/ontology#geonamesID">http://www.geonames.org/ontology#geonamesID</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The ID of a geographical feature.</td>
</tr>
<tr>
<td>Comments</td>
<td>Examples: <code>http://sws.geonames.org/5128581/</code>, <code>http://sws.geonames.org/6252001/</code>, <code>http://sws.geonames.org/2347283/</code>.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#geonamesfeature">GeoNamesFeature</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#anyURI">http://www.w3.org/2001/XMLSchema#anyURI</a></td>
</tr>
</tbody>
</table>
<h2 id="observation">Observation</h2>
<table>
<thead>
<tr>
<th>Term name</th>
<th>alm:Observation</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Class</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>Observation</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>Observação</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://w3id.org/AlmesCore#Observation">https://w3id.org/AlmesCore#Observation</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A recorded observation of an agricultural product price on a specific date. The observation captures key attributes such as the price, date of observation, and the applicable currency, which provide a snapshot of the economic value of the product at a given time.</td>
</tr>
</tbody>
</table>
<h3 id="date">date</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>dc:date</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>date</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>data</td>
</tr>
<tr>
<td>URI</td>
<td><a href="http://purl.org/dc/elements/1.1/date">http://purl.org/dc/elements/1.1/date</a></td>
</tr>
<tr>
<td>Definition</td>
<td>A point or period of time associated with an event in the lifecycle of the resource.</td>
</tr>
<tr>
<td>Comment 1</td>
<td>Date may be used to express temporal information at any level of granularity. Recommended practice is to express the date, date/time, or period of time according to ISO 8601-1 [ISO 8601-1] or a published profile of the ISO standard, such as the W3C Note on Date and Time Formats [W3CDTF] or the Extended Date/Time Format Specification [EDTF]. If the full date is unknown, month and year (YYYY-MM) or just year (YYYY) may be used. Date ranges may be specified using ISO 8601 period of time specification in which start and end dates are separated by a &#39;/&#39; (slash) character. Either the start or end date may be missing.</td>
</tr>
<tr>
<td>Comment 2</td>
<td>In case the date is a range, <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#startdate">sdo:startDate</a> and <a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#enddate">sdo:ednDate</a> should be used instead to indicate the beginning and the end of the period.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#date">http://www.w3.org/2001/XMLSchema#date</a></td>
</tr>
</tbody>
</table>
<h3 id="price">price</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:price</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>price</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>preço</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/price">https://schema.org/price</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The offer price of a product.</td>
</tr>
<tr>
<td>Comment</td>
<td>The price should be indicated as a float number with two decimal digits.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#float">http://www.w3.org/2001/XMLSchema#float</a></td>
</tr>
</tbody>
</table>
<h3 id="currency">currency</h3>
<table>
<thead>
<tr>
<th>Term name</th>
<th>sdo:currency</th>
</tr>
</thead>
<tbody>
<tr>
<td>Type of Term</td>
<td>Property</td>
</tr>
<tr>
<td>Label (EN)</td>
<td>currency</td>
</tr>
<tr>
<td>Label (PT-BR)</td>
<td>moeda</td>
</tr>
<tr>
<td>URI</td>
<td><a href="https://schema.org/currency">https://schema.org/currency</a></td>
</tr>
<tr>
<td>Definition</td>
<td>The currency in which the monetary amount is expressed.</td>
</tr>
<tr>
<td>Comment</td>
<td>Use standard formats: ISO 4217 currency format, e.g. &quot;USD&quot;; Ticker symbol for cryptocurrencies, e.g. &quot;BTC&quot;; well known names for Local Exchange Trading Systems (LETS) and other currency types, e.g. &quot;Ithaca HOUR&quot;.</td>
</tr>
<tr>
<td>Domain</td>
<td><a href="https://github.com/AlmesCore/Almes-Core/blob/main/core2024-07-08.md#observation">Observation</a></td>
</tr>
<tr>
<td>Range</td>
<td><a href="http://www.w3.org/2001/XMLSchema#string">http://www.w3.org/2001/XMLSchema#string</a></td>
</tr>
</tbody>
</table>
