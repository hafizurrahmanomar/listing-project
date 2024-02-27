At first environment setup for laravael code run
___

```jason
{
  // For Laragon setting
  "php.validate.executablePath": "C:\\laragon\\bin\\php\\php-8.110-Win32-vs16-x64\\php.exe",
  "artisan.php.location": "C:\\laragon\\bin\\php\\php-8.110-Win32-vs16-x64\\php.exe",
  "git.path": "C:\\laragon\\bin\\git\\bin\\git.exe",

  "terminal.integrated.profiles.windows": {
    "laragon": {
      "path": "${env:windir}\\System32\\cmd.exe",
      "args": ["/k", "C:\\laragon\\bin\\cmder\\vendor\\bin\\vscode_init.cmd"]
    }
  },

  "terminal.integrated.defaultProfile.windows": "laragon",
  
```
