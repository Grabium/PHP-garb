# PHP-GARB
Welcome to the php-garb. 
PHP-Garb is a script that enable mananger garbage files through alias of directies.
The developer can make a backup (save function) and after generate a lot resdue, call a folder cleaning (clear function) deleting only files not saved on backup.
**************
## Download
You can get'it of 2 way:
 1. [Download scrit from Github](#DownloadCodeFromGithub)
 2. [Using Composer](#UsingComposer)

<div id='DownloadCodeFromGithub'/>

 ### Dowload Code From GitHub
 * **Download:** Try the link [https://github.com/Grabium/PHP-GARB](https://github.com/Grabium/PHP-GARB/) and go to `code`/`download zip`. Continue reading [Optmize](#Optmize)
<div id='UsingComposer'/>
  
### Using Composer
* **Install Composer:** It's possible to get information on the [getcomposer.org/download/](https://getcomposer.org/download/)
* **Require:** Use the command on Shell terminal: `composer require php-garb/php-garb` .
*  **Move script to root** You must move the file `garb.php` and folder `Garb` to the root of you project. It will be located at `vendor/garb-php/garb-php/`.
*******************
<div id='Optmize'/>
 
## Optmize
On the root directory rename garb.php to garb (without extenssion) for decrease command text on shell terminal.

## How use functions
Alias is the backup name that refer to directory that will be handled. All operations use it.

### 1 - Help
Get informations about commands, arguments and other details, locate the terminal in the same local of garb (garb.php) and try: `php garb` or `php garb help`