# Central-EV

React + Laravel + PostgreSQL, run with Docker.

## Setup
1. Install Git and Docker Desktop (open it and wait until it is running).
2. Clone and start:
   git clone https://github.com/somaknasaroeurn-rgb/Central-EV.git
   cd Central-EV
   copy backend\.env.example backend\.env
   docker compose up --build -d
3. After a few minutes, run:
   docker compose exec backend php artisan key:generate
   docker compose exec backend php artisan migrate
4. Open http://localhost:5173 (React) and http://localhost:8000 (Laravel).
