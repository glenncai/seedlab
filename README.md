# Software Security (Buffer Overflow)

### Introduction

The learning objective of this lab is for students to gain the first-hand experience on buffer-overflow vulnerability by putting what they have learned about the vulnerability from class into actions. Buffer overflow is defined as the condition in which a program attempts to write data beyond the boundaries of pre-allocated fixed length buffers. This vulnerability can be utilized by a malicious user to alter the flow control of the program, even execute arbitrary pieces of code. This vulnerability arises due to the mixing of the storage for data (e.g. buffers) and the storage for controls (e.g. return addresses): an overflow in the data part can affect the control flow of the program, because an overflow can change the return address.

### Lab Task Reference

- [Buffer-Overflow Vulnerability Lab](https://seedsecuritylabs.org/Labs_16.04/Software/Buffer_Overflow/)
- [The Chinese University of Hong Kong, Information Engineering Department](https://www.ie.cuhk.edu.hk/main/index.shtml)

### Details

<a href="./IERG4130_SoftwareLab.pdf" target="_blank">Click here to view task details 👈</a>

# Web Security (Cross-Site Scripting Attack)

### Introduction

Cross-site scripting (XSS) is a type of computer security vulnerability typically found in web applications. This vulnerability makes it possible for attackers to inject malicious code (e.g. JavaScripts) into victim's web browser. Using this malicious code, the attackers can steal the victim's credentials, such as cookies. The access control policies (i.e., the same origin policy) employed by the browser to protect those credentials can be bypassed by exploiting the XSS vulnerability. Vulnerabilities of this kind have been exploited to craft powerful phishing attacks and browser exploits.

To demonstrate what attackers can do by exploiting XSS vulnerabilities, we have set up a web application named Elgg in our pre-built Ubuntu VM image. Elgg is a very popular open-source web application for social network, and it has implemented a number of countermeasures to remedy the XSS threat. To demonstrate how XSS attacks work, we have commented out these countermeasures in Elgg in our installation, intentionally making Elgg vulnerable to XSS attacks. Without the countermeasures, users can post any arbitrary message, including JavaScript programs, to the user profiles. In this lab, students need to exploit this vulnerability to launch an XSS attack on the modified Elgg, in a way that is similar to what Samy Kamkar did to MySpace in 2005 through the notorious Samy worm. The ultimate goal of this attack is to spread an XSS worm among the users, such that whoever views an infected user profile will be infected, and whoever is infected will add you (i.e., the attacker) to his/her friend list.

### Lab Task Reference

- [Cross-Site Scripting Attack Lab (Elgg)](https://seedsecuritylabs.org/Labs_16.04/Web/Web_XSS_Elgg/)
- [The Chinese University of Hong Kong, Information Engineering Department](https://www.ie.cuhk.edu.hk/main/index.shtml)

### Details

<a href="./IERG4130_WebLab.pdf" target="_blank">Click here to view task details 👈</a>
