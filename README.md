# Secure Communication System
This project is a secure communication platform that enables encrypted messaging via a web application, designed to prioritize data privacy and security. Using robust cryptographic algorithms, the system ensures end-to-end encrypted message delivery and integrates the Twilio SMS API for reliable real-time communication.

### Project Overview
Our class project aimed to develop a secure messaging system focused on privacy, utilizing Flask as the backend framework. The platform encrypts messages with advanced cryptographic methods to ensure confidentiality and uses the Twilio SMS API for message delivery. This project was collaboratively developed by a team of 4 members.

### Features
- End-to-End Encryption: Messages are encrypted on the sender's side and decrypted on the receiver's side using strong encryption.
- Twilio SMS Integration: Sends encrypted messages via SMS using Twilio API for prompt delivery.
- Secure Session Management: Flask-Session is used to manage user sessions securely.
- Web-Based Interface: The app is accessible via (https://twillio-app.vercel.app), offering an intuitive user experience.

### Technology Stack
- Backend: Flask
- Cryptography: PyCryptodome for encryption and decryption
- Session Management: Flask-Session for secure user sessions
- API Integration: Twilio API for SMS functionality
- HTTP Requests: Python Requests library

### Usage
1. Register/Login: Create an account or log in to access the system.
2. Send Encrypted Message: Input the recipient’s details and type your message, which is then encrypted and sent via SMS.
3. Decrypt Message: Messages received can be decrypted using the correct keys, maintaining confidentiality.

### Future Enhancements
- Additional encryption options
- Two-factor authentication for added security
- Enhanced UI for a smoother user experience
- Support for email-based communication

