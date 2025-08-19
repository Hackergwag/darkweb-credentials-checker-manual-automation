<h1>darkweb-credentials-checker-manual-automation</h1>

<h2>Description</h2>

darkweb-credentials-checker-manual-automation is a cybersecurity project that demonstrates how organizations can detect exposed credentials on the dark web. The project includes both manual analysis methods and a Python automation script, designed to showcase practical skills in dark web monitoring, threat intelligence, and security awareness.
<br />

This project is designed to showcase practical skills in:  
- Dark web research  
- Python scripting for automation  
- Cyber threat intelligence (CTI)  
- Security awareness for organizations  
<br />

<h2>Languages and Utilities Used</h2>

- <b>Kali</b>
- <b>Python3</b>
- <b>Tor-browser</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Manual Method: <br/>
<img src="https://imgur.com/1ZlulVN.png="darkweb"/>
<br />
<br />
<p align="center">
Manual scrapping of the darkweb:  <br/>
<img src="https://imgur.com/ms3PP1I.png" height="80%" width="80%" alt="darkweb"/>
<br />
<br />
  
## 🛠️ Manual Step-by-Step Process  
This involes the manual process of checking dark web marketplaces, forums, and paste sites for exposed credentials.  

1. 🔎 **Identify Target Sites**  
   - Collect `.onion` URLs of marketplaces, forums, and paste sites.  
   - These may come from threat intelligence feeds or OSINT sources.  

2. 🌐 **Connect to the Tor Network**  
   - Start the Tor service locally.  
   - Configure the browser to route traffic through Tor (SOCKS5 proxy).  

3. 📥 **Access Dark Web Sites**  
   - Visit each `.onion` site manually using Tor Browser.  
   - Authenticate if required (some marketplaces require registration).  

4. 🔍 **Search for Credentials**  
   - Manually browse forums, search paste dumps, or check marketplace data listings.  
   - Look for email addresses, usernames, passwords, or leaked database dumps.  

5. 📝 **Document Findings**  
   - Record which sites were accessible.  
   - Note if exposed credentials were found or if the site was unreachable.  
 

<p align="center">
Automated Method (Python):  <br/>
<img src="https://imgur.com/tvDuPG4.png" height="80%" width="80%" alt="darkweb"/>
<br />
<br />

<p align="center">
Automation Scan Result :  <br/>
<img src="https://imgur.com/wsfSo5W.png" height="80%" width="80%" alt="darkweb"/>
</p>

## 📌 Overview
DarkCheck is a Python-based automation tool designed to check `.onion` (Tor hidden service) sites for potential data leaks.  
The tool leverages the **Tor network** for anonymous connections and uses automation to scan multiple dark web URLs quickly.  

From the sample run:
- ✅ The first marketplace was **reachable** and returned a "no leaks found" result.  
- ⚠️ The second URL was **temporarily unreachable** due to issues on the server side (host not responding).  

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
