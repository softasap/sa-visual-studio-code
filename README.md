sa-visual-studio-code
=====================

[![Build Status](https://travis-ci.org/softasap/sa-visual-studio-code.svg?branch=master)](https://travis-ci.org/softasap/sa-visual-studio-code)

You could benefit from this editor, if you use to develop with .net core for linux.
See also  https://github.com/softasap/sa-mono-aspnet

Suggested extensions:

christian-kohler.npm-intellisense https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense
christian-kohler.path-intellisense https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
waderyan.gitblame https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame
alefragnani.Bookmarks https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks
ms-vscode.atom-keybindings https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings


Simple:

```YAML


     - {
         role: "sa-visual-studio-code"
       }

```


Advanced:

```YAML


    - {
        role: "sa-visual-studio-code",
        vs_code_packages: ["donjayamanne.python", "robertohuertasm.vscode-icons", "dbaeumer.vscode-eslint", "dbaeumer.jshint", "eg2.tslint", "EditorConfig.EditorConfig", "ms-vscode.mono-debug", "PeterJausovec.vscode-docker"]        
      }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)
