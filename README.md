# PyERP

# Deploy
```
apt-get update && apt-get upgrade -y
apt  install docker.io
sudo curl -L "https://github.com/docker/compose/releases/download/1.23.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

```
docker-compose up -d --build
```


# Install PyERP using the following command
```
virtualenv env --python=python3
source env/bin/activate
cd erp-sap
crear archivo installed_apps.py
pip3 install -r requirements.txt
python manage.py init_pyerp
python manage.py runserver
``` 
