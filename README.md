# bookroad
An intelligent reading planner that recommends books based on your available time, reading preferences, and personal goals.

## Running with Docker

You can easily run the entire application (backend API and PostgreSQL database) using Docker Compose.

### Prerequisites
- Docker and Docker Compose installed on your system.

### Steps to Run
1. Clone the repository and navigate to the root directory.
2. Build and start the containers using Docker Compose:
   ```bash
   docker compose up -d --build
   ```
3. The backend application will be available at `http://localhost:8080`.

### Stopping the Application
To stop the running containers:
```bash
docker compose down
```

To view the backend logs:
```bash
docker compose logs -f backend
```
