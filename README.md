# The Pentester automator

## Description
This application automates most of the penetration testing tasks using the command line. It automates DNS information ,Gathering emails, WHOIS, Files, SocialMedia, Scan for live hosts, Port scan, Vulnerability assessment, Brute-force attack, Scan for Web site security as well.
This application can be used only on OS "Kali Linux", it will not work on other Linux versions unless you install all the tools manually.



## Information Gathering
  ```DNS

  $python pat.py --company [YourClientDomainName] -dns
  ```
  
   ```Emails

  $python pat.py --company [YourClientDomainName] -emails
  ```
  
   ```WHOIS

  $python pat.py --company [YourClientDomainName] -whois
  ```
  
   ```Files

  $python pat.py --company [YourClientDomainName] -files
  ```
  
   ```SocialMedia
 
  $python pat.py --company [YourClientDomainName] -socialmedia
  ```
  
   ```WebSearch

  $python pat.py --company [YourClientDomainName] -websearch
  ```
  
## Scanning
   ```LiveHosts

 $python pat.py --company [YourClientDomainName] -ip [NetworkIPAddress/Range] -livehosts
  ```
  
   ```PortScan

  $python pat.py --company [YourClientDomainName] -ip [NetworkIPAddress/Range] -portscan
  ```
  
## Vulnerability Assessment
   ```VulnsScan
  $python pat.py --company [YourClientDomainName] -ip [NetworkIPAddress/Range] -vulns
  ```
  
   ```BruteForce

  $python pat.py --company [YourClientDomainName] -ip [NetworkIPAddress/Range] -bruteforce
  ```
## Web Application Scan  
   ```WAF
  
  $python pat.py --company [YourClientDomainName] --url [WebServerUrl] -waf
  ```
  
   ```SSL
  
  $python pat.py --company [YourClientDomainName] --url [WebServerUrl] -ssl
  ```
  
   ```LoadBalance

  $python pat.py --company [YourClientDomainName] --url [WebServerUrl] -loadbalance
  ```
  
  ```WebVulns
  Web Server Vulnerability Assessment:  $python pat.py --company [YourClientDomainName] --url [WebServerUrl] -webvulns
  ```
  
## 💻 Meet the maker

Created with 💖 by Harish S.G

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

  
