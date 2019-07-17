# Question-Hacking
#1. What is Phreaking?
(1 Mark)
Hacking into mobile phones.
Hacking into telephone networks.
Hacking into cable TV networks.
Hacking using phones.
Explanation. 
Phreaking is a primitive term used with hacking into telephone networks majorly for making free calls.

2. How many MAC addresses can a computer have?
(1 Mark)
1
Depends on how many ports are open
Depends on how many network devices are there in the system
2 (One for internal and one for external network)
Explanation. 
MAC address is the hardware address of each network interface in a system. This means there will be a MAC address for your wireless card, one for your LAN card, one for Bluetooth adapter and so on.

3. Which of the following windows command are used to get all the MAC addresses of your device?
(1 Mark)
getmac
Ipconfig /all
getmac /v
All of the above
None of the above
Explanation. 
All these commands can be used to get MAC addresses of a windows device.

4. Which of the following is an internal IP?
(1 Mark)
56.251.36.44
192.148.2.1
172.16.96.123
100.2.36.89
None of the above
Correct Answer : c

Explanation. 
None of the given IP address falls in the range of Internal IP addresses (given below): 
192.168.0.0 - 192.168.255.255
172.16.0.0 - 172.31.255.255
10.0.0.0 - 10.255.255.255

5. How many valid IP addresses are possible in the given IP range (both ends included)? 
192.168.56.12 - 192.168.57.256
(1 Mark)
499
500
501
244
None of the above
Correct Answer : a

Explanation. 
Number of IPs in the range 192.168.56.12 to 192.168.57.12 = 256 IPs (both included)
Number of IPs in the range 192.168.57.13 to 192.168.57.256 = 244 IPs (both included)
But 192.168.57.256 is an invalid IP address, so total IP address possible in the given IP range = 256+244-1=499

6. Lease time is used in which protocol?
(1 Mark)
DNS
ARP
ICMP
DHCP
Explanation. 
The Dynamic Host Configuration Protocol (DHCP) is used to automatically assign IP addresses to the devices in a network. Each host is assigned an IP with a given lease time (in seconds). Now, if a device stays disconnected for more than the given lease time, the IP address assigned to the device is freed up which can be given to another new host, but if the host connects back within the given lease time, it will get the same IP address as before.

7. When you type api.facebook.com in the browser, the following steps will be taken to resolve the name (ignore caching): 
Entry will be checked in the hosts file.
DNS request will be sent to the router.
The router will send it to ISP DNS provider using static IP.
DNS provider will send the request to .com TLD server. 
.com will send it to facebook authoritative name server.
Facebook authoritative name server will check for subdomain entries.
It will pick the IP address of api.facebook.com entry and return the IP back.
Which of the following step is missing?
(1 Mark)
Request sent to the second level name server
Request sent to root name server
Both (a) and (b)
None of the above
Correct Answer : b

Explanation. 
The ISP sends the resolving request to the hidden dot (.) at the end of api.facebook.com. which signifies the root name server. The root name server then sends the request to TLD. Second level name server would have been used after TLD if the domain would have been facebook.co.in

8. OPTIONS method in HTTP is to:
(1 Mark)
Get the <head> of the response.
Get the available options on the website.
Get the available HTTP methods on the website.
It is an invalid HTTP method.
Correct Answer : c

Explanation. 
The HTTP OPTIONS method is used to get all the available HTTP methods like GET, POST, HEAD, TRACE etc. To get the , the HEAD method is used.

9. HTTPs requests are made so that the hackers cannot intercept them and see the data in them while they are being transferred. This makes it impossible to intercept and tamper HTTPs requests.
(1 Mark)
True
False
Explanation. 
We can still intercept HTTPs requests after installing the Burp CA certificate in our browser just like we did in the training through a 3rd party. A hacker cannot do this until he installs the certificate in the victim’s browser.

10. What is the size of port numbers in TCP requests given that there can be 65536 (2^16) ports in total?
(1 Mark)
1 Byte
2 Bytes
16 Bytes
32 bits
Explanation. 
Max number of ports given is 65536 i.e. 2^16.
1 Byte means 8 bits (1 byte = 8 bits) i.e. 2^8 possibilities which means 32.
2 Bytes is 16 bits which means 2^16 i.e. 65536.
32 bits is 2^32 which is 4.2 billion.

11. Which of the following command is used to see - what computers we are connected with?
(1 Mark)
Netstat
Ipconfig /show_connections
WiFi icon in the taskbar
ping command
Correct Answer : a

Explanation. 
Netstat command can be used to show IP addresses and port numbers of devices to which we are connected within windows, mac and Linux operating systems. It tells the protocol, the source IP, source port, destination IP/domain,and destination port too.

12. When we connect to a Virtual Private Network (VPN), the device will be assigned a unique:
(1 Mark)
Internal IP address like 10.56.69.123
External IP address like 165.56.36.144
Correct Answer : a

Explanation. 
VPN, as the name says, is a “Private” network. It makes us a part of a private internal network. Hence, it assigns the device a unique internal IP. Try connecting to a VPN and run ‘ipconfig’ command, you will see an internal IP address.

13. Which layer is responsible to encode and compress data?
(1 Mark)
Network
Transport
Presentation
Application
Explanation. 
The Presentation layer converts the data taken from the application layer into computer friendly format by encoding it, translating it into computer representations (like ASCII, hex, URL encode, etc.) and encryption/compression.

14. In the below given google dork, what will be searched in the SQL files? 
“admin” ext:sql site:x.com intext:password -download
(1 Mark)
admin
admin and password
password
download
Explanation. 
“Admin” (in quotes) means that the search will look for the keyword ‘admin’ everywhere but it must be somewhere in the result. intext:password will ensure that the response contains the word password anywhere in the body i.e. the SQL file. Hence, both will be searched in the SQL files.

15. What is the purpose of “dnsdumpster.com”?
(1 Mark)
To convert a Domain name to an IP
To convert an IP to a domain name
To find subdomains of a given domain
All of the above
None of the above
Explanation. 
“dnsdumpster.com” is used to find subdomains of a given domain name.

16. What can be the uses of “web.archive.org”?
(1 Mark)
(N.A)
Used to see how a website used to look at a certain time in the past
Used to download files from links that have expired but used to work previously
Search for ex-employees of a company
All of the above
None of the above
Correct Answer : d

Explanation. 
“web.archive.org” records all the client side part of websites and stores it, so that it can be used to see how a website/webpage used to look at a specific date/time in the past (which can reveal information of ex-employees on company websites). But, if the link used to contain a downloadable file, the web.archive will download the file to its own server. This means, if you click a download link and it’s not working, you can try opening it with web.archive.org and it might get downloaded.

17. What will happen when the “yolo” button is clicked? 
<body>
<a href=”http://google.com” id=’link1’ >clickme</a>
<button onclick='alert(document.getElementsByTagName("link1").href)'>yolo</button>
</body>
(1 Mark)
Popup with a text: http://google.com
Popup with a text: clickme
Error
Popup with a text: undefined
Nothing will happen
Explanation. 
There is no element with tag name “link1”. Instead, the id is “link1”. So, the href becomes undefined and the popup text will contain undefined. HTML code doesn't show errors like PHP, SQL, etc. If the code would have been alert(document.getElementById("link1").href), then the output would have been a popup with text http://google.com.

18. What will be the output of the following PHP code? 
<?php
$a=1;
while($a < 10){
echo("hello");
}
?>​
(1 Mark)
“hello” is displayed 10 times
“hello” is displayed 10 times in the same line
“hello” is displayed 9 times
“hello” is displayed 9 times in the same line
None of the above
Explanation. 
The above code is checking, if $a<10.But it is never increasing the value of $a using $a++ or $a=$a+1 
So, the value of $a always stays 1 and the loop executes infinite times. Hence, “none of the above” option is correct.

19. Uploading a txt file when website is asking for jpg file. This is a part of:
(1 Mark)
VA
PT
Correct Answer : a

Explanation. 
This is part of Vulnerability Assessment (VA) where we are simply trying to see if the website is checking the file type or not. Instead, if this step works and then we try uploading a PHP shell, that will come under Penetration Testing (PT).

20. What will be the output of this SQL query? 
SELECT news_title FROM news WHERE news_id=1 UNION SELECT password FROM users# test query
(1 Mark)
A row containing ‘news’ title whose id is 1 and second row containing a ‘password’.
A row containing ‘news’ title whose id is 1 and then rows containing all the passwords in the users table.
Error.
Correct Answer : b

Explanation. 
Union combines the output of 2 select queries. Here, the first query is fetching the news_title whose news_id is 1. The second query is fetching password from the users. This will give all the passwords in the users table as we haven't given any condition. # at the end is just to add a comment which will not execute. So, the output will be all rows of the first query and all rows of the second query.

21. Which authentication bypass payload will work for this login query (Assume your input will go in place of admin and password? 
Select * from login where user=(“admin”) && pass=(“password”)
(1 Mark)
‘ or ‘1’=’1
“ or “1”=”1
“) or (“1”)=(“1
“ 1=1--+
None of the above
Explanation. 
As in the query our data is going in between (“ HERE “) In our payload, we will use “) and (“ If we put option ‘c’ in the query: Select * from login where user=(“admin”) && pass=(“password“) or (“1”)=(“1”)

22. group_concat() in SQL is used to concat all rows in the output?
(1 Mark)
True
False
Correct Answer : a

Explanation. 
If there is a column called “name” containing:
Admin
Bulla
User123
And we run a query: select group_concat(name) from users, the output will be: Admin,bulla,user123 
If we do not use group_concat: select name from users, the output will be: 
Admin
Bulla
User123

23. In time based SQL injection, we ask the website: 
If length(database())>5 Then sleep(10)
If the website responds after 10 seconds, we get to know that the length of the database name is greater than 5.
(1 Mark)
True
False
Explanation. 
In time based SQL injections, we ask the website yes/no questions and tell the website to sleep for x seconds in case of a true/false statement. This is helpful when no other techniques are working.

24. Which of the following sqlmap script can be used to load HTTP request from a file?
(1 Mark)
-r
-request
-f
--load-file
Explanation. 
sqlmap.py -r httprequest.txt 
-r sqlmap script can be used to do injection everywhere in the HTTP request given in httprequest.txt
You can right click on any request in the burp suite and click on “copy to file” to create a file and pass it to sqlmap as shown above.

25. Why do we need to put CA certificate of the burp in our browser?
(1 Mark)
To intercept HTTPs requests of websites
So that our browser can trust Burp suite and allow intercept
To do pentesting easily on all the websites
All of the above
Explanation. 
Installing the CA certificate of the burp in our browser is done so that the browser can trust the Burp suite. Moreover, it allows the burp to intercept HTTP/HTTPs requests which makes pentesting easy on all the websites.

26. You have a list of XSS payloads. You want to try all those payloads in 10 parameters at the same time with the same value. Which intruder attack type is best suited for this?
(1 Mark)
Sniper
Cluster Bomb
Pitch Fork
Battle Ram
Correct Answer : a

Explanation. 
Sniper attack is used when your list of input is only 1 and you want to try those items in 1 or more positions at the same time.

27. Which vulnerability is most probable in this URL: 
http://site.com/home.php?include=readme.txt
(1 Mark)
SQL injection
IDOR
RFI
XSS
Correct Answer : c

Explanation. 
Whenever you see a filename especially with an extension in the parameter value like x.php?y=a.php There is a high chance of File Inclusion vulnerabilities like Remote File Inclusion (RFI) and Local File Inclusion (LFI).

28. You can brute force cookies with Burp Suite:
(1 Mark)
True
False
Explanation. 
With Burp intruder, you can brute force any part of an HTTP request. To do this, we need to send the request to the intruder and in the positions tab, simply select the cookie value you want to brute force and click the add button.

29. Below is a part of PHP code in the file upload function of a website. How will you bypass this and upload a usable PHP shell on the website: if($filename contains “php”){ die(“GO AWAY HACKER!!!”); }
(1 Mark)
Upload shell.Php
Upload shell.php.txt
Change filetype from php to image/jpeg in Burp
All of the above
None of the above
Correct Answer : a

Explanation. 
As you can see the code is checking if the filename contains the word “php” So, if we rename the file from shell.php to shell.PHP or shell.pHp we can bypass the filter.

30. Below is an XSS filter, how will you bypass it to create a popup: 
$input=$_GET[‘user_name’];
echo(remove_xss($input));

remove_xss($input){
convert $input to lowercase
remove all “script” 
remove all double and single quotes
Remove all img, iframe, onclick, body, svg, button, div, video
Remove all equal-to signs
}
(1 Mark)
<h1 onmouseover=alert(1)>
<scrIpT>alert(1)</ScRipt>
<javascript>alert(1)</javascript>
<scrSCRIPTipt>alert(1);</scrSCRIPTipt>
None of the above
Correct Answer : d

Explanation. 
Option ‘a’ will fail because it has =
Option ‘b’ will fail because everything is being converted to lowercase. Hence, scrIpT will become script which will get blocked.
Option ‘c’ will fail because there is no tag java script and it has the word script.
In case of option ‘d’, when the word SCRIPT be removed, the payload will become: <script>alert(1);</script>
This itself is a valid payload and will bypass the filter.

31. Which of the following is not a property in a ‘cookie’?
(1 Mark)
Cookie name
Cookie value
Cookie expiry time
Cookie https (secure) flag
Cookie created date time
Correct Answer : e

Explanation. 
Cookie has expiration date time but no creation date time.

32. In which of the following URL you are most likely to find an Apache tomcat login page?
(1 Mark)
http://site.com/html/manager
http://site.com/manager/html
http://site.com/tomcat
http://site.com/apache/admin
Correct Answer : b

Explanation. 
/manager/html is the default path for Apache tomcat manager application.

33. The following exploit is made in which language” https://www.exploit-db.com/exploits/46330
(1 Mark)
Python
Perl
C
Bash
None of the above
Explanation. 
This exploit is an example of a walk-through which does not have any code but has a write up explaining how to find and exploit SQL injection in osCommerce 2.3.4.1 - 'reviews_id' parameter.

34. WordPress default login page is at which URL:
(1 Mark)
/login
/wp-login
/admin
/wplogin
Explanation. 
WordPress default login page is at site.com/FOLDER/wp-login.php WordPress is usually installed in the blog part of the website. Note that the WordPress is not installed at the homepage of the website, it can be in a specific folder/part of the website.

35. How does a website comes to know that you are running a DirBuster and blocks it due to:
(1 Mark)
Default User-Agent header in Dirbuster Quickly trying
100s of directories and file names
Extensions Dirbuster tries
Cookies used by DirBuster
Correct Answer : a

Explanation. 
DirBuster by default does not have a normal user-agent like Mozilla/Chrome. Instead, it’s username by default is “DirBuster-0.12”, which can be easily blocked by the websites. Hence, if you see DirBuster not working properly, you can try changing this Dirbuster options -> HTTP options.

36. Which switch is used in Nmap to store the output in XML format?
(1 Mark)
-oN
-oX
-oA
None of the above
Explanation. 
-oN is used to save default text output.
-oX is used to store the output in XML.
-oA is used to save the output in all available formats.

37. You report a vulnerability to a company telling them about a vulnerability in “Yoast SEO” plugin in their WordPress. What will you recommend them to patch it:
(1 Mark)
Use a different plugin.
Make SEO feature manual instead of a plugin.
Update WordPress to the latest version.
Enable auto update feature in WordPress settings.
Correct Answer : d

Explanation. 
To fix such vulnerability, the client is supposed to update the plugin to the latest version or to disable it, till a patch is released (which is rare) . Enabling auto update feature in WordPress settings updates all plugins and WordPress version automatically.

38. You run Dirbuster and find the default login page of an application, you guess the password and get admin access to the website. Which of the following you do not include in PoC:
(1 Mark)
Dirbuster screenshot.
Screenshot of the login page.
Default password that worked.
Screenshot of the page after login.
Screenshots of critical things you are able to find/do after login.
Explanation. 
You do not need to include dirbuster screenshot, it is irrelevant to the developer. The developer only needs to know what you have found and how it can be exploited. He does not need to know how you found something. So, screenshots of Burp telling the vulnerability, nikto outputs, dirbuster outputs, etc. are not included in the reports.

39. You must put a detailed business impact in both developer and management level report.
(1 Mark)
True
False
Explanation. 
The business impact should be properly conveyed to both the developers and the higher management as they both need to know how critical a bug is so that they can prioritize patching the bugs.

40. Metasploit is a tool ________
(1 Mark)
That contains thousands of automatic exploits which can be used on various products easily.
To ease the process of report generation and PoC collection.
Which is a command line (non GUI) version of Zenmap.
That can be used to steal passwords and other data in networks.
That can be used to hack WiFi passwords.
Explanation. 
Metasploit is a ruby based tool which is mostly installed on Linux machines. It contains thousands of exploits like in case of exploit-db. The only difference being that you do not need to read the code to run them, instead, the entire tool is made so that you can run public exploit easily and automatically without needing to download scripts and other dependencies. It is an automated tool for VA and PT of public software like WordPress, Apache, windows, etc.

41. Acunetix is different than burp suite because:
(1 Mark)
Burp Suite is a semi-automated tool while acunetix is an automated tool
Acunetix makes beautiful Developer and Management level reports while Burp does not
Automated VAPT using Acunetix is paid while with Burp it’s free
All of the above
Correct Answer : a

Explanation. 
Burp suite is more of a semi automated tool which hackers can use to find bugs manually and even exploit them manually whereas acunetix is fully automated. Both make beautiful reports and are paid tools. Burps suits version that does automatic scanning like acunetix is a paid tool and not a free version (Burp Suite Community edition).

