# USCoreConditionAssertedDate - Health eData 1 Sandbox v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **USCoreConditionAssertedDate**

## SearchParameter: USCoreConditionAssertedDate 

| | | |
| :--- | :--- | :--- |
| *Official URL*:http://hl7.org/fhir/us/core/SearchParameter/us-core-condition-asserted-date | *Version*:0.1.0 | |
| *Standards status:*[Trial-use](http://hl7.org/fhir/R4/versions.html#std-process) | [Maturity Level](http://hl7.org/fhir/versions.html#maturity): 5 | *Computable Name*:USCoreConditionAssertedDate |

 
Returns conditions with an[assertedDate extension](http://hl7.org/fhir/StructureDefinition/condition-assertedDate)matching the specified date (dateTime). 



## Resource Content

```json
{
  "resourceType" : "SearchParameter",
  "id" : "us-core-condition-asserted-date",
  "extension" : [
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-fmm",
      "valueInteger" : 5
    },
    {
      "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-standards-status",
      "valueCode" : "trial-use",
      "_valueCode" : {
        "extension" : [
          {
            "url" : "http://hl7.org/fhir/StructureDefinition/structuredefinition-conformance-derivedFrom",
            "valueCanonical" : "http://www.fhir.org/guides/healthedata1-sandbox/ImplementationGuide/healthedata1-sandbox"
          }
        ]
      }
    }
  ],
  "url" : "http://hl7.org/fhir/us/core/SearchParameter/us-core-condition-asserted-date",
  "version" : "0.1.0",
  "name" : "USCoreConditionAssertedDate",
  "status" : "active",
  "experimental" : false,
  "date" : "2023-04-13",
  "publisher" : "Health eData Inc",
  "contact" : [
    {
      "telecom" : [
        {
          "system" : "email",
          "value" : "mailto:ehaas@healthedatainc.com"
        }
      ]
    }
  ],
  "description" : "Returns conditions with an [assertedDate extension](http://hl7.org/fhir/StructureDefinition/condition-assertedDate) matching the specified date (dateTime).",
  "code" : "asserted-date",
  "base" : ["Condition"],
  "type" : "date",
  "expression" : "Condition.extension.where(url = 'http://hl7.org/fhir/StructureDefinition/condition-assertedDate').value",
  "xpathUsage" : "normal",
  "multipleOr" : true,
  "_multipleOr" : {
    "extension" : [
      {
        "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
        "valueCode" : "MAY"
      }
    ]
  },
  "multipleAnd" : true,
  "_multipleAnd" : {
    "extension" : [
      {
        "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
        "valueCode" : "SHOULD"
      }
    ]
  },
  "comparator" : [
    "eq",
    "ne",
    "gt",
    "ge",
    "lt",
    "le",
    "sa",
    "eb",
    "ap"
  ],
  "_comparator" : [
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "MAY"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "MAY"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "SHALL"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "SHALL"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "SHALL"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "SHALL"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "MAY"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "MAY"
        }
      ]
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/StructureDefinition/capabilitystatement-expectation",
          "valueCode" : "MAY"
        }
      ]
    }
  ]
}

```
