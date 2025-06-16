# airflow-projects
## 🚀Airflow + Astro (Weather ETL Pipeline)
This project demonstrates how to build a data pipeline using **Apache Airflow** powered by **Astro (Astronomer)**.\
The pipeline fetches real-time weather or space-related data from public APIs, transforms it, and loads it into a PostgreSQL database.
## Install Astro CLI (if not installed)
curl -sSL https://install.astronomer.io | sudo bash\
astro dev init  # Initializes Astro project structure if needed
## Start Airflow locally
astro dev start\
Airflow UI will be available at: http://localhost:8080 \
Default credentials: admin / admin