---
"aywson": patch
---

Fixed: Resolved an issue where the replace method ignored fields containing empty objects ({}) or objects containing only keys with undefined values ({ key: undefined }). These fields are now correctly overwritten as intended.