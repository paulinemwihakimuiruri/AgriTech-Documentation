This section provides a summary of the technical implementation of the AgriTech system, including the system architecture, backend setup, database structure, and integrations.

## System Architecture

AgriTech is built using a modular architecture that separates user-facing interfaces from backend services and hardware integrations.

### Architecture Components:

- **React Dashboard** – For cooperatives and system admins
- **Mobile Apps (Farmer & Extension Officer)** – Built using Kotlin compose and designed in Figma
- **Backend (API)** – Python code, hosted on Render
- **Database** – MongoDB (NoSQL), hosted via MongoDB Atlas
- **IoT Layer** – ESP32 microcontroller + GPS for real-time tracking
- **Payment Gateway** – Integrated with Safaricom's Daraja API
  > ![System Architecture Diagram](../assets/system-architecture.png)

## Entity Relationship Diagram (ERD)

The ERD shows how data is structured and connected in the system. Entities include:

- **Users** (Farmer, Cooperative, Supplier, Extension Officer)
- **Machinery**
- **Lending records**
- **Payments**
- **Officer visits**
- **tracking**
- **authentication**
  > ![ERD Diagram](../assets/erd.png)

## Testing

- Unit tests implemented for critical backend endpoints
- QA test cases written for user flows (login, request, payment, reporting)
- IoT alerts tested using Wokwi simulator

## Dev Tools Used

- Visual Studio Code (development)
- Postman (API testing)
- Git & GitHub (version control)
- Figma (UI/UX designs)
  -Arduino(IoT device code)
