Burp-Yara-Rules
========

##Description
Yara rules to be used with the Burp Yara-Scanner extension

##Introduction
Burp-Yara-Rules is a collection of Yara rules built from malicious code samples found on the Internet, in addition to Yara rules created by third-parties that identify malicious software commonly found hosted on websites.

The rules are intended to be used with the Burp Yara-Scanner extension found here: https://github.com/PolitoInc/Yara-Scanner.  The goal being to identify infected web pages during a web application assessment.

##Usage
Add the Yara-Scanner extension within Burp (follow the directions at the Yara-Scanner link above).  Then use the all.yar rules file as it combines all rules in this repository into a single file.

##Additional Details
The Yara rules in this repository were found by searching the Internet for rules that detect common exploit kits, as well as by running the YaraGenerator (https://github.com/Xen0ph0n/YaraGenerator/) against downloaded exploit kit samples.  The rules look for:
* Signs of infection in HTML code
* Signs of infection in JavaScript code
* Signs of infection in CSS code
* Detection of infected JAR files
* Detection of infected PDF files
* Detection of infected SilverLight XAP files
* Detection of infected Flash SWF files
