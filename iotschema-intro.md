
### What is iot.schema.org ?

- An open, publicly available, repository of semantic definitions for connected things 
- An extension of schema.org to enable descriptions of things in the physical world and their data
- A common set of tools and patterns, and a community process for contribution and publication of iot.schema.org definitions
- A way for domain experts to easily create semantic definitions that are relevant to their application domain

### What Problem Does It Solve?

- There are many diverse connected devices and many standards for communication with connected devices
- These address specific use case requirements, and there will not be a single best protocol or format
- The Device SDOs are focused on device certification and protocol level interoperability with other devices of the same SDO
- The Device SDOs scope does not address broader considerations of application interoperability

### How does iot.schema.org enable Semantic Interoperability?

- iot.schema.org definitions provide a protocol- and format-neutral way for applications to understand the affordances of, and data provided by, connected things
- iot.schema.org definitions enable these affordances and data to be understood in relationship with the physical world 
- iot.schema.org definitions are used to annotate instances of connected things and their data using simple markup with common formats like HTML, JSON, and web linking formats

### How it Works  

#### Semantic Categories

iot.schema.org semantic definitions consist of three  categories, or classes, that describe a measurement or actuation, of some physical property or item. 
1. A Capability describes general measurement and actuation of some physical variable or set of variables, for example the temperature of something, or the brightness of a light bulb. A Capability has some related Interactions.
2. An Interaction describes an affordance to the capability, which may be to read or write a value, or perform a complex action like smoothly changing the brightness of a light bulb. An Interaction annotation could be used with a hypermedia link or form to describe the link target or form action.
3. Data Item descriptions contain data types, units, minimum and maximum values, and other information about the data model, for example a shape or schema. Interactions exchange Data Items.

Category annotations are optional and may be used standalone, e.g. annotated Data Items may be used independently of their Interactions.

#### Features of Interest

Features Of Interest (FoI) describe the real-world targets of sensing and actuation
- Definitions may be developed in iot.schema.org, or more likely will come from domain experts
- GENIVI/VSS is a Specification for Automotive Features of Interest, called Branches, and actuation/measurement points, called Attributes and Signals 
- BrickSchema is an adaptation of Haystack that defines Features of Interest of buildings and actuation or measurement points

iot.schema.org defines relationships between Capabilities and Features of Interest to enable full descriptions of connected physical systems.s

### Who is it for?

- IoT platform providers will use iot.schema.org to make it easy for third party applications to use the platform
- Device vendors and SDOs will use iot.schema.org to publish protocol-neutral definitions of their devices to enable web scale adoption
- Domain experts will use iot.schema.org to create domain-specific languages for connected things and their applications
- Application providers will use iot.schema.org to make their applications portable across platforms

### How is it used?

- iot.schema.org semantic identifiers enable annotation of W3C Thing Descriptions 
- Thing Descriptions have Action, Event, and Property Interaction definitions that can be annotated with iot.schema.org Interaction names
- Thing Descriptions have DataSchema elements that can be annotated with iot.schema.org Data Item constraints, such as data type and units
- Thing Description enables applications to interact with connected things using diverse protocols and data formats
- iot.schema.org enables web pages to be annotated using schema.org style annotation in RDFa or microformats
- iot.schema.org terms can be used to annotate machine hyperlinks using rfc6690
- The semantic categories (Capability, Interaction, Data Item) are each optional and can be used separately, enabling data plane decoupling and data analysis without needing to interact with the sensors or actuators

### How do I Find Out More or Get Involved?

- Monthly teleconferences every third Thursday at 0900 Pacific time
https://github.com/iot-schema-collab/teleconferences/blob/master/README.md
- Join the W3C Community Group for definitions
https://www.w3.org/community/wot/
- iotschema-collab github issues for comments on models
https://github.com/iot-schema-collab/iotschema/issues






