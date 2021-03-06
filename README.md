Seccubus V2 Read Me
===================
Seccubus automates regular vulnerability scans with vrious tools and aids 
security people in the fast analysis of its output, both on the first scan and 
on repeated scans.

On repeated scan delta reporting ensures that findings only need to be judged 
when they first appear in the scan results or when their output changes.

Seccubus 2.x is the only actively developed and maintained branch and all support 
for Seccubus V1 has officially been dropped. 

Seccubus V2 works with the following scanners:
* Nessus 4.x and 5.x (professional and home feed)
* Skipfish
* OpenVAS
* Medusa (local and remote)
* Nikto (local and remote)
* NMap (local and remote)
* SSLyze

For more information visit [www.seccubus.com]

18-08-2014 - 2.9 - Qualys SSLlabs integration
=============================================
Seccubus can now fetch the results of www.ssllabs.com automatic scanner and monitor for deltas

Bug Fixes
============================================
* #122 - SSLlabs integration
* #120 - SELinux problem on RHEL6
* #99 - The ability to remote is not reflected in the scanner help text
* #67 - -o usage needs to be more specific for e.g. nikto and nmap scanner 
* #63 - Scan table does not display scanner correctly
* #59 - Explanation of $ATTACH: in notifications is not very clear
