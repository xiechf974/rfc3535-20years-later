# Notes

* Collection of NEW requirements from operators
* Labelling of a requirement/description can be tweaked to capture a common message
* This is work-in-progress
* Paper # are listed [here](https://github.com/boucadair/rfc3535-20years-later/blob/main/Prez/IETF120/nemops-session2-summary.md#papers).

# Summary


|NEW Ops Requirement Label| Description| Papers|
|-------------------------|:------:|:------:|
|NEW-OPS-REQ-STRENGTHEN-DM |Network softwarization can only happen with a strong, committed standardization effort, complemented by active involvement in open-source projects that facilitate access to code|#1, #4|
|NEW-OPS-REQ-DM-RATIONALIZE|TRationalize this space and avoid redundant efforts. Unlike service and network models, IETF-defined device models are not widely implemented|#3, #4|
|NEW-OPS-REQ-QUICK-BUT-WELL|Develop a more agile process for the development and maintenance of YANG modules in the IETF. RFCs might not be suited for documenting YANG modules|#4, #5, #8|
|NEW-OPS-REQ-GUIDE-AND-PROFILE|The target application/applicability of a network management approach should be documented (e.g., edit profile documents that outline a set of recommendations for core/key features, along with appropriate justifications, will help foster more implementations that meet operators’ needs) |#4|
|NEW-OPS-REQ-ARCH|Need to promote more arch and framework documents to exemplify the intended use|#5|
|NEW-OPS-REQ-EASE-EXPOSURE|Focus on protocols and data models to expose network/service capabilities, network-wide services, and related operations |#1, #3, #4|
|NEW-OPS-REQ-TIMELY-DM|Consider having YANG as part of the protocol specification/change where possible, or have the YANG document progress in parallel|#4|
|NEW-OPS-REQ-READILTY-IMPLEM|The availablability of implementation is concerning|#4|
|NEW-OPS-REQ-DM2API|Readily available API specifications should be generalized from YANG modules for fast development, prototyping, and validation |#4|
|NEW-OPS-REQ-NW-API-DISCOVERY|Define a reference approach/process for service exposure discovery (APIs discovery)|#4|
|NEW-OPS-REQ-REASSESS|Reassess the value of some IETF proposals compared to competing or emerging solutions (e.g., gRPC/gNMI)|#4|
|NEW-OPS-REQ-BRIDGE|Create an eco-system where data and networking engineers can collaborate|#4|
|NEW-OPS-REQ-INTEGRATION|Consider approaches to ease integration by-design (e.g., protocols and data models)|#4|
|NEW-OPS-REQ-LOSSLESS|Consider programmatic approaches to ensure lossless mappings between service/network/device data models|#4|
|NEW-OPS-REQ-REUSABILITY|Consider approaches to ensure reuse/consistent data structure across various NM segments|#4, #5, #7|
|NEW-OPS-REQ-SCALE|Consider approaches for YANG models to scale + protocol considerartions (transactions, touches, etc.)|#4, #7|
|NEW-OPS-REQ-UNSILO|Necessity to handle the heterogeneity of data, configuration, and network management/requirements. Resolving such issue could draw on insights from parallel technical fields such as knowledge engineering practices and concepts associated with Linked Data in the Semantic Web, areas where it is common to manage problems of heterogeneity and data reconciliation across various application domains|#4, #8|
|NEW-OPS-REQ-IT-INTEGRATION|There is a need to ease the integration of low-level/network-oriented solution with native "IT tooling" (e.g., "https://opentelemetry.io/")|#3, #4|
|NEW-OPS-REQ-ITER|Need a velocity and approach to standardisation that allows for business goals to be incrementally realised|#5, #6|
|NEW-OPS-REQ-Y2KG|Need for reference specifications to translate YANG-based data into the knowledge graph|#4, #8|
|NEW-OPS-REQ-CLIENT-TOOLS|Focus on tooling is needed, especially on the client side.|#3, #4, #5, #8|
|NEW-OPS-REQ-IETF-TOOLS|Ease exposure of libraries and host tools (e.g., `yangkit`) to ease integration|#4|
|NEW-OPS-REQ-NEW-NEED|Some networks have specific network management requirements such as the need for asynchronous operations or constraints on data compactness|#4|
|NEW-OPS-REQ-GLUE|Distinct approaches followed in both the compute and the network environments make necessary to define suitable mechanisms for enabling an efficient interplay, while highly automating the overall service delivery procedure.|#2, #4, #8|

# Requirement Level

> Feel free to complete a column with your own assessment + update OP# with the operator name.
>


|NEW Ops Requirement Label   | Orange       | Telefonica     | Swisscom       | Equinix        |    DT          | China Telecom  |
|----------------------------|:------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|  
|NEW-OPS-REQ-STRENGTHEN-DM   |Strong        |     Strong     |  Nice to have  |     Strong     |      Strong    |    Strong      |    
|NEW-OPS-REQ-DM-RATIONALIZE  |Strong        |     Strong     |     Strong     |     Strong     |      Strong    |    Strong      |  
|NEW-OPS-REQ-QUICK-BUT-WELL  |Strong        |     Strong     |     Strong     |     Strong     |      Strong    |    Strong      | 
|NEW-OPS-REQ-GUIDE-AND-PROFILE|Nice to have  | Nice to have   |     Strong     | Nice to have  |      Strong    |    srtong      |
|NEW-OPS-REQ-ARCH            |Nice to have  | Nice to have   |     Strong     | Nice to have   |      Strong    | Nice to have   |
|NEW-OPS-REQ-EASE-EXPOSURE   |Strong        |     Strong     |     Strong     | Strong         |      Strong    |    strong      |
|NEW-OPS-REQ-TIMELY-DM       |Strong        |     Strong     |     Strong     | Strong         |      Strong    |    strong      |
|NEW-OPS-REQ-READILTY-IMPLEM |Strong        |     Strong     |     Strong     | Strong         |      Strong    |    strong      |
|NEW-OPS-REQ-DM2API          |Strong        |  Nice to have  |     Strong     | Nice to have   |      Strong    |    strong      |
|NEW-OPS-REQ-NW-API-DISCOVERY|Nice to have  |     Strong     |  Nice to have  | Nice to have   |  Nice to have  |   Nice to have |
|NEW-OPS-REQ-REASSESS        |Strong        |     Strong     |     Strong     | Strong         |      Strong    |     strong     | 
|NEW-OPS-REQ-BRIDGE          |Nice to have  |     Strong     |     Strong     |  Nice to have  |      Strong    |  Nice to have  |
|NEW-OPS-REQ-INTEGRATION     |Strong        |     Strong     |     Strong     |Strong          |    Strong      |     strong     | 
|NEW-OPS-REQ-LOSSLESS        |Nice to have  |     Strong     |   Nive to have | Nice to have   |      Strong    |  Nice to have  |
|NEW-OPS-REQ-REUSABILITY     |Strong        |     Strong     |     Strong     | Strong         |      Strong    |     strong     |
|NEW-OPS-REQ-SCALE           |Strong        |     Strong     |     Strong     |Strong          |      Strong    |  Nice to have  |
|NEW-OPS-REQ-UNSILO          |Nice to have  |  Nice to have  |     Strong     | Nice to have   |      Strong    |     strong     |
|NEW-OPS-REQ-IT-INTEGRATION  |Strong        |   Nice to have |   Nice to have | Nice to have   |  Nice to have  |  Nice to have  |
|NEW-OPS-REQ-ITER            |Strong        |     Strong     |     Strong     | Nice to have   |      Strong    |     strong     |
|NEW-OPS-REQ-Y2KG            |Nice to have  | Nice to have   |  Nice to have  | Nice to have   |  Nice to have  |  Nice to have  |
|NEW-OPS-REQ-CLIENT-TOOLS    |Strong        |     Strong     |  Nice to have  | Strong         |  Nice to have  |  Nice to have  |
|NEW-OPS-REQ-IETF-TOOLS      |Nice to have  |  Nice to have  |  Nice to have  | Nice to have   |  Nice to have  |  Nice to have  |
|NEW-OPS-REQ-NEW-NEED        |Nice to have  |     Strong     |  Nice to have  |Nice to have    |  Nice to have  |  Nice to have  |
|NEW-OPS-REQ-GLUE            |Nice to have  |     Strong     |  Nice to have  |Nice to have    |  Nice to have  |     strong     |

# Papers

1. [NEMOPS: RFC3535 and the forgotten word](https://www.ietf.org/slides/slides-nemopsws-nemops-rfc3535-and-the-forgotten-word-00.pdf)
   + (NEW-OPS-REQ-STRENGTHEN-DM) "New services can/should be modeled directly in YANG"
   + (NEW-OPS-REQ-EASE-EXPOSURE) "Should focus more on operational data aspects. There must be enough information to come to data driven decisions, which then ends in closed
     loops that solve (or prevent) incidents"
2. [Towards a Unified Compute and Communication Infrastructure for Application and Network Management](https://www.ietf.org/slides/slides-nemopsws-paper-towards-a-unified-compute-and-communication-infrastructure-for-application-and-network-management-00.pdf)
   + (NEW-OPS-REQ-GLUE) "Providing standardized models of unified compute and communication infrastructure, along with mechanisms to expose their properties"
3. [RFC3535, 20 Years Later from an Operator's Perspective (Deutsche Telekom)](https://www.ietf.org/slides/slides-nemopsws-paper-rfc3535-years-later-from-an-operators-perspective-deutsche-telekom-00.pdf)
   + (NEW-OPS-REQ-DM-RATIONALIZE) "The stability of the IETF models and the conformance to proper IETF YANG make them superior to OpenConfigg whose models suffer from inconsistencies across
     versions, this in turn leads to operational and interoperability issues"
   + (NEW-OPS-REQ-DM-RATIONALIZE) "We don't want to go down the path of scope and feature creep with an ever larger surface area of the language"
   + (NEW-OPS-REQ-CLIENT-TOOLS) "Collaboration on open-source software, like Orchestron (https://github.com/orchestron-orchestrator/)"
   + (NEW-OPS-REQ-EASE-EXPOSURE) "the convergence of configuration management and the collection and monitoring of operational state is essential"
   + (NEW-OPS-REQ-INTEGRATION) "The IETF could do more to help bridge the gap by providing standardized operational monitoring models to match the configuration models; at both the device level and the network/service level"
   + (NEW-OPS-REQ-IT-INTEGRATION) "The combination of the relevant TMF specifications and IETF YANG service models would offer service providers a comprehensive and powerful solution"
4. [RFC 3535, 20 Years Later: An Update of Operators Requirements on Network Management Protocols and Modelling](https://www.ietf.org/slides/slides-nemopsws-paper-rfc3535-years-later-an-update-of-operators-requirements-on-network-management-protocols-and-modelling-00.pdf)
5. [Rethinking Standardisation of Network Management](https://www.ietf.org/slides/slides-nemopsws-paper-rethinking-standardisation-of-network-management-00.pdf)
   + (NEW-OPS-REQ-QUICK-BUT-WELL) "need for iteration"
   + (NEW-OPS-REQ-ITER) "To keep operators engaged, the IETF needs a velocity and approach to standardisation that allows for business goals to be incrementally realised."
   + (NEW-OPS-REQ-CLIENT-TOOLS) "The need for open source"
   + (NEW-OPS-REQ-GUIDANCE) "There is little or no publications or standards consideration for how different IETF technologies might fit together. This places constraints on the relevance of the technologies that are developed in the IETF"
   + (NEW-OPS-REQ-REUSABILITY) "The need for reuse"
   + NEW-OPS-REQ-ARCH
6. [Agile Incremental Driven Development for Network Management](https://www.ietf.org/slides/slides-nemopsws-paper-agile-incremental-driven-development-for-network-management-00.pdf)
   + (NEW-OPS-REQ-ITER) "Enable agile incremental driven development"
7. [Evolving Challenges and Solutions in Network Management](https://www.ietf.org/slides/slides-nemopsws-paper-evolving-challenges-and-solutions-in-network-management-00.pdf)
   + (NEW-OPS-REQ-SCALE) "YANG Scalability"
   + "data sources should implement active streaming of data to post-processing systems immediately upon production, this will also ensure that closed-loop automation systems have access to data in near real-time."
   + (NEW-OPS-REQ-REUSABILITY) "There is potential for retrofitting Internet of Things (IoT) oriented protocols on telemetry or management-type signaling within the network management domain"
8. [IAB NEMOPS Position Paper - Telefonica](https://www.ietf.org/slides/slides-nemopsws-paper-iab-nemops-position-paper-telefonica-00.pdf)
   + (NEW-OPS-REQ-Y2KG) "the YANG language should evolve towards a grounding on formal knowledge representation to achieve the semantic  interoperability level. Standards like Resource Definition Framework (RDF) and Web 
Ontology Language (OWL) from the Semantic Web may serve as reference in this area."
   + (NEW-OPS-REQ-UNSILO) "Fixed hierarchical structure limits the modeling of complex scenarios where relationships within the data are important...graph structures provide a 
more flexible structure that can accommodate any kind of data"
   + (NEW-OPS-REQ-CLIENT-TOOLS) "Lack of mature YANG libraries, with several efforts in different programming languages that have been abandoned or that do not keep the pace of the standards"
   + (NEW-OPS-REQ-QUICK-BUT-WELL) "maintenance and up-to-date documentation of the YANG models is a not agile process"
   + (NEW-OPS-REQ-GLUE) "Integrating additional relevant information that could be required for those applications for taking decisions on the network"
