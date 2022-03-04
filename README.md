# sagemaker
sagemaker


```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    Note right of iframe: hoge \n fuga
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
