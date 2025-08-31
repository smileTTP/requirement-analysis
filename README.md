# Requirement Analysis in Software Development.
This repo is to practice and document the principles of Requirement Analysis in the software development lifecycle.

# Why is Requirement Analysis Important?
Requirement Analysis is a critical phase in the Software Development Lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders share a clear and mutual understanding of what the system should do (functional requirements) and how it should perform (non-functional requirements).

Its importance lies in the fact that it creates the foundation for the entire project. Well-defined requirements help prevent miscommunication, reduce costly rework, and ensure that the final product aligns with business goals and user needs. By clarifying the project scope, requirement analysis guides the design, coding, and testing phases, while also providing measurable acceptance criteria for validation.

In short, without proper requirement analysis, projects risk scope creep, missed objectives, and wasted resources. With it, teams gain clarity, efficiency, and a structured path to successful software delivery.

# Key Activities in Requirement Analysis.
- Clarity and Understanding:
Requirement analysis ensures that all stakeholders have a shared understanding of what the software should do. This reduces ambiguity, prevents misunderstandings, and aligns the project team with user expectations.

- Scope Definition:
Clearly defining functional and non-functional requirements sets the boundaries of the project. This prevents scope creep and keeps the development process focused on agreed objectives.

- Foundation for Design, Development, and Quality Assurance:
Requirements act as the blueprint for system design and development, while also serving as benchmarks for testing and validation. This structured foundation helps in estimating cost and time accurately, and ensures the final product meets quality standards and customer needs.

# Key Activities in Requirement Analysis.
1. Requirement Gathering

This is the first step, where the project team collects information about the system from stakeholders such as clients, users, and subject matter experts. The goal is to understand the business needs and expectations.

Example: Interviewing hotel managers and customers to understand what features are essential in a booking management system (e.g., room search, booking, cancellation).

2. Requirement Elicitation

Elicitation goes beyond gathering — it focuses on uncovering hidden needs, clarifying vague requirements, and resolving conflicts between stakeholders. It ensures the real needs are captured, not just the stated ones.

Example: Running a workshop with hotel staff to identify pain points in the current booking process, such as difficulties in updating room availability in real-time.

3. Requirement Documentation

Once requirements are gathered and refined, they are documented in a structured way so they can serve as a reference throughout the SDLC. Documentation can take the form of Software Requirement Specifications (SRS), user stories, or use cases.

Example: Creating a requirement specification that states, “The system shall allow users to cancel bookings up to 24 hours before check-in and issue an automatic refund.”

4. Requirement Analysis and Modeling

In this step, the requirements are examined for feasibility, consistency, completeness, and priority. The team may also model the requirements using visual tools like UML diagrams, flowcharts, or entity-relationship diagrams to better understand system interactions.

Example: Creating a use-case diagram that shows how different actors (customers, admins, staff) interact with the booking system.

5. Requirement Validation

Validation ensures that the documented requirements truly reflect stakeholder needs and align with business goals. This step involves reviews, walkthroughs, and stakeholder sign-off to confirm accuracy, clarity, and testability of requirements.

Example: Reviewing the requirement list with hotel management to confirm that the system supports seasonal pricing and discount codes before development begins.

# Types of Requirements.
### 1. Requirement Gathering

- **Functional Requirements (FRs):**

    - Hotel Search: Users must be able to search for hotels based on various criteria such as location, check-in/check-out dates, price range, and amenities.

    - Room Availability: The system should display real-time room availability to prevent double bookings.

- **Non-Functional Requirements (NFRs):**

    - Performance: Search results should be returned within 2 seconds to ensure a responsive user experience.

    - Scalability: The system should be able to handle a large number of simultaneous search queries, especially during peak times.

### 2. Requirement Elicitation

- **Functional Requirements (FRs):**

    - Booking Process: Users should be able to select a room, enter guest information, and complete the booking process online.

    - Payment Integration: The system must support multiple payment methods, including credit/debit cards and online wallets.

- **Non-Functional Requirements (NFRs):**

    - Security: All payment transactions must be encrypted and comply with industry security standards to protect user data.

    - Availability: The booking system should be available 24/7, with minimal downtime for maintenance.

### 3. Requirement Documentation

- **Functional Requirements (FRs):**

    - User Profiles: The system should allow users to create and manage their profiles, including personal information and booking history.

    - Admin Dashboard: Administrators should have access to a dashboard to manage hotel listings, view bookings, and generate reports.

- **Non-Functional Requirements (NFRs):**

    - Usability: The user interface should be intuitive and easy to navigate for both guests and administrators.

    - Maintainability: The system should be modular, allowing for easy updates and maintenance.

### 4. Requirement Analysis and Modeling

- **Functional Requirements (FRs):**

    - Room Management: The system should allow hotel staff to update room availability, pricing, and amenities in real-time.

    - Booking Modifications: Users should be able to modify or cancel their bookings within specified policies.

- **Non-Functional Requirements (NFRs):**

    - Reliability: The system should ensure data consistency and integrity, especially during concurrent updates.

    - Performance: Updates to room availability and pricing should be reflected in the system within 1 second.

### 5. Requirement Validation

- **Functional Requirements (FRs):**

    - Confirmation Notifications: The system should send booking confirmations via email or SMS, including reservation details and booking reference.

    - Cancellation Policy: Users should be notified of the hotel's cancellation policy before confirming a booking.

- **Non-Functional Requirements (NFRs):**

    - Compliance: The system should adhere to legal and regulatory requirements, including data protection laws and consumer rights.

    - Performance: Notification delivery should occur within 1 minute of booking confirmation.