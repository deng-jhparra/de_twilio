Modificar 
TWILIO_ACCOUNT_SID ='XxYyZzXxYyZzXxYyZzXxYyZzXxYyZzXxYyZz'
TWILIO_AUTH_TOKEN ='XxYyZzXxYyZzXxYyZzXxYyZzXxYyZzXxYyZz'
PHONE_NUMBER ='+1 123 456 789'
API_KEY_WAPI = 'XxYyZzXxYyZzXxYyZzXxYyZzXxYyZzXxYyZz'

En utils.py modifica la linea colocando un numero de telefono valido  

to='+573222007879'


Crear un crontab para automatizar la tarea
53 13 * * * /usr/bin/python3 /home/ubuntu/de_twilio/twilio_script.py >> /home/ubuntu/de_twilio/twilio.log 2>&1
