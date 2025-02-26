# Stretchoid
## Maintained list of Stretchoid scanner IPs
### Background
Stretchoid recently moved their scanner infrastructure to Microsoft Azure, obsoleting all of the Stretchoid IP lists currently in circulation.  This list is updated frequently with the latest available IPs used by Stretchoid scanners.
### Instructions
Point your security product/firewall to the following URL as an external threat feed/IP list:
```https://raw.githubusercontent.com/Xorlent/Stretchoid/main/stretchoid.txt```  
If your appliance or program does not correctly interpret Windows CR/LF, you can post-process the list with (thanks @jlongua):
```sed -i "s/\r//g" stretchoid.txt```
### Support
If you believe there are missing IP entries, please open a Github issue with all suspected IP addresses so we can improve this list.  Thank you!
