# 🚀 Personal API Documentation

Welcome to my personal API documentation. This API provides information about me as a Back-End Developer specialized in Java Spring Boot and PHP Laravel.

## Base URL

https://api.github.com/users/rodrigomedeirosdevjava

## Endpoints

### GET /me

Returns comprehensive information about my professional profile.

#### Response

```json
{
  "name": "Rodrigo Medeiros",
  "age": 40,
  "profession": "Back-End Developer",
  "specialization": "Java with Spring Boot | PHP with Laravel | APIs & Microservices",
  "about_me": "I am passionate about building the foundation and business logic of web applications through robust APIs and microservices architectures. My career has allowed me to work on projects across diverse sectors, including financial, banking, e-commerce, logistics, and government, always focusing on delivering secure, scalable, and low-maintenance solutions.",
  "technical_skills": {
    "languages": ["Java", "PHP"],
    "frameworks": ["Spring Boot", "Laravel", "Lumen"],
    "databases": ["MySQL", "PostgreSQL", "MongoDB", "DynamoDB"],
    "messaging": ["Kafka", "RabbitMQ"],
    "cloud_platforms": ["AWS", "Azure"],
    "testing": ["JUnit", "Mockito", "PHPUnit"],
    "tools": ["Docker", "Git"]
  },
  "methodologies": ["Clean Code", "SOLID", "TDD", "Microservices", "REST API Design"],
  "industry_experience": ["Financial", "Banking", "E-commerce", "Logistics", "Government", "Education"],
  "soft_skills": ["Clear Communication", "Proactivity", "Ownership", "Problem Solving"],
  "location": "São Luís/MA, Brazil"
}
