![Build Status](https://img.shields.io/github/actions/workflow/status/usuario/eventlens-backend/ci.yml)
![License](https://img.shields.io/badge/license-none-lightgrey)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

# EventLens Backend

## Description  
EventLens is the backend system powering a collaborative photography app for social events such as weddings, parties, and birthdays. It handles event and user management, secure photo storage, and AI-driven image processing. The frontend is available on iOS, Android, and web browsers like Chrome.

## Main Features  
- Manage events and users (hosts and guests)  
- Authentication via magic links or QR codes  
- Secure, automatic upload and cloud storage of photos  
- AI integration for automatic image enhancement and creative filters  
- REST APIs to connect frontend and external services  

## Architecture  
- Modular microservices architecture including:  
  - Event service  
  - Photo service  
  - AI processing service  
- CI/CD pipeline enabling automated testing and deployment  
- PostgreSQL for relational data management  
- Cloud storage using S3, Cloudinary, or equivalent  

## Technologies  
- Node.js backend services  
- Docker containerization  
- PostgreSQL database  
- Integration with AI APIs (e.g., Replicate, Stability AI, OpenAI DALL·E)  
- Automated CI/CD workflows  

## License  
No license. Use at your own risk.