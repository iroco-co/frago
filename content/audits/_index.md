---
title: Services numériques
outputs:
  - html
  - json
disableKinds:
  - RSS
  - taxonomy
  - taxonomyTerm
cascade:
- _target:
    path: /audits/**/index.md
  outputs:
    - html
    - json
    - declaration
    - declarationpage
    - accessibility
    - ecoconception
    - publishing
    - quality
    - recommendation
    - performance
    - accessibilitypage
    - ecoconceptionpage
    - publishingpage
    - qualitypage
    - recommendationpage
    - performancepage
- _target:
    path: /audits/**/_index.md
  outputs:
    - html
    - json
    - declaration
    - declarationpage
- _target:
    path: /audits/_index.md
  outputs:
    - html
    - json
    - declaration
    - accessibility
    - ecoconception
    - publishing
    - quality
    - recommendation
    - performance
    - accessibilitypage
    - ecoconceptionpage
    - publishingpage
    - qualitypage
    - recommendationpage
    - performancepage
- _target:
    path: /audits/index.md
  type: "audits"
---
