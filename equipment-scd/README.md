# Enterprise Equipment and Systen Control Diagram (SCD) function block types

These types are implemented and used to transform and harmonize diverse information coming from multiple OPC UA sources on the plant containing different information models. OPC UA gives each company high degree of freedom in how to structure the OPC UA address space, and as long as standardized OPC UA information models are not used in the industry, each company will define and describe similar type of information differently in each OPC UA server. These OPC UA types are instantiated in the Enterprise semantic layer where a unified asset hierarcy is constructed to be used by higher-level business applications and decision support systems.

The types in this NodeSet XML file is sub-typed from the ISA-95 OPC UA Companion Specification (https://github.com/OPCFoundation/UA-Nodeset/tree/master/ISA-95) so in order to use our published information model you first need to create a namespace and import the ISA-95 NodeSet XML file. We have used the ISA-95 Equipment object model which means that our types are subtyped from *EquipmentClassType* and *EquipmentType*

