##Web, Web Applications & Browsers




TOC

Intro
Cull
General Attacks & OWASP Top Ten
Databases
* MongoDB
* PostgreSQL
* Mysql
* Oracle
* MSSQL
Securing Web Applications
Books
Papers
Talks
Reference Sites



http://yehg.net/encoding/


###Cull







[Cookieless Monster: Exploring the Ecosystem of Web-based Device Fingerprinting](http://securitee.org/files/cookieless_sp2013.pdf)
* Abstract �The web has become an essential part of our society and is currently the main medium of information delivery. Billions of users browse the web on a daily basis, and there are single websites that have reached over one billion user accounts. In this environment, the ability to track users and their online habits can be very lucrative for advertising companies, yet very intrusive for the privacy of users. In this paper, we examine how web-based device fingerprint- ing currently works on the Internet. By analyzing the code of three popular browser-fingerprinting code providers, we reveal the techniques that allow websites to track users without the need of client-side identifiers. Among these techniques, we show how current commercial fingerprinting approaches use questionable practices, such as the circumvention of HTTP proxies to discover a user�s real IP address and the installation of intrusive browser plugins. At the same time, we show how fragile the browser ecosystem is against fingerprinting through the use of novel browser- identifying techniques. With so many different vendors involved in browser development, we demonstrate how one can use diversions in the browsers� implementation to distinguish successfully not only the browser-family, but also specific major and minor versions. Browser extensions that help users spoof the user-agent of their browsers are also evaluated. We show that current commercial approaches can bypass the extensions, and, in addition, take advantage of their shortcomings by using them as additional fingerprinting features.


[Security and Open Redirects  Impact of 301-ing people in 2013](https://makensi.es/rvl/openredirs/#/)

[Writing an XSS Worm](http://blog.gdssecurity.com/labs/2013/5/8/writing-an-xss-worm.html)

[SSL/TLS Interception Proxies and Transitive Trust](http://media.blackhat.com/bh-eu-12/Jarmoc/bh-eu-12-Jarmoc-SSL_TLS_Interception-WP.pdf)
* Secure Sockets Layer (SSL) [ 1 ] and its successor Transport Layer Security (TLS) [ 2 ] have become key components of the modern Internet . The privacy, integrity, and authenticity [ 3 ] [ 4 ] provided by these protocols are critical to allowing sensitive communications to occur . Without these systems, e - commerce, online banking , and business - to - business exchange of information would likely be far less frequent. Threat actors have also recognized the benefits of transport security, and they are increasingly turning to SSL to hide their activities . Advanced Persistent Threat ( APT ) attackers [ 5 ] , botnets [ 6 ] , and eve n commodity web attacks can leverage SSL encryption to evade detection. To counter these tactics, organizations are increasingly deploying security controls that intercept end - to - end encrypted channels. Web proxies, data loss prevention ( DLP ) systems, spec ialized threat detection solutions, and network intrusion prevention systems ( N IPS ) offer functionality to intercept, inspect , and filter encrypted traffic. Similar functionality is present in lawful intercept systems and solutions enabling the broad surve illance of encrypted communications by governments. Broadly classified as �SSL/TLS interception proxies ,� these solutions act as a � man in the middle , � violating the end - to - end security promises of SSL. This type of interception comes at a cost . Intercepti ng SSL - encrypted connections sacrifices a degree of privacy and integrity for the benefit of content inspection, often at the risk of authenticity and endpoint validation . Implementers and designers of SSL interception proxies should consider these risks and understand how their systems operate in unusual circumstances



[ParrotNG](https://github.com/ikkisoft/ParrotNG/releases)
* ParrotNG is a Java-based tool for automatically identifying vulnerable SWF files, built on top of swfdump. One JAR, two flavors: command line tool and Burp Pro Passive Scanner Plugin.

[WebAppSec Testing Checklist](http://tuppad.com/blog/wp-content/uploads/2012/03/WebApp_Sec_Testing_Checklist.pdf)

http://google-gruyere.appspot.com/part1


[OWASP Web Application Security Testing Cheat Sheet](https://www.owasp.org/index.php/Web_Application_Security_Testing_Cheat_Sheet)


[MCIR - Magical Code Injection Rainbow](https://github.com/SpiderLabs/MCIR)
* The Magical Code Injection Rainbow! MCIR is a framework for building code injection vulnerability testbeds. MCIR unites SQLol, XMLmao, ShelLOL and XSSmh together in a magical world of code injection! They can experience the magic of feature sharing. Instead of having to wait for unicornFurnace to update each one, all the MCIR friends get updates they can all use! YAY! MCIR is designed to be good at making new friends, and they get to share updates to sanitization routines, environmental factor options, and interface tweaks. If you want to make a new friend to join the dancing and singing in the Magical Code Injection Rainbow, you can use any of the existing MCIR friends as a template and rewrite the portion where the friend does its magic, so we can inject ALL the things! YIPPEE!1


[wikto](https://github.com/sensepost/wikto)
* Wikto is Nikto for Windows - but with a couple of fancy extra features including Fuzzy logic error code checking, a back-end miner, Google assisted directory mining and real time HTTP request/response monitoring. Wikto is coded in C# and requires the .NET framework. 

[OWASP Testing Checklist](https://www.owasp.org/index.php/Testing_Checklist)


[skipfish](https://code.google.com/p/skipfish/)
* Skipfish is an active web application security reconnaissance tool. It prepares an interactive sitemap for the targeted site by carrying out a recursive crawl and dictionary-based probes. The resulting map is then annotated with the output from a number of active (but hopefully non-disruptive) security checks. The final report generated by the tool is meant to serve as a foundation for professional web application security assessments. 



[HTTPie - curl for humans](https://github.com/jakubroztocil/httpie)
* HTTPie (pronounced aych-tee-tee-pie) is a command line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. It provides a simple http command that allows for sending arbitrary HTTP requests using a simple and natural syntax, and displays colorized output. HTTPie can be used for testing, debugging, and generally interacting with HTTP servers.







Bypassing WAFs](http://www.nethemba.com/bypassing-waf.pdf)

https://xss-game.appspot.com/

XSS game http://escape.alf.nu/




[Making Mongo Cry Attacking NoSQL for Pen Testers Russell Butturini](https://www.youtube.com/watch?v=NgsesuLpyOg)



[leaps - shared text editing in Golang](https://github.com/denji/leaps)
* Leaps is a service for hosting collaboratively edited documents using operational transforms to ensure zero-collision synchronization across any number of editing clients.



[Postcards from a Post-XSS World - Michael Zalewski](http://lcamtuf.coredump.cx/postxss/#dangling-markup-injection)
* This page is a rough collection of notes on some of the fundamental alternatives to direct script injection that would be available to attackers following the universal deployment of CSP or other security mechanisms designed to prevent the execution of unauthorized scripts. I hope to demonstrate that in many cases, the capabilities offered by these alternative methods are highly compatible with the goals of contemporary XSS attacks. 

[Drupal Attack Scripts](https://github.com/gfoss/attacking-drupal)
* Set of brute force scripts and Checklist

[Drupal Security Checklist](https://github.com/gfoss/attacking-drupal/blob/master/presentation/drupal-security-checklist.pdf)

[SQL Injection wiki](http://www.sqlinjectionwiki.com/)

[Shadow Daemon](https://shadowd.zecure.org/overview/introduction/)
* Shadow Daemon is a collection of tools to detect, protocol and prevent attacks on web applications. Technically speaking, Shadow Daemon is a web application firewall that intercepts requests and filters out malicious parameters. It is a modular system that separates web application, analysis and interface to increase security, flexibility and expandability. Shadow Daemon is free software. It is released under the license GPLv2, so its source code can be examined, modified and distributed by everyone.

[unindexed](https://github.com/mroth/unindexed/blob/master/README.md)
* The site is constantly searching for itself in Google, over and over and over, 24 hours a day. The instant it finds itself in Google search results, the site will instantaneously and irrevocably securely delete itself. Visitors can contribute to the public content of the site, these contributions will also be destroyed when the site deletes itself.



[Self-Exfiltration: The Dangers of Browser-Enforced Information Flow Control](http://ericchen.me/self_exfiltration.pdf)
* Abstract �Since the early days of Netscape, browser vendors and web security researchers have restricted out-going data based on its destination. The security argument accompanying these mechanisms is that they prevent sensitive user data from being sent to the attacker�s domain. However, in this paper, we show that regulating web information flow based on its destination server is an inherently flawed security practice. It is vulnerable to self-exfiltration attacks, where an adversary stashes stolen information in the database of a whitelisted site, then later independently connects to the whitelisted site to retrieve the information. We describe eight existing browser security mechanisms that are vulnerable to these �self-exfiltration� attacks. Furthermore, we discovered at least one exfiltration channel for each of the Alexa top 100 websites. None of the existing information flow control mechanisms we surveyed are sufficient to protect data from being leaked to the attacker. Our goal is to prevent browser vendors and researchers from falling into this trap by designing more systems that are vulnerable to self-exfiltration.


[The Devil is in the Constants: Bypassing Defenses in Browser JIT Engines](http://users.ics.forth.gr/~elathan/papers/ndss15.pdf)
* Abstract �Return-oriented programming (ROP) has become the dominant form of vulnerability exploitation in both user and kernel space. Many defenses against ROP exploits exist, which can significantly raise the bar against attackers. Although protecting existing code, such as applications and the kernel, might be possible, taking countermeasures against dynamic code, i.e., code that is generated only at run-time, is much harder. Attackers have already started exploiting Just-in-Time (JIT) engines, available in all modern browsers, to introduce their (shell)code (either native code or re-usable gadgets) during JIT compilation, and then taking advantage of it. Recognizing this immediate threat, browser vendors started employing defenses for hardening their JIT engines. In this paper, we show that�no matter the employed defenses�JIT engines are still exploitable using solely dynamically generated gadgets. We demonstrate that dynamic ROP payload construction is possible in two modern web browsers without using any of the available gadgets contained in the browser binary or linked libraries. First, we exploit an open source JIT engine (Mozilla Firefox) by feeding it malicious JavaScript, which once processed generates all re- quired gadgets for running any shellcode successfully. Second, we exploit a proprietary JIT engine, the one in the 64-bit Microsoft Internet Explorer, which employs many undocumented, specially crafted defenses against JIT exploitation. We manage to bypass all of them and create the required gadgets for running any shellcode successfully. All defensive techniques are documented in this paper to assist other researchers. Furthermore, besides showing how to construct ROP gadgets on-the-fly, we also show how to discover them on-the-fly, rendering current randomization schemes ineffective. Finally, we perform an analysis of the most important defense currently employed, namely constant blinding , which shields all three-byte or larger immediate values in the JIT buffer for hindering the construction of ROP gadgets. Our analysis suggests that extending constant blinding to all immediate values (i.e., shielding 1-byte and 2-byte constants) dramatically decreases the JIT engine�s performance, introducing up to 80% additional instructions



###Securing Web Applications


[Center for Internet Security Apache Server 2.4 Hardening Guide](https://benchmarks.cisecurity.org/tools2/apache/CIS_Apache_HTTP_Server_2.4_Benchmark_v1.1.0.pdf)



[Magical Code Injection Rainbow Framework](https://github.com/SpiderLabs/MCIR)
* The Magical Code Injection Rainbow! MCIR is a framework for building configurable vulnerability testbeds. MCIR is also a collection of configurable vulnerability testbeds. Has testing lessons for xss/csrf/sql



###LFI & RFI

[LFI Local File Inclusion Techniques (paper)](http://www.ush.it/2008/08/18/lfi2rce-local-file-inclusion-to-remote-code-execution-advanced-exploitation-proc-shortcuts/) 
* This paper exposes the ability from the attacker standpoint to use /proc in order to exploit LFI (Local File Inclusion) vulnerabilities. While using /proc for such aim is well known this one is a specific technique that was not been previously published as far as we know. A tool to automatically exploit LFI using the shown approach is released accordingly. 
* [Update: a third (known) technique has been dissected here](http://www_ush_it/2008/07/09/local-file-inclusion-lfi-of-session-files-to-root-escalation/ ) 


[Liffy](https://github.com/rotlogix/liffy)
* Liffy is a Local File Inclusion Exploitation tool. 
Current features include: 
data:// for code execution
expect:// for code execution
input:// for code execution
filter:// for arbitrary file reads
/proc/self/environ for code execution in CGI mode
Apache access.log poisoning
Linux auth.log SSH poisoning
Direct payload delivery with no stager
Support for absolute and relative paths 
Support for cookies
! I have had issues with access log poisoning on current versions of Apache. This not an issue with the payload delivery and or poisoning. This is more of an issue with the request after the poisoning to kick off your shell. This may require a browser refresh. 









###HTML 5


[SH5ARK](http://sh5ark.professionallyevil.com)
* The Securing HTML5 Assessment Resource Kit, or SH5ARK, is an open source project that provides a repository of HTML5 features, proof-of-concept attack code, and filtering rules. The purpose of this project is to provide a single repository that can be used to collect sample code of vulnerable HTML5 features, actual attack code, and filtering rules to help prevent attacks and abuse of these features. The intent of the project is to bring awareness to the opportunities that HTML5 is providing for attackers, to help identify these attacks, and provide measures for preventing them

* [Presentation on SH5ARK](https://www.youtube.com/watch?v=1ZZ-vIwmWx4)

* [GetSH5ARK here](http://sourceforge.net/projects/sh5ark/)




##(NO)SQL Injection


[SQL Injection Cheat Sheet](http://ferruh.mavituna.com/sql-injection-cheatsheet-oku/)


[SQL Injection Knowledge Base](http://websec.ca/kb/sql_injection#MySQL_Testing_Injection)

[Pen Testing MongoDB](http://www.irongeek.com/i.php?page=videos/derbycon4/t408-making-mongo-cry-attacking-nosql-for-pen-testers-russell-butturini)

[Laduanum](http://laudanum.sourceforge.net/)
* �Laudanum is a collection of injectable files, designed to be used in a pentest when SQL injection flaws are found and are in multiple languages for different environments.They provide functionality such as shell, DNS query, LDAP retrieval and others.�








SQLi Lab lessons
From: https://github.com/Audi-1/sqli-labs
SQLI-LABS is a platform to learn SQLI Following labs are covered for GET and POST scenarios: 
Error Based Injections (Union Select) 
String
Integer
Error Based Injections (Double Injection Based)
BLIND Injections: 1.Boolian Based 2.Time Based
Update Query Injection.
Insert Query Injections.
Header Injections. 1.Referer based. 2.UserAgent based. 3.Cookie based.
Second Order Injections
Bypassing WAF 
Bypassing Blacklist filters Stripping comments Stripping OR & AND Stripping SPACES and COMMENTS Stripping UNION & SELECT
Impidence mismatch
Bypass addslashes()
Bypassing mysql_real_escape_string. (under special conditions)
Stacked SQL injections.
Secondary channel extraction