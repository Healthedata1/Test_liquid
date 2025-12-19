# Practitioner 1 Example - Health eData 1 Sandbox v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Practitioner 1 Example**

## Example Practitioner: Practitioner 1 Example

| |
| :--- |
| *Page standards status:*[Informative](http://hl7.org/fhir/R4/versions.html#std-process) |

**Exception generating Narrative: Script template: Unknown flow control statement 'comment'**



## Resource Content

```json
{
  "resourceType" : "Practitioner",
  "id" : "practitioner-1",
  "meta" : {
    "extension" : [
      {
        "url" : "http://hl7.org/fhir/StructureDefinition/instance-name",
        "valueString" : "Practitioner 1 Example"
      },
      {
        "url" : "http://hl7.org/fhir/StructureDefinition/instance-description",
        "valueMarkdown" : "This is a practitioner 1 example for the *US Core Practitioner Profile*."
      }
    ],
    "profile" : [
      "http://hl7.org/fhir/us/core/StructureDefinition/us-core-practitioner"
    ]
  },
  "identifier" : [
    {
      "system" : "http://hl7.org/fhir/sid/us-npi",
      "value" : "9941339100"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/us/core/StructureDefinition/us-core-jurisdiction",
          "valueCodeableConcept" : {
            "coding" : [
              {
                "system" : "https://www.usps.com",
                "code" : "MA"
              }
            ],
            "text" : "Massachusetts"
          }
        }
      ],
      "system" : "http://www.acme.org/practitioners",
      "value" : "25456"
    }
  ],
  "name" : [
    {
      "family" : "Bone",
      "given" : ["Ronald"],
      "prefix" : ["Dr"]
    }
  ],
  "address" : [
    {
      "use" : "work",
      "line" : ["1003 Healthcare Drive"],
      "city" : "Amherst",
      "state" : "MA",
      "postalCode" : "01002"
    }
  ]
}

```
