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
curl demo.ine.local/uploads/ --upload-file jasee.txt && echo "Success: Uploaded jasee.txt"    # for the messages
curl -X OPTIONS www.topjobs.lk -I
curl -I http://www.sliate.ac.lk | grep "Server"
curl -s http://www.sliate.ac.lk | grep -i "version"

Basic Request: curl www.sliate.ac.lk
Retrieve HTTP Headers: curl -I www.sliate.ac.lk
Follow Redirects: curl -L www.sliate.ac.lk
Save Output to File: curl -o sliate_homepage.html www.sliate.ac.lk
Save to Specific Path: curl -o ~/Downloads/sliate_homepage.html www.sliate.ac.lk
Download Multiple Files: curl -O url1 -O url2
Send Cookies from File: curl -b cookies.txt www.sliate.ac.lk
Include HTTP Headers in Output: curl -i www.sliate.ac.lk
Specify GET Parameters: curl -G -d "param1=value1&param2=value2" www.sliate.ac.lk
Use Proxy Server: curl -x http://proxy.example.com:8080 www.sliate.ac.lk
Limit Transfer Speed: curl --limit-rate 50k www.sliate.ac.lk
Simulate Browser User-Agent: curl -A "Mozilla/5.0" www.sliate.ac.lk
Request Compressed Response: curl --compressed www.sliate.ac.lk
Set Connection Timeout: curl --connect-timeout 10 www.sliate.ac.lk
Save HTTP Headers to File: curl -D headers.txt www.sliate.ac.lk
Pass Custom HTTP Headers: curl -H "Authorization: Bearer YOUR_TOKEN" www.sliate.ac.lk
POST Data to Server: curl -X POST -d "param1=value1&param2=value2" www.sliate.ac.lk
Upload File: curl -F "file=@/path/to/file" www.sliate.ac.lk/upload
Verbose Mode for Debugging: curl -v www.sliate.ac.lk
Silent Mode: curl -s www.sliate.ac.lk
Silent Mode with Errors Only: curl -sS www.sliate.ac.lk
Retry Command if Fail: curl --retry 3 www.sliate.ac.lk
Include Both Headers and Body: curl -i www.sliate.ac.lk
Get JSON Output: curl -H "Accept: application/json" www.sliate.ac.lk/api
Download Files with Wildcard: curl -O url/images/[1-10].jpg
Get HTTP Status Code: curl -o /dev/null -s -w "%{http_code}\n" www.sliate.ac.lk
HTTP Basic Authentication: curl -u username:password www.sliate.ac.lk/securepage
Specify Custom HTTP Method: curl -X DELETE www.sliate.ac.lk/resource/123
Download File in Background: curl -o sliate.html www.sliate.ac.lk &> curl_log.txt &
Upload JSON Data: curl -X POST -H "Content-Type: application/json" -d '{"key":"value"}' www.sliate.ac.lk/api
Download with Timeout and Retry: curl --retry 5 --connect-timeout 10 -O www.sliate.ac.lk/file.zip
Send Multiple Headers: curl -H "Authorization: Bearer TOKEN" -H "Content-Type: application/json" www.sliate.ac.lk/api
Get Response Time: curl -o /dev/null -s -w "Total time: %{time_total}\n" www.sliate.ac.lk
Upload and Save Cookies: curl -c cookies.txt -b cookies.txt www.sliate.ac.lk
Test Connection Without Data Download: curl -I www.sliate.ac.lk
Redirect Output to STDERR: curl -w "@curl-format.txt" -o /dev/null www.sliate.ac.lk 2> stderr_output.txt
Follow Redirects and Get Final URL: curl -L -w "%{url_effective}\n" -o /dev/null www.sliate.ac.lk
Colorize JSON Output: curl -s www.sliate.ac.lk/api | jq '.'
Set Maximum Redirects: curl --max-redirs 5 -L www.sliate.ac.lk
Use IPv4 Only: curl --ipv4 www.sliate.ac.lk
Use IPv6 Only: curl --ipv6 www.sliate.ac.lk
Add Referer Header: curl -e "http://example.com" www.sliate.ac.lk
Set Minimum TLS Version: curl --tlsv1.2 www.sliate.ac.lk
Ignore SSL Validation: curl -k https://www.sliate.ac.lk
Resume Partially Downloaded File: curl -C - -O url/largefile.zip
Save Error Output to Log: curl www.sliate.ac.lk --stderr error.log
Define Output Formatting Template: curl -w "HTTP Code: %{http_code}\nTime Total: %{time_total}\n" -o /dev/null -s www.sliate.ac.lk
Download with Random User-Agent: curl -A "$(shuf -n 1 user_agents.txt)" www.sliate.ac.lk
Limit Download Rate and Retry: curl --retry 5 --limit-rate 100k www.sliate.ac.lk
Exit on Non-200 Response: curl --fail www.sliate.ac.lk



```
