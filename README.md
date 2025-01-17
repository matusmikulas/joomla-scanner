# joomla-scanner

Development version of scanning tool for Joomla extensions. 

Tool will consist of two types of scans:
- **light scan**
- **full scan**

**Light scan** - download the index file and look for all the extensions subtypes: {components, modules, packages, extensions, plugins, libraries, languages} and based on common patterns try to detect the versions of these subtypes. Lightscan also follow redirects in case of some wild implementation where extension subtypes .xml files are stored somwhere else. 

**Full scan** - invasive type of scanner which is going to use knwoledge-base which contains all the specific extensions installation files. This was retrieved by installing hundreds of extensions and extracting all the installed files. 
