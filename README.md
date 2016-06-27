Burp-Yara-Rules
========

##Description
Yara rules to be used with the Burp Yara-Scanner extension

##Introduction
Burp-Yara-Rules is a collection of Yara rules built from malicious code samples found on the Internet, in addition to Yara rules created by third-parties that identify malicious software commonly found hosted on websites.

The rules are intended to be used with the Burp Yara-Scanner extension found here: https://github.com/PolitoInc/Yara-Scanner.  The goal being to identify infected web pages during a web application assessment.

##Usage
Add the Yara-Scanner extension within Burp (follow the directions at the Yara-Scanner link above).  Then use the all.yar rules file as it combines all rules in this repository into a single file.
