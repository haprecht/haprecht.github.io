---
layout: default
---

## Welcome to another page

<div class="mermaid">
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'themeVariables': {
              'tagLabelFontSize': '16px',
              'commitLabelFontSize': '16px'
       }, 'gitGraph': {'showBranches': true, 'showCommitLabel':true,'mainBranchName': 'Career'}} }%%
      gitGraph TB:
        commit id:"Training as an IT specialist for application development"
        branch Study
        commit id:"Bachelor of Science Business Informatics"
        checkout Career        
        commit id:"Junior Software Engineer"
        checkout Study
        commit id: "Master of Science Computer Science"
        checkout Career
        commit id:"Software Engineer"
        merge Study
        commit id:"Phoenix"
        commit type: HIGHLIGHT id:"Denver"
        commit id:"Boston"
        checkout MetroLine1
        commit id:"Atlanta"
        merge MetroLine3
        commit id:"Miami"
        commit id:"Washington"
        merge MetroLine2 tag:"MY JUNCTION"
        commit id:"Boston"
        commit id:"Detroit"
        commit type:REVERSE id:"SanFrancisco"
</div>

[back](./)
