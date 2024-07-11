# Smart Data Models

An Umbrella Repository for collecting Data Models based on real world use-cases

The availability of widely adopted (de-facto standard) information models is key
for creating a global digital single market of interoperable and replicable
(portable) smart solutions in multiple domains (smart cities, smart agrifood, 
smart utilities, smart industry, …). Such models provide an essential
element in the common technical ground needed for standards-based open
innovation and procurement.

Data Models play a crucial role because they define the **harmonised
representation formats and semantics** that will be used by applications both to
consume and to publish data.

<!--
[![Status badge](https://img.shields.io/badge/status-draft-red.svg)](RELEASE_NOTES)
[![Build badge](https://img.shields.io/travis/smart-data-models/data-models.svg "Travis build status")](https://travis-ci.org/smart-data-models/data-models/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
-->

| :mega: [Latest news](https://smartdatamodels.org/) | :dart: [Roadmap](roadmap.md) | :closed_book: [Manifesto](MANIFESTO.md) | :inbox_tray: [eMail](mailto:info@smartdatamodels.org) | :wave: [Contact Us](http://smartdata-models.org/index.php/submit-an-issue-2/) |
| -------------------------------------------------- | ---------------------------- | --------------------------------------- |------------------------------------------------------------ | ----------------------------------------------------------------------------- |

**Note: This Repository does not accept Pull Requests concerning Data Models.
Pull Requests concerning Data Models shall be made against the corresponding
subject Repository where the data model is located**

## Full list of Data Models

A full list of the data models in machine-readable JSON format can be found in the file
[official_list_data_models.json](https://github.com/smart-data-models/data-models/blob/master/specs/AllSubjects/official_list_data_models.json).
Further details on the available subjects, properties and their descriptions can be found via the [search tool](https://smartdatamodels.org/index.php/ddbb-of-properties-descriptions/)

## Application Domains

There are new data models in progress for the following application domains (sectors):

-   [Cross Sector](https://github.com/smart-data-models/CrossSector)
-   [Smart Agrifood](https://github.com/smart-data-models/SmartAgrifood)
-   [Smart Cities](https://github.com/smart-data-models/SmartCities)
-   [Smart Energy](https://github.com/smart-data-models/SmartEnergy)
-   [Smart Environment](https://github.com/smart-data-models/SmartEnvironment)
-   [Smart Sensoring](https://github.com/smart-data-models/Smart-Sensoring)
-   [Smart Water](https://github.com/smart-data-models/SmartWater)
-   [Smart Destination](https://github.com/smart-data-models/SmartDestination) 
-   [Smart Aeronautics](https://github.com/smart-data-models/SmartAeronautics) 
-   [Smart Robotics](https://github.com/smart-data-models/SmartRobotics)
-   [Smart Health](https://github.com/smart-data-models/SmartHealth)
-   [Smart Manufacturing](https://github.com/smart-data-models/SmartManufacturing) 
-   [Smart Logistics](https://github.com/smart-data-models/SmartLogistics) (Just opened)


A frontend [web page](http://smartdatamodels.org/) provides global updates on the Smart data models.  
Additionally there is a repository for drafting data models named [incubated](https://github.com/smart-data-models/incubated/tree/master) where anybody
(under request) can draft data models that later can submit by PR or any other method. This repo is always open to collaboration.

## Who are we?

The **FIWARE Foundation** **IUDX**, **TM Forum** and **OASC** and others, are leading 
a joint collaboration program to support the adoption of a reference architecture 
and compatible common data models that underpin a digital market of interoperable and
replicable smart solutions in multiple sectors, starting with smart cities.

The Reference Architecture and Data Models use the ETSI NGSI API and TM Forum
Open APIs for interoperability and scalability of smart solutions. The FIWARE
Context Broker technology, implementing the ETSI NGSI APIs (**NGSI v2 and
NGSI-LD**), provides the basis for breaking information silos in organizations
aiming at becoming smart. Actually, it enables a real-time (or close to real
time, i.e., right-time) view and foundation for the development of governance
systems at global organization level. Examples of such organizations include
cities, factories, hospitals, airports, farms, etc.

Combined with [TM Forum Open APIs](https://www.tmforum.org/open-apis/), data 
publication platforms can support organizations to realise the potential of 
real-time (or right-time) open data, easing development of innovative solutions 
by third parties. In addition, organizations can evolve their current data sharing 
policies towards a vision which, shared with other organizations, brings support 
to a Data Economy. This way, the proposed Reference Architecture is ready to 
solve the needs of organizations today while future-proofing for 
tomorrow’s requirements.

This GitHub organization structure contains **JSON Schemas and documentation**
on Smart Data Models for different Smart Domains. The following repositories are available:

-   [data-models repository](https://github.com/smart-data-models/data-models) which is an umbrella repository that contains all the
    Data Models from different verticals (e.g., Parking, Street lighting, etc.).
    _This Repository only admit Pull Requests for templates and general documentation and 
    not for data models._

-   For each Domain (industrial sector) there is a Repository containing as submodules the link to the 
    Subjects containing all the Data Models related. And some other shared elements for all the domain.

-   For each Vertical(Subject) there is a Repository containing the Data Models related
    to that vertical. _These repositories do admit pull requests regardign data models_.

## General Principles

-   **Driven-by-implementation approach**: Specifications will be considered
    stable as soon as enough end user organizations (i.e., cities) have
    validated them in practice.

-   **Open-closed**. Breaking changes to already approved specs are not allowed.
    Instead, new versions shall deprecate attributes, add new attributes, extend
    enumerations, etc.

-   **Public and royalty-free** nature of specifications. Data Model Licensing
    mode. Preferred [Creative Commons by Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)

-   **Open contribution**. Contributions open to anybody (not only members),
    while final decision making corresponds to the administrators of the domains and Subjects. Steerin board could opposed to some contributions if it does not meet coding guidelines.
   

## Lifecycle

Specifications evolve over time through versions generated by the contributors in the communities 
of every Subject. A minimum of a version each year is recommended. The parameter schemaVersion in 
the schema denotes the version.

The way to handle new Data Models is administrated by the different subjects and domains:

- Steering board (currently, FIWARE foundation, IUDX, OASC and TMForum) will check for the consistency and updating of the different data models in this group of repositories. This sterring board will grow in coming dates.


## How to contribute

Contributions should come in the form of **pull requests** made against the corresponding Vertical Data Model repository.
An [introductory presentation](http://bit.ly/contribution_manual) about it.

As an alternative it is also possible to request a [new data model](http://smartdatamodels.org/index.php/submit-an-issue-2/) 
choose option **new data model** in the dropdown list.

A Data Model will contain the following artefacts in this structure:

-   `dataModel/`
  -   `README.md`: Pointing to the schema, the specifications in different formats and languages, etc 
information **This README.md is generated automatically**
  -   `schema.json`: The JSON Schema definition. It includes in the description of every property the type of property, the model, the valid values and some other elements according to the [contribution manual](https://bit.ly/contribution_manual)
  -    `notes.yaml`: Optional. File for customizing the specification of the data model.
  -    `LICENSE.md`. [Templated document](https://github.com/smart-data-models/data-models/blob/master/templates/LICENCE.md) with the text of the license default CC-BY 4.0
    -   `schemaDTDL.json`: The export of JSON Schema definition into [langauge DTDL](https://docs.microsoft.com/en-us/azure/digital-twins/concepts-models). 
   -  `/doc`. This directory contains the specifications of the data model in the different languages. They are generated automatically out of the json schema. 
   -  `/examples`. This directory contains the examples for the different versions of NGSI standard and different formats. 
               Example: [schema.json of WeatherObserved](https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/schema.json)
    -   `example.json`: a JSON example file key values of NGSI v2
               Example: [example.json of WeatherObserved](https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/examples/example.json)
    -   `example-normalized.json`: An example file in NGSI v2 normalized format
               Example: [example-normalized.json of WeatherObserved](https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/examples/example-normalized.json)
    -   `example.jsonld`: a JSON example file key values of NGSI LD
               Example: [example.json of WeatherObserved](https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/examples/example.jsonld)
    -   `example-normalized.jsonld`: A JSON example file in **NGSI-LD** normalized format
               Example: [example-normalized-ld.jsonld of WeatherObserved](https://github.com/smart-data-models/dataModel.Weather/blob/master/WeatherObserved/example-normalized.jsonld)
  -    `ADOPTERS.yaml`. [Templated document](https://github.com/smart-data-models/data-models/blob/master/templates/dataModel/ADOPTERS.yaml) with references a actual adoption of the data model.
               
Other files automatically generated                   
  -    `examplexxx.csv`: Automatically generated examples of the data model exported to csv format and located in the `/examples` directory
  -    `model.yaml`: Automatically generated model exported from schema.json. Only descriptions are completed manually (if not set in schema). Located in the root directory.        
  -    `swagger.yaml`: Automatically generated opbject to be visualized in [swagger editor](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/smart-data-models/dataModel.WaterNetworkManagement/master/Valve/swagger.yaml). Located in the root directory.

To facilitate contributions and their validation, we developed:
- [json schema validator](https://smartdatamodels.org/index.php/data-models-contribution-api/) for validating that the documented properties are complete and compliant with the [contribution manual](https://bit.ly/contribution_manual)

To achieve a better performance, we need to break down silo’s of data, 
ensuring that artificial intelligence can be applied across aggregated datasets 
and to ensure that individual citizen experience can be optimized across 
different services.

To achieve this, TM Forum and FIWARE launched this initiative, later IUDX adn OASC has joined it which seeks to 
harmonize data models across Smart applications. Other organizations are pending to join.

By agreeing across different communities, the common definition of smart
data models, this will empower innovators and companies to develop solutions
that adhere to this common definition and ultimately help enable
interoperability of services.

## @context

A @context is necessary when using this data models under a linked data paradigm.

Every subject (repository for a group of data models) has a file in the root named _context.jsonld_ with the reference context.
It is true that there is another _context.jsonld_ in the directory of this README.md file. It is obsolete and it is there only for historical reasons.
In case that you need to merge several @context from different subjects you can use this service in the [front page](https://smartdatamodels.org):

Home -> Tools -> [Subjects' @context merger (last option)](https://smartdatamodels.org/index.php/generate-a-local-context-based-on-smart-data-models-iris/)
