```
curl -X GET http://demo.ine.local
curl -I http://demo.ine.local
curl -X OPTIONS http://demo.ine.local -v
curl -X OPTIONS demo.ine.local -v
curl -X POST demo.ine.local
curl -X PUT demo.ine.local
curl -X OPTIONS demo.ine.local/login.php -v
curl -X POST demo.ine.local/login.php
curl -X POST demo.ine.local/login.php -d "name=john&password=password" -v
curl -X OPTIONS demo.ine.local/post.php -v
curl -X OPTIONS demo.ine.local/uploads/
curl -X OPTIONS demo.ine.local/uploads/ -v
echo "Hello World" > jasee.txt
curl demo.ine.local/uploads/ --upload-file hello.txt
curl demo.ine.local/uploads/ --upload-file jasee.txt
curl -X DELETE demo.ine.local/uploads/jasee.txt
```
