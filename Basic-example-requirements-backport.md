# example-requirements-backport - Health eData 1 Sandbox v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **example-requirements-backport**

## Basic: example-requirements-backport

Profile: `http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements`

**Extension Definition for Requirements.url for Version 5.0**: [Example Requirements Resource](Requirements-example-requirements.md)

**Extension Definition for Requirements.name for Version 5.0**: ExampleRequirements

**Extension Definition for Requirements.title for Version 5.0**: Example Requirements Resource

**Extension Definition for Requirements.version for Version 5.0**: 1.0.0

**Extension Definition for Requirements.status for Version 5.0**: draft

**Extension Definition for Requirements.date for Version 5.0**: 2026-02-13

**Extension Definition for Requirements.publisher for Version 5.0**: Example Organization

**Extension Definition for Requirements.jurisdiction for Version 5.0**: United States of America

**Extension Definition for Requirements.copyright for Version 5.0**: 

Copyright (c) 2026 Example Organization. All rights reserved.

> **Extension Definition for Requirements.actor for Version 5.0**
* key: actor-01
* reference: Clinical End User

> **Extension Definition for Requirements.statement for Version 5.0**
* key: stmt-01
* conformance: SHALL
* requirement: 
* actor: actor-01

The system SHALL allow the actor to search for patients by name.

> **Extension Definition for Requirements.statement for Version 5.0**
* key: stmt-02
* conformance: SHOULD
* requirement: 
* actor: actor-01

The system SHOULD display patient demographics in a summary view.

**code**: Requirements



## Resource Content

```json
{
  "resourceType" : "Basic",
  "id" : "example-requirements-backport",
  "meta" : {
    "profile" : [
      "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements"
    ]
  },
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.url",
      "valueUri" : "http://example.org/fhir/Requirements/example"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.name",
      "valueString" : "ExampleRequirements"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.title",
      "valueString" : "Example Requirements Resource"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.version",
      "valueString" : "1.0.0"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.status",
      "valueCode" : "draft"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.date",
      "valueDateTime" : "2026-02-13"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.publisher",
      "valueString" : "Example Organization"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.jurisdiction",
      "valueCodeableConcept" : {
        "coding" : [
          {
            "system" : "urn:iso:std:iso:3166",
            "code" : "US",
            "display" : "United States of America"
          }
        ]
      }
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.copyright",
      "valueMarkdown" : "Copyright (c) 2026 Example Organization. All rights reserved."
    },
    {
      "extension" : [
        {
          "url" : "key",
          "valueId" : "actor-01"
        },
        {
          "url" : "reference",
          "valueReference" : {
            "display" : "Clinical End User"
          }
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.actor"
    },
    {
      "extension" : [
        {
          "url" : "key",
          "valueId" : "stmt-01"
        },
        {
          "url" : "conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "requirement",
          "valueMarkdown" : "The system SHALL allow the actor to search for patients by name."
        },
        {
          "url" : "actor",
          "valueId" : "actor-01"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "key",
          "valueId" : "stmt-02"
        },
        {
          "url" : "conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "requirement",
          "valueMarkdown" : "The system SHOULD display patient demographics in a summary view."
        },
        {
          "url" : "actor",
          "valueId" : "actor-01"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    }
  ],
  "code" : {
    "coding" : [
      {
        "system" : "http://hl7.org/fhir/fhir-types",
        "code" : "Requirements",
        "display" : "Requirements"
      }
    ]
  }
}

```
