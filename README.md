# Doctor-API-project
The Doctor Appointment Application is a web-based application that simplifies the process of scheduling and managing appointments with doctors. It offers a user-friendly interface for patients to create accounts, log in, explore doctors' profiles, and schedule appointments. The application also includes features for appointment cancellation and secure authentication.

## Features
- **User Sign-up:** Patients can easily create an account by providing their name, email, password, and contact details.
- **User Sign-in:** Registered patients can securely log in using their email and password to access their account.
- **Doctor Profiles:** Patients can browse through comprehensive profiles of doctors, including their specialties, qualifications, and availability.
- **Appointment Booking:** Patients can conveniently schedule appointments with their preferred doctors by selecting suitable dates and times.
- **Appointment Cancellation:** Patients have the flexibility to cancel appointments if their plans change or if they no longer require the consultation.
- **Token-based Authentication:** The application ensures secure access to user accounts by implementing token-based authentication.
## Technologies Used
The Doctor Appointment Application is developed using the following technologies:

- Java
- Spring Boot
- Spring Data JPA
- Lombok
- Maven

## Endpoints
Here are some example endpoints provided by the Doctor Appointment Application:
- **POST /api/signup -** Create a new patient account.
- **POST /api/signin -** Sign in with a patient account.
- **GET /api/doctors -** Retrieve a list of available doctors.
- **POST /api/appointments -** Book a new appointment.
- **DELETE /api/appointments/{appointmentId} -** Cancel a specific appointment.

## How to Use
- **Sign Up:** Create a new account by providing your personal details.
- **Sign In:** Log in to your account using your email and password.
- **Browse Doctors:** Explore the list of doctors and view their profiles.
- **Book an Appointment:** Select a doctor, choose a suitable date and time, and confirm your appointment.
- **Cancel Appointment:** If needed, you can cancel your appointment from your account.
- **Log Out:** To securely sign out, click on the "Log Out" button.

## Summary
The Doctor Appointment Application is a user-friendly web-based platform that simplifies the process of scheduling and managing appointments with doctors. Patients can create accounts, log in, browse through doctors' profiles, schedule appointments, and cancel them if necessary. The application ensures secure access to user accounts through token-based authentication, providing a reliable and convenient experience for patients seeking medical consultation.
