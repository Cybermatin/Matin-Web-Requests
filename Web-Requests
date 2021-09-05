#!/bin/user/python3
import requests
import colorama
from colorama import Fore,init

colorama.init() ## initialize the colorama

class colorma:
    CYAN = '\033[96m'
    BLUE = '\033[94m'
    GREEN = '\033[92m'
    YELLOW = '\033[93m'
    RED = '\033[91m'
    BOLD = '\033[1m'
    UNDER = '\033[4m'
    #--- ITS END ---
    END = '\033[0m'

print(f"""{colorma.CYAN}
    ╔══[Coded by : C Security,{colorma.RED}[Web.Requests]{colorma.CYAN}]
    ║
    ╠═Author of tools : MatiN
    ╠═Team name : dark_shell
    ║
    ╠═(~bay~)
    """)
    
init() #init the colorama Fore,init
search = ['robots.txt',
'search/',
'admin/',
'login/',
'sitemap.xml',
'sitemap2.xml',
'config.php',
'wp-login.php',
'log.txt',
'update.php',
'INSTALL.pgsql.txt',
'user/login/',
'INSTALL.txt',
'profiles/',
'scripts/',
'LICENSE.txt',
'CHANGELOG.txt',
'themes/',
'inculdes/',
'misc/',
'user/logout/',
'user/register/',
'cron.php',
'filter/tips/',
'comment/reply/',
'xmlrpc.php',
'modules/',
'install.php',
'MAINTAINERS.txt',
'user/password/',
'node/add/',
'INSTALL.sqlite.txt',
'UPGRADE.txt',
'INSTALL.mysql.txt']

url = input(Fore.YELLOW+" Enter the website : ")
for page in search:
	req = requests.get("https://"+url+"/"+page)
	if req.status_code == 200:
		print(Fore.GREEN+" [+] The desired page was found : "+url+"/"+page)
	else:
		print(Fore.RED+" [-] Page Not Found : "+url+"/"+page)
