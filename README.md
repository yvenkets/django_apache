# django_apache

Download apache (httpd-2.4.57-win64-VS17)

extract c:\apache24

cd c:\apache24\bin\

Command to start Apache - httpd.exe -k install

Command to start Apache - httpd.exe -k start

install vs build tools

https://visualstudio.microsoft.com/it/visual-cpp-build-tools/

![image](https://github.com/yvenkets/django_apache/assets/38104778/ea9db4bd-2564-4b29-b179-c131f4b0e80a)

run the below command for create environment variable 

set "MOD_WSGI_APACHE_ROOTDIR=C:\Apache24"
to activate the virtual environment

activate venv

to install mod_wsgi 

"pip install mod_wsgi"

execute the below command and paste the result in apache config file

mod_wsgi-express module-config

optional
edit settings.py
ALLOWED_HOSTS = ['www.app-name.com', 'app-name.com']
add your domain name or '*' to allow all domains.

the sample httpd.conf file available in the repositry.




