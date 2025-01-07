# Common-Forensic-tools
Forensic tools are important in helping a digital investigator properly handle a case from the point of collection, to transfer, to analysis, to documentation, and to court presentation. These forensic tools help to automate the process of identifying a crime as well as justifying that the crime was not only committed but how it was committed.
 
# Five Common Forensic Tools and Their Primary Functions
# 1)	EnCase
a.	Primary Function: This a digital forensics tool used for the acquisition, analysis, and reporting of digital evidence. It allows investigators to collect evidence from various devices, including hard drives, mobile devices, and removable media.
b.	 Features:
     i.	Disk imaging to create a forensic copy of the data.
    ii.	File recovery (including deleted or hidden files).
    iii.	Detailed analysis of file metadata, email, internet history, and more.
    iv.	Report generation for presenting findings in court.
# 2)	FTK (Forensic Toolkit)
a.	Primary Function: FTK is a comprehensive digital investigation platform that assists in scanning and analyzing hard drives for potential evidence.
b.	Features:
    i.	Data carving to recover deleted files or fragments.
    ii.	Indexing for fast keyword searches across large datasets.
   iii.	Encryption detection and decryption capabilities.
   iv.	Email analysis and visualization of internet activity.
  	
# 4)	Wireshark
  a.	Primary Function: Wireshark is a network protocol analyzer used to capture and examine live network traffic or analyze previously captured traffic (PCAP files). Its terminal tool is called Tshark
  b.	Features:
  i.	Captures and analyzes network packets.
  ii.	Detects suspicious traffic, such as unauthorized access or malware communication.
  iii.	Examines protocols like HTTP, FTP, DNS, and more for signs of intrusion or data exfiltration.
iv.	Helpful in network-based investigations, such as identifying data breaches or hacking attempts.

# 5)	Volatility
a.	Primary Function: Volatility is an open-source memory forensics tool that focuses on analyzing the volatile memory (RAM) of systems.
b.	Features:
i.	Analyzes memory dumps to detect malware, rootkits, and suspicious processes.
ii.	Recovers artifacts like passwords, browser history, and network connections from memory.
iii.	Helps in investigating advanced persistent threats (APTs) or malware that operates in memory rather than on disk.

# 6)	Autopsy
a.	Primary Function: Autopsy is a free and open-source digital forensics tool used for analyzing disk images and recovering evidence.
b.	Features:
   i.	File system analysis, including recovery of deleted files.
    ii.	Timeline creation to track user activity across devices.
      iii.	Built-in modules for analyzing web activity, email, and multimedia files.
          iv.	Integration with other tools like The Sleuth Kit for more advanced forensic analysis.

          
# Importance of Selecting Appropriate Tools Based on the Type of Digital Evidence
The importance of selecting appropriate tools is outlined below:
1)	The Type of Device:
a)	Some tools are better suited for specific types of devices (e.g., mobile forensics tools like Cellebrite for phones or XRY for tablets). If you are working with a windows or linux operating system, other specialized tool can be used. 
b)	If the evidence involves network traffic, a tool like Wireshark is more appropriate. For file system analysis or recovering deleted files, a tool like EnCase or Autopsy would be more suitable.
2)	The Forensic Soundness:
a)	The chosen tool must maintain the integrity of the evidence and create an unaltered copy for analysis (e.g., disk imaging tools like FTK Imager or EnCase Imager). Tools must be tested and validated to avoid claims of evidence tampering or modification.
3)	The Efficiency and Scope:
a)	Some tools, like FTK and EnCase, offer comprehensive solutions for many forensic tasks, while others, like Volatility, are more specialized. For an extensive case that involves multiple types of data (e.g., emails, network activity, and disk images), a comprehensive suite like FTK may be required to cover all areas effectively.
4)	Its Court Admissibility:
a)	In legal cases, it is crucial that the selected forensic tools meet industry standards and are widely accepted in the forensic community. Tools like EnCase and FTK have built-in reporting features that create court-admissible documents.
