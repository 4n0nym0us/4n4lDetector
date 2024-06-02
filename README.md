<html>
<head>
<img src="https://user-images.githubusercontent.com/76454196/168347380-fc575373-40d8-4e7d-b755-7167ef23fe98.jpg"</img>
</head>
<h2>Advanced static analysis tool</h2>
<body>
4n4lDetector is a scan tool for Microsoft Windows executables, libraries, drivers and mdumps. Its main objective is to collect the necessary information to facilitate the identification of malicious code within the analyzed files. This tool analyzes, among other things, the PE header and its structure, the content of the sections, the different types of strings, among many other things. It also incorporates a multitude of its own ideas to recognize anomalies in the construction of files and the detection of mechanisms used by current malware.<br><br>

Using the tool is simple, just configure the options in the drop-down panel on the right and drag the samples into 4n4lDetector.<br>

<h2>Full support:</h2>
  - 32 bits (8086, x86, ARMv7)<br>
  - 64 bits (AMD64, x86-64, x64, ARMv8)<br>

<h2>Buttons code:</h2>
  <span style="color: green;">- Buttons colored green are action buttons that open files and folders or are used to interact with the tool's utilities.</span><br>
  <span style="color: red;">- The buttons colored in red perform reconfigurations, deletion of data or reset of functional files.</span><br>
  <span style="color: purple;">- Purple buttons announce the activation of online interactions.</span><br>
  <span style="color: pink;">- The pink buttons are shortcut buttons that the tool uses as tabs to navigate between different types of utilities.</span><br>

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
   
<h3>Some Images:</h3>

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
![aEhI](https://user-images.githubusercontent.com/76454196/165567354-124a64e9-d6b7-445c-9fb7-d2855490b2ef.png)
<br>

<h2>It is recommended to delete the contents of the old 4n4lDetector directory to include the new version files.</h2>

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
