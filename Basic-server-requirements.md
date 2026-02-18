# Resource server-requirements



## Resource Content

```json
{
  "resourceType" : "Basic",
  "id" : "server-requirements",
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
      "valueUri" : "http://example.org/fhir/Requirements/server-requirements"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.version",
      "valueString" : "0.1.0"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.name",
      "valueString" : "ServerRequirements"
    },
    {
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.title",
      "valueString" : "Server Requirements"
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
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0001"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To support a US Core Profile, a Server: **SHALL** Be able to populate all profile data elements that are mandatory and/or flagged as Must Support as defined by that profile’s StructureDefinition."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0002"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To support a US Core Profile, a Server: **SHOULD** declare support for a US Core Profile by including its official URL in the Server’s `CapabilityStatement.rest.resource.supportedProfile` element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0003"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers may deploy and support one or more US Core Profiles to represent clinical information"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0004"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Server may deploy and support ... the following US Core interaction: “Quick Start” defined for each Profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0005"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Server may deploy and support ... the following US Core interaction: [Clinical Notes](https://hl7.org/fhir/us/core/clinical-notes.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0006"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Server may deploy and support ... the following US Core interaction: [Medication List](https://hl7.org/fhir/us/core/medication-list.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0007"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Server may deploy and support ... the following US Core interaction: [Basic Provenance](https://hl7.org/fhir/us/core/basic-provenance.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0008"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Server may deploy and support ... the following US Core interaction: [Screening and Assessments](https://hl7.org/fhir/us/core/screening-and-assessments.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0009"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers implementing ... [clinical information representation] can claim conformance to the US Core Profile content structure ... by implementing all or parts of the US Core CapabilityStatement into their capabilities."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0010"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers implementing ... [interactions] can claim conformance to the ... RESTful interactions defined by implementing all or parts of the US Core CapabilityStatement into their capabilities"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/us/core/StructureDefinition/uscdi-requirement",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0011"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server that certifies to the [21st Century Cures Act for accessing patient data](https://www.federalregister.gov/d/2020-07419/p-1177) must implement all components in the USCDI [[USCDI link](https://www.healthit.gov/isp/united-states-core-data-interoperability-uscdi)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/us/core/StructureDefinition/uscdi-requirement",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0012"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server that certifies to the [21st Century Cures Act for accessing patient data](https://www.federalregister.gov/d/2020-07419/p-1177) must implement all components in the ... the US Core CapabilityStatement [[Definition](https://hl7.org/fhir/us/core/CapabilityStatement-us-core-Server.html)] ."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0013"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To claim conformance to a US Core Profile] a conformant Server:\n\n**SHALL** Be able to populate all profile data elements that are mandatory and/or flagged as Must Support as defined by that profile’s StructureDefinition."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0014"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To claim conformance to a US Core Profile] a conformant Server:\n\n**SHOULD** declare conformance with the US [Core Server Capability Statement](https://hl7.org/fhir/us/core/CapabilityStatement-us-core-Server.html) by including its official URL in the Server’s `CapabilityStatement.instantiates` element: `http://hl7.org/fhir/us/core/CapabilityStatement/us-core-Server`"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0015"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To claim conformance to a US Core Profile] a conformant Server:\n\n**SHALL** specify the full capability details from the US Core CapabilityStatement it claims to implement."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0016"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To claim conformance to a US Core Profile] a conformant Server:\n\n**SHALL**… Declare support for the US Core Profile by including its official URL in the Server’s CapabilityStatement.rest.resource.supportedProfile element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0017"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To claim conformance to a US Core Profile] a conformant Server:\n\n**SHALL**… Declare support for the US Core Profile’s FHIR RESTful transactions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0018"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Required binding](http://hl7.org/fhir/R4/terminologies.html#required) to a ValueSet definition means that one of the codes from the specified ValueSet **SHALL** be used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0019"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For `CodeableConcept`, which permits multiple codings and a text element, this [[Required binding](http://hl7.org/fhir/R4/terminologies.html#required) to a ValueSet definition] rule applies to at least one of the codings"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0020"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For a [[required binding](http://hl7.org/fhir/R4/terminologies.html#required) to a ValueSet definition], a `CodeableConcept`which permits multiple codings and a text element … [using] only text is not valid."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0021"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When populating a coded element with a [required binding](http://hl7.org/fhir/R4/terminologies.html#required] to a ValueSet definition] US Core Responders **SHALL** provide a code exclusively from [the required binding] ValueSet"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0023"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Extensible binding] (http://hl7.org/fhir/R4/terminologies.html#extensible) means that one of the codes from the specified ValueSet **SHALL** be used if an applicable concept is present."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0024"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When using an [extensible Binding] (http://hl7.org/fhir/R4/terminologies.html#extensible)] If no suitable code exists in the [extensible] ValueSet, alternate code(s) may be provided."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0026"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For `CodeableConcept` [with an [extensible binding] (http://hl7.org/fhir/R4/terminologies.html#extensible) … If only text is available and it has no conceptual overlap with the bound coded values, then just text may be used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0027"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When claiming conformance to ... [to a US Core profile extensible binding rule, a] US Core Responders Shall provide:\nA code from … [the] valueset 'DataElement.code.code' if the concept exists in the valueset [for a DataElement.code that has an extensible binding]\nOr an alternative code if the concept does not exist in the valueset [for a DataElement.code that has an extensible binding]\nOr text in ... `[DataElement.code.text]’ if only text is available [for a DataElement.code that has an extensible binding]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0029"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Alternate codes may be provided in addition to the standard codes defined in required or extensible ValueSets. These alternate codes are called \"additional codings\"."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0030"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The additional codings] may be equivalent to or narrower in meaning than the standard concept code."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0033"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Not all modifier elements are Mandatory or Must Support, and there is no requirement for supporting them"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0034"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers **MAY** communicate a system-wide profile in their CapabilityStatement to identify which additional elements, including modifier elements, they support"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0039"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the source system does not have data for an element with a minimum cardinality = 0 (including elements labeled Must Support), the data element **SHALL** be omitted from the resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0040"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the data element is a Mandatory element (in other words, where the minimum cardinality is > 0), it **SHALL** be present even if the source system does not have data."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0041"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For [mandatory] non-coded data elements [where data is not available], use the [DataAbsentReason Extension](http://hl7.org/fhir/R4/extension-data-absent-reason.html) in the data type ... [with] the code `unknown` - The value is expected to exist but is not known."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0042"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements … [with] *example*, *preferred*, or *extensible* binding strengths (CodeableConcept or Coding datatypes) If the source system has text but no coded data, only the text element is used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0043"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements… [with] *example*, *preferred*, or *extensible* binding strengths (CodeableConcept or Coding datatypes):\nFor Coding datatypes, the text-only data is represented as a display element"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0044"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements… [with] *example*, *preferred*, or *extensible* binding strengths (CodeableConcept or Coding datatypes): … If there is neither text nor coded data ... [then] use the appropriate “unknown” concept code from the ValueSet if available."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0045"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements… [with] *example*, *preferred*, or *extensible* binding strengths (CodeableConcept or Coding datatypes): … If there is neither text nor coded data ... [then] if the ValueSet does not have the appropriate “unknown” concept code, use unknown from the [DataAbsentReason Code System](http://hl7.org/fhir/R4/codesystem-data-absent-reason.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0046"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements… [with] *required* binding strength (CodeableConcept or code datatypes): use the appropriate “unknown” concept code from the ValueSet if available"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0047"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In situations where data is not available] for [mandatory] coded data elements… [with] *required* binding strength (CodeableConcept or code datatypes): If the ValueSet does not have the appropriate “unknown” concept code, you must use a concept from the ValueSet. Otherwise, the instance will not be conformant"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0048"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If the source system does not have data for a Mandatory element for a coded data element with *required* binding strength] If any of these status codes is missing [meaning it lacks an \"unknown\" or otherwise appropriate concept code from the ValueSet, a] 404 HTTP error code and an OperationOutcome **SHALL** be returned in response to a read transaction on the resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0049"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If the source system does not have data for a Mandatory element for a coded data element with *required* binding strength, and the ValueSet does not have the appropriate \"unknown\" concept code, then] if returning a response to a search, the problematic resource **SHALL** be excluded from the search set"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0050"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If the source system does not have data for a Mandatory element for a coded data element with *required* binding strength, and the ValueSet does not have the appropriate \"unknown\" concept code, then] if returning a response to a search, … a *warning* OperationOutcome **SHOULD** be included indicating that other search results were found but could not be compliantly expressed and have been suppressed."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0051"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The [FHIR RESTful Search API](http://hl7.org/fhir/R4/http.html#search) requires that Servers that support search **SHALL** support the HTTP `POST`-based search."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0052"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For all the supported search interactions in this guide, Servers **SHALL** also support the `GET`-based search."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0055"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When searching using the `token` type searchparameter [(how to search by token)](http://hl7.org/fhir/R4/search.html#token) The Server **SHALL** support both [system and code values]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0058"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When searching using the `reference` type searchparameter [(how to search by reference)](http://hl7.org/fhir/R4/search.html#reference) The Server **SHALL** support both [id and Type values]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0061"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When searching using the `date` type searchparameter [(how to search by date)](http://hl7.org/fhir/R4/search.html#date) The Server **SHALL** support values precise to the day for elements of datatype `date`"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0062"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When searching using the `date` type searchparameter [(how to search by date)](http://hl7.org/fhir/R4/search.html#date) The Server **SHALL** support values precise … to the second + time offset for elements of `datatype` dateTime"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0063"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers are strongly encouraged to support a query for resources without requiring a status parameter."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0064"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If business requirements prohibit [querying a resource without a status parameter], they **SHALL** follow the guidelines here."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0065"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For searches where the Client does not supply a status parameter, an implementation’s business rules may override the FHIR RESTful search expectations and require a status parameter to be provided"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0066"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For searches where the Client does not supply a status parameter, … systems [that require a status parameter to be provided] are allowed to reject such requests as follows:\n\n**SHALL** return an HTTP 400 status"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0067"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For searches where the Client does not supply a status parameter, … systems [that require a status parameter to be provided] are allowed to reject such requests as follows:\n\n**SHALL** return an [OperationOutcome](http://hl7.org/fhir/R4/operationoutcome.html) specifying that status(es) must be present."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0068"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For searches where the Client does not supply a status parameter, … systems [that require a status parameter to be provided] are allowed to reject such requests as follows:\n\n**SHALL** support search with status if status required"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0069"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For systems that require a status parameter to be provided, they] **SHALL** NOT restrict search results ( i.e., apply ‘hidden’ filters) when a Client includes status parameters in the query."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0070"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For systems that require a status parameter to be provided,] if a system doesn’t support a specific status code value that is queried, it **SHOULD** return an HTTP 200 status with a search bundle."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0071"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For systems that require a status parameter to be provided,] if a system doesn’t support a specific status code value that is queried [and returns a search bundle],... [t]he search bundle **SHOULD** contain resources matching the search criteria"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0072"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For systems that require a status parameter to be provided,] if a system doesn’t support a specific status code value that is queried [and returns a search bundle],... [t]he search bundle **SHOULD** contain ... an OperationOutcome warning the Client which status code value is not supported."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0073"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For searches where the Client does not supply a status parameter, … systems [that require a status parameter to be provided] are allowed to reject such requests as follows:...\n\n**SHALL** document this behavior in its CapabilityStatement for the “search-type” interaction in `CapabilityStatement.rest.resource.interaction.documentation.`"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0074"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When an element is Mandatory, the data is expected always to be present."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0075"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For querying and reading US Core Profiles, Must Support on any profile data element **SHALL** be interpreted as follows…:\n\nUS Core Responders **SHALL** be capable of populating all data elements as part of the query results specified by the [US Core Server Capability Statement](https://hl7.org/fhir/us/core/STU8/CapabilityStatement-us-core-Server.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0078"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For querying and reading US Core Profiles, Must Support on any profile data element **SHALL** be interpreted as follows…:\n\nWhen information on a particular data element is not present, and the reason for absence is unknown, US Core Responders **SHALL NOT** include the data elements in the resource instance returned as part of the query results."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0080"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For querying and reading US Core Profiles, Must Support on any profile data element **SHALL** be interpreted as follows…:\n\nIn cases where information on a specific data element is missing, and the US Core Responder knows the precise reason for the absence of data (other than suppressed data), US Core Responders **SHOULD** send the reason for the missing information."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0081"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When sending reason for missing information, follow] the same methdology outlined in the [Missing Data](https://hl7.org/fhir/us/core/STU8/general-requirements.html#missing-data) section but using the appropriate reason code instead of unknown [reason code]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0084"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementors [US Core Responders] seeking ONC certification [in the ONC IT Health Certification program] **SHALL** interpret Additional USCDI Requirements as Must Support elements as documented above and below;"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0086"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementors [US Core Responders] [not] seeking ONC certification [in the ONC IT Health Certification program] **SHALL** interpret Additional USCDI Requirements as … optional."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0087"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If an element is marked as Must Support and defined by a pattern [as described by [ElementDefinition.pattern](http://hl7.org/fhir/R4/elementdefinition-definitions.html#ElementDefinition.pattern_x_)], then the pattern defines the elements and element values that the Server **SHALL** be capable of providing."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0090"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Primitive elements are single elements with a primitive value. If they are marked as Must Support, then the Server **SHALL** be capable of providing the element value to meet the Must Support requirement."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0091"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[W]hen claiming conformance [to a profile with a must support primitive element] … US Core responders SHALL be capable of providing the value [of the primitive element]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0093"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For any complex element marked as Must Support, the Server **SHALL** be capable of providing at least one of the sub-element values."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0094"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If any sub-element is marked as Must Support [for a complex element], it must also meet the Must Support requirements and satisfy the Must Support requirements for the parent element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0095"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f any sub-element is marked as Must Support or Additional USCDI [for a complex element] and the parent element is not, there is no expectation that you must support the parent."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0096"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f any sub-element is marked as Must Support [for a complex element] and the parent element is not… [and] the parent element is represented in the structure, Servers SHALL support the sub-element(s) marked as Must Support."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0097"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When claiming conformance [to a must support complex element with no must support sub-elements] … US Core Responders SHALL be capable of providing a value in [the] sub-element"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0099"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When claiming conformance [to a must support complex element with one or more must support sub-elements] … US Core Responders SHALL be capable of providing a value in [each must support sub-element]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0101"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems [US Core Responders] can support the other elements [of a complex element, not labeled as a Must Support], but this is not a requirement of US Core"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0103"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The U.S. Core Data for Interoperability (USCDI) may require additional elements, [which is a requirement for certification in the ONC IT Health Certification program, but not a requirement of US Core conformance for US Core Responders]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0105"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "In certain profiles, only specific resource references are labeled as Must Support.\n\n...\n\n- US Core Responders **SHALL** be capable of providing [such an element] with a valid reference to [all listed Must Support profile(s).]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0107"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems [US Core Responders] can support other [resource] references [other than those labeled as Must Support], but this is not a requirement of US Core"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0109"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "In specific profiles, only a single resource reference is present on an element labeled Must Support.\n\n...\n\n- US Core Responders **SHALL** be capable of providing [such an element] with a valid reference to [the Must Support Profile.]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0111"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a profile has] a Must Support element [with] a choice of datatypes for its content [and some of] the datatypes … are labeled as Must Support[, or a profile has] an Additional USCDI element [with] a choice of datatypes for its content [and some of] the datatypes … are labeled as Additional USCDI\n\n… When claiming conformance to [such a] profile:\n\n- US Core Responders **SHALL** be capable of populating [the Must Support or Additional USCDI data type choice]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0114"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a profile has] a Must Support element [with] a choice of datatypes for its content [and some of] the datatypes … are labeled as Must Support[, or a profile has] an Additional USCDI element [with] a choice of datatypes for its content [and some of] the datatypes … are labeled as Additional USCDI\n\n…\n\n[US Core Responders] **MAY** support populating ... other [data type] choice elements (such as Observation.effectivePeriod), but this is not a requirement of US Core."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0115"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "There are several instances in this Guide where there is a choice of supporting one or another profile element to meet the Must Support or Additional USCDI requirement. In such cases, the Server  or Certifying System **SHALL** support at least one element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0117"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An individual SMART Server will publish a granular list of its capabilities, and a set of these capabilities is combined to support a specific use, a Capability Set. See SMART App Launch’s [FHIR OAuth authorization Endpoints and Capabilities](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#smart-on-fhir-oauth-authorization-endpoints-and-capabilities) for more details. Servers MAY support ... [any] SMART on FHIR Capability Sets and capabilities [(see [FHIR OAuth authorization Endpoints and Capabilities](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#smart-on-fhir-oauth-authorization-endpoints-and-capabilities))]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0118"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "At least one of the following SMART on FHIR Capability Sets SHOULD be supported for US Core Servers that support User-Facing Applications ...\n[Patient Access Standalone Apps](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#patient-access-for-standalone-apps)\n[Clinician Access for EHR Launch](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#clinician-access-for-standalone)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0119"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For certified systems[, those participating in the ONC IT Health Certification program], both SHALL be supported:\n[Patient Access Standalone Apps](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#patient-access-for-standalone-apps)\n[Clinician Access for EHR Launch](http://hl7.org/fhir/smart-app-launch/STU2/conformance.html#clinician-access-for-standalone)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0120"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementations [US Core Responders] supporting Backend Services ... SHALL include support for the Client-confidential-asymmetric capability."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0121"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementations [US Core Responders] supporting Backend Services ... SHALL include support for the ... system/scopes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0122"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementations [US Core Requestors] supporting Backend Services – for example, to meet US EHR certification requirements [of the ONC IT Health Certification program]- SHALL include support for the Client-confidential-asymmetric capability and system/scopes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0123"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server[s] SHALL support token introspection defined by the SMART App Launch Guide. For more details and additional consideration, see SMART App Launch’s [Token Introspection](http://hl7.org/fhir/smart-app-launch/STU2/token-introspection.html#token-introspection)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0124"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementations meeting US EHR certification [of the ONC IT Health Certification program] requirements must support all US Core’s required scopes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0125"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Other systems only need to support scopes for the US Core APIs they support [instead of all US Core's required scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0126"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers MAY support other scopes in addition to those listed below and in the Quick Start sections."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0128"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For “User-Facing Applications”, a system’s support for patient-level (patient) or user-level (user) scopes depends on its published list of SMART on FHIR capabilities (see the [capability sets](https://hl7.org/fhir/us/core/STU8/scopes.html#capability-sets) above). For example, if a Server lists permission-patient and permission-user in its capabilities, it SHALL support both patient-level and user-level required scopes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0129"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For “User-Facing Applications”, a system’s support for patient-level (patient) or user-level (user) scopes depends on its published list of SMART on FHIR capabilities (see the [capability sets](https://hl7.org/fhir/us/core/STU8/scopes.html#capability-sets) above). For example, if a Server lists permission-patient and permission-user in its capabilities, it ... SHOULD support both patient-level and user-level recommended best-practice scopes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0130"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For “Backend-Services”, System-level scopes (system) describe data that a Client system is directly authorized to access. Systems that support system-level (system) scopes SHALL support the required US Core scopes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0131"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For “Backend-Services”, System-level scopes (system) describe data that a Client system is directly authorized to access. Systems that support system-level (system) scopes SHOULD support the recommended US Core scopes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0132"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] AllergyIntolerance [the] <patient|user|system>/AllergyIntolerance.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0133"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] CarePlan [the] <patient|user|system>/CarePlan.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0134"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] CareTeam [the] <patient|user|system>/CareTeam.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0135"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Condition [the] <patient|user|system>/Condition.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0136"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Coverage [the] <patient|user|system>/Coverage.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0137"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Device [the] <patient|user|system>/Device.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0138"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] DiagnosticReport [the] <patient|user|system>/DiagnosticReport.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0139"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] DocumentReference [the] <patient|user|system>/DocumentReference.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0140"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Encounter [the] <patient|user|system>/Encounter.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0141"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Goal [the] <patient|user|system>/Goal.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0142"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Immunization [the] <patient|user|system>/Immunization.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0143"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] MedicationDispense [the] <patient|user|system>/MedicationDispense.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0144"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] MedicationRequest [the] <patient|user|system>/MedicationRequest.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0145"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0146"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Organization [the] <patient|user|system>/Organization.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0147"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Patient [the] <patient|user|system>/Patient.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0148"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Practitioner [the] <patient|user|system>/Practitioner.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0149"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] PractitionerRole [the] <patient|user|system>/PractitionerRole.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0150"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Procedure [the] <patient|user|system>/Procedure.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0151"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Provenance [the] <patient|user|system>/Provenance.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0152"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] QuestionnaireResponse [the] <patient|user|system>/QuestionnaireResponse.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0153"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] RelatedPerson [the] <patient|user|system>/RelatedPerson.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0154"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] ServiceRequest [the] <patient|user|system>/ServiceRequest.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0155"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **SHALL** be supported\n...\n[For] Specimen [the] <patient|user|system>/Specimen.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0156"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **MAY** be supported\n...\n[For] Location [the] <patient|user|system>/Location.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0157"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following scopes that correspond directly to FHIR resource types **MAY** be supported\n...\n[For] Medication [the] <patient|user|system>/Medication.rs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0158"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Condition [the] <patient|user|system>/Condition.rs?category=http://hl7.org/fhir/us/core/CodeSystem/condition-category|health-concern [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0159"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Condition [the] <patient|user|system>/Condition.rs?category=http://terminology.hl7.org/CodeSystem/condition-category|encounter-diagnosis [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0160"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Condition [the] <patient|user|system>/Condition.rs?category=http://terminology.hl7.org/CodeSystem/condition-category|problem-list-item [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0161"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs?category=http://hl7.org/fhir/us/core/CodeSystem/us-core-category|sdoh [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0162"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs?category=http://terminology.hl7.org//CodeSystem-observation-category|social-history [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0163"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs?category=http://terminology.hl7.org/CodeSystem/observation-category|laboratory [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0164"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs?category=http://terminology.hl7.org/CodeSystem/observation-category|survey [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0165"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHALL** be supported\n...\n[For] Observation [the] <patient|user|system>/Observation.rs?category=http://terminology.hl7.org/CodeSystem/observation-category|vital-signs [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0166"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following granular scopes **SHOULD** be supported\n...\n[For] DocumentReference [the] <patient|user|system>/DocumentReference.rs?category=http://hl7.org/fhir/us/core/CodeSystem/us-core-documentreference-category|clinical-note [see [SMART Clinical Scope Syntax](https://hl7.org/fhir/smart-app-launch/STU2/scopes-and-launch-context.html#clinical-scope-syntax) for details on clinical data scopes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0167"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "In addition to the capabilities defined in the Server’s CapabilityStatement, Servers SHALL document their SMART capabilities in their [Well-Known Uniform Resource Identifiers (URIs)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known) JSON file."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0168"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core requires ... additional metadata [to be available through the Server's [Well-Known Uniform Resource Identifier (URI)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known)]: ... [in] `scopes_supported` [the] array of scopes a Client may request.... The Server SHALL list all the required US Core Scopes for the US Core Profiles they support in the scopes_supported array"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0169"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core requires ... additional metadata [to be available through the Server's [Well-Known Uniform Resource Identifier (URI)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known)]: ... [in] `scopes_supported` [the] array of scopes a Client may request. The Server [MAY support] additional scopes (so Clients should not consider … [the required scopes] an exhaustive list)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0170"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core requires ... additional metadata [to be available through the Server's [Well-Known Uniform Resource Identifier (URI)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known)]: ... [in] `scopes_supported` [the] array of scopes a Client may request. Servers MAY limit Clients’ scopes to those configured at registration time."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0171"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core requires ... additional metadata [to be available through the Server's [Well-Known Uniform Resource Identifier (URI)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known)]: ... [in] `scopes_supported` [the] array of scopes a Client may request. … Servers SHALL allow users to select a subset of the requested scopes at the approval time."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0173"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core requires ... additional metadata [to be available through the Server's [Well-Known Uniform Resource Identifier (URI)](https://hl7.org/fhir/smart-app-launch/STU2/conformance.html#using-well-known)]: ... [in] `introspection_endpoint` the URL to a Server’s introspection endpoint. ... Servers SHALL document this endpoint in the file"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0174"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Therefore, a [reference](http://hl7.org/fhir/R4/references.html) to a US Core resource SHOULD include a logical id (Reference.reference), not an identifier (Reference.identifier)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0175"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For all references, US Core Responders SHOULD return resources that conform to a US Core profile if a US Core profile exists for the resource type."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0176"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD-NOT"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When responding to a query, Servers SHOULD not use inline [contained](http://hl7.org/fhir/R4/references.html#contained) resources to represent the returned data."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0177"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f referencing a contained resource in a US Core Profile, the contained resource SHOULD be a US Core Profile if a US Core Profile exists for the resource type."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0178"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[M]asking data [where a specific piece of data is hidden for security and privacy reasons] SHOULD be handled based on implemented policies."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0179"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When masking data] elements with a minimum cardinality = 0 (including elements labeled Must Support) [for security and privacy reasons], the element SHOULD be omitted from the resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0180"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When masking] Mandatory elements (in other words, where the minimum cardinality is > 0) [for security and privacy reasons, use the code “unknown” following the guidance on Missing Data in the Conformance Sections."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0181"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When using SNOMED codes in US Core Profiles I]mplementers MAY use the default system URI [of [SNOMED CT](http://snomed.info/sct)], which refers to an unspecified edition/version [of SNOMED]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0182"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[To enable] terminology Servers to be able to validate US Edition-only codes [of [SNOMED CT](http://snomed.info/sct)], implementers SHOULD provide the accompanying system URI to describe the edition [see example 2 on [US Core general guidance](https://hl7.org/fhir/us/core/STU8/general-guidance.html#snomed-ct-united-states-edition)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0183"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] US Core Profiles binds the Quantity.code element in the Quantity datatype to the [UCUM](http://unitsofmeasure.org/) code system, [then] systems should also use UCUM for the optional valueRange and valueRatio datatypes (which are complex datatypes with Quantity elements)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0184"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] US Core Profiles binds the Quantity.code element in the Quantity datatype to the [UCUM](http://unitsofmeasure.org/) code system, [when] UCUM code [is] provided [it SHOULD be indicated in the Quantity.unit and Quantity.code elements with Quantity.system = \"http://unitsofmeasure.org\"]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0185"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] US Core Profiles binds the Quantity.code element in the Quantity datatype to the [UCUM](http://unitsofmeasure.org/) code system, [then] if UCUM units are unavailable, represent units in the unit element"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0186"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD-NOT"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] US Core Profiles binds the Quantity.code element in the Quantity datatype to the [UCUM](http://unitsofmeasure.org/) code system, [when]\nno units [are available systems SHOULD NOT supply the unit field]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0187"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD-NOT"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A FHIR Server SHOULD not delete records."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0188"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A FHIR Server SHOULD update the appropriate resource status to entered-in-error or inactive [when requested to delete records]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0189"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a system supports the deletion of records, they SHOULD refer to the [Deletion Safety Checks](http://hl7.org/fhir/R4/safety.html#conformance) in the FHIR specification."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0190"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A FHIR Server SHOULD allow these resources [those entered in error] to be searchable by Client applications."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0191"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the FHIR Server has updated the resource status to entered-in-error:\nFor patient facing applications, A FHIR Server SHOULD remove the resource’s contents, leaving only an id and status. Note that this typically will not conform to the US Core or FHIR StructureDefinitions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0192"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the FHIR Server has updated the resource status to entered-in-error:\n...\nFor provider-facing applications, the content may be supplied with content and additional detail (such as the reason for the status change) that the patient viewing system would typically not have access to."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0193"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "the data provider SHOULD do their best to translate (safely) to the requested language [when accessing records in a native or requested language]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0195"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When Clients request a resource in a specific language] Servers SHOULD make reasonable efforts to translate what can be safely translated."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0196"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When Clients request a resource in a specific language] Servers SHOULD populate the Resource’s language element with a code based on the underlying language of record, not the requested language.\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0197"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When Clients request a resource in a specific language] Servers SHOULD … [use] the [Human Language](http://hl7.org/fhir/R4/extension-language.html) Extension when the language of a display, etc, is known to differ from the stated (or inferred) language."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0198"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When Clients request a resource in a specific language] [Servers SHOULD use] the [Translation](http://hl7.org/fhir/R4/extension-translation.html) Extension when the Server provides additional translations by its own choice or in response to a different Accept-Language than what the resource is stored in."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0199"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When Clients request a resource in a specific language] Servers SHOULD make it known what languages are supported in their CapabilityStatement(s) using this extension:\nhttp://hl7.org/fhir/5.0/StructureDefinition/extension-CapablilityStatement.acceptLanguage [[definition](https://hl7.org/fhir/R5/capabilitystatement-definitions.html#CapabilityStatement.acceptLanguage)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0200"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD support the [_lastUpdated](http://hl7.org/fhir/R4/search.html#lastUpdated) search parameter for US Core Profiles"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0201"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers ... SHOULD populate [Resource.meta.lastUpdated](http://hl7.org/fhir/R4/resource.html#Meta) for US Core Profiles as accurately as possible."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0202"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL document in CapabilityStatement.rest.resource.searchParam.documentation the types of changes that can be detected using the _lastUpdated search parameter"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0203"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Servers [MAY support compartment based searchs, but] are not required to support patient [compartment](http://hl7.org/fhir/R4/compartmentdefinition.html) based searches."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0204"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Servers [MAY resolve absolute URLs, but] are not required to resolve absolute URLs external to their environment."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0205"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers can [MAY] choose to return the results in a series of pages to manage the number of search results returned."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0206"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Consultation Note (11488-4)](https://loinc.org/11488-4.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0207"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Discharge Summary (18842-5)](https://loinc.org/18842-5.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0208"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[History & Physical Note (34117-2)](https://loinc.org/34117-2.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0209"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Procedures Note (28570-0)](https://loinc.org/28570-0.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0210"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Progress Note (11506-3)](https://loinc.org/11506-3.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0211"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Imaging Narrative (18748-4)](https://loinc.org/18748-4.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0212"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Laboratory Report Narrative (11502-2)](https://loinc.org/11502-2.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0213"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Pathology Report Narrative (11526-1)](https://loinc.org/11526-1.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0214"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … DiagnosticReport categories:\n[Cardiology (LP29708-2)](https://loinc.org/LP29708-2)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0215"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … DiagnosticReport categories:\n[Pathology (LP7839-6)](https://loinc.org/LP7839-6)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0216"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … DiagnosticReport categories:\n[Radiology (LP29684-5)](https://loinc.org/LP29684-5)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0217"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "systems are encouraged to support other common notes types, such as:\n[Referral Note (57133-1)](https://loinc.org/57133-1.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0218"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "systems are encouraged to support other common notes types, such as:\n[Surgical Operation Note (11504-8)](https://loinc.org/11504-8.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0219"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "systems are encouraged to support other common notes types, such as:\n[Nurse Note (34746-8)](https://loinc.org/34746-8.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0220"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To enable consistent access to scanned DiagnosticReport clinical reports, the FHIR Server SHALL expose these overlapping scanned or narrative-only reports through both DiagnosticReport and DocumentReference by representing the same attachment URL [as] DocumentReference.content.attachment.url [and]\nDiagnosticReport.presentedForm.url"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0221"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "when DiagnosticReport.presentedForm.url references a Scan (PDF), that Attachment SHALL also be accessible through DocumentReference.content.attachment.url"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0222"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems [Servers] may extend their capabilities [around types of clinical notes] to the complete US Core DocumentReference Type Value Set."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0223"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "This guide requires [Server] systems to implement the [US Core DocumentReference Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-documentreference.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0224"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "This guide requires [Server] systems to implement the [US Core DiagnosticReport Profile for Report and Note exchange](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-diagnosticreport-note.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0225"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems [Servers] may support other [DiagnosticReport] categories as well."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0227"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following SHOULD be exposed via DiagnosticReport: Imaging Narrative\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0228"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following SHOULD be exposed via DiagnosticReport: Laboratory Report Narrative\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0229"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following SHOULD be exposed via DiagnosticReport: Pathology Report Narrative\n"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0230"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The following SHOULD be exposed via DiagnosticReport: Procedure Note"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0231"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers that support DiagnosticReport will include the clinical note narrative content in DiagnosticReport.presentedForm"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0233"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "FHIR Server claiming support to this guide SHOULD support the $expand operation [[operation link](http://hl7.org/fhir/R4/valueset-operation-expand.html) to provide information to Clients requesting information on the note and report types the Server supports]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0234"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.category&contextDirection=outgoing for DiagnosticReport report category discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0235"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.category&contextDirection=incoming for DiagnosticReport report category discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0236"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.code&contextDirection=outgoing for DiagnosticReport report type discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0237"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.code&contextDirection=incoming for DiagnosticReport report type discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0238"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.category&contextDirection=outgoing for DocumentReference note category discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0239"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.category&contextDirection=incoming for DocumentReference note category discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0240"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.type&contextDirection=outgoing for DocumentReference note type discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0241"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation for discovering note and report types, then Servers SHALL support] the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.type&contextDirection=incoming for DocumentReference note type discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0242"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation then] the note and report types for a particular Server [SHOULD be] discovered by invoking the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.presentedForm.contentType&contextDirection=outgoing for DiagnosticReport report content type discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0243"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation then] the note and report types for a particular Server [SHOULD be] discovered by invoking the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-diagnosticreport-note#DiagnosticReport.presentedForm.contentType&contextDirection=incoming for DiagnosticReport report content type discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0244"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation then] the note and report types for a particular Server [SHOULD be] discovered by invoking the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.content.attachment.contentType&contextDirection=outgoing for DocumentReference note content type discovery [for read operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0245"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If Servers support the [$expand] (http://hl7.org/fhir/R4/valueset-operation-expand.html) operation then] the note and report types for a particular Server [SHOULD be] discovered by invoking the #expand operation as follows:\nGET [base]/ValueSet/$expand?context=http://hl7.org/fhir/us/core/StructureDefinition/us-core-documentreference#DocumentReference.content.attachment.contentType&contextDirection=incoming for DocumentReference note content type discovery [for write operations]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0246"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The [MedicationAdministration](http://hl7.org/fhir/R4/medicationadministration.html) and [MedicationStatement](http://hl7.org/fhir/R4/medicationstatement.html)] medication resources are not profiled by US Core, and systems that support US Core are permitted to use them"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0247"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When using a code [to represent a medication][, the code SHALL follow the [extensible](http://hl7.org/fhir/R4/terminologies.html#extensible) binding rules to [Medication Clinical Drug (RxNorm)](https://vsac.nlm.nih.gov/valueset/2.16.840.1.113762.1.4.1010.4/expansion) - i.e., unless RxNorm does not cover the concept, the RxNorm code SHALL be used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0248"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "USCDI recommends the [National Drug Codes (NDC)](https://www.fda.gov/drugs/drug-approvals-and-databases/national-drug-code-directory) as an optional medication terminology. They can be supplied as an additional coding element [when representing a medication]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0249"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When referencing the Medication resource, the resource may be included in the returned bundle, as an external resource, or as a [contained](http://hl7.org/fhir/R4/references.html#contained) resource if it can’t stand alone. … The Server application MAY choose any combination of these methods"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0250"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "if an external reference to Medication is used, the Server SHALL support the [_include](http://hl7.org/fhir/R4/search.html#include) parameter for searching this element"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0252"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nA MedicationRequest resource query **SHALL** be all that is required to access \"all medications\" or \"all active medications\" for a patient. (In other words, no other medication resource type needs to be fetched)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0253"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nThe [MedicationRequest resource] query result **SHALL** include all MedicationRequest resources with a `MedicationRequest.intent` = \"order\" representing authorized medication orders directly derived from the system's orders."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0254"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nThe [MedicationRequest resource] query result **SHALL** include all prescribed and \"self-prescribed\" MedicationRequest resources with a `MedicationRequest.intent` = \"plan\" representing reported medications."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0256"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nServers **SHALL** use the `MedicationRequest.reported[x]` element to indicate that the MedicationRequest record was captured as a secondary \"reported\" record rather than an original primary source-of-truth record."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0257"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nServers [MAY] use the `MedicationRequest.reported[x]` element to indicate ... the source of the report."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0258"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nWhen recording \"self-prescribed\" medication, Servers **SHOULD** use the `MedicationRequest.requester` element to indicate the Patient or RelatedPerson is the prescriber."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0259"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nServers **SHOULD** support the encounter search parameter. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0260"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\n[If Servers support the encounter search parameter, s]earching by encounter will return all medications ordered during that encounter, including medications administered in the hospital and prescribed or discharge medications intended to be taken at home."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0262"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Requirements to access “all medications” [all historical, active, and future prescribed medications and medications entered in error and whose status is unknown.] and “all active medications” [all medications with an active status. Active medications do not include past, future, unknown status, and entered-in-error medications.] for a patient:\nServers **MAY** support the search parameters `category`and `encounter`. This search will return all medications ordered during an encounter for a given MedicationRequest.category such as \"inpatient\"."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0263"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To provide a list of a patient’s medications, it may be necessary to “de-duplicate” them. The de-duplication activity MAY be supplied by the Server"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0266"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The HIE must maintain the original data source."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0267"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An agent.type=”assembler”, agent.type=”transmitter”, or other agents from [Provenance Agent Type](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-provenance-participant-type.html) value set MAY also be included."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0268"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "implementers [of US Core's framework of Screening and Assessments] SHOULD consider more constrained, domain-specific profiles derived from the US Core Profiles to meet the needs of their respective use cases."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0269"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Every Server that supports the USDCI Data Class “Health Status/Assessments”:\n\nSHALL support representing clinical judgments using [US Core Condition Problems and Health Concerns Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-condition-problems-health-concerns.html) or [US Core Simple Observation Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-simple-observation.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0270"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Every Server that supports the USDCI Data Class “Health Status/Assessments”:\n...\nThe US Core Simple Observation Profile's Observation.derivedFrom element **SHOULD** reference the [Structured Screening and Assessment](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#structured-screening-and-assessments) upon which clinical judgment observations are made"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0271"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Every Server that supports the USDCI Data Class “Health Status/Assessments”:\n...\nthe US Core Condition Profile's Condition.evidence.detail element **SHOULD** reference the [Structured Screening and Assessment](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#structured-screening-and-assessments) which assist in diagnosing problems or health concerns."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0272"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For API developers using US Core, it’s important to understand when to use the QuestionnaireResponse versus Observation to represent structured assessments and surveys. Here are some guidelines to help choose the appropriate profile:\nObservations represent specific point-in-time facts that need to be searched, trended, the subject of statistical analysis, and directly referenced in support of other actions ... anything that meets one of the preceding criteria must be surfaced as an Observation."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0273"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For API developers using US Core, it’s important to understand when to use the QuestionnaireResponse versus Observation to represent structured assessments and surveys. Here are some guidelines to help choose the appropriate profile:\nObservations represent specific point-in-time facts that need to be searched, trended, the subject of statistical analysis, and directly referenced in support of other actions ... anything that meets one of the preceding criteria must be surfaced as an Observation."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0274"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For FHIR implementers, it is important to note that QuestionnaireResponse [which represent the source-of-truth of a completed form, shall] references a specific version of a form, whether it was represented as a FHIR Questionnaire or not. This reference provides the context of exactly what options were available, what logic was used to calculate answers, and what questions were asked."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0280"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers SHOULD treat these [USCDI Health Status Assessments Data Element] value sets as having an [extensible](http://hl7.org/fhir/R4/terminologies.html#extensible) binding."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0281"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "when recording SDOH data [with] US Core Profiles, Servers SHOULD use … [Social Determinants of Health Conditions Value Set](https://vsac.nlm.nih.gov/valueset/2.16.840.1.113762.1.4.1196.788/expansion), [Social Determinants of Health Procedures Value Set](https://vsac.nlm.nih.gov/valueset/2.16.840.1.113762.1.4.1196.789/expansion), [Social Determinants of Health Goals Value Set](https://vsac.nlm.nih.gov/valueset/2.16.840.1.113762.1.4.1247.71/expansion), [and] [Social Determinants of Health Service Requests Value Set](https://vsac.nlm.nih.gov/valueset/2.16.840.1.113762.1.4.1196.790/expansion)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0282"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server may support Version DSTU2 and Argonaut Data Query"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0283"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server may support … FHIR R4 and US Core ver 3.1.1+"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0284"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server may support [both] [(]Version DSTU2 and Argonaut Data Query[) and (] FHIR R4 and US Core ver 3.1.1+[)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0285"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server may make explicit which version of Argo/US Core is on their FHIR endpoint (e.g., “DSTU2” or “R4” path component or separate files based on version)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0287"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD maintain a stable common identifier for a resource across [FHIR] versions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0288"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "In an upgraded R4 endpoint, any data in FHIR DSTU2 SHOULD be in FHIR R4."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0289"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The FHIR RESTful resource types supported in a DSTU2 implementation SHOULD be supported in a R4 implementation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0290"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The FHIR RESTful resource types supported in a DSTU2 implementation SHOULD be supported in a R4 implementation [with the] exception [of]\nMedicationStatement may be deprecated, and the data SHOULD be mapped to MedicationRequest."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0291"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The FHIR RESTful resource types supported in a DSTU2 implementation SHOULD be supported in a R4 implementation [with the] exception [of]\nCare teams as represented by CarePlan in DSTU2 SHOULD be replaced by and the data mapped to CareTeam in R4"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0295"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD make available the same information in DSTU2 and R4 where the more recent standard allows."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0296"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD make available the same information in DSTU2 and R4 where the more recent standard allows … [with the] exception [of]\nMedicationStatement data [should be] mapped to MedicationRequest"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0297"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD make available the same information in DSTU2 and R4 where the more recent standard allows … [with the] exception [of]\ncare teams, as represented by CarePlan, SHOULD be mapped to CareTeam in R4"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0298"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Data SHOULD be maintained between [FHIR] versions (i.e., not be degraded)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0300"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Separate authorization is required [between different versions of FHIR]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0302"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The clinical status of the allergy] SHALL be present if verification status is not “entered-in-error”"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0303"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The clinical status of the allergy] SHALL NOT be present if verification Status is “entered-in-error”"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0305"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Profile Specific Implementation Guidance:\n\nNo Known Allergies may be represented using the US Core-AllergyIntolerance profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0306"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When used No Known Allergies is documented the system Shall use an] appropriate negation code in AllergyIntolerence.code"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0307"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When used No Known Allergies is documented the system Shall use an] verification status in AllergyIntolerance.verificationStatus"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0308"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a patient has not been asked about their allergies, this would be represented as:\nAllergyIntolerance.code = “1631000175102” (Patient not asked (contextual qualifier) (qualifier value))\nAllergyIntolerance.verificationStatus = “unconfirmed” or empty (in other words, then element omitted)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0309"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a patient has been asked, but has indicated they have no known allergies, this would be represented as:\nAllergyIntolerance.code = “716186003” (No known allergy (situation))\nAllergyIntolerance.verificationStatus = “confirmed”"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0310"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Considerations for systems aligning with [HL7 Consolidated (C-CDA)](http://www.hl7.org/implement/standards/product_brief.cfm?product_id=492) Care Plan requirements: US Core Goal SHOULD be present in CarePlan.goal"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0311"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Considerations for systems aligning with [HL7 Consolidated (C-CDA)] (http://www.hl7.org/implement/standards/product_brief.cfm?product_id=492) Care Plan requirements: ... US Core Condition SHOULD be present in CarePlan.addresses"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0312"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Considerations for systems aligning with [HL7 Consolidated (C-CDA)] (http://www.hl7.org/implement/standards/product_brief.cfm?product_id=492) Care Plan requirements: Assessment and Plan MAY be included as narrative in CarePlan.text"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0313"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although both US Core Practitioner Profile and US Core PractitionerRole are Must Support, ... Server system[s conforming to the US Core CareTeam profile are] ... not required to support references to both, but SHALL support at least one of them"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0317"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When conforming to the US Core CareTeam profile] Because the US Core PractitionerRole Profile supplies the provider’s location and contact information and a reference to the Practitioner, Server systems [conforming to the US Core CareTeam profile] SHOULD reference it instead of the US Core Practitioner Profile [when conforming to the US Core CareTeam profile] ."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0318"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers [conforming to the US Core CareTeam profile] that support only US Core Practitioner Profile and do not support the US Core PractitionerRole Profile SHALL provide implementation-specific guidance on how to access a provider’s location ... information using only the Practitioner resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0319"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers [conforming to the US Core CareTeam profile] that support only US Core Practitioner Profile and do not support the US Core PractitionerRole Profile SHALL provide implementation-specific guidance on how to access a provider’s ... contact information using only the Practitioner resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0320"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For Problems and Health Concerns [records, systems SHOULD] use the [US Core Condition Problems and Health Concerns Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-condition-problems-health-concerns.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0321"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Newly created Encounter Diagnosis records SHALL have a] Condition.code … [from the] [“current”](https://hl7.org/fhir/R5/terminologies.html#binding) … [value set] binding."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0322"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Historical Encounter Diagnosis records MAY have a] Condition.code … [from the] base “preferred” … [value set] binding."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0323"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "USCDI’s applicable vocabulary standards for Encounter Diagnosis are SNOMED CT and ICD-10-CM. The US Core Condition Codes only supports ICD-9-CM for historical purposes. When using ICD codes, only non-header ICD-10-CM codes SHOULD be used as the primary code for current encounter diagnoses."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0324"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[A US Core Condition Encounter Diagnosis] encounter SHOULD always be referenced in Condition.encounter."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0330"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For Encounter Diagnosis [records, systems SHOULD] use the [US Core Condition Encounter Diagnosis Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-condition-encounter-diagnosis.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0331"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the category is \"problem-list-item\", Condition.clinicalStatus SHOULD be present."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0332"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect: New problems and health concerns "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0333"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect:\nChanges in the clinical status or verifications status of problems or health concerns [This will change to a SHALL requirement in US Core v8.0.0]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0334"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A coverage.type of “81” (Self-pay) MAY be used to imply that the patient has no coverage or that an individual or organization other than an insurer is taking responsibility for payment for a portion of the health care costs."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0335"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers should refer to the [PHDSC Payer Type Committee User’s Guide](https://www.nahdo.org/sites/default/files/2020-12/SourceofPaymentTypologyUsersGuideVersion9.2December2020.pdf) for the Source of Payment Typology when selecting codes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0336"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To differentiate Medicare Parts A, B, C, and D systems can use the following codes [when sending Coverage.type]: [For] Part A and B [use] 121 (Medicare Fee For Service)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0337"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To differentiate Medicare Parts A, B, C, and D systems can use the following codes: [For] Part C (Medicare Advantage Plan) [use] 111 (Medicare HMO), 112 (Medicare PPO), 113 (Medicare POS)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0338"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To differentiate Medicare Parts A, B, C, and D systems can use the following codes: [For] Part D [use] 122 (Medicare Drug Benefit)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0339"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If Insurers issue unique member IDs for dependents, then the memberId Coverage.identifier should be used [with the unique dependent ID] instead of Coverage.dependent to uniquely refer to the dependent with respect to their insurance."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0340"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For non-implantable devices (for example, software or crutches), use the base FHIR Device resource or other use case-specific Device profiles."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0341"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers are encouraged to use the FDA Global UDI Database (GUDID) and associated APIs to parse and validate the [unique device ID] UDI"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0342"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implantable medical devices with UDI information SHALL represent the UDI code in Device.udiCarrier.carrierHRF"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0343"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "UDI-PI elements present [in Device.udiCarrier.carrierHRF] SHALL be represented in the corresponding US Core Implantable Device Profile elements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0344"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If UDI is not present and the manufacturer … is available, … [it] SHOULD be included to support historical reports of implantable medical devices [where] manufacturer [is sent in] Device.manufacturer"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0345"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If UDI is not present and the ... model number information is available, … [it] SHOULD be included to support historical reports of implantable medical devices [where] model [is sent in] Device.model"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0346"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD support query by Device.type to allow Clients to request the patient’s devices by a specific type."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0347"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Records of implanted devices MAY be queried against UDI data, including: UDI HRF string (udi-carrier)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0348"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Records of implanted devices MAY be queried against UDI data, including:UDI Device Identifier (udi-di)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0349"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Records of implanted devices MAY be queried against UDI data, including: Manufacturer (manufacturer)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0350"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Records of implanted devices MAY be queried against UDI data, including: Model number (model)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0351"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers MAY also adopt custom SearchParameters for searching by lot numbers"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0352"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers MAY also adopt custom SearchParameters for searching by serial number"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0353"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers MAY also adopt custom SearchParameters for searching by expiration date"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0354"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers MAY also adopt custom SearchParameters for searching by manufacture date"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0355"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Implementers MAY also adopt custom SearchParameters for searching by distinct identifier"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0356"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The diagnostically relevant time (known as the “effective time” and typically the time of specimen collection) … SHALL be present if status [of the diagnostic report] is ‘partial’, ‘preliminary’, ‘final’, ‘amended’, ‘corrected’, or ‘appended’."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0357"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When the report was released … SHALL be present if status [of the diagnostic report] is ‘partial’, ‘preliminary’, ‘final’, ‘amended’, ‘corrected’, or ‘appended’."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0358"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect New laboratory reports. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0359"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect changes in the status of laboratory reports, including events that trigger the same status (e.g., amended → amended)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0360"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The DiagnosticReport.category binding Must Support, at a minimum, the US Core DiagnosticReport Category Codes of Cardiology, Radiology, and Pathology"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0361"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Other [diagnostic report] categories may be supported [when using US Core DiagnosticReport Profile for Report and Note Exchange]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0362"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[L]inkages between specific LOINC codes and the LP-type codes may be used as guidance [for a Server's categorization of diagnostic reports]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0364"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For Diagnostic Imaging Reports systems SHOULD support using the subset of LOINC codes defined in CONF-DIR-19 in HL7 Implementation Guide for CDA Release 2: Imaging Integration, Levels 1, 2, and 3, Basic Imaging Reports in CDA and DICOM Diagnostic Imaging Reports (DIR) - Universal Realm, Release 1.0."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0365"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The DocumentReference.type binding Must Support, at a minimum, the 10 [Common Clinical Notes](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-documentreference.html#mandatory-and-must-support-data-elements)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0366"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The DocumentReference.type binding may extend to the whole [US Core DocumentReference Type Value Set](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-documentreference-type.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0367"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[DocumentReference.type may also use] other category schemes such as the LOINC-based [Document Class Value Set](http://hl7.org/fhir/R4/valueset-document-classcodes.html) and [IHE XDSclassCode](https://wiki.ihe.net/index.php/XDS_classCode_Metadata_Coding_System)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0368"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although both [DocumentReference.attachment.url and DocumentReference.attachment.data] are marked as Must Support, the Server system is not required to support an address and inline base64 encoded data, but SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0372"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If there are multiple DocumentReference.content element repetitions, these SHALL all represent the same document in different formats or attachment metadata"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0373"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The [documentReference.content] element SHALL NOT contain different versions of the same content."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0374"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The organization responsible for the DocumentReference SHALL be present either in DocumentReference.custodian or accessible in the Provenance resource targeting the DocumentReference using Provenance.agent.who or Provenance.agent.onBehalfOf"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0375"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although ... marked as Must Support, Servers are not required to support both [an Encounter.reasonCode or a reference with Encounter.reasonReference], but they SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0378"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If Encounter.reasonReference references an Observation, it SHOULD conform to a US Core Observation [profile applicable to the observation being made]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0379"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although … marked as Must Support, Servers are not required to support both Encounter.location.location and Encounter.serviceProvider, but they SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0382"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the event facility/location differs from the Encounter.location, systems SHOULD reference it directly"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0383"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the event facility/location differs from the Encounter.location, … systems SHALL use the location element for all resources where the element is available."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0384"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the event facility/location differs from the Encounter.location … systems MAY use the standard [Event Location Extension](http://hl7.org/fhir/StructureDefinition/event-location) for US Core DiagnosticReport Profile for Laboratory Results Reporting and US Core Observation Clinical Result Profile."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0385"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect New encounters/visits"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0386"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Updates to .meta.lastUpdated SHOULD reflect changes in the status of encounters, including events that trigger the same status (e.g., in-progress → in-progress)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0387"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although both Goal.startDate and Goal.target.dueDate are marked as Must Support, the Server system is not required to support both, but SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0390"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Servers shall] use the status code: not-done to represent that an immunization was not given."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0391"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organization participating in the ONC Health IT Certification program] [CVX vaccine codes](https://www2a.cdc.gov/vaccines/iis/iisstandards/ndc_crosswalk.asp) are required"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0392"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[NDC vaccine codes](http://www2a.cdc.gov/vaccines/iis/iisstandards/ndc_crosswalk.asp) SHOULD be supported as an additional code [of [CVX Vaccine Codes](https://www2a.cdc.gov/vaccines/iis/iisstandards/ndc_crosswalk.asp)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0393"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The preferred code system identifier … is [http://hl7.org/fhir/sid/cvx](http://hl7.org/fhir/sid/cvx) for CVX [vaccine codes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0394"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The preferred code system identifier … is [http://hl7.org/fhir/sid/ndc](http://hl7.org/fhir/sid/ndc) for NDC vaccine codes]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0395"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Location.address.line"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0396"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Location.address.city"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0397"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When using a code [to represent a medication for a medication dispense], RXNorm concepts are used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0398"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When using a code [to represent a medication for a medication dispense], [National Drug Codes (NDC)](https://www.fda.gov/drugs/drug-approvals-and-databases/national-drug-code-directory) can be supplied as an additional coding element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0399"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When referencing a Medication resource in .medicationReference, the resource may be [contained](http://hl7.org/fhir/R4/references.html#contained)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0400"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When referencing a Medication resource in .medicationReference, the resource may be an external resource"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0401"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Server systems are not required to support both a [medication] code and a reference [when sending medicationDispense], but SHALL support at least one of these methods"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0402"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If an external reference to a Medication resource is used, the Server SHALL support the [_include](http://hl7.org/fhir/R4/search.html#include) parameter for searching this element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0405"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organization participating in the ONC Health IT Certification program Servers SHALL support the [additional USCDI requirement](https://hl7.org/fhir/us/core/STU8/must-support.html#additional-uscdi-requirements):], The reason or indication for the prescription"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0406"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organization participating in the ONC Health IT Certification program Servers SHALL support the [additional USCDI requirement](https://hl7.org/fhir/us/core/STU8/must-support.html#additional-uscdi-requirements):] reported adherence to prescribed medication instructions"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0407"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When recording “self-prescribed” medication, requester SHOULD be used to indicate the Patient or RelatedPerson as the prescriber"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0408"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although [medicationRequest.reportedBoolean and MedicationRequest.reportedReference] are both marked as Must Support, the Server system is not required to support both, but SHALL support at least one of these elements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0411"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although both MedicationRequest.reasonCode and MedicationRequest.reasonReference are marked as Additional USCDI Requirements [which are required for organizations participating in the ONC Health IT Certification program]. The certifying Server system is not required to support both, but SHALL support at least one of these elements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0414"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program and supporting MedicationRequest.reasonReference,] Servers SHALL support at least one target resource in MedicationRequest.reasonReference"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0416"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] the referenced resources SHOULD be a US Core Profile as documented in [Referencing US Core Profiles](https://hl7.org/fhir/us/core/STU8/general-guidance.html#referencing-us-core-profiles)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0417"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Source EHR identifiers SHOULD be included to support deduplication across MedicationRequest resources."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0419"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The observations MAY have additional codes that translate or map to the Observation code or category codes [such as] … local system-specific codes [and] …more specific codes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0420"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For an Observation a] code system value SHOULD be supplied for each additional code"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0421"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Because the blood pressure values are communicated in the mandatory systolic and diastolic components [when using the US Core Average Blood Pressure Profile,] the Observation.value[x] element SHALL be omitted"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0422"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The context or precondition of a patient’s [care experience] preference SHOULD be supplied in the Observation.valueString or in an extension"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0423"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHOULD use the base FHIR [Observation Category Codes] (http://hl7.org/fhir/R4/valueset-observation-category.html) [in Observation.category]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0424"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD support Observation.effectivePeriod to accurately represent measurements over time"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0425"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An Observation.component without a value, SHALL include a reason why the data is absent"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0426"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems that never provide a component observation without a component value … [MAY choose not] to support Observation.component.dataAbsentReason"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0427"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An Observation without a value, SHALL include a reason why the data is absent"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0428"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For] an Observation without a value … [Systems MAY choose not to] include a reason why the data is absent … [if] there are component observations or … reporting panel observations using Observation.hasMember"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0429"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems that never provide an observation without a value ... [MAY choose not] to support Observation.dataAbsentReason"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0430"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When sending US Core Laboratory Results Observation Profile] updates to .meta.lastUpdated SHOULD reflect new laboratory observations"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0431"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When sending US Core Laboratory Results Observation Profile] updates to .meta.lastUpdated SHOULD reflect changes in the status of laboratory observations, including events that trigger the same status (e.g., amended → amended)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0432"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When sending US Core Observation Occupation Profile] for … [a] current job, [Servers SHALL] omit observation.effectivePeriod.end to indicate it is ongoing."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0433"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When the industry is known, but the occupation is not, [Servers SHALL] use the value “unknown” from the [DataAbsentReason Code System](http://hl7.org/fhir/R4/codesystem-data-absent-reason.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0434"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "when the occupation is known but the industry is not, [Servers SHALL] omit the industry Observation.component"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0435"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To represent the patient’s pregnancy status, [Servers SHALL] use the [US Core Observation Pregnancy Status Profile](https://hl7.org/fhir/us/core/StructureDefinition-us-core-observation-pregnancystatus.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0436"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "To represent the patient’s intent to become pregnant, [Servers SHALL] use the [US Core Observation Pregnancy Intent Profile](https://hl7.org/fhir/us/core/StructureDefinition-us-core-observation-pregnancyintent.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0437"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For] multi-question surveys or assessments Observation.code is an overarching assessment or screening code, and the Observation.value element SHOULD be empty"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0438"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A practitioner’s clinical observation or assertion about a patient’s health status, which is not a response to a screening or assessment question,SHOULD use the [US Core Simple Observation Profile](https://hl7.org/fhir/us/core/StructureDefinition-us-core-simple-observation.html) instead [of the US Core Observation Screening Assessment Profile]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0439"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "the Server system ... SHALL support [either] Reference(US Core Observation Screening Assessment Profile) or Reference(US Core QuestionnaireResponse Profile) for Observation.derivedFrom"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0440"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Additional codes that translate or map to the Observation code (e.g., local codes) are allowed [when using US Core Observation Sexual Orientation Profile]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0441"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Observations formally part of an assessment tool or survey SHOULD use the [US Core Observation Screening Assessment Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-observation-screening-assessment.html)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0442"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An assertion or determination derived from screening and assessment tools SHOULD reference them using Observation.derivedFrom"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0443"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When using `Observation.derivedFrom’ to reference an Observation, the referenced Observation SHOULD be a US Core Observation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0444"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although none of the Observation.derivedFrom [references are flagged as Must Support](https://hl7.org/fhir/us/core/STU8/must-support.html#must-support---resource-references), the Server SHALL support at least one of them"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0445"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[US Core] treatment intervention preferences expressed by a patient may be documented in narrative (text) form or the result of selecting from a list of options provided by the content creator/implementer."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0446"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When using US Core Treatment Intervention Preference Profile] the context or precondition of a patient’s preference SHOULD be supplied in the Observation.valueString ... or an extension"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0447"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[US Core Vital Signs] observations MAY have [component](http://hl7.org/fhir/R4/observation.html#gr-comp) observations … [see] FHIR core specification [vital signs table](http://hl7.org/fhir/R4/observation-vitalsigns.html#vitals-table) for examples"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0448"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Information about the growth chart tables used to determine percentiles SHOULD be supplied in Observation.note.text"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0449"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the US Core Blood Pressure Profile] because the blood pressure values are communicated in the mandatory systolic and diastolic components[,] the Observation.value[x] element SHOULD be omitted"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0450"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the US Core Blood Pressure Profile] because the blood pressure values are communicated in the mandatory systolic and diastolic components[,] an Observation without a systolic or diastolic result value, SHALL include a reason why the data is absent in Observation.component.dataAbsentReason"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0451"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the US Core Blood Pressure Profile] because the blood pressure values are communicated in the mandatory systolic and diastolic components[,] All Server systems - including those that never provide a component observation without a value - SHALL support Observation.component.dataAbsentReason for the components."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0452"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Inspired oxygen therapy may be represented with [component](http://hl7.org/fhir/R4/observation.html#gr-comp) observations when measured at the same time as the pulse oximetry measurements [in the US Core Pulse Oximetry profile]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0453"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Many pulse oximetry readings are taken while the patient is breathing room air. The concept of “room air” (unmodified, ambient air) SHOULD be represented as an inhaled oxygen flow rate of 0 liters/min"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0454"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A pulse oximetry reading without inspired oxygen component observations may imply that the measurement was performed while the patient was breathing room air or that the inspired oxygen reading was omitted. To remove this uncertainty, the inspired oxygen [component](http://hl7.org/fhir/R4/observation.html#gr-comp) observations SHOULD be used [when using the US Core Pulse Oximetry profile.]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0455"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL support National Provider Identifier (NPI) for organizations"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0456"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems … SHOULD the National Association of Insurance Commissioners NAIC Company code (sometimes called “NAIC Number” or “cocode”) for payers."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0457"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems … SHOULD support Clinical Laboratory Improvement Amendments (CLIA) for laboratories"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0458"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Organization.address.line and Organization.address.city"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0459"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for Race ... allow[s] for one or more codes of which [Must Support](https://hl7.org/fhir/us/core/STU8/must-support.html) at least one category code from the OMB Race ... Category Value Sets that draw from the [Race & Ethnicity - CDC (CDCREC)](https://phinvads.cdc.gov/vads/ViewCodeSystem.action?id=2.16.840.1.113883.6.238) code system [for the [US Core Race Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-race.html)]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0460"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for ... Ethnicity allow[s] for one or more codes of which [Must Support](https://hl7.org/fhir/us/core/STU8/must-support.html) at least one category code from the OMB ... Ethnicity Category Value Sets that draw from the [Race & Ethnicity - CDC (CDCREC)](https://phinvads.cdc.gov/vads/ViewCodeSystem.action?id=2.16.840.1.113883.6.238) code system [for the [US Core Ethnicity Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-ethnicity.html)]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0461"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for Race ... allow[s] for one or more codes of which MAY include additional codes from the detailed ethnicity ... value sets drawn from the [Race & Ethnicity - CDC (CDCREC)](https://phinvads.cdc.gov/vads/ViewCodeSystem.action?id=2.16.840.1.113883.6.238) code system [when using the [US Core Race Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-race.html)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0462"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for Race ... allow[s] for one or more codes of which SHALL include a text description [of category codes when using the [US Core Race Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-race.html)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0463"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for ... Ethnicity allow[s] for one or more codes of which MAY include additional codes from the detailed ... race value sets drawn from the [Race & Ethnicity - CDC (CDCREC)](https://phinvads.cdc.gov/vads/ViewCodeSystem.action?id=2.16.840.1.113883.6.238) code system [when using the [US Core Race Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-race.html)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0464"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Complex [Extension] for ... Ethnicity allow[s] for one or more codes of which SHALL include a text description [of category codes when using the [US Core Ethnicity Extension] (https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-ethnicity.html)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0465"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although Patient.deceased[x] is marked as additional USCDI, certifying systems are not required to support both [boolean and dateTime data types], but SHALL support [at] least Patient.deceasedDateTime"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0466"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Previous name is represented by setting Patient.name.use to “old” or providing an end date in Patient.name.period or doing both"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0467"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Previous address is represented by setting Patient.address.use to “old” or providing an end date in Patient.address.period or doing both."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0469"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Certifying systems](https://www.healthit.gov/topic/certification-ehrs/about-onc-health-it-certification-program) [, those that are participating in the ONC Health IT certification program,] SHALL ... follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Patient.address.line and Patient.address.city for new and updated records."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0470"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Non-certifying systems[, systems that are not participating in the ONC Health IT certification program,] SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Patient.address.line and Patient.address.city for new and updated records."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0471"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For systems participating in the ONC Health IT certification program,] this requirement [to follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) for Patient.address.line and Patient.address.city] does not apply to historical records or documents that are exposed through FHIR-based APIs. [Organizations MAY choose not to use use Project US@ Technical Specification for Patient Addresses Final Version 1.0 when sending historical records]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0472"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD-NOT"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Patient’s Social Security Numbers SHOULD NOT be used as a patient identifier in Patient.identifier.value"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0473"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers that support only the US Core Practitioner Profile and do not support the [US Core PractitionerRole Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-practitionerrole.html) SHALL provide implementation-specific guidance on how to access a provider’s location and contact information using only the Practitioner resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0474"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although Practitioner.address is marked as Must Support, the Server system … [MAY choose not to] support it if they support the US Core PractitionerRole Profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0475"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[When using the US Core Practioner Profile] Practitioner.address … SHALL [be supported] if … [the Server does] not support the US Core PractitionerRole Profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0477"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Only professional/work contact information about the practitioner SHOULD be available to the patient"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0478"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for Practitioner.address.line and Practitioner.address.city."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0479"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Procedure codes … [MAY] be taken from SNOMED-CT, CPT, HCPCS II, ICD-10-PCS, CDT, or LOINC [for procedure.code]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0480"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If using LOINC codes in procedure.code] only LOINC concepts that reflect actual procedures SHOULD be used"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0481"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "communication.preferred MAY designate a preferred language when multiple languages are represented"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0482"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program] Servers … SHALL support ... US Core Procedure Profile for communicating the reason or justification for a referral as Additional USCDI Requirements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0484"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] although both Procedure.reasonCode and Procedure.reasonReference are marked as Additional USCDI Requirements, the certifying Server system is not required to support both, but SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0486"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] when using Procedure.reasonReference Servers SHALL support at least one target resource in Procedure.reasonReference"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0488"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] when using Procedure.reasonReference …The referenced resources SHOULD be a US Core Profile as documented in [Referencing US Core Profiles](https://hl7.org/fhir/us/core/STU8/general-guidance.html#referencing-us-core-profiles)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0489"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type AllergyIntolerance"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0490"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type CarePlan"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0491"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type CareTeam"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0492"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Condition"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0493"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Coverage"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0494"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Device"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0495"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type DiagnosticReport"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0496"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Document Reference"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0497"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Encounter"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0498"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Goal"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0499"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Immunization"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0500"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type MedicationDispense"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0501"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type MedicationRequest"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0502"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Observation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0503"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Patient"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0504"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type Procedure"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0505"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type QuestionnaireResponse"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0506"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type RelatedPerson"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0507"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The US Core Provenance resource SHALL be supported for … [this] US Core resource type ServiceRequest"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0508"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a system receives a provider in Provenance.agent.who as free text, they must capture [the organization] who sent them the information [and upon] request ... SHALL provide this organization as the source"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0509"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a system receives a provider in Provenance.agent.who as free text, … [upon request they] MAY include the free text provider."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0510"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems that need to know the activity has occurred SHOULD populate the activity [Provenance.activity]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0511"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the QuestionnaireResponse is based on a non-FHIR form [then a] ... FHIR Questionnaire [needs to] represent at least the relevant metadata"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0512"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the QuestionnaireResponse is based on a non-FHIR form [then a] … FHIR Questionnaire's questions may be omitted"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0513"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD follow the [Project US@ Technical Specification for Patient Addresses Final Version 1.0](https://asapnet.org/wp-content/uploads/2022/03/Project_US_FINAL_Technical_Specification_Version_1.0.pdf) as the standard style guide for RelatedPerson.address.line and RelatedPerson.address.city"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0514"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Must Support `ServiceRequest.category` is bound, at a minimum, to the [US Core ServiceRequest Category Codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-servicerequest-category.html), and other category codes can be used."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0515"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The ServiceRequest.code value ... SHOULD be constrained to a subset for a particular use case or domain"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0516"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program] Servers … SHALL support ... US Core Service Request Profile for communicating the reason or justification for a referral as Additional USCDI Requirements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0518"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] although both ServiceRequest.reasonCode and ServiceRequest.reasonReference are marked as Additional USCDI Requirements, the certifying Server system is not required to support both, but SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0520"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] when using ServiceRequest.reasonReference Servers SHALL support at least one target resource in ServiceRequest.reasonReference"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0522"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For organizations participating in the ONC Health IT Certification program,] when using ServiceRequest.reasonReference …The referenced resources SHOULD be a US Core Profile as documented in [Referencing US Core Profiles](https://hl7.org/fhir/us/core/STU8/general-guidance.html#referencing-us-core-profiles)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0523"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Since the binding [for Specimen.type and additional USCDI elements] is [extensible](http://hl7.org/fhir/R4/terminologies.html#extensible) when a code is unavailable, just text is allowed [and conformant]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0524"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although both Specimen.identifier and Specimen.accessionIdentifier are marked as Must Support, the Server system is not required to support both, but SHALL support at least one of these elements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0532"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[Servers] SHOULD Support the ...\n[SMART App Launch version 2.0.0 and later](http://hl7.org/fhir/smart-app-launch/history.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0533"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL support the US Core Patient resource profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0534"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL support … at least one additional resource profile [in addition to the US Core Patient resource profile] from the list of US Core Profiles"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0535"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … Implement the RESTful behavior according to the FHIR specification."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0536"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … return the following response class (Status 400) [for] invalid parameters"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0537"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … return the following response class (Status 401/4xx) [for] unauthorized request"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0538"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … return the following response class (Status 403) [for] insufficient scopes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0539"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … return the following response class (Status 404) [for] unknown resource"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0540"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHALL … support JSON source formats for all US Core interactions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0541"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHOULD … support XML source formats for all US Core interactions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0542"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core Server SHOULD … identify the US Core profiles supported as part of the FHIR meta.profile attribute for each instance."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0543"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "A Server SHALL reject any unauthorized requests by returning an HTTP 401 \"Unauthorized\", HTTP 403 \"Forbidden\", or HTTP 404 \"Not Found\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0548"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[US Core Servers] SHOULD support [$expand](http://hl7.org/fhir/OperationDefinition/ValueSet-expand) operation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0549"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If a Server supports DocumentReference for creating, using, and sharing clinical notes, it SHOULD also support the context and contextdirection parameters of the $expand operation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0550"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL establish a risk analysis and management regime that conforms with HIPAA security regulatory requirements"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0552"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Federal systems SHOULD conform with the risk management and mitigation requirements defined in NIST 800 series documents."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0554"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Federal systems … SHOULD include security category assignment following NIST 800-60 vol. 2 Appendix D.14."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0556"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The coordination of risk management and the related security and privacy controls … SHOULD be defined in the Business Associate Agreement when available."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0558"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL reference a single time source to establish a common time base for security auditing and clinical data records among computing systems."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0560"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The selected time service SHOULD be documented in the Business Associate Agreement when available."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0562"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL keep audit logs of the various transactions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0564"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL use TLS version 1.2 or higher for all transmissions not taking place over a secure network connection."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0566"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Federal systems SHOULD conform with FIPS PUB 140-2."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0568"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL conform to [FHIR Communications Security](http://hl7.org/fhir/R4/security.html#http) requirements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0570"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For Authentication and Authorization, Systems SHALL support any [SMART App Launch Version 2.0.0](http://hl7.org/fhir/smart-app-launch/history.html) for Client <-> Server interactions."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0572"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHALL implement consent requirements per their state, local, and institutional policies."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0574"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The Business Associate Agreements SHOULD document systems’ mutual consent requirements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0576"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems SHOULD provide Provenance statements using the [US Core Provenance Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-provenance.html) resource and associated requirements."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0578"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems MAY implement the [FHIR Digital Signatures](http://hl7.org/fhir/R4/security.html#digital%20signatures)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0580"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems MAY protect the confidentiality of data at rest via encryption and associated access controls."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0583"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The [additional] current binding [[FHIR R5 link](https://hl7.org/fhir/R5/terminologies.html#binding)] requires newly recorded, non-legacy data to be drawn from the [bound] value set."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0584"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If the QuestionnaireResponse is based on a non-FHIR form [then a] ... FHIR Questionnaire [will communicate] the identifier of the non-FHIR form instead of the canonical URI using the US Core Extension Questionnaire URI extension."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0587"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Each AllergyIntolerance Must Support: a verification status"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0588"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Each AllergyIntolerance Must Support: a reaction manifestation"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0801"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If an element is marked as *Additional USCDI* and defined by a pattern [as described by [ElementDefinition.pattern](http://hl7.org/fhir/R4/elementdefinition-definitions.html#ElementDefinition.pattern_x_)], then the pattern defines the elements *and* element values that the Certifying System **SHALL** be capable of providing."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0802"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "\n\n\nPrimitive elements are single elements with a primitive value…. If they are marked as *Additional USCDI*, then the Certifying System **SHALL** be capable of providing the element value to meet the *Additional USCDI* requirement."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0803"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For any complex element marked as *Additional USCDI*, the Certifying System **SHALL** be capable of providing at least one of the sub-element values. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0804"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "If any sub-element is marked as *Additional USCDI* [for a complex element], it must also meet the *Additional USCDI* requirements and satisfy the *Additional USCDI* requirements for the parent element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0805"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f any sub-element is marked as *Additional USCDI* [for a complex element] and the parent element is not… [and] the parent element is represented in the structure, Certifying System **SHALL** support the sub-elements labeled as *Additional USCDI*."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0808"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When a Reference type element is labeled as Must Support and has a single target profile referenced, the target profile **SHALL** be supported."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0809"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When a Reference type element is labeled as Additional USCDI and has a single target profile referenced, the target profile **SHALL** be supported for Certifying Systems."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0810"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When a Reference type element is labeled as Must Support, has multiple target profiles referenced, and specific targets are labeled as Must Support, the Must Support target profile(s) **SHALL** be supported."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0811"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "When a Reference type element labeled as Additional USCDI, has multiple target profiles referenced, and specific targets are labeled as Must Support, the Must Support target profile(s) **SHALL** be supported by Certifying Systems."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0812"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f a slice is labeled as ... Additional USCDI and the slicer element is not labeled as ... Additional USCDI, then if the ... certifying system supports the element, it must support the slice's definition. There are no examples of this structure in US Core."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0813"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] slicer's Must Support property only defines the element level … Additional USCDI property[, i.e.,] no … Additional USCDI property is defined for the slice, then support for that slice's definition is optional."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0814"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f a slice is labeled as … Additional USCDI and the slicer element is ... labeled as … Additional USCDI, then … certifying system [**SHALL** support] the element[ and] the slice's definition."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0818"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Surgical Operation Note (11504-8)](https://loinc.org/11504-8.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0819"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers SHALL support, at minimum, these … \"Common Clinical Notes\":\n[Emergency Department Note (34111-5)](https://loinc.org/34111-5.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0820"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers that support the USCDI Health Status/Assessments Data Class **SHALL** support the US Core Observation Screening Assessment Profile"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0821"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers that support the USCDI Health Status/Assessments Data Class ... **SHOULD** support the SDC Base Questionnaire and the US Core QuestionnaireResponse Profile.\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0822"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For the US Core Simple Observation Profile, Servers **SHALL** support all the category codes [listed](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#category-codes)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0823"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For the … US Core Observation Screening Assessment Profiles, Servers **SHALL** support all the category codes [listed](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#category-codes)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0824"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For the US Core Condition Problems and Health Concerns Profile, Servers **SHALL** support the code ,\"sdoh\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0825"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For the US Core Condition Problems and Health Concerns Profile, Servers **SHOULD** support the other category codes [listed](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#category-codes)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0826"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "For the US Core ServiceRequest Profile, Servers SHOULD support all the [[listed](https://hl7.org/fhir/us/core/STU8/screening-and-assessments.html#category-codes)] category codes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/requirements-statementshallnot",
          "valueBoolean" : true
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0827"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "US Core SearchParameters referenced in [the US Core Client] CapabilityStatement that are derived from standard FHIR SearchParameters are only defined to document Server ... expectations. They specify additional expectations for the following SearchParameter elements:B7\n\n- multipleAnd\n- multipleOr\n- comparator\n- modifier\n- chain\n\nThey **SHALL NOT** be interpreted as search parameters for search. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0828"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers ... **SHOULD** use the standard FHIR SearchParameters."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0831"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The Server **SHALL** support the] category of \"problem-list-item\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0832"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[The Server **SHALL** support the] category of \"health-concern\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0833"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Certifying Systems **SHALL** support, a category of \"sdoh\""
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0834"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Certifying Systems ... **SHOULD** support the ... [US Core Simple Observation Category](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-simple-observation-category.html) codes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0835"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Certifying Systems ... **MAY** support other categories"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0836"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The `DiagnosticRequest.basedOn` element connects the DiagnosticReport to the originating order in the EHR. Systems that initiate the order **SHOULD** use this element when reporting the results."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0837"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The `DiagnosticReport.media.link` element **SHOULD** be used to support links to various patient-friendly content, such as jpg images of x-rays (see the DiagnosticReport Chest X-ray Report Example)."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0838"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The `DiagnosticReport.imagingStudy` element **SHOULD** be used to support exchange with systems that can view DICOM (Digital Imaging and Communications in Medicine) studies, series, and SOP (Service-Object Pair) instances referenced in the -[ImagingStudy](http://hl7.org/fhir/R4/imagingstudy.html) resource."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0839"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : " If the referenced a document or file [referenced by `DocumentReference.content.attachment.url`]  is hosted on a Server outside the FHIR Server, it should be securely accessible using the same authorization credentials that were used to access the FHIR Server. This reduces complexity for the Client and improves the user experience."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0840"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although the [US Core Interpreter Needed] extension is marked as an Additional USCDI Requirements on both US Core Patient and US Core Encounter Profiles, the certifying Server system is not required to support the extension on both profiles, but **SHALL** support the extension on at least one."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0841"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "There is no guarantee that vaccine lot numbers are globally unique, and they are not recommended for matching or de-duplication across systems unless used with other data elements such as a vaccine product code, manufacturer code, or date of administration. Implementers **MAY** communicate the `Immunization.manufacturer` to ensure global uniqueness to lot numbers."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0842"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers **SHALL** return all active medications following the [Get All Active Medications](https://hl7.org/fhir/us/core/STU8/medication-list.html#get-all-active-medications) guidance."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0843"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For US Core Laboratory Result Observation Profile, even] when the specimen type is already implied by the LOINC code used in `Observation.code` (e.g., a LOINC code for Blood Glucose), the `Observation.specimen` element **SHOULD** also be populated with the referenced Specimen resource to explicitly communicate the collected specimen type."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0844"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For US Core Laboratory Result Observation Profile, the] type of specimen [in `Observation.specimen`] SHOULD not conflict with the LOINC code [in `Observation.code`]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0845"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For the US Core Observation Screening Assessment Profile, the]  category type \"survey\" is required."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0846"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For the US Core Observation Screening Assessment Profile,] Certifying Systems **SHALL** support, the [US Core Screening Assessment Observation Category](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-screening-assessment-observation-category.html) codes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0847"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For the US Core Observation Screening Assessment Profile,] Certifying Systems **SHOULD** support, the [US Core Screening Assessment Observation Maximum Category](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-screening-assessment-observation-maximum-category.html) codes"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0848"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For the US Core Observation Screening Assessment Profile,] Certifying Systems **MAY** support other codes."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0850"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For the US Core Observation Screening Assessment Profile,] when using Observation.derivedFrom to reference an Observation, the referenced Observation SHOULD be a US Core Observation."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0851"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Servers can use the [US Core Interpreter Needed Extension](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-interpreter-needed.html) on [the [US Core Patient Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-patient.html)] or the [US Core Encounter Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-encounter.html) to communicate whether a patient needs an interpreter."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0852"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although the [[US Core Interpreter Needed Extension](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-interpreter-needed.html)] is marked as an Additional USCDI Requirement on both US Core Patient and US Core Encounter Profiles, the certifying Server system is not required to support the extension on both profiles but **SHALL** support the extension on at least one."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0855"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems **SHOULD** designate the patient's preferred language in the Patient.communication.preferred element."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0856"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "The `Procedure.performed` is mandatory if `Procedure.status` is \"completed\" or \"in-progress\"."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0857"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the [US Core ServiceRequest Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-servicerequest.html), for] the USCDI Laboratory Order, ... implementers SHOULD use the corresponding category codes listed ... below:\n- [108252007 Laboratory procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=108252007&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0858"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the [US Core ServiceRequest Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-servicerequest.html), for] the USCDI ... Clinical Test Order, ... implementers SHOULD use the corresponding category codes listed ... below:\n- [386053000 Evaluation procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=386053000&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)\n- [410606002 Social service procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=410606002&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)\n- [387713003 Surgical procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=387713003&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0859"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the [US Core ServiceRequest Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-servicerequest.html), for] the USCDI ... Imaging Order, ... implementers SHOULD use the corresponding category codes listed ... below:\n- [363679005 Imaging (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=363679005&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0860"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[In the [US Core ServiceRequest Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-servicerequest.html), for] the USCDI ... Procedure Order Data Elements, implementers SHOULD use the corresponding category codes listed ... below:\n- [386053000 Evaluation procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=386053000&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)\n- [410606002 Social service procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=410606002&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)\n- [387713003 Surgical procedure (procedure)](https://browser.ihtsdotools.org/?perspective=full&conceptId1=387713003&edition=MAIN/2024-10-01&release=&languages=en&latestRedirect=false)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0861"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHOULD"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For [US Core Simple Observation Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-simple-observation.html), ]Certifying Systems ... **SHOULD** support the other [US Core Simple Observation Category codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-simple-observation-category.html) [in addition to  the [US Core Screening Assessment Observation Category codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-screening-assessment-observation-category.html)]"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0862"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For [US Core Simple Observation Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-simple-observation.html), ]Certifying Systems **SHALL** support, the [US Core Screening Assessment Observation Category codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-screening-assessment-observation-category.html)"
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0863"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[For [US Core Simple Observation Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-simple-observation.html), ]Certifying Systems ... **MAY** support other categories [in addition to  [US Core Screening Assessment Observation Category codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-screening-assessment-observation-category.html) and  [US Core Simple Observation Category codes](https://hl7.org/fhir/us/core/STU8/ValueSet-us-core-simple-observation-category.html)]."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0864"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An Observation without a value, **SHALL** include a reason why the data is absent unless there are 1) component observations, or 2) reporting panel observations using Observation.hasMember. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0865"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems that never provide an observation without a value are not required to support `Observation.dataAbsentReason`."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0866"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "An `Observation.component` without a value, SHALL include a reason why the data is absent. "
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0867"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Systems that never provide a component observation without a component value are not required to support `Observation.component.dataAbsentReason`."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0868"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "Although 'Observation.performer' target profiles [US Core Practitioner Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-practitioner.html) and [US Core Patient Profile](https://hl7.org/fhir/us/core/STU8/StructureDefinition-us-core-patient.html) are labeled Must Support. Servers are not required to support both, but SHALL support at least one."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0870"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f a slice is labeled as Must Support... and the slicer element is not labeled as Must Support..., then if the Server... supports the element, it must support the slice's definition. There are no examples of this structure in US Core."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0871"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "MAY"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[If a] slicer's Must Support property only defines the element level Must Support...[, i.e.,] no Must Support... property is defined for the slice, then support for that slice's definition is optional."
        }
      ],
      "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement"
    },
    {
      "extension" : [
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.key",
          "valueId" : "CONF-0872"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.conformance",
          "valueCode" : "SHALL"
        },
        {
          "url" : "http://hl7.org/fhir/5.0/StructureDefinition/extension-Requirements.statement.requirement",
          "valueMarkdown" : "[I]f a slice is labeled as Must Support... and the slicer element is ... labeled as Must Support..., then ... the Server... [**SHALL** support] the element[ and] the slice's definition."
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
