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

```

```
curl www.sliate.ac.lk  # Fetches the content of the specified URL (www.sliate.ac.lk)

curl -I www.sliate.ac.lk  # Only retrieves HTTP headers from the specified URL

curl -L www.sliate.ac.lk  # Follows redirects automatically

curl -o sliate_homepage.html www.sliate.ac.lk  # Saves the output to a file

curl -o ~/Downloads/sliate_homepage.html www.sliate.ac.lk  # Saves the output to a specific file path

curl -O http://www.sliate.ac.lk/file1.pdf -O http://www.sliate.ac.lk/file2.pdf  # Downloads multiple files with their original names

curl -b cookies.txt www.sliate.ac.lk  # Sends cookies from a file to the specified URL

curl -i www.sliate.ac.lk  # Includes HTTP headers in the output

curl -G -d "param1=value1&param2=value2" www.sliate.ac.lk  # Sends GET request with parameters

curl -x http://proxy.example.com:8080 www.sliate.ac.lk  # Uses a proxy server for the request

curl --limit-rate 50k www.sliate.ac.lk  # Limits the transfer speed to 50 KB/s

curl -A "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 Chrome/91.0.4472.124 Safari/537.36" www.sliate.ac.lk  # Simulates a browser User-Agent

curl --compressed www.sliate.ac.lk  # Requests a compressed response from the server

curl --connect-timeout 10 www.sliate.ac.lk  # Specifies a 10-second connection timeout

curl -D headers.txt www.sliate.ac.lk  # Saves the HTTP headers to a separate file

curl -H "Authorization: Bearer YOUR_TOKEN" www.sliate.ac.lk  # Sends a custom Authorization header

curl -X POST -d "param1=value1&param2=value2" www.sliate.ac.lk  # Sends POST data to the server

curl -F "file=@/path/to/your/file.txt" www.sliate.ac.lk/upload  # Uploads a file using multipart form data

curl -v www.sliate.ac.lk  # Enables verbose mode for debugging

curl -s www.sliate.ac.lk  # Runs the command in silent mode (no progress information)

curl -sS www.sliate.ac.lk  # Silent mode with error messages only

curl --retry 3 www.sliate.ac.lk  # Retries the command up to 3 times if it fails

curl -i www.sliate.ac.lk  # Includes both headers and body in the output

curl -H "Accept: application/json" www.sliate.ac.lk/api  # Requests a response in JSON format

curl -O http://www.sliate.ac.lk/images/[1-10].jpg  # Downloads multiple files with a range of numbers

curl -o /dev/null -s -w "%{http_code}\n" www.sliate.ac.lk  # Outputs only the HTTP status code

curl -u username:password www.sliate.ac.lk/securepage  # Uses HTTP Basic Authentication for secure pages

curl -X DELETE www.sliate.ac.lk/resource/123  # Sends a DELETE request to a specific resource

curl -o sliate.html www.sliate.ac.lk &> curl_log.txt &  # Downloads a file in the background with a log

curl -X POST -H "Content-Type: application/json" -d '{"key":"value"}' www.sliate.ac.lk/api  # Uploads JSON data to the server

curl --retry 5 --connect-timeout 10 -O www.sliate.ac.lk/file.zip  # Downloads a file with retry and timeout

curl -H "Authorization: Bearer TOKEN" -H "Content-Type: application/json" www.sliate.ac.lk/api  # Sends multiple headers

curl -o /dev/null -s -w "Total time: %{time_total}\n" www.sliate.ac.lk  # Displays the total response time

curl -c cookies.txt -b cookies.txt www.sliate.ac.lk  # Uploads and saves cookies for reuse

curl -I www.sliate.ac.lk  # Tests the connection without downloading data (HEAD request)

curl -w "@curl-format.txt" -o /dev/null www.sliate.ac.lk 2> stderr_output.txt  # Redirects output to stderr

curl -L -w "%{url_effective}\n" -o /dev/null www.sliate.ac.lk  # Follows redirects and shows final URL

curl -s www.sliate.ac.lk/api | jq '.'  # Displays the response in a colored format (requires jq for JSON)

curl --max-redirs 5 -L www.sliate.ac.lk  # Limits the maximum number of redirects to 5

curl --ipv4 www.sliate.ac.lk  # Forces using IPv4 for the connection

curl --ipv6 www.sliate.ac.lk  # Forces using IPv6 for the connection

curl -e "http://example.com" www.sliate.ac.lk  # Sets the Referer header for the request

curl --tlsv1.2 www.sliate.ac.lk  # Forces using TLS version 1.2 for the connection

curl -k https://www.sliate.ac.lk  # Ignores SSL certificate validation (useful for self-signed certificates)

curl -C - -O http://www.sliate.ac.lk/largefile.zip  # Resumes a partially downloaded file

curl www.sliate.ac.lk --stderr error.log  # Saves error output to a separate log file

curl -w "HTTP Code: %{http_code}\nTime Total: %{time_total}\n" -o /dev/null -s www.sliate.ac.lk  # Defines a custom output format

curl -A "$(shuf -n 1 user_agents.txt)" www.sliate.ac.lk  # Downloads with a random User-Agent from a list

curl --retry 5 --limit-rate 100k www.sliate.ac.lk  # Limits download rate and retries if the command fails

curl --fail www.sliate.ac.lk  # Exits on non-200 HTTP responses (fails quietly)

```
