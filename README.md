# Laravel Docker Setup

A demonstration project integrating **Laravel**, **Docker**, **PHP**, and **MySQL**.

**Author:** Marcin Lorek  
**License:** Custom configuration released for free use while retaining the author’s rights.  
**Components:**  
- Laravel (MIT License)  
- Docker (Apache 2.0 License)  
- PHP (PHP License)  
- MySQL (GPLv2 License)

---

Project Structure

laravel/
├── db/                     # Initialization scripts (if any)
│
├── docker-compose.yml       # Main Docker Compose configuration
│
├── laravel-app/             # Laravel application source code
│
├── mysql-data/              # Persistent MySQL database data
│
├── nginx/                   # Nginx configuration files
│   └── conf.d/
│
└── php/                     # PHP container setup
    ├── Dockerfile
    └── php.ini
