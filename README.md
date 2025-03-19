import sys
import requests
from pathlib import Path
import argparse
import pyfiglet as py
from pyfiglet import DEFAULT_FONT
from colorama import Fore, Style
import  logging
#logging.basicConfig(filename='log.txt',level=logging.debug, format='(ascine)s - (leevelname)s- (message)s')
text = Fore.CYAN+ Style.BRIGHT + " WELCOME TO AFRIKYOU TECHNOLOGY HACKING "
#logging.info("logo afficher")
#logging.error("erreur de log")
text_logo =r''''       __      _ _                      
  __ _ / _|_ __(_) | ___   _  ___  _   _ 
 / _` | |_| '__| | |/ / | | |/ _ \| | | |
| (_| |  _| |  | |   <| |_| | (_) | |_| |
 \__,_|_| |_|  |_|_|\_\\__, |\___/ \__,_|
                       |___/ 
                       '''
print(Fore.GREEN+Style.BRIGHT+text_logo)
print(text)
exit()
