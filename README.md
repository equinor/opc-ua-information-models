# OPC UA information models

In this repository Equinor makes OPC UA information models available as open source so that everybody can take advantage of what we have done and further develop it. Some of these OPC UA information models will be Equinor-specific, some of them will be based on other standards (that only exist as PDF documents) and some of them are sub-typed from existing OPC UA companion specifications. 

The OPC UA information models published here are not joint OPC UA companion specifications. All joint OPC UA companion specifications are published at https://github.com/OPCFoundation/UA-Nodeset (NodeSet XML files) and https://reference.opcfoundation.org/v104/ (Specification).

All our information models are published as XML files according to the NodeSet schema standardized by OPC Foundation and described in OPC UA Part 6 (https://reference.opcfoundation.org/v104/Core/docs/Part6/). 

Feel free to report feedback and issues at https://github.com/equinor/opc-ua-information-models/issues - all contributions are welcome.

## Why open source OPC UA information models?

* OPC UA is not only a connectivity framework standard, it is a global community working together to achieve interoperability and a secure and reliable exchange of information (data in context) across companies and platforms in the industry. We utilize and benefit from this community, and by open sourcing these information models we also contribute back to the community. Being open is a key to achieve adoption and we believe openness is in the spirit of OPC UA.

* We hope and believe that our work will result in and push a development of official joint OPC UA companion specifications, for example an IEC 63131 OPC UA companion specification, because people and companies will see that we have done quite a lot in that direction already. What we publish here is only the first step, our final destination are joint OPC UA companion specification that the industry commonly agrees on and commits to use. 

* If our suppliers and partnes actually use and build further on these models, it may result in increased adoption and standardization which mean less manual data mapping and interpretation of company-specific information in our future projects.

* We also believe and experience that when we open up and share, other companies do the same and we get access to more innovation. We as an industry get access to more innovation.

* The IT function in Equinor has a clear open source direction and ambition, in fact - we have a technical requirement in Equinor that all software developed by Equinor or on behalf of Equinor shall be made open source unless there is a very good reason not do it.

## Published OPC UA information models

* [equipment-scd](https://github.com/equinor/opc-ua-information-models/tree/master/equipment-scd): A set of enterprise OPC UA object types that we have sub-typed from the ISA-95 OPC UA companion specification (https://reference.opcfoundation.org/v104/ISA-95/ and https://opcfoundation.org/developer-tools/specifications-opc-ua-information-models/isa-95-common-object-model/). It includes typical oil & gas equipment types with naming and structure inspired from ISO 14224 (https://www.iso.org/standard/64076.html) and control function blocks with output terminals and parameters based on IEC 63131 (https://webstore.iec.ch/publication/60599). 
