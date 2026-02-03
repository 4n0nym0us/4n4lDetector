<html>
<head>
    <header class="header">
    <img src="https://github.com/4n0nym0us/4n4lDetector/assets/76454196/4eb8924e-ad49-4896-aa16-d72ee48e849a"</img>
    </head>
<h1>Advanced Static Analysis Tool</h1>
<body>
4n4lDetector is a powerful static analysis tool focused on Microsoft Windows executables, libraries, drivers, and memory dumps, while its integrated modules can analyze virtually any file type with reliable performance and accurate detection.<br>

It performs deep inspection of Portable Executable (PE) structures, sections, headers, and resources to identify anomalies, obfuscation layers, and embedded malicious components. Beyond standard PE analysis, its specialized modules extract and classify strings, metadata, and embedded code from non-PE files, extending its scope to a wide range of binary formats.<br>

One of its most distinctive features is the <b>Flow Anomalies module</b>, which identifies unusual patterns in the program’s control flow without executing the sample, such as irregular jumps, embedded junk code, and execution redirection behaviors commonly used in obfuscated or evasive malware. By combining heuristic and signature-based analysis, 4n4lDetector can uncover subtle structural inconsistencies invisible to traditional scanners.<br>

Designed with efficiency, precision, and depth in mind, <b>4n4lDetector</b> began its development in 2015 while I was working at Panda Antivirus, originally conceived as a personal tool to assist in my daily malware analysis tasks. Since then, it has been solely developed and continuously refined by myself, evolving into a robust and reliable framework for malware research, reverse engineering, and forensic investigation.<br>

Using the tool is simple: configure the options in the right-side panel and drag your samples directly into 4n4lDetector.<br>

For more information about my professional background and projects, visit my LinkedIn profile: <a href="https://www.linkedin.com/in/enelpc/" target="_blank">https://www.linkedin.com/in/enelpc/
</a>.<br>
</body>
    <h2>Pescan.io (Web Scanner)</h2>
        <p>
        Explore, analyze, and uncover malware effortlessly with our online scanner. Built upon the powerful <b>4n4lDetector</b> engine, this enhanced version delivers advanced capabilities, improved performance, and superior extraction of Indicators of Compromise (IOCs) to strengthen malware detection and analysis.  
        <br>
        Developed with a focus on precision and scalability, PEScan Online brings the proven static analysis technology of 4n4lDetector to the web enabling secure, in-depth examination of suspicious files directly from your browser.
        </p>
        <a class="github-link" href="https://pescan.io" target="_blank">PESCAN.IO</a>

<h2>Full support:</h2>
  - 32 bits (8086, x86, ARMv7)<br>
  - 64 bits (AMD64, x86-64, x64, ARMv8)<br>

<h2>IT and ET Extraction:</h2>
Alpha AXP, ARM, ARM Thumb-2 (32-bit Thumb), ARM64, EFI Byte Code, EFI Byte Code (EBC), Hitachi SH3, Hitachi SH3, Hitachi SH4, Hitachi SH5, Intel i860, Intel Itanium (IA-64), M32R, MIPS16, MIPS16 with FPU, MIPS R3000, MIPS R4000, MIPS with FPU, MIPS little-endian, MIPS little-endian WCE v2, x64, x86, x86-64.<br>

<h2>Buttons code:</h2>
  <span style="color: green;">- Buttons colored green are action buttons that open files and folders or are used to interact with the tool's utilities.</span><br>
  <span style="color: red;">- The buttons colored in red perform reconfigurations, deletion of data or reset of functional files.</span><br>
  <span style="color: purple;">- Purple buttons announce the activation of online interactions.</span><br>
  <span style="color: pink;">- The pink buttons are shortcut buttons that the tool uses as tabs to navigate between different types of utilities.</span><br>

<h2>PE chart code:</h2>
  - The executable header is displayed in light blue.<br>
  - The executable sections are pink.<br>
  - Non-executable sections are black.<br>
  - Code added to executables externally to a compiler appears in red. (Crypters, Joiners, Droppers...)<br>

<h2>Chart code for other files:</h2>
  - Printable characters are blue.<br>
  - Non-printable characters (Null Bytes) are black.<br>

<h2>Shortcuts:</h2>
  - [A] Main analysis tab<br>
  - [W] Analysis tab in modifiable HTML format for report (WebView)<br>
  - [S] Viewer of strings extracted from the parsed file<br>
  - [V] Module with the Virustotal report using its API<br>
  
<h2>Console Options (Analysis to file):</h2>
Start the graphical interface parsing a file from the console:<br>
  <code>4n4lDetector.exe Path\App.exe -GUI</code><br><br>
Remove binary after scan:<br>
  <code>4n4lDetector.exe Path\App.exe -GREMOVE</code><br><br>
Parse a file from the console and the output is written to a TXT file:<br>    
  <code>4n4lDetector.exe Path\App.exe -TXT</code><br><br>
Parse a file from the console and the output is written to HTML file:<br>
  <code>4n4lDetector.exe Path\App.exe -HTML</code>

<h2>Detections:</h2>
PE Information, Unusual Entry Point Position or Code (Algorithms, Anomalous Instructions... ), Packers, Compilations, Binders/Joiners/Crypters, Architectures, Possible malicious functions, Registry Keys, Files Access, Juicy Words, Anti-VM/Sandbox/Debug, URLs Extractor, Payloads, AV Services, Duplicate Sections, IP/Domains List, Config RAT (Only In Memory Dumps), Call API By Name, Unusual Chars In Description File (Polymorphic Patterns), Rich Signature Analyzer, CheckSum Integrity Problem, PE Integrity Check, SQL Queries, Emails, Malicious resources, PE Carve, Exploits, File Rules for Entry Points and more... 😃<br>


<h2>How to add 4n4lDetector to Windows right click?</h2>
  <img src="https://github.com/4n0nym0us/4n4lDetector/assets/76454196/16649189-849e-4c77-b0e3-b9a624135497"</img>
   <br>

<h2><a href="http://www.enelpc.com/p/4n4ldetector.html">WWW.ENELPC.COM</a></h2>

If you enjoy my work and would like to support me, please consider making a donation through PayPal. Any amount is greatly appreciated!<br>
[![Donar con PayPal](https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_150x38.png)](https://paypal.me/enelpc)
<br>

  <h2>Legal Disclaimer</h2>
  <p>This software is provided "as is," without any warranties, either express or implied, including, but not limited to, warranties of merchantability or fitness for a particular purpose. The author shall not be held liable for any direct, indirect, incidental, or consequential damages arising from its use or inability to use it. Any use of the files that comprise the 4n4lDetector or 4n4lDetector Pro applications for purposes other than those intended requires the explicit authorization of the author.</p>
  <p>The author reserves the right to disable or block the software at any time without prior notice or the right to refunds. This software is distributed under a usage license, and if it is found to be leaked or shared through any public or private channel, it may be immediately disabled.</p>
  <p>By using this software, you acknowledge that you have read and fully understood this disclaimer.</p>

  <h2>License of Use</h2>
  <h3>4n4lDetector (Free Version)</h3>
  <p>This software is free for personal and research purposes only. Commercial use, resale, redistribution, or integration of this software into online services, platforms, or security products without the explicit written authorization of the author is strictly prohibited.</p>

  <h3>4n4lDetector Pro</h3>
  <p>The Pro version is provided under individual authorization by the author. Any redistribution, resale, commercial use, or integration into online services or products without the explicit written authorization of the author is strictly prohibited.</p>

  <p>By downloading, copying, or using this software (Free or Pro), you agree to be bound by these terms.</p><br>
   
<h3>Some Images:</h3>

![0](https://github.com/user-attachments/assets/72db3570-1117-417c-b99b-f0234e48e1bf)
<br>

![ANti444](https://github.com/user-attachments/assets/a846c896-851b-41d8-b977-a0b6a6a94b06)
<br>

![1](https://github.com/4n0nym0us/4n4lDetector/assets/76454196/e07ff8a6-eaaa-4783-a230-2ec41518f30b)
<br>

![2](https://github.com/4n0nym0us/4n4lDetector/assets/76454196/cdb55872-b502-480c-82c6-ece6245ade9c)
<br>

![5](https://github.com/4n0nym0us/4n4lDetector/assets/76454196/9742bbe8-bab5-49e7-9345-1d26b27b4dd9)
<br>
        
 ![RESOURCES](https://user-images.githubusercontent.com/76454196/174343536-6832d5c2-b9b0-4fac-afc6-c31e9bc1617b.png)
<br>

![RULES](https://user-images.githubusercontent.com/76454196/165567392-43a4393f-09e1-4de7-bf5c-85fafeb5718c.png)    
<br>

<h2>It is recommended to delete the contents of the old 4n4lDetector directory to include the new version files.</h2>

<h3>v3.4</h3>
    [+] Optimized the string cleaner, improving overall analysis speed.<br>
    [+] Performed a security review of the File Access execution extraction section.<br>
    [+] Fixed a bug that could affect section reading from the DIE library.<br>
    [+] Improved handling of errors related to corrupted section counts.<br>
    [+] Enhanced error control when opening malformed files.<br>
    [+] Replaced certain RVA values with "N/A" when required.<br>
    [+] Filled detection of empty or out-of-range resource fragments with "N/A".<br>
    [+] Fixed duplication of IP addresses detected in the IP Addresses module.<br>
    [+] Reviewed and optimized string search functionality from the "Strings" button in the right panel.<br>
    [+] Improved speed optimization and security controls for the Intelligent Strings module.<br>
    [+] Enhanced buffer cleanup used in Exported Functions carving.<br>
    [+] Optimized ASCII and NullByte character counting in the "Entropy/Recount" section.<br>
    [+] Increased detection of multiple TLS callbacks (32/64-bit):<br>
          &nbsp;&nbsp;&nbsp;-> Added pointer and indirection support.<br>
          &nbsp;&nbsp;&nbsp;-> Introduced controlled heuristics.<br>
          &nbsp;&nbsp;&nbsp;-> Provided complete RVA, VA, and section information.<br>
    [+] Added a general optimization review and new features to the Flow Anomalies module:<br>
          &nbsp;&nbsp;&nbsp;-> Added new detection of anomalous executable sections to the heuristic module.<br>
          &nbsp;&nbsp;&nbsp;-> Added new detection of Exception Hooks to the heuristic module.<br>
          &nbsp;&nbsp;&nbsp;-> Reduced the minimum extraction size for indirect jumps and calls to 100 bytes.<br>
    [+] Added Highlighting with search functionality and color scaling based on criticality:<br>
          &nbsp;&nbsp;&nbsp;-> Yellow: Important but non-critical findings; serves as a warning.<br>
          &nbsp;&nbsp;&nbsp;-> Orange: Potential anomalies or suspicious behavior requiring investigation.<br>
          &nbsp;&nbsp;&nbsp;-> Red: Evidence of malicious activity; requires prioritized review and deep analysis.<br>

<h3>v3.3</h3>
    [+] Fixed an intermittent bug that could display the rotating "hacker" logo at the end of the first scan.<br>
    [+] Added extraction of the IAT disk address in the Information panel.<br>
    [+] Show Offsets notifications now display location details for the offset when pressing "DUMP" and "Disassemble".<br>
    [+] Added overflow checks to the external signature modules.<br>
    [+] Reviewed section counting for PE files with corrupt headers.<br>
    [+] Readjusted Subsystem and MajorOSVersion identifiers in PE files.<br>
    [+] Added the MinorOSVersion field to the analysis shown in Information.<br>
    [+] Reviewed duplicate section counting routine for PE headers.<br>
    [+] Complete refactor of the SQL extraction module — now significantly more powerful.<br>
    [+] Reviewed the File Access execution extraction section.<br>
    [+] Improved detection of names in the Export Table carving section.<br>
    [+] If the Options form was open during analysis, it will remain visible until completion. (REVISION2)<br>
    [+] Fixed an intermittent bug affecting UNICODE string searching in the Finder.<br>
    [+] Slight increase in detections by the Intelligent String module.<br>
          &nbsp;&nbsp;&nbsp;-> Added a dedicated string cleansing routine for Go (Golang) builds.<br>
    [+] Reviewed the File Access module:<br>
          &nbsp;&nbsp;&nbsp;-> Maximized Unicode string extraction capability in the File Access module.<br>
          &nbsp;&nbsp;&nbsp;-> Improved ASCII extraction cleaning to address Golang compiler false positives.<br>
    [+] Review of the sections overview:<br>
          &nbsp;&nbsp;&nbsp;-> Added entropy and Chi-square (Chi2) calculations to file sections.<br>
          &nbsp;&nbsp;&nbsp;-> Included full flag descriptions for all sections.<br>
          &nbsp;&nbsp;&nbsp;-> Sections without names now appear as *unnamed*.<br>
    [+] Rebalance of the Flow Anomalies module:<br>
          &nbsp;&nbsp;&nbsp;-> Added detection of *padding* and *header* patterns for fragments between sections.<br>
          &nbsp;&nbsp;&nbsp;-> Included reading of TLS Callbacks.<br>
          &nbsp;&nbsp;&nbsp;-> Improved detection speed for shellcode and payload instruction patterns in Flow Anomalies.<br>
          &nbsp;&nbsp;&nbsp;-> Adjusted opcode interpretation with ModR/M and SIB to distinguish simple "Displacement form" cases from complex "ModRM/SIB parsed" cases, while maintaining continuity with previous versions.<br>
          &nbsp;&nbsp;&nbsp;-> Junk-code detection at entry points now applies across the entire PE file.<br>
          &nbsp;&nbsp;&nbsp;-> Restructured section-field detection so it is explicitly tied to the on-disk offset.<br>
          &nbsp;&nbsp;&nbsp;-> The heuristic module now features the [cnf] shortcut to open [Settings].<br>
          &nbsp;&nbsp;&nbsp;-> Extended translation compatibility for x64 instruction decoding.<br>
    [+] Added a new "Indirect Call/Jump" heuristic options section to control indirect calls and jumps in [Settings]:<br>
          &nbsp;&nbsp;&nbsp;-> Allows selecting the code-size to analyze in decimal, from 1,000 to 100,000 bytes.<br>
          &nbsp;&nbsp;&nbsp;-> Init Offset defines the analysis starting point and accepts decimal or hexadecimal values.<br>
          &nbsp;&nbsp;&nbsp;-> CALL [static], JMP [static], CALL [reg], and JMP [reg] options are selectable via checkboxes.<br>
          &nbsp;&nbsp;&nbsp;-> "Indirect Call/Jump" configurations are automatically saved and loaded at application start and can be removed from the "Config files" section.<br>

<h3>v3.2</h3>
    [+] Compatibility with the achievement medal system and unlocking of functionalities from the previous version.<br>
    [+] Fixed an issue that caused duplicate section counts in non-executable files.<br>
    [+] Inclusion of form state controls during analysis.<br>
    [+] Complete review of the heuristic and email modules, now enabled by default.<br>
    [+] If the Options form was open during analysis, it will remain visible until completion.<br>
    [+] Manual string search limited to 100 characters.<br>
    [+] Redistribution and minor adjustments in the payload module detections.<br>
    [+] Review of the decimal-to-hexadecimal and hexadecimal-to-decimal offset conversion routine.<br>
    [+] Optimization of the Intelligent Strings module, improving performance on large files.<br>
    [+] Slight improvement in SQL query extraction.<br>
    [+] Update and optimization of the file description extraction module:<br>
          &nbsp;&nbsp;&nbsp;-> Language and CodePage fields are now included in all descriptions.<br>
    [+] Inclusion of the Flow Anomalies module, responsible for static code flow checks:<br>
          &nbsp;&nbsp;&nbsp;-> Identification of indirect calls in executables.<br>
          &nbsp;&nbsp;&nbsp;-> Detection of suspicious jump sequences (JMP and conditional), indicating possible obfuscation or packing.<br>
          &nbsp;&nbsp;&nbsp;-> Detection of instructions related to shellcodes and payloads.<br>
          &nbsp;&nbsp;&nbsp;-> Detection of NOP and breakpoint (BP) sequences.<br>
          &nbsp;&nbsp;&nbsp;-> Extraction of Overlay in hexadecimal and character format.<br>
          &nbsp;&nbsp;&nbsp;-> Verification of junk code in Entry Points.<br>

<h3>v3.1</h3>
    [+] A new button with a coronavirus icon has been added to the main panel, redirecting the user to PEscan.io when clicked.<br>
    [+] Manual integration of all Zw functions with their descriptions, including detection of Call API By Name invocations.<br>
    [+] Significant improvements in the information gathering module via SQL queries, optimizing both performance and accuracy.<br>
    [+] Optimization of the detection and analysis process for duplicate sections in PE files.<br>
    [+] Adjustment in the RVA calculation for the Export Table, now based on its real offset.<br>
    [+] New controls implemented for the extraction of the Import Table, Export Table, and Resources.<br>
    [+] A preventive control has been added to avoid general overflow-related errors.<br>
    [+] SSL support updated to ensure compatibility with the VirusTotal API.<br>
    [+] The automatic download of the current message in the Settings section has been disabled; it now requires manual user action.<br>
    [+] Additional security checks added for the Reset and Updates buttons in Settings to prevent accidental execution.<br>
    [+] Redesign and improvement of report presentation, both in the main panel and HTML version, aimed at a better user experience.<br>
    [+] File access module revised to improve extraction of styled HTML content.<br>
    [+] Buffer handling optimized during analysis to enhance overall performance.<br>
    [+] Additional information included, such as the .NET version and a new flag indicating Any CPU support.<br>
    [+] Settings and Help forms now open centered relative to the main form.<br>
    [+] Updated rule dictionaries for Entry Point and custom "4n4l.Rules".<br>
    [+] Fixed a sporadic error in the file paths section.<br>
    [+] Added plain text format extraction for data retrieved from executable resources.<br>
          &nbsp;&nbsp;&nbsp;-> Reviewed detection of executables embedded within resources.<br>
          &nbsp;&nbsp;&nbsp;-> Text extraction from resources is now limited according to actual content size.<br>
    [+] Improved Intelligent Strings module with broader pattern coverage and detections.<br>
          &nbsp;&nbsp;&nbsp;-> Enhanced collection of serial numbers and IP addresses in the module.<br>

<h3>v3.0</h3>
    [+] The function search code for "Import Table" and "Call Api By Name" has been optimized.<br>
    [+] A general optimization has been performed with one of the largest buffers in memory, this positively affects the stability and speed of the general analysis.<br>
    [+] The size of the file to be analyzed has been increased by default to 50MB.<br>
    [+] An optimization has been made in the search engine for the "Show Offsets" option and in the handling of buffers.<br>
    [+] Searches for generic malware terms, different types of exploitation, APTs and terminologies that may affect the State in "4n4l.Rules" have been included.<br>
    [+] A cleaning of null bytes 0x00 is performed in the variable where the report is stored to avoid bugs in the output of the text box of the main form.<br>
    [+] The tool interface takes on a darker base tone.<br>
    [+] A donation button via (PAYPAL) has been included since I have finally decided to continue with the project publicly for everyone.<br>
    [+] A bug was fixed in which false functions could be included in the "Export Table" list by carving.<br>
    [+] The Interest's Words module includes new internal words for the tool, for ansi and unicode.<br>
    [+] A bug in the web view was fixed that could aesthetically affect the view of the Interest's Words module statement.<br>
    [+] Optimizations were made in the Known IP/Domains module for ansi and unicode.<br>
    [+] New search syntaxes were included in the "Intelligent Strings" module to increase interesting results.<br>
          &nbsp;&nbsp;&nbsp;-> Internal cleanup syntaxes were added to show more stylized results.<br>
          &nbsp;&nbsp;&nbsp;-> An optimization has been made with a direct impact on the variables used in this module.<br>
    [+] A more selective cleaning of the extracted URLs is performed:<br>
          &nbsp;&nbsp;&nbsp;-> URLs with extensions in the context of PKI digital certificates are reconstructed.<br>
          &nbsp;&nbsp;&nbsp;-> Htm extensions are reconstructed.<br>
          &nbsp;&nbsp;&nbsp;-> ".com" domain endings are cleaned.<br>
          &nbsp;&nbsp;&nbsp;-> Possible HTML code cleaning is performed.<br>
    [+] A progression system based on medals has been included.<br>
          &nbsp;&nbsp;&nbsp;-> Brown Padawan Medal, Bronze Medal, Silver Medal, Gold Medal and Platinum Medal.<br>
          &nbsp;&nbsp;&nbsp;-> The process can be slow, don't despair... because it's worth it.<br>
          &nbsp;&nbsp;&nbsp;-> These medals will be earned as you use the tool over the course of days, weeks, months and consequently their functionality will also increase progressively.<br>
          &nbsp;&nbsp;&nbsp;-> The medals will only work on the work machine on which they have been earned, if you want to make it work on another machine of yours try it yourself (You're a hacker, right?).<br>
          &nbsp;&nbsp;&nbsp;-> The features or surprises that come with leveling up are not included in this file, although you can review them in the "Settings" section of the tool.<br>

<h3>v2.9</h3>
    [+] New logo of the application by Sandra Badia Gimeno (www.sandrabadia.com).<br>
    [+] Relocated Kernel-mode functions to the Suspicious Functions section.<br>
    [+] Surprises are included so you don't get bored with daily use of the tool.<br>
    [+] A multitude of tests were carried out focused on providing the greatest stability, speed and effectiveness of the extracted contents.<br>
    [+] Optimization during idle state. File creation checks are no longer performed for the PECarve and UPX functionalities.<br>
    [+] Detection of sections that allow writing from flags was included.<br>
    [+] The extraction of functions from the "Export Table" using Carving has been slightly improved.<br>
    [+] The name of the file under analysis has been included in the content of the report.<br>
    [+] Added a longer description about the possibilities of the Zombie_AddRef function.<br>
    [+] Fixed a bug where the "Show Offsets" tool dump did not allow reading a small portion of the end of the analyzed file.<br>
    [+] Now when you click on the Virustotal result in the main form, it will take us to the analysis web page.<br>
    [+] Virustotal analysis has been included in the analyzes carried out from console mode.<br>
    [+] Review of Shikata_ga_nai detections and update of Payload detection heuristics.<br>
    [+] Increased and improved the query extraction functionality of the ASCII and UNICODE records branch.<br>
    [+] Increased and improved the ASCII and UNICODE SQL query extraction functionality.<br>
    [+] Increased and improved URL extraction functionality, also searches FTP and SFTP in ASCII and UNICODE.<br>
    [+] Increased and improved ASCII and UNICODE file name extraction functionality.<br>
          &nbsp;&nbsp;&nbsp;-> .EXE, .DLL, .BAT, .VBS, .VBE, .JSE, .WSF, .WSH, .PS1, .PSM1, .PSC1, .SCR, .HTA, .DLL, .PIF, .MSI , .MSP, .SYS, .CPL, .JAR, .TXT, .INI, .PDF, .WDS, .DOC<br>
    [+] The word finder has been completely delimited for any search location of the text boxes.<br>
          &nbsp;&nbsp;&nbsp;-> In web view the browser is now automatically blocked.<br>
    [+] Fixed a rare error in the IPs section that could lead the execution thread to a loop without finishing analyzing the files.<br>
          &nbsp;&nbsp;&nbsp;-> This fix also fixed the ability to end analysis with a single active option in the tool's modules panel.<br>
    [+] The 4n4l.rules module now internally converts text format rules "T:" to Unicode format.<br>
          &nbsp;&nbsp;&nbsp;-> The rules of this file have been optimized, now search more with less.<br>
    [+] The bytes to be reviewed at the Entry Point by the rules file are increased from 100 to 1500.<br>
          &nbsp;&nbsp;&nbsp;-> Revised some of the rules to eliminate false positives after the update.<br>
    [+] The reading of the rule files is done only once after starting the application or after the first analysis, then it is loaded into memory for future uses.<br>
          &nbsp;&nbsp;&nbsp;-> The charging status can be checked from the "Settings" section.<br>
    [+] Added the tilde (~), the dollar ($), the single quote (') and the double quote (") as characters that can be part of the reports.<br>
          &nbsp;&nbsp;&nbsp;-> A conversion filter is applied to these quotes for the tool's Web view.<br>
    [+] Worked on the efficiency of the "Intelligent Strings" module.<br>
          &nbsp;&nbsp;&nbsp;-> The length of strings to be analyzed was increased in all the Strings functionalities of the tool (75% longer strings).<br>
          &nbsp;&nbsp;&nbsp;-> Specific cleanup of anomalous characters is now performed and new ones are allowed.<br>
          &nbsp;&nbsp;&nbsp;-> Search words were extended.<br>
    [+] Added a graph in charge of displaying the content of the executables and any analyzed files.<br>
          &nbsp;&nbsp;&nbsp;-> The executable header is displayed in blue.<br>
          &nbsp;&nbsp;&nbsp;-> The identified sections are divided between magenta for the executable sections and black for the rest.<br>
          &nbsp;&nbsp;&nbsp;-> The excess code of the executables will have a red color as in Crypters, Binders, Joiners...<br>
          &nbsp;&nbsp;&nbsp;-> If the analyzed section contains an RSize of zero, its content will not be painted on the graph.<br>
          &nbsp;&nbsp;&nbsp;-> If the file is not a Windows executable, it will be scanned for printable characters and the absence of printable characters. Blue and black when there is no content.<br>
          &nbsp;&nbsp;&nbsp;-> When you double click on the graph, it will automatically be saved in the analysis folder.<br>
          &nbsp;&nbsp;&nbsp;-> The executions measure the console mode of the application "-TXT", "-HTML" or "-GREMOVE" include the graph as analysis output.<br>

<h3>v2.8</h3>
    [+] A notice is added to the sections section when the identified section is executable.<br>
    [+] The SHA-256 and SHA-1 Hashes of all analyzed files are now also calculated.<br>
    [+] Including the original name of the analyzed library in the "[Export Table]" button.<br>
    [+] Now 4n4lDetector is able to identify content in the Import Table even though the "Original First Thunk" Offset is at "0" as in UPX tablets.<br>
    [+] The "Settings" module now has a subtle optimization to avoid freezes when downloading notifications.<br>
    [+] The code responsible for resource extraction has been optimized, it is now faster.<br>
    [+] Entry Point extraction has been restructured, optimizing its code and improving extraction speed.<br>
    [+] Optimized and removed some of the internal rules of 4n4lDetector to avoid some false positives.<br>
    [+] The file description extractor algorithm was modified, it is now more effective.<br>
    [+] The Carving PE result is now stored in a folder called PECarve within the analysis section.<br>
    [+] Virustotal information has been relocated to the main panel. (Use your personal API_KEY).<br>
          &nbsp;&nbsp;&nbsp;-> SORRY MICROSOFT... I think we are at peace after that CobaltStrike detection <3<br>
    [+] The "IT Functions:" section of the main analysis is now called "Suspicious functions:", this being more accurate.<br>
          &nbsp;&nbsp;&nbsp;-> Functions now have a description of their functionalities.<br>
    [+] The "Strings" functionality now runs automatically, visible in the "[s]" button after scans while "Intelligent Strings" is active.<br>
          &nbsp;&nbsp;&nbsp;-> Increased the effectiveness and speed of the "Intelligent Strings" module and the "Strings" functionality.<br>
    [+] The "Sections Info" option is now internal and in its place an optional one has been created to decompress UPX samples.<br>
          &nbsp;&nbsp;&nbsp;-> The unzipped samples are stored in the analysis path, within a folder called UPX.<br>
          &nbsp;&nbsp;&nbsp;-> The UPX binary is located in the root of 4n4lDetector, in a folder called "bin" and can be modified by the user.<br>
    [+] The verification of signed executables, the checksum signature and the Rich signature are now grouped in the "Signatures" section.<br>
    [+] Changes in the management of the Rich firm.<br>
          &nbsp;&nbsp;&nbsp;-> The entire signature is extracted, not just the first part.<br>
          &nbsp;&nbsp;&nbsp;-> Added a hash for detection.<br>
          &nbsp;&nbsp;&nbsp;-> its integrity is verified with a review of the old algorithm.<br>
    [+] A new tool has been added to extract Offsets directly from the executable and view its contents.<br>
          &nbsp;&nbsp;&nbsp;-> It is now possible to manually perform code searches in hexadecimal, ASCII and UNICODE.<br>
          &nbsp;&nbsp;&nbsp;-> A functionality to review the assembly code has also been included.<br>
          &nbsp;&nbsp;&nbsp;-> This tool executes its main functions automatically with the Entry Point after each analysis.<br>
    [+] Added extraction of import and export tables from the rest of the existing executable architectures.<br>
          &nbsp;&nbsp;&nbsp;-> Alpha AXP, ARM, EFI Byte Code, EFI Byte Code (EBC), Hitachi SH3, Hitachi SH3, Hitachi SH3, Hitachi SH4, Hitachi SH5, Intel Itanium (IA-64), Intel i860, M32R, MIPS16, MIPS16 with FPU, MIPS R3000, MIPS R4000, MIPS little-endian, MIPS little-endian WCE v2, MIPS with FPU.<br>
            
<h3>v2.7</h3>
    [+] Executable analysis for 32- and 64-bit ARM architectures (ARMv7 and ARMv8) has been implemented.<br>
    [+] Added an option called "Sections Info" that includes additional information about sections.<br>
    [+] Corrected tabulations that could not appear in some lines of reports in several modules.<br>
    [+] Added the capture of possible Logins to "Intelligent Strings".<br>
    [+] The "Intelligent Strings" module now correctly separates library names from the "Import Table".<br>
    [+] Fixed a bug in a rare case that could hide the "Export Table" button after viewing its contents.<br>
    [+] Eliminated the extra line breaks that were included at the end of all reports.<br>
    [+] Improved the collection of SQL queries from the selectable module in the right options panel.<br>
    [+] Optimization of the code of the old "Online Area" and the rest of the new options of the now called "Settings" were carried out.<br>
    [+] Organized and included new rules for reviewing entry points from the "EP.rules" file.<br>
    [+] Included the "[C]" button to select the color of the application's letters with auto-save function.<br>
    [+] Restructured and adjusted the main form panel options.<br>
    [+] The Virustotal result was included as an active part of the right panel of the main form.<br>
    [+] The maximum file size to be analyzed is increased to 10MB by default.<br>
    [+] Added the extraction of IT, ET and IAT disk addresses in the Information section.<br>
    [+] Added a progress bar that appears during scans to the left of the main form.<br>
    [+] Better control of files to be analyzed was developed and error control was improved.<br>
    [+] Moved the counter functionality from "NOP Caves" to the "Entropy/Recount" option.<br>
    [+] The "Rich Signature" option becomes "Signatures" as it also includes signed executables.<br>
    [+] Verification of executable signatures has been added and we can now find the following types.<br>
          &nbsp;&nbsp;&nbsp;-> Signed executables.<br>
          &nbsp;&nbsp;&nbsp;-> Unsigned executables.<br>
          &nbsp;&nbsp;&nbsp;-> Signed but modified executables.<br>
          &nbsp;&nbsp;&nbsp;-> Others... 0.0<br>
    [+] An error that prevented console analysis in the previous version was corrected and the code for this functionality was improved.<br>
          &nbsp;&nbsp;&nbsp;-> The "-HELP" or "?" parameter was included. to display help from console mode.<br>
          &nbsp;&nbsp;&nbsp;-> Made case-sensitive.<br>
    [+] Increased the extraction of the first 40 bytes of the Entry Point to a total of 50 bytes.<br>
          &nbsp;&nbsp;&nbsp;-> This also increases the effectiveness of the rules file "EP.rules".<br>

<h3>v2.6</h3>
   [+] A new form has been included with access to an Online Area.<br>
          &nbsp;&nbsp;&nbsp;-> The "[Online Area]" button opens a form with real-time notifications that can be modified by me at any time.<br>
          &nbsp;&nbsp;&nbsp;-> It is possible to respond to the contents of the notifications through the "Reply" button via email.<br>
          &nbsp;&nbsp;&nbsp;-> The content of the notifications will be merely informative about the development status of the tool or current malware alerts.<br>
          &nbsp;&nbsp;&nbsp;-> From the File Rules section it is possible to download and modify the new "4n4l.rules" and "EP.rules" files with ease.<br>
          &nbsp;&nbsp;&nbsp;-> The current date and time is included at the beginning of the files after each download to record their modification.<br>
   [+] A carving functionality is included to review PE headers inside the analyzed files.<br>
          &nbsp;&nbsp;&nbsp;-> If executables are identified, the size of their PEs is calculated and they are extracted to disk.<br>
          &nbsp;&nbsp;&nbsp;-> Extracted files are stored with the name of the Start Offset from which they were extracted and assigned a non-executable extension.<br>
          &nbsp;&nbsp;&nbsp;-> The storage folder of the extracted PE files is the same as the HTML parsing storage folder.<br>
   [+] A "[GO]" button is included in the "PE Carve" module that will open the created files folder, otherwise it will open the analysis folder.<br>
          &nbsp;&nbsp;&nbsp;-> A flashing light on the "[GO]" button will notify the user when the folder containing the files is generated.<br>
   [+] A section of rules for exploit detection is included.<br>
          &nbsp;&nbsp;&nbsp;-> In the Entry Point from the "EP.Rules" dictionary<br>
          &nbsp;&nbsp;&nbsp;-> In the "4n4l.Rules" dictionary<br>
          &nbsp;&nbsp;&nbsp;-> In the resources<br>
   [+] A multitude of optimizations have been included to improve analysis times.<br>
   [+] The file cutter functionality has been removed due to lack of community use due to larger samples being analyzed.<br>
   [+] A change has been made to the icon of the main form and that of the application executable.<br>
   [+] Fixed small visual defects that occurred in some unusual system configuration of Windows 10 and Windows 11 systems.<br>
   [+] The "Show Options" button is launched with a delay of one second on the first execution.<br>
   [+] The storage path of the HTML documents is now located within a folder named after the MD5 hash of the analyzed file.<br>
   [+] The RAT configuration module becomes part of the Heuristics module disabled by default.<br>
   [+] Increased the effectiveness of the carving algorithm for extracting functions from the Export Table that may be missing.<br>
   [+] Analysis content size and time statistics are kept in the WebView tab title.<br>
   [+] From the WebView tab you can now apply another background color for the generation of the HTML file.<br>
   [+] The code that performs the extraction of IP addresses has been reviewed, improved and optimized prioritizing its speed and effectiveness.<br>
   [+] The internal "Known IP/Domains" module now has an expanded list of DNS service detections.<br>
   [+] Fixed a small bug that painted one of the modules yellow without the analysis option being enabled.<br>
   [+] Fixed a small bug that omitted the first string from the "Intelligent Strings" buffer and from the "Strings" functionality.<br>
   [+] The tool's color code now marks purple buttons as a (direct internet connection).<br>
   [+] Form buttons now show an indication of their action.<br>
   [+] Increased detection of new syntaxes in the "Intelligent Strings" module.<br>
   [+] Mimikatz detection by dictionary "4n4l.Rules".<br>
   [+] Correction of some rules of the known Entry points detection dictionary and the "4n4l.Rules" dictionary.<br>
   [+] SysCall detection from "4n4l.Rules" by Miguel Ángel Arenas.<br>
   [+] Sample reanalysis option in the main form, idea of Miguel Ángel Arenas.<br>
   
<h3>v2.5</h3> 
     [+] Greater effectiveness and detection of new syntaxes in the "Inlligent Strings" module and in the "Strings" functionality.<br>
     [+] The analysis tab stores the statistical information in the form title of the current session.<br>
     [+] A warning is included to detect strings that are too long for the search engine and the singular is assigned for a match.<br>
     [+] The entire Detect It Easy “DIE” database was updated with the new rules as of December 5, 2023.<br>
     [+] Added new rules to the "4n4l.rules" file.<br>
     [+] The add file button has been removed from the main interface, now the graphical interface will only have the possibility of dragging files to analyze them.<br>
     [+] Included a new option to parse the content of "LNK" shortcuts with or without their default extension.<br>
     [+] Fixed a cosmetic bug affecting some high-resolution UltraWide displays.<br>
     [+] Improved integration of the window resizing module for Windows 7, 10 and 11 operating systems.<br>
     [+] Included a quick access button to the default "Show Options" view in case the window has been resized.<br>
     [+] The "Show Options" button now changes to "Hide Options" based on the size of the main form and when the button is activated.<br>
     [+] The app now opens options on every startup to keep them in view during use.<br>
     [+] The analysis progress changes the color of the modules name, within the options section in real time as it progresses.<br>
         &nbsp;&nbsp;&nbsp;-> Red indicates the module in which the tool is being analyzed.<br>
         &nbsp;&nbsp;&nbsp;-> Yellow indicates the end of the analysis of that module.<br>
         &nbsp;&nbsp;&nbsp;-> White indicates that the tool has not analyzed with that module.<br>
     [+] Please don't touch the red button or Beelzebub will come, Thank you.<br>
        
<h3>v2.4</h3>        
   [+] Unlimited the number of characters shown in the String viewer, also affecting the Export and Import Table.<br>
   [+] Optimizations have been made prioritizing the stability of the tool at the expense of the minimum loss of speed during the analysis.<br>
   [+] Added extraction of the SYSTEM branch of the registry.<br>
   [+] The Strings tool has been optimized, having a very positive impact on its speed.<br>
   [+] Expanded the Strings tool's collection of new strings.<br>
   [+] Added a new string search module called Inlligent Strings. (Search for keywords just like a malware analyst would)<br>
        &nbsp;&nbsp;&nbsp;-> Included a cleanup function for routes and internet addresses that affects this module.<br>
   [+] Included a time control after finishing the analysis in the title of the main form.<br>
   [+] Blocked the option to drag samples over the Web code avoiding the option to execute.<br>
        
<h3>v2.3</h3>
   [+] Added a new functionality that allows choosing the sizes of the files to analyze.<br>
        &nbsp;&nbsp;&nbsp;-> Analysis times are higher with settings well above the default in the MaxFileLen(MB) field.<br>
        &nbsp;&nbsp;&nbsp;-> It is recommended to disable options in files larger than usual.<br>
   [+] The process runs with high priority during the scan time and while some demanding tasks are performed.<br>
   [+] Fixed a bug that could lead to an unexpected application crash after parsing a malformed executable type.<br>
   [+] Fixed a bug that could lead to an unexpected application crash after parsing a malformed header type.<br>
   [+] Unlimited the number of characters shown in the analysis viewer by default, affecting the web view and the analysis from the console.<br>
   [+] Unlimited the number of characters shown in the HTML code viewer from the web view.<br>
   [+] The extraction of functions in the export table is now increased from 130 to 400 in the carving section.<br>
   [+] Fixed a bug that could hang the program during the extraction of the name of the sections.<br>
   [+] The use of the Timers of the tool during the analysis time was optimized.<br>
   [+] Added multitude of detections in Unicode format for the "4n4l.rules" rules file.<br>
   [+] Fixed a bug that could disable the Export Table button for some libraries.<br>
   [+] Fixed a bug that could generate a lot of junk characters after parsing certain UPX files.<br>
   [+] Optimizations have been made with the application's memory usage.<br>
   [+] The program bar now shows the number of characters in the analysis report.<br>
        
<h3>v2.2</h3>
     [+] Correction of slight visual defects in the interface.<br>  
     [+] Correction in the URL extraction module.<br>  
     [+] Including the detection of APIs referring to the following points in the "4n4l.rules" file:<br>  
         &nbsp;&nbsp;&nbsp;-> Networks<br>  
         &nbsp;&nbsp;&nbsp;-> Persistence<br>  
         &nbsp;&nbsp;&nbsp;-> Encryption<br>  
         &nbsp;&nbsp;&nbsp;-> Anti-analysis virtual machine<br>  
         &nbsp;&nbsp;&nbsp;-> Stealth<br>  
         &nbsp;&nbsp;&nbsp;-> Execution<br>  
         &nbsp;&nbsp;&nbsp;-> Antivirus<br>  
         &nbsp;&nbsp;&nbsp;-> Privileges<br>  
         &nbsp;&nbsp;&nbsp;-> Keyboard keys<br>  
         &nbsp;&nbsp;&nbsp;-> WMI executions<br>  
     [+] Reorganization of files:<br>  
         &nbsp;&nbsp;&nbsp;-> Configuration "cnf" and "vtapi" (Virustotal) in the folder<br>  
         &nbsp;&nbsp;&nbsp;-> Dictionaries in the ".\db\rules" folder.<br>  
     [+] Improved the integration of the "Strings" tab along with the "Export table" and "Import table" functions.<br>  
     [+] Included in the analysis tab the Virustotal detection rate if the sample is detected by any antivirus.<br>  
     [+] Mobile interface with magical surprises.<br>  
     
<h3>v2.1</h3>
     [+] Labels displayed in the report section that may come from the analytics tab will now be converted to HTML entities.<br>  
     [+] Included in the internal list of 4n4lDetector new words of interest.<br>  
     [+] Added the extraction of new execution statements from the analyzed binaries.<br>  
     [+] Eliminated null detections (PE: 0) by DIE.<br>  
     [+] Reorganization of Packer/Compiler/Entropy detections.<br>  
     [+] Currently the entropy calculation is done from the DIE section next to the Entropy/count option activated.<br>  
     [+] Including checking all resources for malicious executables.<br>  

<h3>v2.0</h3>
  [+] From the command line by default and without the need to use any parameter, the files will be analyzed by opening the graphical interface as if "-GUI" is used.<br>
  [+] Updated Detect It Easy "DIE" application database included for all file types.<br>
  [+] Included the entropy analysis of the analyzed file in the "Extra 4n4lysis" section.<br>
  [+] Drag and add file options are now blocked while performing a scan.<br>
  [+] ImpHash calculation included (x86/x64).<br>
  [+] Analyze the assembled code for x64 binaries with Capstone Disassembler.<br>
  [+] The extraction is extended to 40 bytes of the Entry Point, improving the detections with "EPRules" (x86/x64).<br>
  [+] The TimeDateStamp field now defaults to hexadecimal.<br>
  [+] Fixed Epoch conversion failing for some TimeDateStamp.<br>
  [+] Raw Entry Point detection for all x64 binaries.<br>
  [+] Improved the extraction of information from the XML resource for the UAC execution level.<br>
  [+] Improved the reading of the characteristics field in x64 binaries to identify EXE/DLL.<br>

<h3>v1.9</h3>
  [+] Included a modifiable dictionary of wildcard rules for the first 25 bytes of the EP, with over 3.700 compiler and packer detection lines.<br>
  [+] Details and settings in the interface.<br>
  [+] The form opens in the center of the screen to improve viewing at unusual resolutions.<br>
  [+] Added list of thanks ;)<br>
  [+] Fixed a bug in opening executables blocked by the system observed in Windows 11.<br>
  [+] Fixed current folder crash when manually dragging a sample for analysis.<br>
  [+] Improved the stability of the application form.<br>
  [+] Added two buttons that will be activated automatically when identifying functions in the import/export tables.<br>
  [+] Several bugs related to the extraction of opcodes in some Entry Points have been corrected.<br>
  [+] Fixed a bug that could unexpectedly close the application after parsing certain UPX files.<br>
  [+] A warning is included for when a user executes 4n4lDetector.exe without the necessary files for its correct operation.<br>
  [+] UPX compression version detector updated.<br>
  [+] The "Emails" module is included as (optional disabled) by default, due to the delay it could cause in some rare binaries.<br>
<h3>v1.8</h3>
  [+] Double header detection in ELF Linux executables<br>
  [+] Added UPX version number extraction for ELF Linux executables (Widely used in malware these days)<br>
  [+] Added identification of all ELF Linux executable types<br>
  [+] The user interface is friendlier than ever.<br>
  [+] The first fragment of the Rich signature is included in case you find it.<br>
  [+] It's taken 9 versions of 4n4lDetector... but it's here, you can now maximize the form!<br>
  [+] Improved email identification algorithm to avoid duplicate addresses.<br>
  [+] Fixed a bug that could unexpectedly close the application after opening a specific type of file.<br>
  [+] Improved string cleaning after extracting libraries in UNICODE format.<br>
  [+] Fixed a bug when showing the available functions and their count in the export table.<br>
  [+] Added functionality to view reports "[W]" from a Web viewer with the following tools<br>
       &nbsp;&nbsp;&nbsp;-> Options for modifying the title and content of the report<br>
       &nbsp;&nbsp;&nbsp;-> A viewer of the generated HTML code for display<br>
       &nbsp;&nbsp;&nbsp;-> A button to save the report to a document<br>
       &nbsp;&nbsp;&nbsp;-> Integrated a button to open the folder that houses all the saved reports<br>
  [+] Added the "-HTML" parameter for extracting reports in HTML format by console:<br>
       &nbsp;&nbsp;&nbsp;-> 4n4lDetector.exe Path\App.exe -HTML<br>
<h3>v1.7</h3>
  [+] Added new functionality to identify ASLR-enabled binaries.<br>
  [+] Fixed a bug that could lead to the application crashing in some binaries.<br>
  [+] Improved the integration of the debugger for reading the Entry Point of the x86 binaries.<br>
  [+] Smoothed out the design of the form interface and repositioning of controls.<br>
  [+] The process execution functionality is eliminated, although the possibility of analyzing MDUMPS is maintained.<br>
<h3>v1.6</h3>
  [+] Added new functionality to view the Entry Point code in ASM for x86 binary.<br>
  [+] Added combined rules for strings in hexadecimal and text, with multiple matches.<br>
      &nbsp;&nbsp;&nbsp;-> The end of the rule description field contains the rule number separated by "-" from the total number of rules belonging to the same combination.<br>
         Example: H:1A6C6488F2736988:Rich Signature Found 1-2<br>
         (Currently it only allows a maximum of 9 matches...) ;)<br>
<h3>v1.5 new revision for Enelpc_debugger</h3> 
  [+] Fixed a bug in the word search engine of the main interface.<br>
  [+] Changed the cleanup function that removes extraneous characters from the output.<br>
  [+] Added section name extraction.<br>
  [+] Added the option to select a dictionary of words and codes in hexadecimal to search in the binary in a personalized way.<br>
      &nbsp;&nbsp;&nbsp;-> "H" Defines the string in hexadecimal.<br>
      &nbsp;&nbsp;&nbsp;-> "T" Defines the string as text.<br>
      &nbsp;&nbsp;&nbsp;-> The last field separated by ":" is the description used in the 4n4lDetector output.<br>
<h3>v1.4 new revision for Enelpc_debugger</h3> 
  [+] Fixed a bug (fucked up) with the "-TXT" option for console executions.<br>
  [+] Added the ability to open LNK files to automatically resolve the executable path.<br>
  [+] The "Add File" button allows for a simpler file search.<br>
<h3>v1.4</h3>
  [+] Small bug fixes.<br>
  [+] Added the identification of the version of the operating system where the sample can run in "Information".<br>
  [+] Added [A], [S] and [V] buttons to the interface. Analysis, Strings and Virustotal.<br>
  [+] Added the Virustotal option to the list of checks, along with a button to select the ApiKey.<br>
  [+] Added a "Check" to extract emails.<br>
<h3>v1.3</h3>
  [+] Fixed a bug in the extraction of some versions of UPX.<br>
  [+] Extraction of the SQL Queries contained in the binary.<br>
  [+] The number of blocks of 5 existing NOPs are counted, in search of Code Caves.<br>
  [+] More unusual codes are checked after the Entry Point.<br>
  [+] Added Zw function extraction (Kernel Mode).<br>
  [+] Added polymorphism detections. (PEScrambler)<br>
  [+] Added a counting routine for Ascii characters and null characters.<br>
  [+] Added the "Show Options" button, where many of the features are found.<br>
  [+] Added a module for email extraction.<br>
  [+] Added a module for IP address extraction.<br>
  [+] Added a warning when finding a digital signature.<br>
  [+] Added Drag&Drop to the text box where the information is displayed.<br>
  [+] Added a DOS Header check algorithm to the Heuristics module.<br>
  [+] Improved the cleanliness in which the extracted strings are displayed.<br>
  [+] Added a new button to the main interface, in order to view the strings that the binary contains.<br>
  [+] Added a word search engine.<br>
  [+] Added two buttons that are activated after using the "Strings" button, which allow you to navigate between the main information and that obtained with said button.<br>
<h3>v1.2</h3>
  [+] Fixed a bug showing old versions of UPX.<br>
  [+] Fixed a bug that affected the detection of some Entry Points.<br>
  [+] Added the word EOF, in the description of the Dropper detections.<br>
  [+] Increased the effectiveness of the Shikata Ga Nai detection routine.<br>
  [+] Removed extracted executables with asterisks·<br>
  [+] Review of the integrity of the PE format.<br>
  [+] Microsot Rich Signature Integrity Review.<br>
  [+] CheckSum integrity check.<br>
  [+] Added TimeDateStamp field and build date.<br>
  [+] Detection of migrations from the Entry Point to other areas of executable code.<br>
  [+] Added an icon viewer.<br>
  [+] Added detection routine for Visual Basic 5/6 applications with unusual codes after their Entry Point.<br>
  [+] Expanded Packers detection.<br>
  [+] Added incomplete (truncated) executable detection routine.<br>
  [+] Added the creation of a registry file "Add4n4lMenu.reg", to include the analyzes quickly to the explorer dropdown.<br>
  [+] Added library extraction.<br>
  [+] Added parameter detection for the 4n4lDetector.exe executable<br>
       &nbsp;&nbsp;&nbsp;-> 4n4lDetector.exe Path\App.exe -GUI<br>
       &nbsp;&nbsp;&nbsp;-> 4n4lDetector.exe Path\App.exe -TXT<br>
       &nbsp;&nbsp;&nbsp;-> 4n4lDetector.exe Path\App.exe -GREMOVE (Deletion of the binary after its analysis)<br>
  </body>
</html>
