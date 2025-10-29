Author: Yutian Yi
Affiliation: Xi’an Jiaotong-Liverpool University (XJTLU)
Year: 2025

📘 Overview

This ontology defines the core classes and properties required for automated compliance checking of residential building regulations in a Building Information Modeling (BIM) environment.
It is designed to support SHACL-based rule validation and linked data interoperability with IFC and Revit models.

The ontology enables:
Semantic description of architectural spaces (e.g., bedrooms, kitchens, bathrooms, corridors)
Encoding of measurable attributes (e.g., usable area, net height, clear width)
Alignment with IFC 4 entities (ifc:IfcSpace, ifc:IfcDoor, etc.)
Integration with pyRevit-based BIM data extraction workflows
This work forms part of a research framework exploring ontology-enabled BIM compliance checking and digital twin trust mechanisms for the AEC industry.

🧩 File Description

File: buildingRegulations_ex.ttl
Format: Turtle (RDF 1.1)
Prefix: ex: → http://yutian-research.org/buildingRegulations#
Aligned Standards: IFC 4, SHACL 1.1, RDF 1.1, OWL 2 DL
Key classes include: ex:Bedroom, ex:Kitchen, ex:Bathroom, ex:Corridor, ex:BalconyRailing
Key properties include: ex:usableArea, ex:netHeight, ex:clearWidth, ex:storeyHeight, ex:railingNetHeight# BuildingRegulations-Ontology
