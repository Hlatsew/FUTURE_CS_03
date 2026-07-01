Future_CS_03_API_SECURITY


Overview

This repository contains the deliverables for cyber security task 2 (2026) by the task involved performing a read-only API security analysis on the JSONPlaceholder API by identifying common risks and recommending remediation steps with the OWASP API security Top 10.

objectives

1. Analyse demo/public API endpoints
2. Identify security risks
3. classify risk severity ( low/ meium/ high)
4. Explain business impact in clear language
5. suggest actionable remediation steps
6. document findings in a professional report

ToolS Used

1. postman (https://www.postman.com) for API requests and header inspection
2. Browser DevTools for response validation and header analysis
3. Ms word for report drafting and formatting

API Tested

JSONPlaceholder (Test API)
https://jsonplaceholder.typicode.com

Endpoints analyzed:
1. /posts
2. /users
3. /users/1

Deliverables

1. Report - API-Security Risk Analysis pdf
2. Evidence - postman requests and hearder inspections
3. README.md - summary

Key Findings

1.open endpoints - no authentication requied (High risk)
2. Excessive data exposure - user emails and gwo coordinates (Medium risk)
3. Broken access control - direct object access possible (High risk)
4, Missing security headers - weak security controls (Low risk)

Buisness impact

1. privacy violation and phishing risks
2. Location tracking and profiling threats
3. Reduced customer yrust and reputational damage
4. potential misuse of exposed data by malicious actors

Recommendations

1. implement API key
2. Apply role-based access control
3. limit response fields to necessary data only
4. Add rate limiting to prevent abuse

   
