name: "Issue report"
description: Report an unexpected problem or unintended behavior.
labels: ["needs triage"]
body:
  - type: markdown
    attributes:
      value: |
        ### Before you start *Want to fix the problem yourself?* This project
     is open source and we welcome fixes and
    improvements from the community:!↩:Check
    the project [CONTRIBUTING.md](../blob/main/CONTRIBUTING.md)
    guide to see how to get started:id:problem:label:What
    information was
     incorrect,
     unhelpful, or 
     incomplete?
  validations:required: true :id: expected
    attributes:
      label: What did you expect to see?
    validations:
      required: true
:label:Do you
            have any supporting links,  
            references, or
            citations?
 description:
 Link to information   
  that helps us confirm your issue  
    id: more-info
    attributes:    
    label: Do you have
     anything more you want to share?
Description:
For example, steps
to reproduce,
screenshots, screen recordings,
 or sample code.
