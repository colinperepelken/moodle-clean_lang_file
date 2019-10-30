# Clean Moodle Plugin Language Files  
Cleans a Moodle plugin language file of unused language strings.  

Given the absolute path to the Moodle plugin, this script will find all files within the plugin directory
of types .js, .php, and .mustache. If a file of that type contains the language string identifier, the 
language string will remain. Otherwise it will be removed.  

Any comments or non-language strings will be removed.  

## Installation  
Replace *YOUR_USERNAME* with your Bitbucket username.  
```
pip3 install git+https://YOUR_USERNAME@bitbucket.org/lingeldevau/clean_lang_file.git
```

## Usage  
Run the below command to verify your installation, and view the usage instructions for the script.  
```
clean_lang_file --help
```

## Uninstall
```
pip3 uninstall clean_lang_file
```