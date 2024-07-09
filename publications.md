---
layout: default
---

## Welcome to another page

<div class="mermaid">
%%{init: { 'logLevel': 'debug', 'theme': 'forest', 'themeVariables': {
              'tagLabelFontSize': '16px',
              'commitLabelFontSize': '16px'
       }, 'gitGraph': {'showBranches': true, 'showCommitLabel':true,'mainBranchName': 'Career'}} }%%
      gitGraph TB:
        commit id:"Training as an IT specialist for application development"
        branch Study
        commit id:"Bachelor of Science Business Informatics"
        checkout Career
        commit id:"Junior Software Developer"
        checkout Study
        commit id:"Master of Science Computer Science"
        checkout Career
        commit id:"Software Engineer"
        merge Study
        commit id:"Research Associate HAPTIK"
        checkout Study
        commit id:"PhD Student"
        checkout Career
        commit id:"Tech Lead Startup @ HAPTIK"
        commit id:"Research Associate TiPP"
        branch SideGigs
        commit id:"Software Engineer @ datenschmiede.ai"              
</div>

[back](./)
