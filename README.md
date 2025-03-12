# EMAIL-SENDER
Email automatize proccess 


Este repositorio contiene:

Introducción de código:

Este código su funcionalidad es automatizar el proceso de enviar correos electrónicos, de manera sencilla a través de una terminal, se realiza colocando el server del que se enviara los correos electrónicos, el correo que emite el mensaje, y quien o quienes lo recibirá, se comprobó que el código funciona tras realizar pruebas exitosas.


Se necesita descargar las siguientes librerías para poder ejecutarlo:
from email.mime.multipart import MIMEMultipart
from email.mime.text import MIMEText
import smtplib
import json
