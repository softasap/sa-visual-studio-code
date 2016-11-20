sa-visual-studio-code
=====================

[![Build Status](https://travis-ci.org/softasap/sa-visual-studio-code.svg?branch=master)](https://travis-ci.org/softasap/sa-visual-studio-code)

You could benefit from this editor, if you use to develop with .net core for linux.
See also  https://github.com/softasap/sa-mono-aspnet



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

Copyright - Vyacheslav Voronenko

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
