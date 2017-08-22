# Homestead Wordpress Generator

Tools to generate and remove Homestead projects. Supports UNIX based OS's.

## Requirements

 - Homestead and its requirements: https://laravel.com/docs/5.4/homestead
 - Node, NPM (Yarn)
   - Node: https://nodejs.org/
   - NPM: https://www.npmjs.com/
   - Yarn: https://yarnpkg.com/
 - Composer: https://getcomposer.org/

## Installation
Clone this repo to a folder (for example ~/workspace/homestead-wp-generator).
Continue to the next step by your OS.

### Linux
```
echo "PATH=$PATH:~[folder the repo is in]/bin" >> ~/.bashrc
```

### Mac
```
echo "[folder the repo is in]/bin" | sudo tee -a /etc/paths
```

## Optional
All the default plugins and the repo can be found on the top of the script itself. You can change these if needed.

## Possible issues
  codesniffer requires php-simplexml  
Try `apt install php-xml`. Now you should have PHP-simplexml installed.

## Honorable mentions
This script was inspired and started from this thread's starting post:  
https://laracasts.com/discuss/channels/tips/automatically-create-new-project-in-homestead-20  
  
Jenkins Job creation adjusted from this repo  
https://github.com/adampats/bash

## License
Can be found in the LICENSE file.
