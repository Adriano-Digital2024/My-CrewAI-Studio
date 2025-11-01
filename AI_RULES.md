# AI_RULES.md

## Tech Stack

- **Programming Language**: Python 3.8+
- **Web Framework**: Streamlit for building the web application
- **Database**: PostgreSQL for relational data
- **ORM**: SQLAlchemy for database interactions
- **Frontend Framework**: Streamlit for building user interfaces
- **Styling**: Tailwind CSS for utility-first CSS
- **Authentication**: OAuth2 with JWT for secure authentication
- **Containerization**: Docker for containerizing applications
- **Orchestration**: Docker Compose for container orchestration
- **CI/CD**: GitHub Actions for continuous integration and deployment

## Library Usage Rules

1. **Streamlit**: Use Streamlit for building all frontend components and backend logic. Avoid using Flask or Django for this project.
2. **SQLAlchemy**: Use SQLAlchemy for all database interactions. Avoid using raw SQL queries directly.
3. **Tailwind CSS**: Use Tailwind CSS for all styling needs. Avoid using traditional CSS or CSS frameworks like Bootstrap.
4. **OAuth2 with JWT**: Use OAuth2 with JWT for all authentication and authorization needs. Avoid using session-based authentication.
5. **Docker**: Use Docker for containerizing all services. Avoid using virtual machines.
6. **Docker Compose**: Use Docker Compose for orchestrating Docker containers in development and testing. Avoid using Kubernetes for this project.
7. **GitHub Actions**: Use GitHub Actions for CI/CD pipelines. Avoid using Jenkins or Travis CI.