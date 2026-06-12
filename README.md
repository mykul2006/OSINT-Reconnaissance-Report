<p align="center">

&#x20; <img src="assets/banner.png" alt="OSINT Report Banner" width="100%">

</p>


# OSINT Reconnaissance and Website Information Gathering Report

## Overview

This project demonstrates the use of Open-Source Intelligence (OSINT) techniques to gather publicly available information about websites using various reconnaissance tools.

## Objectives

* Perform Google Dorking for website discovery.
* Collect domain information using WHOIS.
* Conduct Reverse IP Lookup.
* Identify technologies used by websites using Wappalyzer.
* Determine server information using IdServe.
* Retrieve historical website snapshots using the Wayback Machine.
* Mirror websites using HTTrack for offline analysis.

## Tools Used

* Google Dorks
* WHOIS Lookup
* DomainTools Reverse IP Lookup
* Wappalyzer
* IdServe
* Wayback Machine
* HTTrack

## Methodology

### 1\. Website Discovery using Google Dorks

Different Google search operators were used to identify websites from multiple countries.

Examples:

* site:.pk intitle:"index of"
* site:.uk filetype:pdf
* site:.au inurl:login

### 2\. WHOIS Analysis

WHOIS lookups were performed to identify:

* Registrar information
* Domain creation dates
* Name servers
* Registration status

### 3\. Reverse IP Lookup

Reverse IP lookups were performed to discover domains hosted on the same infrastructure.

### 4\. Technology Fingerprinting

Wappalyzer was used to identify:

* CMS technologies
* JavaScript frameworks
* Hosting providers
* Analytics services

### 5\. Server Identification

IdServe was used to identify web server technologies and response headers.

### 6\. Historical Analysis

Wayback Machine snapshots were examined to observe website evolution over time.

### 7\. Website Mirroring

HTTrack was used to create offline copies of selected websites for educational analysis.

## Key Findings

* Publicly available information can reveal significant details about an organization's infrastructure.
* Technology fingerprinting assists in identifying attack surfaces.
* Historical website data can expose previous configurations and content.
* OSINT techniques provide valuable reconnaissance without direct interaction with target systems.

## Ethical Considerations

All activities were performed using publicly available information for educational purposes only. No unauthorized access, exploitation, or intrusive actions were conducted.

## Skills Demonstrated

* OSINT
* Information Gathering
* Domain Enumeration
* Website Fingerprinting
* Reconnaissance Methodology
* Cybersecurity Documentation

