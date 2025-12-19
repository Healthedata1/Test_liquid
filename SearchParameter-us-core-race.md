# USCoreRace - Health eData 1 Sandbox v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **USCoreRace**

## SearchParameter: USCoreRace 

| | | |
| :--- | :--- | :--- |
| *Official URL*:http://hl7.org/fhir/us/core/SearchParameter/us-core-race | *Version*:0.1.0 | |
| *Standards status:*[Trial-use](http://hl7.org/fhir/R4/versions.html#std-process) | [Maturity Level](http://hl7.org/fhir/versions.html#maturity): 5 | *Computable Name*:USCoreRace |

 
Returns patients with a race extension matching the specified code. 



## Resource Content

```json
{
  "resourceType" : "SearchParameter",
  "id" : "us-core-race",
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
  "url" : "http://hl7.org/fhir/us/core/SearchParameter/us-core-race",
  "version" : "0.1.0",
  "name" : "USCoreRace",
  "status" : "active",
  "experimental" : false,
  "date" : "2022-04-14",
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
  "description" : "Returns patients with a race extension matching the specified code.",
  "code" : "race",
  "base" : ["Patient"],
  "type" : "token",
  "expression" : "Patient.extension.where(url = 'http://hl7.org/fhir/us/core/StructureDefinition/us-core-race').extension.value.code",
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
        "valueCode" : "MAY"
      }
    ]
  }
}

```
