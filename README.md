# Malwoverview

[<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/alexandreborges/malwoverview?color=red&style=for-the-badge">](https://github.com/alexandreborges/malwoverview/releases/tag/v6.2) [<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alexandreborges/malwoverview?color=Yellow&style=for-the-badge">](https://github.com/alexandreborges/malwoverview/releases) [<img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/alexandreborges/malwoverview?label=Release%20Date&style=for-the-badge">](https://github.com/alexandreborges/malwoverview/releases) [<img alt="GitHub" src="https://img.shields.io/github/license/alexandreborges/malwoverview?style=for-the-badge">](https://github.com/alexandreborges/malwoverview/blob/master/LICENSE) 
[<img alt="GitHub stars" src="https://img.shields.io/github/stars/alexandreborges/malwoverview?logoColor=Red&style=for-the-badge">](https://github.com/alexandreborges/malwoverview/stargazers)
[<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/ale_sp_brazil?style=for-the-badge&logo=X&color=blueviolet">](https://twitter.com/ale_sp_brazil)
[<img alt="Downloads/Last Month" src="https://img.shields.io/pypi/dm/malwoverview?color=blue&style=for-the-badge&label=Last%20Month">](https://pypistats.org/packages/malwoverview)
[![Downloads](https://static.pepy.tech/personalized-badge/malwoverview?period=month&units=international_system&left_color=grey&right_color=orange&left_text=Last%2030%20days)](https://pepy.tech/project/malwoverview)
[<img alt="Downloads/Total" src="https://static.pepy.tech/personalized-badge/malwoverview?period=total&units=international_system&left_color=grey&right_color=red&left_text=Total%20Downloads">](https://pepy.tech/project/malwoverview)
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://www.buymeacoffee.com/alexandreborges)

![Alt text](pictures/picture_1.jpg?raw=true "Title")
![Alt text](pictures/picture_2.jpg?raw=true "Title")
![Alt text](pictures/picture_3.jpg?raw=true "Title")
![Alt text](pictures/picture_4.jpg?raw=true "Title")
![Alt text](pictures/picture_5.jpg?raw=true "Title")
![Alt text](pictures/picture_6.jpg?raw=true "Title")
![Alt text](pictures/picture_7.jpg?raw=true "Title")
![Alt text](pictures/picture_8.jpg?raw=true "Title")
![Alt text](pictures/picture_9.jpg?raw=true "Title")
![Alt text](pictures/picture_10.jpg?raw=true "Title")
![Alt text](pictures/picture_11.jpg?raw=true "Title")
![Alt text](pictures/picture_12.jpg?raw=true "Title")
![Alt text](pictures/picture_13.jpg?raw=true "Title")
![Alt text](pictures/picture_14.jpg?raw=true "Title")
![Alt text](pictures/picture_15.jpg?raw=true "Title")
![Alt text](pictures/picture_16.jpg?raw=true "Title")
![Alt text](pictures/picture_17.jpg?raw=true "Title")
![Alt text](pictures/picture_18.jpg?raw=true "Title")
![Alt text](pictures/picture_19.jpg?raw=true "Title")
![Alt text](pictures/picture_20.jpg?raw=true "Title")
![Alt text](pictures/picture_21.jpg?raw=true "Title")
![Alt text](pictures/picture_22.jpg?raw=true "Title")
![Alt text](pictures/picture_23.jpg?raw=true "Title")
![Alt text](pictures/picture_24.jpg?raw=true "Title")
![Alt text](pictures/picture_25.jpg?raw=true "Title")
![Alt text](pictures/picture_26.jpg?raw=true "Title")
![Alt text](pictures/picture_27.jpg?raw=true "Title")
![Alt text](pictures/picture_28.jpg?raw=true "Title")
![Alt text](pictures/picture_29.jpg?raw=true "Title")
![Alt text](pictures/picture_30.jpg?raw=true "Title")
![Alt text](pictures/picture_31.jpg?raw=true "Title")
![Alt text](pictures/picture_32.jpg?raw=true "Title")
![Alt text](pictures/picture_33.jpg?raw=true "Title")
![Alt text](pictures/picture_34.jpg?raw=true "Title")
![Alt text](pictures/picture_35.jpg?raw=true "Title")
![Alt text](pictures/picture_36.jpg?raw=true "Title")
![Alt text](pictures/picture_37.jpg?raw=true "Title")
![Alt text](pictures/picture_38.jpg?raw=true "Title")
![Alt text](pictures/picture_39.jpg?raw=true "Title")
![Alt text](pictures/picture_40.jpg?raw=true "Title")
![Alt text](pictures/picture_41.jpg?raw=true "Title")
![Alt text](pictures/picture_42.jpg?raw=true "Title")
![Alt text](pictures/picture_43.jpg?raw=true "Title")
![Alt text](pictures/picture_44.jpg?raw=true "Title")
![Alt text](pictures/picture_45.jpg?raw=true "Title")
![Alt text](pictures/picture_46.jpg?raw=true "Title")
![Alt text](pictures/picture_47.jpg?raw=true "Title")
![Alt text](pictures/picture_48.jpg?raw=true "Title")
![Alt text](pictures/picture_49.jpg?raw=true "Title")
![Alt text](pictures/picture_50.jpg?raw=true "Title")

      Copyright (C)  2018-2025 Alexandre Borges (https://exploitreversing.com) 

      This program is free software: you can redistribute it and/or modify
      it under the terms of the GNU General Public License as published by
      the Free Software Foundation, either version 3 of the License, or
      (at your option) any later version.

      This program is distributed in the hope that it will be useful,
      but WITHOUT ANY WARRANTY; without even the implied warranty of
      MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
      GNU General Public License for more details.

      See GNU Public License on <http://www.gnu.org/licenses/>.


## Current Version: 6.2

     Important note:  Malwoverview does NOT submit samples to any endpoint by default, 
     so it respects possible Non-Disclosure Agreements (NDAs). There're specific options
     that explicitly submit samples, but these options are explained in the help.


## ABOUT

Malwoverview.py is a first response tool for threat hunting, which performs an initial and quick 
triage of malware samples, URLs, IP addresses, domains, malware families, IOCs and hashes. Additionally,
Malwoverview is able to get dynamic and static behavior reports, submit and download samples
from several endpoints. In few words, it works as a client to main existing sandboxes. 

This tool aims to : 

01. Determine similar executable malware samples (PE/PE+) according to the import table (imphash) and group 
    them by different colors (pay attention to the second column from output). Thus, colors matter!
02. Show hash information on Virus Total, Hybrid Analysis, Malshare, Polyswarm, URLhaus, Alien Vault, 
    Malpedia and ThreatCrowd engines. 
03. Determining whether the malware samples contain overlay and, if you want, extract it. 
04. Check suspect files on Virus Total, Hybrid Analysis and Polyswarm.
05. Check URLs on Virus Total, Malshare, Polyswarm, URLhaus engines and Alien Vault. 
06. Download malware samples from Hybrid Analysis, Malshare, URLHaus, Polyswarm and Malpedia engines.
07. Submit malware samples to VirusTotal, Hybrid Analysis and Polyswarm.
08. List last suspected URLs from URLHaus.
09. List last payloads from URLHaus. 
10. Search for specific payloads on the Malshare.
11. Search for similar payloads (PE32/PE32+) on Polyswarm engine.
12. Classify all files in a directory searching information on Virus Total and Hybrid Analysis. 
13. Make reports about a suspect domain using different engines such as VirusTotal, Malpedia and 
    ThreatCrowd. 
14. Check APK packages directly from Android devices against Hybrid Analysis and Virus Total. 
15. Submit APK packages directly from Android devices to Hybrid Analysis and Virus Total. 
16. Show URLs related to an user provided tag from URLHaus.
17. Show payloads related to a tag (signature) from URLHaus.
18. Show information about an IP address from Virus Total, Alien Vault, Malpedia and ThreatCrowd.
19. Show IP address, domain and URL information from Polyswarm. 
21. Perform meta-search on Polyswarm Network using several criteria: imphash, IPv4, domain, URL and
    malware family. 
22. Gather threat hunting information from AlienVault using different criteria. 
23. Gather threat hunting information from Malpedia using different criteria. 
24. Gather threat hunting information from Malware Bazaar using different criteria. 
25. Gather IOC information from ThreatFox using different criteria. 
26. Gather threat hunting information from Triage using different criteria. 
27. Get evaluation to hashes from a given file against Virus Total. 
28. Submit large files (>= 32 MB) to Virus Total. 
29. Malwoverview uses Virus Total API v.3, so there isn't longer any option using v.2.
30. Retrieve different information from InQuest Labs and download samples from there. 
31. Retrieve information and download malware samples from Virus Exchange (vxunderground). 
32. Retrieve information about a given IP address from IPInfo service.
33. Retrieve information about a given IP address from BGPView service.
34. Retrieve combined information about a given IP address from multiple services.
35. Offer extra option to save any downloaded file to a central location.

## CONTRIBUTORS

      Alexandre Borges (https://github.com/alexandreborges) | project owner and main developer
      Artur Marzano (https://github.com/Macmod) | co-main developer
      Corey Forman (https://github.com/digitalsleuth) | responsible for REMnux integration
      Christian Clauss (https://github.com/cclauss)

## HOW TO CONTRIBUTE TO THIS PROJECT

Since version 6.0.0, there is a new branch named "dev". All contributions and proposals 
must be done into this "dev" branch.

Professionals who want to contribute must open an issue explaining your proposed improvement 
and how it would make the project better. Once it has been accepted, so she/he is 
authorized to submit the PR, which will be tested. 

Once all changes are tested, this new version of Malwoverview is replicated to the master 
branch and a new Python package is generated.

## INSTALLATION

This tool has been tested on REMnux, Ubuntu, Kali Linux, macOS and Windows. Malwoverview 
can be installed by executing the following command:

      * pip3.11 install git+https://github.com/alexandreborges/malwoverview
      
      or...
      
      * python -m pip install -U malwoverview
      
If you want to install the Malwoverview on macOS, you have to execute the following commands:

      * /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
      * brew install libmagic
      * pip3 install urllib3==1.26.6
      * pip3 install -U malwoverview
      * Add Python binary directory to the PATH variable by editing .bash_profile file in your home 
        directory. Example:

          export PATH=$PATH:/Users/alexandreborges/Library/Python/3.9/bin

      * Execute: . ./.bash_profile

If you are installing Malwoverview on Windows, make sure that the following conditions are true  
AFTER having installed Malwoverview:

      * python-magic is NOT installed. (pip show python-magic)
      * python-magic-bin IS installed. (pip show python-magic-bin)

#### Note: It is recommended to save the .malwapi.conf before any update!


## REQUIRED APIs

It is possible to start using Malwoverview does without inserting all APIs. However, 
to use all options of Malwoverview, you must insert the respective API of the following services:
VirusTotal, Hybrid Analysis, URLHaus, Malshare, Polyswarm, Alien Vault, Malpedia, Triage, 
InQuest, Virus Exchange, APInfo, Malware Bazaar and ThreatFox into the .malwapi.conf 
configuration file, which must be present (or created) in the home directory (/home/[username]
or /root on Linux, and C:\Users\[username] on Windows. Alternatively, users can create 
a custom configuration file and indicate it by using the -c option.

To highlight: if the .malwapi.conf file does not exist in your home directory, so you must 
create it!

* A special note about the Alien Vault: it is necessary to subscribe to pulses on Alien Vault 
website before using -n 1 option.

The .malwapi.conf configuration file has the following format:

      [VIRUSTOTAL]
      VTAPI = 

      [HYBRID-ANALYSIS]
      HAAPI = 

      [MALSHARE]
      MALSHAREAPI = 

      [HAUSSUBMIT]
      HAUSSUBMITAPI =

      [POLYSWARM]
      POLYAPI = 

      [ALIENVAULT]
      ALIENAPI = 

      [MALPEDIA]
      MALPEDIAAPI =

      [TRIAGE]
      TRIAGEAPI =

      [INQUEST]
      INQUESTAPI =

      [VIRUSEXCHANGE]
      VXAPI =  

      [IPINFO]
      IPINFOAPI =  
      
      [BAZAAR]
      BAZAARAPI = 

      [THREATFOX]
      THREATFOXAPI = 

The APIs can be requested on the respective service websites:

01. Virus Total (community and paid API): https://www.virustotal.com/gui/join-us
02. Hybrid Analysis: https://www.hybrid-analysis.com/signup
03. Malshare: https://malshare.com/doc.php
04. URLHaus: https://urlhaus.abuse.ch/api/#account 
05. Polyswarm: https://docs.polyswarm.io/consumers
06. Alien Vault: https://otx.alienvault.com/api
07. Malpedia: It doesn't offer open registration, but you can request an user account 
    directly through Twitter (DM) or feedback e-email. The Malpedia Twitter 
    handle is @malpedia.
08. Malware Bazaar: https://bazaar.abuse.ch/api/#auth\_key
09. ThreatFox: https://threatfox.abuse.ch/api/#auth\_key
10. InQuest: https://labs.inquest.net/.
11. Triage: https://tria.ge/signup.
12. Virus Exchange: https://virus.exchange/ 
13. IPInfo: https://ipinfo.io/ 
14. BGPView: https://bgpview.docs.apiary.io/


----------------------------------------------------
Note about API requests to the MALPEDIA:
----------------------------------------------------

The service and acceptance is based on the community vetting. Thus, it's recommended 
you send a request for an API from your business e-mail address and NOT 
public/free one (Gmail, Outlook and so on). Additionally, it'd be great whether 
you provided further information about you (LinkedIn account, Twitter and so on) 
because it would make simpler to proof your identity, professional profile and 
legitimacy, so making quicker the approval of your request.  


----------------------------------------------------
Note about Triage:
----------------------------------------------------

Every Triage operation is based on the Triage ID of each artifact, so you need to
use the "-x 1 -X \<attribute\>:\<value\>" to search for the correct ID of the artifact,
so use this ID information with the remaining Triage options (-x [2-7]) for getting 
further threat hunting information from Triage endpoint.


----------------------------------------------------
Note about Malware Bazaar and Threat Fox: 
----------------------------------------------------

Since second semester of 2025, it is required the Auth-Key (API) to use Malware 
Bazaar and Threat Fox services.


----------------------------------------------------
Note about background color of the terminal:
----------------------------------------------------

Malwoverview has been written to produce outputs to 
dark background terminal. However, there's the -o 0 
option, which changes and adapts output's colors to 
light background.

-----------------------------------------------------


To check the installation, execute:

       malwoverview --help
       
Further information is available on: 

       (PYPI.org repository) https://pypi.org/project/malwoverview/
       (Github) https://github.com/alexandreborges/malwoverview

If you want to perform the manual installation (it is not usually necessary), so few steps 
should be executed, as shown in the next sub-section. 


## MANUAL INSTALLATION (REMnux and Ubuntu)

1. Python version 3.11 or later (Only Python 3.x !!! It does NOT work using Python 2.7) 

       $ apt-get install python3.11  (for example)

2. Python-magic.  

      To install python-magic package you can execute the following command:

       $ pip3.11 install python-magic

      Or you can compile it from the github repository:

       $ git clone https://github.com/ahupp/python-magic
       $ cd python-magic/
       $ python3.11 setup.py build
       $ python3.11 setup.py install

      As there are serious issues related to existing two versions of python-magic package, the  
      recommendation is to install it from github (second procedure above) and copy the magic.py 
      file to the SAME directory of malwoverview tool. 
      
3. Install all needed Python packages: 

       $ pip3.11 install -r requirements.txt

       OR

       $ pip3.11 install -U pefile
       $ pip3.11 install -U colorama
       $ pip3.11 install -U simplejson
       $ pip3.11 install -U python-magic
       $ pip3.11 install -U requests
       $ pip3.11 install -U validators
       $ pip3.11 install -U geocoder
       $ pip3.11 install -U polyswarm-api
       $ pip3.11 install -U pathlib
       $ pip3.11 install -U configparser

4. To check an Android mobile you need to install the "adb" tool:

       $ sudo apt get install adb

   PS: before trying Android's options, check:

       * If the adb tool is listed in the PATH environment variable.
       * If the system has authorized access to the device by using "adb devices -l"


## HELP

usage: python malwoverview.py -c <API configuration file> -d <directory> -o <0|1> -v <1-13>
-V <argument> -a <1-15> -w <0|1> -A <filename> -l <1-7> -L <hash> -j <1-7> 
-J <argument> -p <1-8> -P <argument> -y <1-5> -Y <file name> -n <1-5> 
-N <argument> -m <1-8> -M <argument> -b <1-10> -B <argument> -x <1-7> -X <argurment> -i <1-13> 
-I <argument> -vx <1-2> -VX <argument> -ip <1-3> -IP <argument> -O <directory> 

Malwoverview is a first response tool for threat hunting written by Alexandre Borges. 

> Options:

	-h, --help
	
		+ show this help message and exit

	-c CONFIG FILE, --config CONFIG FILE
	
		+ Use a custom config file to specify API's.

	-d DIRECTORY, --directory DIRECTORY
	
		+ Specifies the directory containing malware samples to be checked against VIRUS TOTAL.
		+ Use the option -D to decide whether you are being using a public VT API or a Premium 
		VT API.

	-o BACKGROUND, --background BACKGROUND
	
		+ Adapts the output colors to a light background color terminal. 
		+ The default is dark background color terminal.

	-v VIRUSTOTAL, --virustotal_option VIRUSTOTAL

		+ -v 1: given a file using -V option, it queries the VIRUS TOTAL database (API v.3)
			  to get the report for the given file through -V option.
		+ v 2: it shows an antivirus report for a given file using -V option (API v.3);
		+ v 3: equal to -v2, but the binary's IAT and EAT are also shown (API v.3); 
		+ v 4: it extracts the overlay; 
		+ v 5: submits an URL to VT scanning; 
		+ v 6: submits an IP address to Virus Total; 
		+ v 7: this options gets a report on the provided domain from Virus Total; 
		+ v 8: verifies a given hash against Virus Total; 
		+ v 9: submits a sample to VT (up to 32 MB). Use forward slash to specify the 
			   target file on Windows systems. Demands passing sample file with -V option; 
		+ -v 10: verifies hashes from a provided file through option -V. This option uses 
				public VT API v.3;
		+ -v 11: verifies hashes from a provided file through option -V. This option uses 
				Premium API v.3; 
		+ -v 12: it shows behaviour information of a sample given a hash through option -V. 
				This option uses VT API v.3; -v 13: it submits LARGE files (above 32 MB)
				to VT using API v.3;

	-V VIRUSTOTAL_ARG, --virustotal_arg VIRUSTOTAL_ARG
	
		+ Provides arguments for -v option.

	-a HYBRID_ANALYSIS, --hybrid_option HYBRID_ANALYSIS
	
		+ This parameter fetches reports from HYBRID ANALYSIS, download samples and submits
		samples to be analyzed. 
		+ The possible values are: 
			+ 1: gets a report for a given hash or sample from a Windows 7 32-bit environment; 
			+ 2: gets a report for a given hash or sample from a Windows 7 32-bit 
			environment (HWP Support); 
			+ 3: gets a report for given hash or sample from a Windows 64-bit environment; 
			+ 4: gets a report for a given hash or sample from an Android environment; 
			+ 5: gets a report for a given hash or sample from a Linux 64-bit environment; 
			+ 6: submits a sample to Windows 7 32-bit environment; 
			+ 7. submits a sample to Windows 7 32-bit environment with HWP support environment; 
			+ 8. submits a sample to Windows 7 64-bit environment;
			+ 9. submits a sample to an Android environment; 
			+ 10. submits a sample to a Linux 64-bit environment;
			+ 11. downloads a sample from a Windows 7 32-bit environment; 
			+ 12. downloads a sample from a Windows 7 32-bit HWP environment; 
			+ 13. downloads a sample from a Windows 7 64-bit environment; 
			+ 14. downloads a sample from an Android environment; 
			+ 15. downloads a sample from a Linux 64-bit environment.
			
	-A SUBMIT_HA, --ha_arg SUBMIT_HA
	
		+ Provides an argument for -a option from HYBRID ANALYSIS.

	-D VT_PUBLIC_PREMIUM, --vtpubpremium VT_PUBLIC_PREMIUM
	
		+ This option must be used with -d option. 
		+ Possible values: 
			+ <0> it uses the Premium VT API v3 (default); 
			+ <1> it uses the Public VT API v3.
			
	-l MALSHARE_HASHES, --malsharelist MALSHARE_HASHES
	
		+ This option performs download a sample and shows hashes of a specific type
		from the last 24 hours from MALSHARE repository. 
		+ Possible values are: 
			+ 1: Download a sample; 
			+ 2: PE32 (default) ; 
			+ 3: ELF ; 
			+ 4: Java; 
			+ 5: PDF ; 
			+ 6: Composite(OLE); 
			+ 7: List of hashes from past 24 hours.

	-L MALSHARE_HASH_SEARCH, --malshare_hash MALSHARE_HASH_SEARCH
	
		+ Provides a hash as argument for downloading a sample from MALSHARE repository.
		
	-j HAUS_OPTION, --haus_option HAUS_OPTION
	
		+ This option fetches information from URLHaus depending of the value passed as argument: 
			+ 1: performs download of the given sample; 
			+ 2: queries information about a 
			provided hash ; 
			+ 3: searches information about a given URL; 
			+ 4: searches a malicious URL by a given tag (case sensitive); 
			+ 5: searches for payloads given a tag; 
			+ 6: retrives a list of downloadable links to recent payloads; 
			+ 7: retrives a list of recent malicious URLs.

	-J HAUS_ARG, --haus_arg HAUS_ARG
	
		+ Provides argument to -j option from URLHaus.

	-p POLY_OPTION, --poly_option POLY_OPTION
	
		+ (Only for Linux) This option is related to POLYSWARM operations:
			+ 1. searches information related to a given hash provided using -P option; 
			+ 2. submits a sample provided by -P option to be analyzed by Polyswarm engine ; 
			+ 3. Downloads a sample from Polyswarm by providing the hash throught option -P.
			Attention: Polyswarm enforces a maximum of 20 samples per month; 
			+ 4. searches for similar samples given a sample file thought option -P;
			+ 5. searches for samples related to a provided IP address through option -P; 
			+ 6. searches for samples related to a given domain provided by option -P; 
			+ 7. searches for samples related to a provided URL throught option -P; 
			+ 8. searches for samples related to a provided malware family given by option -P.

	-P POLYSWARM_ARG, --poly_arg POLYSWARM_ARG
	
		+ (Only for Linux) Provides an argument for -p option from POLYSWARM.

	-y ANDROID_OPTION, --android_option ANDROID_OPTION
	
		+ This ANDROID option has multiple possible values: 
			+ <1>: Check all third-party APK packages from the USB-connected Android device 
			against Hybrid Analysis using multithreads. Notes: the Android device does not 
			need to be rooted and the system does need to have the adb tool in the PATH 
			environment variable; 
			+ <2>: Check all third-party APK packages from the USB-connected Android device
			against VirusTotal using Public API (slower because of 60 seconds delay for each 
			4 hashes). Notes: the Android device does not need to be rooted and the system 
			does need to have adb tool in the PATH environment variable; 
			+ <3>: Check all third-party APK packages from the USB-connected Android device 
			against VirusTotal using multithreads (only for Private Virus API). Notes: the 
			Android device does not need to be rooted and the system needs to have adb tool 
			in the PATH environment variable; 
			+ <4> Sends an third-party APK from your USB-connected Android device to 
			Hybrid Analysis; 
			+ 5. Sends an third-party APK from your USB-connected Android device to Virus-Total.

	-Y ANDROID_ARG, --android_arg ANDROID_ARG
	
		+ This option provides the argument for -y from ANDROID.

	-n ALIENVAULT, --alienvault ALIENVAULT
	
		+ Checks multiple information from ALIENVAULT. The possible values are: 
			+ 1: Get the subscribed pulses; 
			+ 2: Get information about an IP address; 
			+ 3: Get information about a domain; 
			+ 4: Get information about a hash; 
			+ 5: Get information about a URL.

	-N ALIENVAULT_ARGS, --alienvaultargs ALIENVAULT_ARGS
	
		+ Provides argument to ALIENVAULT -n option.

	-m MALPEDIA, --malpedia MALPEDIA
	
		+ This option is related to MALPEDIA and presents different meanings depending on 
		the chosen value. Thus:
			+ 1: List meta information for all families; 
			+ 2: List all actors ID; 
			+ 3: List all available payloads organized by family from Malpedia; 
			+ 4: Get meta information from an specific actor, so it is necessary to use 
			the -M option. Additionally, try to confirm the correct actor ID by executing
			malwoverview with option -m 3; 
			+ 5: List all families IDs; 
			+ 6: Get meta-information from an specific family, so it is necessary to 
			use the -M option. Additionally, try to confirm the correct family ID by 
			executing malwoverview with option -m 5; 
			+ 7: Get a malware sample from malpedia (zip format -- password: infected). 
			It is necessary to specify the requested hash by using -M option;
			+ 8: Get a zip file containing Yara rules for a specific family 
			(get the possible families using -m 5), which must be specified by using -M option.

	-M MALPEDIAARG, --malpediarg MALPEDIAARG
	
		+ This option provides an argument to the -m option, which is related to MALPEDIA.

	-b BAZAAR, --bazaar BAZAAR
	
		+ Checks multiple information from MALWARE BAZAAR and THREATFOX. The possible 
		values are: 
			+ 1: (Bazaar) Query information about a malware hash sample; 
			+ 2: (Bazaar) Get information and a list of malware samples associated 
			and according to a specific tag; 
			+ 3: (Bazaar) Get a list of malware samples according to a given imphash; 
			+ 4: (Bazaar) Query latest malware samples; 
			+ 5: (Bazaar) Download a malware sample from Malware Bazaar by providing a 
			SHA256 hash. The downloaded sample is zipped using the following 
			password: infected; 
			+ 6: (ThreatFox) Get current IOC dataset from last x days given by 
			option -B (maximum of 7 days); 
			+ 7: (ThreatFox) Search for the specified IOC on ThreatFox given by option -B; 
			+ 8: (ThreatFox) Search IOCs according to the specified tag given by option -B; 
			+ 9: (ThreatFox) Search IOCs according to the specified malware family provided by 
			option -B; 
			+ 10. (ThreatFox) List all available malware families.

	-B BAZAAR_ARG, --bazaararg BAZAAR_ARG
	
		+ Provides argument to -b MALWARE BAZAAR and THREAT FOX option:
			+ "-b 1" indicates that the -B's argument must be a hash and a report about 
			the sample will be retrieved; 
			+ "-b 2" indicates that -B's argument must be a malware tag and last samples 
			matching this tag will be shown; 
			+ "-b 3" means that the argument given by -M must be a imphash and last samples 
			matching this impshash will be shown; 
			+ "-b 4" means that the argument given by -M must be "100 or time", where "100" 
			lists last "100 samples" and "time" lists last samples added to Malware Bazaar 
			in the last 60 minutes; 
			+ "-b 5" means that the sample will be downloaded and -B's argument must be 
			a SHA256 hash of the sample that you want to download from Malware Bazaar; 
			+ "-b 6" indicates that a list of IOCs will be retrieved and the -B's value 
			is the number of DAYS to filter such IOCs. The maximum time is 7 (days); 
			+ "-b 7" indicates that the -B's argument is the IOC you want to search for; 
			+ "-b 8" indicates that the -B's argument is the IOC's TAG that you want 
			search for; 
			+ "-b 9" indicates that the -B argument is the malware family that you want 
			to search for IOCs;
			
	-x TRIAGE, --triage TRIAGE
	
		+ Provides information from TRIAGE according to the specified value: 
			+ 1: this option gets sample's general information by providing an 
			argument with -X option in the following possible formats: 
				- sha256:<value>
				- sha1:<value>
				- md5:<value>
				- family:<value>
				- score:<value>
				- tag:<value>
				- url:<value>
				- wallet:<value>
				- ip:<value>; 
				
			+ 2: Get a sumary report for a given Triage ID (got from option -x 1); 
			+ 3: Submit a sample for analysis; 
			+ 4: Submit a sample through a URL for analysis; 
			+ 5: Download sample specified by the Triage ID; 
			+ 6: Download pcapng file from sample associated to given Triage ID; 
			+ 7: Get a dynamic report for the given Triage ID (got from option -x 1);

	-X TRIAGE_ARG, --triagearg TRIAGE_ARG
	
		+ Provides argument for options especified by -x option. Pay attention: 
		the format of this argument depends on provided -x value.

	-i INQUEST, --inquest INQUEST
	
		+ Retrieves multiple information from INQUEST. The possible values are: 
			+ 1: Downloads a sample; 
			+ 2: Retrives information about a sample given a SHA256; 
			+ 3: Retrieves information about a sample given a MD5 hash; 
			+ 4: Gets the most recent list of threats. To this option, the -I 
			argument must be "list" (lowercase and without double quotes); 
			+ 5: Retrives threats related to a provided domain; 
			+ 6: Retrieves a list of samples related to the given IP address; 
			+ 7: Retrives a list of sample related to the given e-mail address; 
			+ 8: Retrieves a list of samples related to the given filename; 
			+ 9: Retrieves a list of samples related to a given URL; 
			+ 10: Retrieves information about a specified IOC; 
			+ 11: List a list of IOCs. Note: you must pass "list" (without 
			double quotes) as argument to -I;
			+ 12: Check for a given keyword in the reputation database; 
			+ 13: List artifacts in the reputation dabatabse. Note: you must 
			pass "list" (without double quotes) as argument to -I.

	-I INQUEST_ARG, --inquestarg INQUEST_ARG
	
		  + Provides argument to INQUEST -i option.

  -vx VXOPTION, --vx VXOPTION
   
      + 1: Gets basic metadata for a given SHA256 hash; 
      + 2: Downloads sample given a SHA256 provided in the -VX argument.

  -VX VXARG, --VX VXARG
      
      + Provides argument to the -vx option from VirusExchange.

  -O OUTPUTDIR, --output-dir OUTPUTDIR
      
      + Set output directory for all sample downloads.
  
  -ip IP, --ip IP

    + Get IP information from various sources. The possible values are: 
      + 1: Get details for an IP address provided with -IP from IPInfo; 
      + 2: Get details for an IP address provided with -IP from BGPView; 
      + 3: Get details for an IP address provided with -IP from all 
           available intel services (VirusTotal/Alienvault).
  
  -IP IPARG, --iparg IPARG
       
      + Provides argument for IP lookup operations specified by the -ip option.


## EXAMPLES

    malwoverview -d /home/remnux/malware/windows_2/
    malwoverview -v 1 -V 95a8370c36d81ea596d83892115ce6b90717396c8f657b17696c7eeb2dba1d2e.exe
    malwoverview -v 2 -V 95a8370c36d81ea596d83892115ce6b90717396c8f657b17696c7eeb2dba1d2e.exe
    malwoverview -v 3 -V 95a8370c36d81ea596d83892115ce6b90717396c8f657b17696c7eeb2dba1d2e.exe
    malwoverview -v 4 -V 95a8370c36d81ea596d83892115ce6b90717396c8f657b17696c7eeb2dba1d2e.exe,
    malwoverview -v 5 -V http://jamogames.com/templates/JLHk/
    malwoverview -v 6 -V 185.220.100.243
    malwoverview -v 7 -V xurl.es
    malwoverview -v 8 -V ab4d6a82cafc92825a0b88183325855f0c44920da970b42c949d5d5ffdcc0585
    malwoverview -v 9 -V cc2d791b16063a302e1ebd35c0e84e6cf6519e90bb710c958ac4e4ddceca68f7.exe
    malwoverview -v 10 -V /home/remnux/malware/hash_list_3.txt
    malwoverview -v 11 -V /home/remnux/malware/hash_list_3.txt
    malwoverview -v 12 -V 9d26e19b8fc5819b634397d48183637bacc9e1c62d8b1856b8116141cb8b4000
    malwoverview -v 13 -V /largefiles/4b3b46558cffe1c0b651f09c719af2779af3e4e0e43da060468467d8df445e93
    malwoverview -a 1 -A 2e1fcadbac81296946930fe3ba580fd0b1aca11bc8ffd7cefa19dea131274ae8
    malwoverview -a 1 -A 2e1fcadbac81296946930fe3ba580fd0b1aca11bc8ffd7cefa19dea131274ae8.exe
    malwoverview -a 2 -A 2e1fcadbac81296946930fe3ba580fd0b1aca11bc8ffd7cefa19dea131274ae8
    malwoverview -a 3 -A 2e1fcadbac81296946930fe3ba580fd0b1aca11bc8ffd7cefa19dea131274ae8
    malwoverview -a 4 -A malware1.apk
    malwoverview -a 4 -A 82eb6039cdda6598dc23084768e18495d5ebf3bc3137990280bc0d9351a483eb
    malwoverview -a 5 -A 2b03806939d1171f063ba8d14c3b10622edb5732e4f78dc4fe3eac98b56e5d46
    malwoverview -a 5 -A 2b03806939d1171f063ba8d14c3b10622edb5732e4f78dc4fe3eac98b56e5d46.elf
    malwoverview -a 6 -A 47eccaaa672667a9cea23e24fd702f7b3a45cbf8585403586be474585fd80243.exe
    malwoverview -a 7 -A 47eccaaa672667a9cea23e24fd702f7b3a45cbf8585403586be474585fd80243.exe
    malwoverview -a 8 -A 47eccaaa672667a9cea23e24fd702f7b3a45cbf8585403586be474585fd80243.exe
    malwoverview -a 9 -A malware_7.apk
    malwoverview -a 10 -A 925f649617743f0640bdfff4b6b664b9e12761b0e24bbb99ca72740545087ad2.elf
    malwoverview -a 11 -A cd856b20a5e67a105b220be56c361b21aff65cac00ed666862b6f96dd190775e
    malwoverview -a 12 -A cd856b20a5e67a105b220be56c361b21aff65cac00ed666862b6f96dd190775e
    malwoverview -a 13 -A cd856b20a5e67a105b220be56c361b21aff65cac00ed666862b6f96dd190775e
    malwoverview -a 14 -A d90a5552fd4ef88a8b621dd3642e3be8e52115a67e6b17b13bdff461d81cf5a8
    malwoverview -a 15 -A 925f649617743f0640bdfff4b6b664b9e12761b0e24bbb99ca72740545087ad2
    malwoverview -l 1 -L d3dcc08c9b955cd3f68c198e11d5788869d1b159dc8014d6eaa39e6c258123b0
    malwoverview -l 2
    malwoverview -l 3
    malwoverview -l 4
    malwoverview -l 5
    malwoverview -l 6
    malwoverview -j 1 -J 7c99d644cf39c14208df6d139313eaf95123d569a9206939df996cfded6924a6
    malwoverview -j 2 -J 7c99d644cf39c14208df6d139313eaf95123d569a9206939df996cfded6924a6
    malwoverview -j 3 -J https://unada.us/acme-challenge/3NXwcYNCa/
    malwoverview -j 4 -J Qakbot
    malwoverview -j 5 -J Emotet
    malwoverview -j 5 -J Icedid
    malwoverview -j 6
    malwoverview -j 7
    malwoverview -p 1 -P 1999ba265cd51c94e8ae3a6038b3775bf9a49d6fe57d75dbf1726921af8a7ab2
    malwoverview -p 2 -P 301524c3f959d2d6db9dffdf267ab16a706d3286c0b912f7dda5eb42b6d89996.exe
    malwoverview -p 3 -P 68c11ef39769674123066bcd52e1d687502eb6c4c0788b4f682e8d31c15e5306
    malwoverview -p 4 -P 68c11ef39769674123066bcd52e1d687502eb6c4c0788b4f682e8d31c15e5306.exe
    malwoverview -p 5 -P 188.40.75.132
    malwoverview -p 6 -P covid19tracer.ca
    malwoverview -p 7 -P http://ksahosting.net/wp-includes/utf8.php
    malwoverview -p 8 -P Qakbot
    malwoverview -y 1
    malwoverview -y 2
    malwoverview -y 3
    malwoverview -y 4 -Y com.spaceship.netprotect
    malwoverview -y 5 -Y com.mwr.dz
    malwoverview -v 1 -V 368afeda7af69f329e896dc86e9e4187a59d2007e0e4b47af30a1c117da0d792.apk
    malwoverview -n 1 -N 10
    malwoverview -n 2 -N 176.57.215.100
    malwoverview -n 3 -N threesmallhills.com
    malwoverview -n 4 -N 6d1756aa6b45244764409398305c460368d64ff9 -o 0
    malwoverview -n 5 -N http://ksahosting.net/wp-includes/utf8.php
    malwoverview -m 1 | more
    malwoverview -m 2 | more
    malwoverview -m 3 | more 
    malwoverview -m 4 -M apt41 | more
    malwoverview -m 5 | more 
    malwoverview -m 6 -M win.qakbot
    malwoverview -m 7 -M 3d375d0ead2b63168de86ca2649360d9dcff75b3e0ffa2cf1e50816ec92b3b7d 
    malwoverview -m 8 -M win.qakbot
    malwoverview -b 1 -B c9d7b5d06cd8ab1a01bf0c5bf41ef2a388e41b4c66b1728494f86ed255a95d48
    malwoverview -b 2 -B Revil | more
    malwoverview -b 3 -B f34d5f2d4577ed6d9ceec516c1f5a744
    malwoverview -b 4 -B 100 
    malwoverview -b 4 -B time | more
    malwoverview -b 5 -B bda50ff249b947617d9551c717e78131ed32bf77db9dc5b7591d3e1af6cb2f1a
    malwoverview -b 6 -B 3 | more
    malwoverview -b 7 -B 193.150.103.37:21330
    malwoverview -b 8 -B Magecart | more
    malwoverview -b 9 -B "Cobalt Strike"
    malwoverview -b 10 | more
    malwoverview -x 1 -X score:10 | more
    malwoverview -x 1 -X 71382e72d8fb3728dc8941798ab1c180493fa978fd7eadc1ab6d21dae0d603e2
    malwoverview -x 2 -X 220315-qxzrfsadfl
    malwoverview -x 3 -X cd856b20a5e67a105b220be56c361b21aff65cac00ed666862b6f96dd190775e
    malwoverview -x 4 -X http://ztechinternational.com/Img/XSD.exe
    malwoverview -x 5 -X 220315-xmbp7sdbel
    malwoverview -x 6 -X 220315-xmbp7sdbel
    malwoverview -x 7 -X 220315-xmbp7sdbel
    malwoverview -i 1 -I 5119c804448dd877e1a32d5157dc2e5ff9344cb55e053b20117c9b3b4c974389 
    malwoverview -i 2 -I 5119c804448dd877e1a32d5157dc2e5ff9344cb55e053b20117c9b3b4c974389
    malwoverview -i 3 -I 0a1b0c7a21c8929b7742db195338af5c
    malwoverview -i 4 -I list
    malwoverview -i 5 -I rebrand.ly | more
    malwoverview -i 6 -I 10.247.111.124 
    malwoverview -i 7 -I diseno@distracom.com 
    malwoverview -i 8 -I 20firmas-02.jpg
    malwoverview -i 9 -I http://diagnostic.htb 
    malwoverview -i 10 -I http://jaao.net 
    malwoverview -i 11 -I list
    malwoverview -i 12 -I rebrand.ly
    malwoverview -i 13 -I list | more
    malwoverview -vx 1 -VX c3247ada71931ee267e975cb04160dc8ac611f3b4409f41b595177e124be7c2e
    malwoverview -vx 2 -VX c3247ada71931ee267e975cb04160dc8ac611f3b4409f41b595177e124be7c2e
    malwoverview -ip 1 -IP 8.8.8.8
    malwoverview -ip 2 -IP 8.8.8.8
    malwoverview -ip 3 -IP 8.8.8.8
    malwoverview -vx 2 -VX <hash> -O <directory>
    malwoverview -b 5 -B <hash> -O <directory> 


## HISTORY


Version 6.2:

      This version:

            * Modifies Malware Bazaar option to use Auth-Key.
            * Modifies Threat Fox option to use Auth-Key.

Version 6.1.1:

      This version:

            * Modifies the code to not require to registers all APIs at the first usage.
            * Add a new section in the README (this file) about required APIs.

Version 6.1.0:

      This version:

            * Introduces -vx option for Virus Exchange.
            * Introduces -ip option for IPInfo and BGPView.
            * Introduces -O option to save samples in a central directory. 
            * Fixes multiple other issues.

Version 6.0.1:

      This version:

            * Issue in Malshare's download option has been fixed.

Version 6.0.0:

      This version:

            * It has been completely refactored.
	    * README.md has been also changed.
            * Special thanks to Artur Marzano, who has contributed
              and dedicated his time to conduct and write this new version.

Version 5.4.5:

      This version:

	    * Includes a fix related to the installation path. 

Version 5.4.4:

      This version:

	    * Includes only small changes and updates in the README.md.

Version 5.4.3:

      This version:

	    * Fixes a recent issue on -v 10 and 11 options (VT) due to 
	      a change in one of the used libraries. 
	    * Fixes other minor issues on several options.

Version 5.4.2:

      This version:

            * Fixes two small issues.

Version 5.4.1:

      This version:

            * Fixes issues related to URLHaus.
            * Fixes issues related to Polyswarm.
            * Fixes issues related to Malware Bazaar.
            * Fixes issues related to InQuest.
            * Introduces changes to the help description. 
            * Introduces changes to installation process. 

Version 5.3:

      This version:

            * Fixes issues related to Malshare (-l and -L options).
            * Adds a new Malshare option (-l 7) to list all samples 
              from last 24 hours.

Version 5.2:

      This version:

            * Multiple issues related to Hybrid Analysis have been fixed.

Version 5.1.1:

      This version:

            * A formatting issue related to -v 10 option has been fixed.

Version 5.1:

      This version:

            * Introduces thirteen options related to InQuest Labs.
            * Fix an issue related to -b 6 option from ThreatFox.

Version 5.0.3:

      This version:

            * Includes the possibility of getting information from 
              Hybrid-Analysis using a SHA256 hash or the malware file.
            * Removes all options related to ThreatCrowd.
            * Fix an issue related to downloading from Malshare.
            * Includes macOS as operating system supported to run Malwoverview.

Version 5.0.2:

      This version:

            * Includes a small fix for options -v 1 and -v 8. 

Version 5.0.0:

      This version:

            * Includes upgrades of all Virus Total options from API v.2 
              to API v.3.
            * Introduces a new option to check hashes within a given
              file using Virus Total.
            * Introduces a new option to submit large files (>= 32 MB) to
              Virus Total.
            * Changes all Virus Total options.
            * Inverts Malpedia options ("m" and "M") purposes.
            * Introduces a new purpose for -D option.
            * Removes Malshare option to check a binary.
            * Removes all Valhalla options completely.
            * Changes all Malshare options.
            * Removes -g option.
            * Changes all URLhaus options.
            * Changes all Polyswarm options.
            * Removes -S and -z options.
            * Upgrades, fixes and merges Android options.
            * Updates Android options to Android 11 version.
            * Removes -t and T options.
            * Fixes and changes Hybrid Analysis options.
            * Changes -d option to Virus Total APIi v.3 with a new content.
            * Swaps options -q and -Q from Threatcrowd.
            * Fixes tag option from Triage.
            * Fixes URL formatting issues from URLhaus.
            * Removes several support functions.
            * Fixes several color issues.
            * Fixes descriptions.
            * Changes configuration, setup and requirement files.
            * Removes many option's letters used in previous versions.

Version 4.4.2:

      This version:

            * It is NOT longer necessary to insert all APIs into .malwapi.conf file 
              before using Malwoverview. For example, if you have only Virus Total
              and Hybrid Analysis APIs, so you can use their respective options 
              without needing insert the remaining ones. The same rule is valid 
              for any API and option. 

            * Small fixes have been done on the code and this README file. 

Version 4.4.1:

      This version:

            * Improves and fixes a formatting issue with cmd field 
              from option -x 2.

Version 4.4.0.2:

      This version:

            * Improves and fixes a formatting issue with cmd field 
              from option -x 7.

Version 4.4:

      This version:

            * Introduces Triage endpoint and seven associated options. 
            * Changes the overlay extraction option (previously -x) 
              to -v 4. 

Version 4.3.5:

      This version:

            * Fixes formating issues related to option -M 6 from Malpedia. 
            * Fixes formating issues related to option -W from URLHaus. 
            * Fixes formating issues related to option -k from URLHaus. 
            * Fixes working issues related to option -L from Malshare. 
            * Corrects misspelled words.

Version 4.3.4:

      This version:

            * Removes two columns from option -y 1 (Android package checking on HA) 
              to offer better formatting. 

Version 4.3.3:

      This version:

            * Fixes output formatting of option -y (Android package checking on VT and HA) 
            * Fixes issue with option -y while using -o 0. 


Version 4.3.2:

      This version:

            * Fixes output formatting of option -n 2 (Alien Vault).
            * Fixes URL output formatting of long URL when using option -I (Virus Total). 
            * Fixes option -f when using a binary without IAT (Virus Total). 
            * Fixes option -B 10, which caused a endless loop (ThreatFox). 
            * Fixes option formatting issue related to -K 2 when fetched URLs were long
              (URLHaus). 
            * Introduces "FireEye" endpoint in -v 2 output (VirusTotal). This
              addition has been suggested by @vxsh4d0w.

Version 4.3.1:

      This version:

            * Introduces a fix in the "-b 8" ThreatFox option.
            * Corrects sentences in the help's section.

Version 4.3:

      This version:

            * Introduces Malware Bazaar and ThreatFox endpoints, with 5 options for each one.
              to get the APIs.
            * Changes background option from -b to -o.
            * Fixes problems on Malpedia and URLHaus options.

Version 4.2:

      This version:

            * Fixes -L option from Malware.
            * Introduces additional instruction on README.md (this file) to help professionals
              to get the APIs.

Version 4.1:

      This version:

            * Introduces the -E and -C options for Valhalla service 
              (https://www.nextron-systems.com/valhalla/) 
            * Introduces few changes in the setup.py file (contribution from Christian 
              Clauss). 
            * Introduces a new contributor: Christian Clauss (https://github.com/cclauss) 

Version 4.0.3:

      This version:

            * Fixes the fact of Virus Total evaluation wasn't showed when the user specified "-v 2" and 
              "-v 3" options.
            * The version of the Python request package is fixed to prevent issues with Polyswarm API 2.x.

Version 4.0.2:

      This version:

            * Two small bugs (typos) in the functions for Polyswarm downloading and Android package checking
              have been fixed. 
            * An unnecessary and dead code has been removed.
            * Several typos in the README.md and in the help have been corrected. 
            * All fixes for this version have been suggested by Christian Clauss (https://github.com/cclauss)


Version 4.0.1:

      This version:

            * Fixes small typos and the README. 


Version 4.0.0:

      This version:

            * Introduces new engines such as Alien Vault, Malpedia and ThreatCrowd. 
            * The -s option has been removed. Use -v 2 option for antivirus report.
            * The -n option is not longer associated to Malshare. Use -l option with 
              values between 1 and 14.
            * To specify the hash in Malshare use the L option instead of -m option. 
            * The -i option has been removed. Use the -v 3 option for IAT/EAT. 
            * The -a option has been changed to include the system environments in Hybrid 
              Analysis. However, the -e option has been kept to be used with other options. 
            * The -M option is not longer responsible for downloading samples in Malshare. Use
              -D option for this task. 
            * The -B option for list URLs from URLHaus has been replaced by -K 2 option. 
            * The -Z and -X options (related to Android) have been replaced for -y 2 and -y 3, 
              respectively. 
            * The -D option (download a malware sample) has been extended to Polyswarm. 
            * The malware sample's DLL list has been introduced. 
            * The -R and -G options from Polyswarm have been completely fixed. Additionally, both
              ones also include the polyscore in the output. 
            * The -N option is not longer associated to Polyswarm . 
            * The -G 4 option has been introduced and it makes possible to search samples by 
              families and types such as "*Trickbot*", "*Ransomware", "*Trojan*" and so on. 
            * Colors from -I option have been fixed. 
            * The -w option has been removed. 
            * Several issues in the help have been fixed. 


Version 3.1.2:

      This version:

            * Introduces the -c option that allows the user to specify a custom API configuration file. 
            * The API configuration file has been changed to .malwapi.conf file.
            * The project structure has been changed to make easier to install it in different operating 
              systems.
            * Updates for this version are a contribution from Corey Forman (https://github.com/digitalsleuth).

Version 3.0.0:

      This version:

            * Includes fixes in the URL reporting (-u option) from Virus Total.  
            * New players have have been included in the URL reporting (-u option) from Virus Total.
            * Fixes have been included in payload listing (-K option) from URLhaus.
            * Yara information has been include in the hash report (-m option) from Malshare.
            * Fixes have been included in the -l option. 
            * New file types have been included in the -n option: Java, Zip, data, RAR, PDF, Composite (OLE),
              MS_DOS and UTF-8.
            * New -W option, which is used to show URLs related to an user provided tags from URLHaus.
            * New -k option, which is used to show payloads related to a tag from URLHaus
            * New -I option, which is used to show information related to an IP address from Virus Total.
            * The -R option was refactored and now it supports searching for file, IPv4, domain or URL on 
              Polyswarm. 

Version 2.5.0:

      This version:

            * Introduces the following options:
                  * -y to check all third-party APKs from an Android device against 
                       the Hybrid Analysis. 
                  * -Y to send a third-party APKs from an Android device to the Hybrid
                       Analysis. 
                  * -Z to check all third-party APKs from an Android device against 
                       the Virus Total. 
                  * -X to check all third-party APKs from an Android device against the
                       Virus Total (it is necessary private API). 
                  * -T to send a third-party APK from an Android device to Virus Total. 
            * Fixes several issues related to color in command outputs.  
            * Adds the filename identification in the report while sending a sample to Virus Total.

Version 2.1.9.1:

      This version:

            * Fixes several issues about colors in outputs. 
            * Removes the -L option from Malshare (unfortunately, Malshare doesn't provide an 
              URL list anymore). 
            * Removes the -c option.
            * Introduces some verification lines in the URLHaus command. 

Version 2.1:

      This version:

            * Fixes formatting issues related to Hybrid Analysis output (-Q 1 -a 1). 
            * Fixes color issues. 
            * Fixes small issues related to Polyswarm. 

Version 2.0.8.1:

      This version:

            * Introduces installation using: pip3.8 install malwoverview (Linux) or 
              python -m pip install malwoverviewwin (Windows). 
            * Fixes small problems related to Polyswarm usage. 
            * Changes the help to verify whether the APIs were inserted into configmalw.py file. 

Version 2.0.1:

      This version:

            * Fixes a problem related to searching by hash on Malshare (-m option). 
            * Fixes a problem related to searching by hash on Polyswarm (-O option). 

Version 2.0.0:

      This version:

            * Introduces a completely ported version of Malwoverview to Python 3.x (it does not work in 
              Python 2.7.x anymore!)
            * Fixes several bugs related to IAT/EAT listing. 
            * Fixes several bugs related to colors. 
            * Introduces multi-threading to some options. 
            * Introduces several options related to Malshare. 
            * Introduces several options related to URLHaus.
            * Introduces several options related to Polyswarm engine. 
            * Changes the place of the API key configuration. Now you should edit the configmalw.py file. 
            * Changes the help libraries and functions, so making the Malwoverview's help more complete. 
            * Introduces geolocation feature by using the package named Geocoder written by Dennis Carrierre.
            * Fixes problems related to Hybrid Analysis engine. 
            * Fixes several mistaked related to a mix between spaces and Tab.
            * Extends the -d option to include Hybrid Analysis. 
            
Version 1.7.5:

      This version: 

            * It has been fixed a problem related to sample submission to Hybrid Analysis on Windows operating 
              system. Additionally, file name handling has been also fixed. 
            
Version 1.7.3:

      This version: 

            * Malwoverview has been adapted to API version 2.6.0 of Hybrid Analysis.
            * -A option has been fixed according to new version (2.6.0) of Hybrid Analysis.
            * -a option has been modified to work together with  -e option.
            * help information has been modified. 
            
Version 1.7.2:

      This version: 

            * A small fix related to -g option has been included. 
            
Version 1.7.1:

      This version: 

            * Relevant fix of a problem related to options -A and -H options.
            * Includes a new Hybrid Analysis environment to the -e option (Windows 7 32-bits with HWP support).
            * Updates the Malwoverview to support Hybrid Analysis API version 2.5.0.

Version 1.7.0:

      This version: 

            * Includes -A option for submitting a sample to Hybrid Analysis.
            * Includes -g option for checking the status a submission of a sample to Hybrid Analysis.
            * Includes -e option for specifying the testing environment on the Hybrid Analysis.
            * Includes -r option for getting a complete domain report from Virus Total.
            * Modifies the -H options for working together the -e option.
            * Modifies several functions of the tool to prepare it for version 1.8.0

Version 1.6.3:

      This version: 

            * Includes creation of new functions aiming 1.7.0 version.
            * Includes new exception handling blocks.

Version 1.6.2:

      This version: 

            * Includes small fixes.
            * For the Hybrid Analysis API version 2.40 is not longer necessary to include the API Secret.  

Version 1.6.1:

      This version: 

            * Includes small format fixes.

Version 1.6.0:

      This version: 

            * It is using the Hybrid Analysis API version 2.4.0.
            * Includes certificate information in the Hybrid Analysis report. 
            * Includes MITRE information in the Hybrid Analysis report. 
            * Includes an option to download samples from Hybrid Analysis. 

Version 1.5.1:

      This version: 

            * Small change to fix format issue in -d option. 

Version 1.5.0:

      This version: 

            * Includes the -u option to check URLs against Virus Total and associated engines. 
            * Includes the -H option to find existing reports on Virus Total and Hybrid Analysis through the 
              hash.
            * Includes the -V option to submit a file to Virus Total. Additionally, the report is shown after 
              few minutes.
            * Includes two small fixes. 

Version 1.4.5.2:

      This version:

            * Includes two small fixes.

Version 1.4.5.1:

      This version:

            * Includes one small fix. 

Version 1.4.5:

      This version:

            * Adds the -w option to use malwoverview in Windows systems.
            * Improves and fixes colors when using -b option with black window.  

Version 1.4: 

      This version:

            * Adds the -a option for getting the Hybrid Analysis summary report.
            * Adds the -i option for listing imported and exported functions. Therefore, imported/exported
              function report was decoupled for a separated option.  

Version 1.3: 

      This version:

            * Adds the -p option for public Virus Total API.

Version 1.2: 

      This version includes:

            * evaluates a single file (any filetype)
            * shows PE sessions.
            * shows imported functions.
            * shows exported function.
            * extracts overlay.
            * shows AV report from the main players. (any filetype)

Version 1.1: 

      This version:

            * Adds the VT checking feature.


Version 1.0:

      Malwoverview is a tool to perform a first triage of malware samples in a directory and group them 
      according to their import functions (imphash) using colors. This version:

            * Shows the imphash information classified by color. 
            * Checks whether malware samples are packed.  
            * Checks whether malware samples have overlay. 
            * Shows the entropy of the malware samples. 


