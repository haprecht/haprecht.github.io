---
layout: default
---

## Welcome to another page


<div class="mermaid">
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'themeVariables': {
              'commitLabelFontSize': '16px'
       }, 'gitGraph': {'showBranches': true, 'showCommitLabel':true,'mainBranchName': 'test'}} }%%
      gitGraph TB:
        commit id:"NewYork"
        commit id:"Dallas"
        branch MetroLine2
        commit id:"LosAngeles"
        commit id:"Chicago"
        commit id:"Houston"
        branch MetroLine3
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
