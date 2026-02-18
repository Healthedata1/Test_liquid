# Resource example-requirements



## Resource Content

```json
{
  "resourceType" : "Basic",
  "id" : "example-requirements",
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-fmm",
      "valueInteger" : 2,
      "_valueInteger" : {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom",
            "valueCanonical" : "http://hl7.org/fhir/us/healthedata1-sandbox/ImplementationGuide/hl7.fhir.us.healthedata1-sandbox"
          }
        ]
      }
    },
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-standards-status",
      "valueCode" : "trial-use",
      "_valueCode" : {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom",
            "valueCanonical" : "http://hl7.org/fhir/us/healthedata1-sandbox/ImplementationGuide/hl7.fhir.us.healthedata1-sandbox"
          }
        ]
      }
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.url",
      "valueUri" : "http://example.org/fhir/Requirements/example"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.version",
      "valueString" : "0.1.0"
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
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.status",
      "valueCode" : "draft"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.date",
      "valueDateTime" : "2026-02-18T02:49:37+00:00"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.publisher",
      "valueString" : "HL7 International / Payer/Provider Information Exchange Work Group"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.contact",
      "valueContactDetail" : {
        "name" : "HL7 International / Payer/Provider Information Exchange Work Group",
        "telecom" : [
          {
            "system" : "url",
            "value" : "http://www.hl7.org/Special/committees/claims"
          },
          {
            "system" : "email",
            "value" : "pie@lists.hl7.org"
          }
        ]
      }
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.jurisdiction",
      "valueCodeableConcept" : {
        "coding" : [
          {
            "system" : "urn:iso:std:iso:3166",
            "code" : "US"
          }
        ]
      }
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.actor",
      "_valueCanonical" : {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/StructureDefinition/display",
            "valueString" : "US Core Requestor (Servers including Certifying Systems)"
          }
        ]
      }
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/us/core/StructureDefinition/uscdi-requirement",
          "valueString" : "true"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "stmt-01"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The system **SHALL** allow the actor to search for patients by name."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "stmt-02"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The system **SHOULD** display patient demographics in a summary view."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "stmt-03"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The system **MAY** support bulk export of patient records."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    }
  ],
  "code" : {
    "coding" : [
      {
        "system" : "http://hl7.org/fhir/fhir-types",
        "code" : "Requirements"
      }
    ]
  }
}

```
