# Laravel Docker Setup

A demonstration project integrating **Laravel**, **Docker**, **PHP**, **MySQL**, **Nginx**, **Composer**, **phpMyAdmin**

**Author:** Marcin Aleksander Lorek(MarcinAL)
**License:** Custom configuration released for free use while retaining the author’s rights.  
**Components:**  
- Laravel (MIT License)  
- Docker (Apache 2.0 License)
- PHP (PHP License)  
- MySQL (GPLv2 License)
- Nginx (BSD 2-Clause License)
- Composer (MIT License)
- phpMyAdmin (GPLv2 License)

Note:
All third-party components retain their original licenses.
If any dependency or author has been unintentionally omitted, please contact the repository maintainer to ensure proper attribution.

---
Read comments in docker-compose.yml if you do not know how to execute container.
---

```text

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
