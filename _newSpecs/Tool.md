---
description: "[One paragraph description]\n[References to supporting information like\
  \ \u201Cuse cases\u201D, \u201Cbioschemas mapping\u201D and \u201Cschema.org posted\
  \ issues\u201D]\n"
g_mapping_file: Tool Mapping
github_url: None
layout: new_spec_detail
name: Tool
new_props: []
properties:
- bsc_dec: ''
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - Text
  - URL
  marginality: Minimum
  name: featureList
  reused_from: SoftwareApplication
  sdo_desc: Features or modules provided by this application (and possibly required
    by other applications).
- bsc_dec: softwareHelp:url, softwareHelp:genre, softwareHelp:description/review
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - CreativeWork
  marginality: Minimum
  name: softwareHelp
  reused_from: SoftwareApplication
  sdo_desc: Software application help.
- bsc_dec: contact/email, contact/url, contact/name, contact/tel, contact/type
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - Text
  - URL
  marginality: Minimum
  name: softwareRequirements
  reused_from: SoftwareApplication
  sdo_desc: 'Component dependency requirements for application. This includes runtime
    environments and shared libraries that are not included in the application distribution
    package, but required to run the application (Examples: DirectX, Java or .NET
    runtime). Supersedes requirements.'
- bsc_dec: ''
  cardinality: ONE
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - DataFeed
  marginality: Minimum
  name: supportingData
  reused_from: SoftwareApplication
  sdo_desc: Supporting data for a SoftwareApplication.
- bsc_dec: ''
  cardinality: ONE
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - Person
  marginality: Minimum
  name: accountablePerson
  reused_from: SoftwareApplication
  sdo_desc: Specifies the Person that is legally accountable for the CreativeWork.
- bsc_dec: ''
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - CreativeWork
  - Text
  marginality: Minimum
  name: citation
  reused_from: SoftwareApplication
  sdo_desc: A citation or reference to another creative work, such as another publication,
    web page, scholarly article, etc.
- bsc_dec: ''
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - Text
  marginality: Minimum
  name: description
  reused_from: SoftwareApplication
  sdo_desc: A description of the item.
- bsc_dec: ''
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - Text
  marginality: Optional
  name: name
  reused_from: SoftwareApplication
  sdo_desc: The name of the item.
- bsc_dec: publication, publication/doi
  cardinality: MANY
  controlled_vocab: ''
  domain_case: reu_sdo
  expected_type:
  - PublicationEvent
  marginality: Recommended
  name: publication
  reused_from: SoftwareApplication
  sdo_desc: A PublicationEvent corresponds indifferently to the event of publication
    for a CreativeWork of any type e.g. a broadcast event, an on-demand event, a book/journal
    publication via a variety of delivery media.
reu_props: []
spec_mapping_url: https://docs.google.com/spreadsheets/d/1D0aQl-Ocp8Fi7a-drKV1Faed6tYUgGwzEM8xypa8S2Y/edit?usp=drivesdk
status: revision
stereotype: None
subtitle: Bioschemas specification for describing SoftwareApplication in the life-science.
version: 0.0.1
---