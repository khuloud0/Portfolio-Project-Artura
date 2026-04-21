# Project Charter – Interior Design Platform

## Project Purpose
The purpose of this project is to develop a lightweight interior design platform that enables users to instantly generate personalized room design suggestions based on structured inputs such as room type, size, style, and color preferences
## Project Objectives
1. To develop a functional MVP that generates interior design suggestions based on at least 4 user input parameters by the end of the project timeline.
2. To ensure users can receive 2–4 design recommendations in under 30 seconds without requiring initial login.
3. To implement a scalable database containing at least 30 predefined interior design templates for accurate matching and filtering.

## Stakeholders

### Internal Stakeholders:
- Project Team (Students / Developers).
They are the individuals responsible for building and developing the platform, including programming, design, and system implementation.


### External Stakeholders:
External stakeholders primarily include the current target users of the platform. Future user groups are outside the scope of the current MVP.

### 1️⃣ Current Target Users 
The primary target users for the MVP are **individuals living in small rented spaces, such as students and early professionals**.

These users need fast, simple, and practical interior design suggestions that help them improve their spaces quickly and easily.

### 2️⃣ Future Users (Scalability Segment)
Future versions may expand to additional user groups such as homeowners or commercial users, but these are not included in the current MVP.

### Team role & Responsibilites:
| Team Member | Role | Key Responsibilities |
| :--- | :--- | :--- |
| **Khuloud Alqarni** | Backend Lead | Backend development, API logic, and server-side functionality. |
| **Raghad Nassef** | Frontend Lead | Building the website interface and implementing the frontend experience. |
| **Layan Aldosari** | QA Lead | Testing, reviewing functionality, and ensuring quality and usability. |
| **Banan Aleid** | Database Lead & Project Manager | Database design and schema structure. Leading planning, task allocation, and cross-team coordination to ensure MVP delivery. |

### Description of the project’s scope
  
| Feature Category | In-Scope (Included) | Out-of-Scope (Excluded) |
| :--- | :--- | :--- |
| **User Interaction** | • User input form (room type, size, style, color preference)<br>• Progressive authentication (save-to-signup flow)<br>• User dashboard for saved designs | • Room image upload or scanning<br>• Advanced personalization algorithms |
| **Core Functionality** | • Template-based interior design suggestion system<br>• Display 2–4 design outputs per request<br>• Save Design functionality | • AI-generated interior design models<br>• 3D visualization or rendering |
| **Data & Filters** | • Filtering system (by room type and style)<br>• SQLite database storing design templates | • Furniture marketplace integration<br>• Payment systems or subscriptions |
| **System Design** | • Minimalist grid-based UI<br>• Modular Flask architecture | • Real-time collaborative design tools |

## Risks and Mitigation Strategies

| Risk | Mitigation Strategy |
| :--- | :--- |
| **Limited design dataset** | Start with curated templates (30–50 designs) |
| **Weak matching accuracy** | Use structured filters (room type, style) |
| **Scope creep** | Strict adherence to MVP features |
| **UI complexity** | Keep interface minimal and grid-based |
| **Backend integration issues** | Modular Flask architecture |
| **Low user engagement** | Add instant preview and simple UX flow |

## High-Level Project Plan

## 🚀 Project Roadmap

### Stage 1: Idea Development (Completed) ✅
* Define project concept and problem statement.
* Identify target users and initial features.

### Stage 2: Project Charter Development (Current Stage) 📍
* Define objectives, scope, stakeholders, and risks.
* Finalize project documentation.

### Stage 3: Technical Documentation 📝
* Design system architecture.
* Create database schema (SQL).
* Define Flask routes and system flow.

### Stage 4: MVP Development 🛠️
* Build backend using Flask and Python.
* Develop frontend.
* Implement design suggestion system.
* Integrate database with templates.
* Add **Save Design** feature with progressive authentication.

### Stage 5: Project Closure 🏁
* Testing and bug fixing.
* Final UI improvements.
* Prepare final presentation and demo.
* Submit documentation and project report.

## 📌 Key Milestones / Deliverables

* ✅ **Concept Defined:** Completed project idea and scope definition.
* ✅ **Project Charter:** Approved Project Charter document.
* ⏳ **Architecture Design:** Technical architecture and database design.
* ⚪ **MVP Launch:** Functional system (
* ⚪ **Final Handover:** Presentation and working demo.

### 💡 Value Proposition
The platform aims to streamline the interior design process by converting complex design decisions into a **simple, structured, and fast** digital experience. It enables users to instantly generate personalized interior design suggestions without requiring technical knowledge or professional expertise.

### 🚀 Key Innovation
* **Frictionless Experience:** No initial authentication required, providing immediate access to core tools.
* **Real-time Generation:** Structured design suggestions based on precise user inputs (room type, size, style).
* **Progressive Authentication:** Seamless user journey where account creation is deferred until the "Save Design" stage.

### 🏆 Competitive Advantage
* **Accessibility:** Simpler than traditional 3D tools that require advanced technical skills.
* **Efficiency:** Faster than manual design platforms or traditional consultation services.
* **Personalization:** More structured than inspiration-based apps that rely on unorganized visual browsing.

---
  
