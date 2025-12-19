# USCoreCareTeamRole - Health eData 1 Sandbox v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **USCoreCareTeamRole**

## SearchParameter: USCoreCareTeamRole 

| | | |
| :--- | :--- | :--- |
| *Official URL*:http://hl7.org/fhir/us/core/SearchParameter/us-core-careteam-role | *Version*:0.1.0 | |
| *Standards status:*[Trial-use](http://hl7.org/fhir/R4/versions.html#std-process) | [Maturity Level](http://hl7.org/fhir/versions.html#maturity): 5 | *Computable Name*:USCoreCareTeamRole |

 
Returns CareTeam resources with a participant role matching the specified code. 



## Resource Content

```json
{
  "resourceType" : "SearchParameter",
  "id" : "us-core-careteam-role",
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
  "url" : "http://hl7.org/fhir/us/core/SearchParameter/us-core-careteam-role",
  "version" : "0.1.0",
  "name" : "USCoreCareTeamRole",
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
  "description" : "Returns CareTeam resources with a participant role matching the specified code.",
  "code" : "role",
  "base" : ["CareTeam"],
  "type" : "token",
  "expression" : "CareTeam.participant.role",
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
