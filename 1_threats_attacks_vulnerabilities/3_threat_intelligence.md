# **Threat Intelligence**

* **Threat Intelligence**
	* Open-Source Intelligence (OSINT) - Security websites, vulnerability databases, news media, social media, dark web, information sharing centers file repositories, code repositories, security researchers
	* Many companies offer proprietary closed-source threat intelligence solutions
	* Email Address Harvesting - Searching for valid emails in a domain
	* Evaluating a source -  Timeliness, Accuracy, Reliability
* **Managing Threat Indicators**
	* Properties that describe a threat
	* Ip addresses, file signatures, communication patterns, etc…
	* Only useful if it's able to be shared
	* CybOX - Cyber Observable eXpression - schema used to classify threats
	* STIX - Structured Threat Information - language used to express CybOX information
	* TAXII - Trusted Automated eXchange of Indicator Information - means to share the STIX content
	* OpenIOC - framework for describing and sharing threat information developed by FireEye
* **Intelligence Sharing**
	* TAXII, STIX and CybOX facilitate information sharing
	* Incident response, vulnerability management, risk management, security engineering, detection and monitoring are all supported by intelligence
	* Information Sharing and Analysis Centers (ISACs ) - Industry-specific way to confidentially share intelligence between like-minded competitors
* **Threat Research**
	* Process of using intelligence to get inside the heads of our adversaries
	* Reputational - detection using previously used indicators
	* Behavioral - Identify actors behaving the same way attackers have in the past
	* Sources include vendor websites, vulnerability feeds, conferences, academic journals, RFC documents, local industry groups, social media, threat feeds, adversary tactics, techniques, and procedures (TTP)
* **Identifying Threats**
	* Threat modeling identifies and prioritizes threats
	* Use a structured approach
		* Asset Focus - walk through potential threats asset by asset
		* Threat Focus - how different threats could affect information systems
		* Service Focus - how threats can interrupt services that others consume
* **Automating Threat Intelligence**
	* Automate the blacklisting of IP addresses from threat feeds
		* May cause service disruptions, deploy in alert-only mode first
	* Incident response is very manual involving tribal knowledge
	* Data Enrichment - automatically supplement threat information
	* AI/ML allows automated creation of malware signatures
	* Security Orchestration, Automation, and Response platforms (SOAR) automate the routine work of cybersecurity
* **Threat hunting**
	* Organized, systematic approach to seek out indicators of compromise
	* Once seen as building impenetrable fortress
	* Now we make "assumption of compromise"
	* Need to think like the attacker
		* Establish a hypothesis
		* Establish Indicators of Compromise
		* Incident Response
