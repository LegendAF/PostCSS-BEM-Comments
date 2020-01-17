CSS Ruleset Comments
=====
This extension allows developers to automatically format their CSS files to have comments at the end of their css rulesets including the selector.
  
## Features
  
Press `CMD+Shift+P` then select `Format CSS Ruleset Comments`. 

## Extension Settings
  
"cssRuleSet.formatterEnable" : false,
  
    Use CSS Ruleset Comments as your default CSS formatter (this will take precedence over any other formatters).  
    Use this if you want to use format on save or just dont use other SCSS formatters.
    NOTE: If you enable this option, you must restart VSCode to use the native Format commands.  

"cssRuleSet.verboseSelectors" : true,  
  
    Concatenate nested selectors if true.
  
"cssRuleSet.includeMediaQueries" : false,  

    Include media query comments if true.  
