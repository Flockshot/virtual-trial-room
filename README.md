# Software Design for an E-Commerce Virtual Trial Room

Designed and documented the complete software architecture for an “Online Trial System Shopping Website” as part of the CNG350 (Software Engineering) course. The goal was to apply a formal software engineering lifecycle to develop an implementation-ready design for a complex e-commerce system featuring 3D virtual dummies, item browsing, and third-party API integrations.

This project's deliverables are two comprehensive engineering documents, compliant with international IEEE and ISO standards, that detail the system's requirements and design.

![Design](https://img.shields.io/badge/Methodology-Software_Engineering_Lifecycle-blue.svg)
![UML](https://img.shields.io/badge/Design-UML_Diagrams-informational.svg)
![Standard](https://img.shields.io/badge/Standards-IEEE_&_ISO-00758F.svg)

---

## 🎯 The System: Virtual Trial Room

The core challenge was to design a next-generation e-commerce platform that solves the "fit" problem. The system requirements included:
* Standard e-commerce features: User registration/login, item browsing, cart, and payment.
* **Virtual Trial Room:** The system's key innovation, allowing users to create a **3D virtual dummy** of themselves.
* **3D Visualization:** Users can select clothing items from the store and see them rendered on their 3D dummy to check visual fit before purchasing.
* **API Integration:** The system must interface with third-party systems, such as a **Bank API** for payment processing.

---

## 1. Deliverable: Software Requirements Specification (SRS)

This document formally defines the "what" of the system, capturing all functional and non-functional requirements in compliance with the **ISO/IEC/IEEE 29148:2011** standard.

* **Functional Requirements:** Detailed descriptions of all system behaviors, including:
    * User Registration & Authentication.
    * 3D Dummy Creation & Customization.
    * Item Browsing, Filtering, and Search.
    * Virtual "Try-On" Process.
    * Payment Transaction Handling.
* **Non-Functional Requirements:** Defined constraints and quality attributes, such as performance (load time), security (payment data), and usability.
* **UML Use Case Diagrams:** The system's behavior was modeled with Use Case diagrams, mapping all processes and interactions for each actor (e.g., Customer, Administrator, Bank API).

> **[Image: Main UML Use Case Diagram for the Virtual Trial Room]**
>
> *(**Developer Note:** Place the main Use Case diagram from your SRS here. It's the best overview of your system's functionality.)*

---

## 2. Deliverable: Software Design Description (SDD)

This document provides the architectural "blueprint" for the system, detailing the "how" in compliance with the **IEEE 1016-2009** standard. It translates the requirements from the SRS into a concrete design.

The SDD is structured around multiple architectural views:

* **Logical View:**
    * **UML Class Diagrams:** A detailed static model of the system, showing all classes (e.g., `Customer`, `Item`, `VirtualDummy`, `PaymentGateway`), their attributes, methods, and relationships (association, inheritance).
* **Process View:**
    * **UML Activity Diagrams:** Modeled the flow of control for complex processes like "Checkout" or "Create Dummy."
    * **UML Sequence Diagrams:** Showcased the time-based interactions between objects for key scenarios, such as `processPayment()`.
* **Development & Physical Views:**
    * **UML Component Diagrams:** Broke the system into modular software components (e.g., Web-UI, Database, 3D-Renderer, Payment-API-Connector).
    * **UML Deployment Diagrams:** Mapped the software components to a physical hardware infrastructure (e.g., Web Servers, Application Servers, Database Servers).

> **[Image: Main UML Class Diagram for the Virtual Trial Room]**
>
> *(**Developer Note:** Place the main Class Diagram from your SDD here. It shows the technical "blueprint" of your design.)*

---

## 🛠️ Key Skills & Concepts

* **Formal Requirements Engineering:** Eliciting, analyzing, and documenting functional and non-functional requirements.
* **IEEE/ISO Standards:** Strict adherence to professional documentation standards for software engineering (IEEE 1016 & ISO 29148).
* **UML-Based Modeling:** Comprehensive use of UML to model all aspects of a complex system (Use Case, Class, Sequence, Activity, Component, Deployment).
* **Software Architecture:** Designing a scalable and maintainable system by separating concerns into logical and physical views.