# AIRFLOW
This is a repository for learning Airflow. It contains notes, code snippets, and examples for learning Airflow.

## Set up

Create a virtual environment and install the required packages.

```bash
python3 -m venv airflow_env
source airflow_env/bin/activate
python3 -m pip install apache-airflow
```

Initialize the database.

```bash
airflow db init
```

Create a user.

```bash
airflow users create \
    --username admin \
    --firstname TorO \
    --lastname Ekle \
    --role Admin \
    --email tor-odin.ekle@capgemini.com
``` 


Start the web server.

```bash
airflow webserver --port 8080
```

Start the scheduler.

```bash
airflow scheduler
```

