## 04 - Create data protection rule

1. Click hamburger icon -> click Governance -> click Rules 

<img width="1728" height="360" alt="image" src="https://github.com/user-attachments/assets/efa508f1-0725-4894-a7bf-395e9ee23fda" />

2. Click Add rule -> select New data protection rule -> set Name to "Masking personal data" -> set Business definition to "Implement data protection rule to comply with Indonesia PDPL" -> click Next button

<img width="1590" height="933" alt="image" src="https://github.com/user-attachments/assets/1a427f8f-9eb8-48c5-8551-b1ce0540b8c3" />

3. At section named "When does this rule apply?" modify the logic as below:

```
If Classification contains any Personal Data
```

5. At section named "What does this rule do?" modify the logic as below:

```
Redact columns when column has Classification That contains any Personal Data
```

7. Finish it by clicking Crate button

<img width="1590" height="933" alt="image" src="https://github.com/user-attachments/assets/453f0456-50c5-4933-b02a-d67f87d4c6ec" />
