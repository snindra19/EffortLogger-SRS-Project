# EffortLogger SRS Project  

This repository contains the complete set of **Software Requirements Specification (SRS)** deliverables for the redesign of the EffortLogger system. The project focuses on building a modern effort logging and estimation system to support enterprise-scale Agile practices and **Planning Poker** estimation.  

---

## **Project Overview**  
The goal of this project is to update the legacy EffortLogger (originally built in the 1990s and updated in the early 2000s) into a system that:  
- Supports Agile processes at enterprise scale (e.g., **SAFe 6.0**, Azure Cloud Adoption Framework).  
- Enables **data-driven effort estimation** using individuals’ historical data.  
- Replaces opinion-based story point estimation with evidence-based decisions during Planning Poker.  
- Collects and organizes effort data (user stories, story points, influencing factors, languages, etc.) for future reference.  

---

## **Deliverables**  

This repository is organized into **four main deliverables**, each building on the previous one:  

### **1. EffortLogger-SRS V1.pdf – Customer Problem & Stakeholders**  
- Identifies the **core problem** faced by Agile teams using the outdated EffortLogger.  
- Lists and prioritizes **stakeholders** (e.g., Developers, Product Owners, Scrum Masters).  
- Uses multi-level outlines to explain the issues from a high-level, non-technical perspective.  

### **2. EffortLogger-SRS V2.pdf – Updated Problem, Stakeholders & Prioritized Operational Concepts**  
- Refines the original customer problem based on feedback.  
- Introduces **storyboards** to visualize developer interactions with the new EffortLogger.  
- Defines **Operational Concepts** using NASA’s ConOps framework to capture expected workflows during Planning Poker.  

### **3. EffortLogger-SRS V3.pdf – Requirements & Traceability**  
- Updates and expands the **received requirements** using **ISO/IEC/IEEE 29148** standards.  
- Adds **derived requirements** linked to received requirements for deeper clarity.  
- Introduces a **Requirements Verification & Validation (V&V) Traceability Matrix**, ensuring every requirement maps back to the customer problem and ConOps.  

### **4. EffortLogger-SRS Final.pdf – Architecture, Design & Implementability**  
- Defines the **architectural design** using UML diagrams and design patterns.  
- Provides **detailed design** of key modules for developers.  
- Explains **two-way traceability** from problem → requirements → design.  
- Justifies **implementability** by referencing standards, proven patterns, and existing systems.  

---

## **Key Concepts**  
- **Planning Poker:** Agile estimation technique enhanced by historical data.  
- **Story Points & User Stories:** Metrics replacing traditional Lines of Code (LOC).  
- **Privacy Focus:** Each developer maintains their own historical data repository.  
- **Non-functional Quality Attributes:** Security, performance, and usability built into the design.  
