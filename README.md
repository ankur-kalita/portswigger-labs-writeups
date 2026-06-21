# PortSwigger Web Security Academy — Technical Writeups

Technical security writeups for PortSwigger Web Security Academy labs, completed as part of the **Application Security** course.

Each writeup follows a standard structure: **Title of Issue · Description · Steps to Exploit · Proof of Concept · Impact · Mitigation / Remediation · CVSS Score · CVSS Justification**.

## Index

| # | Writeup | Category | Difficulty |
|---|---------|----------|-----------|
| 01 | [SQL injection — retrieval of hidden data](01_SQLi_Hidden_Data_Retrieval.pdf) | SQL Injection | Apprentice |
| 02 | [SQL injection — login bypass](02_SQLi_Login_Bypass.pdf) | SQL Injection | Apprentice |
| 03 | [OS command injection — simple case](03_CMDi_Simple_Case.pdf) | Command Injection | Apprentice |
| 04 | [Blind OS command injection — time delays](04_CMDi_Blind_Time_Delay.pdf) | Command Injection | Practitioner |
| 05 | [XXE — file retrieval](05_XXE_File_Retrieval.pdf) | XXE Injection | Apprentice |
| 06 | [XXE — SSRF via XXE](06_XXE_SSRF.pdf) | XXE Injection | Apprentice |
| 07 | [SSTI — basic (ERB)](07_SSTI_Basic_ERB.pdf) | Server-Side Template Injection | Practitioner |
| 08 | [SSTI — code context (Tornado)](08_SSTI_Code_Context_Tornado.pdf) | Server-Side Template Injection | Practitioner |
| 09 | [Reflected XSS](09_XSS_Reflected.pdf) | Cross-Site Scripting | Apprentice |
| 10 | [Stored XSS](10_XSS_Stored.pdf) | Cross-Site Scripting | Apprentice |
| 11 | [CSRF — no defenses](11_CSRF_No_Defenses.pdf) | CSRF | Apprentice |
| 12 | [CSRF — method-based bypass](12_CSRF_Method_Bypass.pdf) | CSRF | Practitioner |
| 13 | [Username enumeration via different responses](13_Auth_Username_Enumeration.pdf) | Authentication | Apprentice |
| 14 | [2FA bypass](14_Auth_2FA_Bypass.pdf) | Authentication | Practitioner |
| 15 | [JWT — unverified signature](15_JWT_Unverified_Signature.pdf) | JWT | Apprentice |
| 16 | [JWT — flawed signature (none algorithm)](16_JWT_None_Algorithm.pdf) | JWT | Apprentice |
| 17 | [Access control — unprotected admin panel](17_AC_Unprotected_Admin_Panel.pdf) | Access Control | Apprentice |
| 18 | [Access control — admin URL disclosed in JS](18_AC_Admin_URL_in_JS.pdf) | Access Control | Apprentice |
| 19 | [API — exposed documentation](19_API_Exposed_Documentation.pdf) | API Testing | Apprentice |
| 20 | [API — unused PATCH endpoint](20_API_Unused_PATCH_Endpoint.pdf) | API Testing | Practitioner |
| 21 | [Business logic — client-side price manipulation](21_BizLogic_ClientSide_Price.pdf) | Business Logic | Apprentice |
| 22 | [Business logic — negative quantity](22_BizLogic_Negative_Quantity.pdf) | Business Logic | Apprentice |
| 23 | [SSRF — against the local server](23_SSRF_Local_Server.pdf) | SSRF | Apprentice |
| 24 | [SSRF — against the back-end network](24_SSRF_Backend_Network.pdf) | SSRF | Practitioner |

## Categories covered

SQL Injection · OS Command Injection · XXE Injection · Server-Side Template Injection · Cross-Site Scripting · CSRF · Authentication · JWT · Access Control · API Testing · Business Logic · SSRF

---

*Educational security research conducted against PortSwigger Web Security Academy's intentionally vulnerable lab environments.*
