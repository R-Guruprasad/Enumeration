# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/f55bef5f-4db4-4a21-bb54-9a7731a27e4f)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/98445dec-77e3-4c94-8b2d-5c5bdacf217b)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/e80b3686-401c-402e-9203-f99e42ac9a19)

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/6f91d65d-f6e6-42f9-94d6-35735e43e1d2)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/4e8e6296-7af2-407d-8124-82ee973cf4a5)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/9f80f6ab-f314-4ea8-b806-56076410f86d)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 ![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/6693e84f-75f9-41b1-b1c3-18d78db5b27b)

#DNS Enumeration

##DNS Recon

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/427e2005-a82f-45de-8c0c-5fc4282de0aa)

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/02c49608-f7cf-4e05-8df2-bb57e49c0031)

![image](https://github.com/R-Guruprasad/Enumeration/assets/119390308/0130dd0c-09a7-4602-b0bf-b1f503d1dcfc)


## OUTPUT:







##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

