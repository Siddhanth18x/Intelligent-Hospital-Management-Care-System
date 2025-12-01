# Intelligent-Hospital-Management-Care-System
The Intelligent Hospital Management System (IHMS) is a full-stack web
application developed to automate and streamline hospital operations such as patient
management, doctor scheduling, appointments, and billing. The system aims to
enhance hospital efficiency, reduce manual effort, and improve patient satisfaction
through digital automation and intelligent decision-making.
Built using Java Spring Boot for the backend, Angular for the frontend, and MySQL as
the database, IHMS provides a secure, scalable, and user-friendly platform. It
incorporates JWT-based role authentication to manage access for Admins, Doctors, and
Patients.
What makes this project intelligent is the integration of AI-assisted smart scheduling,
which predicts optimal appointment slots based on doctor workload and patient
demand, along with an AI-powered chatbot for quick assistance. Additional modules
such as email/SMS notifications, data analytics dashboard, and PDF report generation
make it a complete and professional healthcare management solution.


intelligent-hospital-management-system/
├── backend/ # Spring Boot Backend
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/
│ │ │ │ └── com/
│ │ │ │ └── ihms/
│ │ │ │ ├── IhmsApplication.java
│ │ │ │ ├── config/
│ │ │ │ │ ├── SecurityConfig.java
│ │ │ │ │ ├── JwtConfig.java
│ │ │ │ │ └── DatabaseConfig.java
│ │ │ │ ├── controller/
│ │ │ │ │ ├── AuthController.java

│ │ │ │ │ ├── PatientController.java
│ │ │ │ │ ├── DoctorController.java
│ │ │ │ │ └── AppointmentController.java
│ │ │ │ ├── service/
│ │ │ │ │ ├── AuthService.java
│ │ │ │ │ ├── PatientService.java
│ │ │ │ │ ├── DoctorService.java
│ │ │ │ │ └── AppointmentService.java
│ │ │ │ ├── repository/
│ │ │ │ │ ├── PatientRepository.java
│ │ │ │ │ ├── DoctorRepository.java
│ │ │ │ │ └── AppointmentRepository.java
│ │ │ │ ├── model/
│ │ │ │ │ ├── Patient.java
│ │ │ │ │ ├── Doctor.java
│ │ │ │ │ ├── Appointment.java
│ │ │ │ │ └── User.java
│ │ │ │ ├── dto/
│ │ │ │ │ ├── PatientDTO.java
│ │ │ │ │ ├── DoctorDTO.java
│ │ │ │ │ └── AppointmentDTO.java
│ │ │ │ ├── security/
│ │ │ │ │ ├── JwtAuthenticationFilter.java
│ │ │ │ │ ├── JwtTokenProvider.java
│ │ │ │ │ └── UserDetailsServiceImpl.java
│ │ │ │ └── exception/
│ │ │ │ ├── GlobalExceptionHandler.java

│ │ │ │ └── CustomExceptions.java
│ │ │ └── resources/
│ │ │ ├── application.properties
│ │ │ ├── application-dev.properties
│ │ │ └── application-prod.properties
│ │ └── test/
│ │ └── java/
│ │ └── com/
│ │ └── ihms/
│ │ ├── controller/
│ │ ├── service/
│ │ └── repository/
│ ├── pom.xml
│ └── README.md
├── frontend/ # Angular Frontend
│ ├── src/
│ │ ├── app/
│ │ │ ├── core/
│ │ │ │ ├── guards/
│ │ │ │ ├── interceptors/
│ │ │ │ ├── services/
│ │ │ │ └── models/
│ │ │ ├── shared/
│ │ │ │ ├── components/
│ │ │ │ ├── directives/
│ │ │ │ ├── pipes/
│ │ │ │ └── shared.module.ts

│ │ │ ├── features/
│ │ │ │ ├── auth/
│ │ │ │ │ ├── login/
│ │ │ │ │ ├── register/
│ │ │ │ │ └── auth.module.ts
│ │ │ │ ├── dashboard/
│ │ │ │ ├── patients/
│ │ │ │ ├── doctors/
│ │ │ │ ├── appointments/
│ │ │ │ └── reports/
│ │ │ ├── layout/
│ │ │ │ ├── header/
│ │ │ │ ├── sidebar/
│ │ │ │ └── footer/
│ │ │ ├── app-routing.module.ts
│ │ │ ├── app.component.ts
│ │ │ ├── app.component.html
│ │ │ ├── app.component.scss
│ │ │ └── app.module.ts
│ │ ├── assets/
│ │ │ ├── images/
│ │ │ ├── icons/
│ │ │ └── styles/
│ │ ├── environments/
│ │ │ ├── environment.ts
│ │ │ └── environment.prod.ts
│ │ ├── index.html

│ │ ├── main.ts
│ │ └── styles.scss
│ ├── angular.json
│ ├── package.json
│ ├── tsconfig.json
│ └── README.md
├── docs/ # Documentation
│ ├── api/
│ ├── database/
│ └── deployment/
├── docker-compose.yml # For containerization
├── .gitignore
└── README.md



