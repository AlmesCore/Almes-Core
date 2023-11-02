This document contains the most up-to-date version of the Agriculture and Livestock Metadata Element Set (Almes Core) metamodel, which expresses the relationships between classes and properties.
![image](https://github.com/AlmesCore/Almes-Core/assets/146739645/c56925ce-8d3c-41ed-99e1-96e06edfd16c)

PLantUML code:

@startuml
!define RECTANGLE class

RECTANGLE ResourceShape {
  +dct:title : Literal (1, 1)
  +dct:description : Literal (0, 1)
  +dct:modified : dateTime (0, 1)
  +dct:hasVersion : Literal (1, 1)
  +dct:language : IRI (0, 1)
  +dct:license : IRI (0, 1)
  +dct:rights : Literal (0, 1)
}

RECTANGLE AgentShape {
  +foaf:name : Literal (1, 1)
  +foaf:mbox : Literal (0, 1)
  +foaf:homepage : IRI (0, 1)
}

RECTANGLE DataShape {
  +dc:date : dateTime
  +sdo:price : Literal
  +sdo:currency : Literal
}

RECTANGLE DatasetShape {
  +alm:productGroup : IRI (1, 1)
  +alm:productType : IRI (0, 1)
  +alm:theme : IRI (0, *)
  +dcat:accessURL : IRI (0, 1)
  +dct:accrualPeriodicity : IRI (0, 1)
  +sdo:referenceQuantity : Literal (0, 1)
  +sdo:location : IRI (0, 1)
  +alm:statisticalMethod : IRI (0, 1)
}

ResourceShape "1" -- "1" AgentShape : publisher
ResourceShape "1" -- "*" AgentShape : creator
DatasetShape "1" -- "1" ResourceShape : hasMetadata
DatasetShape "*" -- "*" DataShape : hasData

@enduml




