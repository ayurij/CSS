from Bootstrap 5 - first look: https://youtu.be/I7CfaDYzTVM    
using scss for Bootstrap customization  
Traversy Media youtube channel: https://www.youtube.com/c/TraversyMedia/featured

### development

1. npm

        npm init -y      
        npm install bootstrap@5.0.0  
        npm install bootstrap-icon  
        npm install popper.js   <-- hasn't been used  

2. VSCode: plugin Live Sass Compiler, https://github.com/ritwickdey/vscode-live-sass-compiler,  
from VSCode settings.json:

        "liveSassCompile.settings.formats": [  
            {  
                "format": "compressed",  
                "extensionName": ".css",  
                "savePath": "/dist/css",  
            }  
        ],
        "liveSassCompile.settings.autoprefix": [],
        "liveSassCompile.settings.generateMap": false,
        "liveSassCompile.settings.excludeList": [
            "**/node_modules/**",
            ".vscode/**"
        ]


### setup

    npm i


