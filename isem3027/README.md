# Activate the virtual environment
``` bash
python -m pipenv shell
```

If we do not want to use the virtual environment, we can use the following command to install django

``` bash
pip install django
```
By doing this, we can use the django command in the terminal

# How to lanuch the django server

Find the manage.py file and run the following command in the terminal

```bash
python manage.py runserver
```

## Find the IP address
We can use the following command to find the IP

For the Mac user, we can use the following command to find the IP address
```bash
ifconfig
```

For the Windows user, we can use the following command to find the IP address
```bash
ipconfig
```
## Connect to the server

Then we should locate the en0 and find the inet, which is the IP address

The new command is 

```bash
python manage.py runserver (IP address):(port)
``` 
For example the IP is 158.182.109.249 and the port is 8000, then the command is

```bash
python manage.py runserver 158.182.109.249:8000
```


