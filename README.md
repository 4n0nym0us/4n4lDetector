<html>
<head>
<h1><a href="http://www.enelpc.com/p/4n4ldetector.html">4n4lDetector</a></h1>
<h2>Advanced static analysis tool</h2>
</head>
  <body>
4n4lDetector is an analysis tool for Microsoft Windows executable files, libraries, drivers and mdumps for x86 and x64. As of v1.8 an extended use for analyzing anomalies in Linux ELF executables was also included. Its main objective is to collect the necessary information to facilitate the identification of malicious code inside the analyzed files. This tool analyzes, among other things, the PE header and its structure, the content of the sections, the different types of strings, among many other things. It also incorporates a multitude of its own ideas to recognize anomalies in the construction of files and the detection of mechanisms used by current malware.<br>
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
       -> Options for modifying the title and content of the report<br>
       -> A viewer of the generated HTML code for display<br>
       -> A button to save the report to a document<br>
       -> Integrated a button to open the folder that houses all the saved reports<br>
  [+] Added the "-HTML" parameter for extracting reports in HTML format by console:<br>
       -> 4n4lDetector.exe Path\App.exe -HTML<br>
<h3>v1.7</h3>
  [+] Added new functionality to identify ASLR-enabled binaries.<br>
  [+] Fixed a bug that could lead to the application crashing in some binaries.<br>
  [+] Improved the integration of the debugger for reading the Entry Point of the x86 binaries.<br>
  [+] Smoothed out the design of the form interface and repositioning of controls.<br>
  [+] The process execution functionality is eliminated, although the possibility of analyzing MDUMPS is maintained.<br>
<h3>v1.6</h3>
  [+] Added new functionality to view the Entry Point code in ASM for x86 binary.<br>
  [+] Added combined rules for strings in hexadecimal and text, with multiple matches.<br>
      -> The end of the rule description field contains the rule number separated by "-" from the total number of rules belonging to the same combination.<br>
         Example: H:1A6C6488F2736988:Rich Signature Found 1-2<br>
         (Currently it only allows a maximum of 9 matches...) ;)<br>
<h3>v1.5 new revision for Enelpc_debugger</h3> 
  [+] Fixed a bug in the word search engine of the main interface.<br>
  [+] Changed the cleanup function that removes extraneous characters from the output.<br>
  [+] Added section name extraction.<br>
  [+] Added the option to select a dictionary of words and codes in hexadecimal to search in the binary in a personalized way.<br>
      -> "H" Defines the string in hexadecimal.<br>
      -> "T" Defines the string as text.<br>
      -> The last field separated by ":" is the description used in the 4n4lDetector output.<br>
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
       -> 4n4lDetector.exe Path\App.exe -GUI<br>
       -> 4n4lDetector.exe Path\App.exe -TXT<br>
       -> 4n4lDetector.exe Path\App.exe -GREMOVE (Deletion of the binary after its analysis)<br>
  </body>
</html>
