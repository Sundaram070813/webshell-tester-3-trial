# webshell-test3 trial
 web shell test
Web shell  is a cross platform stand-alone binary built solely for the purpose of identifying, decoding, and tagging files that are suspected to be web shells. The web shell analyzer is the bigger brother to the web shell scanner project (http://github.com/tstillz/webshell-scan), which only scans files via regex, no decoding or attribute analysis.

Disclaimer
The regex and its built-in decoding routines supplied with the scanner are not guaranteed to find every web shell on disk and maybe identify some false positives. It's also recommended you test the analyzer and assess its impact before running on production systems. The analyzer has no warranty, use as your own risk.

Features
Cross platform, statically compiled binary.
JSON output
Currently supports most PHP, ASP/X web shells. JSP/X, CFM and other types are in the works.
Recursive, multi-threaded scanning capable of iterating through nested directories quickly
Ability to handle multiple layers of obfuscated web shells such as base64, gzinflate and char code.
Supports PRE/POST actions which powers layered de-obfuscated and decoding for the analysis engine
Tunable regex logic with modular interfaces to easily extend the analyzers capabilities
Tunable attribute tagging
Raw content captures upon match
System Info.



.
