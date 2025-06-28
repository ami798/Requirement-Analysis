# Requirement Analysis in Software Development

This repository documents the Requirement Analysis phase of the **Software Development Life Cycle (SDLC)** using a simulated **Booking Management System** project. It includes structured insights, categorized requirements, visual diagrams, and well-defined acceptance criteria to simulate real-world software planning.

---

## What is Requirement Analysis?

Requirement Analysis is the process of gathering, analyzing, documenting, and validating what a system needs to achieve to fulfill business and user goals. It helps stakeholders establish a common understanding of the system’s functionality and constraints before development begins.

In the SDLC, this is considered a **blueprint phase**, guiding developers, testers, and designers by defining clear expectations.

---

## Why is Requirement Analysis Important?

1. **Prevents Miscommunication**  
   Aligns developers and stakeholders, reducing confusion and mismatched expectations.

2. **Ensures Scope Clarity**  
   Helps control project scope and manage deliverables efficiently, avoiding "scope creep."

3. **Foundation for Design and Testing**  
   Provides a base for UI/UX design, database modeling, test case creation, and development.

---

## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collect raw information from stakeholders using interviews, surveys, and observation.

- **Requirement Elicitation**  
  Clarify and expand gathered data through techniques like brainstorming, prototyping, or workshops.

- **Requirement Documentation**  
  Formalize the information using structured documentation like SRS, use cases, and user stories.

- **Requirement Analysis and Modeling**  
  Assess requirements for clarity, consistency, completeness, and feasibility. Represent using models and diagrams.

- **Requirement Validation**  
  Review with stakeholders to ensure requirements align with goals and can be realistically achieved.

---

## Types of Requirements

### Functional Requirements
Define **what** the system should do.

Examples (Booking Management System):
- Users can register and log in.
- Users can search properties by location and date.
- Users can book or cancel reservations.
- Admins can manage property listings.

### Non-functional Requirements
Define **how** the system performs.

Examples:
- System must load within **2 seconds**.
- Support at least **500 concurrent users**.
- Ensure secure data storage using **AES-256 encryption**.
- Maintain **99.9% uptime**.

---

## Use Case Diagrams

Use Case Diagrams visualize **interactions between actors and the system**, making system scope easier to understand for technical and non-technical stakeholders.

![Booking Use Case Diagram](https://raw.githubusercontent.com/ami798/requirement-analysis/main/alx-booking-uc.png)

> ✅ Make sure the image file `alx-booking-uc.png` is uploaded to the main folder of this repo.

**Actors:**
- Guest  
- Admin  

**Use Cases:**
- Register  
- Login  
- Search Properties  
- Book Property  
- Cancel Booking  
- Manage Listings  

---

## Acceptance Criteria

Acceptance Criteria define **conditions a feature must meet** to be accepted by the business or client. They ensure features are complete, testable, and aligned with expectations.

### Example: Booking Checkout Feature

- ✅ User must be logged in before initiating checkout.  
- ✅ Display a summary of reservation and total payment.  
- ✅ Allow secure payment via credit card or wallet.  
- ✅ System must receive successful response from payment gateway.  
- ✅ Send booking confirmation via UI message and email after successful transaction.

---

## 📌 Final Notes

This repository acts as the **blueprint phase of a real-world booking system**, reinforcing planning, clarity, and structure in modern software engineering practices. By following the industry-standard requirement analysis process, developers ensure project success before a single line of code is written.
