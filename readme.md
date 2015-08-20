#NOTE
Git LFS is required to upload the tool; request has been made and the file will be uploaded soon!


##Web History Extraction Artefact Tool
###A GNU/Linux USB triage tool for initial forensic investigations.

To install the tool to a memory stick run the command:
> **gunzip -c wheat-0.9.dd.tar.gz | dd of=/dev/sdX**

*Recommended memory stick size: 4GB*

MD5 Checksum: 20c5a3c504e1462daff2b0fcc16ec1ad

SHA1 Checksum: 4d385f3ec61d0a195c130fe1d0f5aa82b055f471


**wheat-demo.webm** is a quick video demonstrating the results of the tool which was used for the Leeds Beckett Computing Showcase and Leeds Ethical Hacking Society presentations I gave.
*It does not go into all features or any acquisition processes as I had strict time constraints while presenting.*


###Notes
* The tool has been tested and works in a forensically sound manner; some functionality is not fully completed.
* I have not yet tested the 32-bit kernel functionality due to lack of access to a 32-bit machine.
* Development is ongoing during my spare time; I will update this file with my intended future development in the near future as well.
* It is intended that the tool will use a squashfs file system to allow an iso for both CD and easy USB installation; however the initial attempts were unsuccessful and abandoned due to time constraints.
* I have uploaded both a unit testing report and a technical document which details the functionality of the main scripts and processes.
* I am currently writing a user guide however the tool is fairly easy to comprehend.
* To switch between acquisition and evidence viewing use CTL+ALT+RIGHT or move the mouse to the bottom right corner and click on the arrow.
* Design and development was undertaken with input from West Yorkshire Police Hi-Tec Crime Unit to produce a tool which can be used both by technical forensic technicians and non-technical police officers alike.

**Any input is welcome.**
