# FUTURE_CS_03
# API Security Risk Analysis – Cyber Security Task 3

## Overview
This project analyzes the security risks of a public API. The purpose is to identify possible vulnerabilities such as data exposure, missing authentication, and lack of rate limiting.

## API Tested
https://jsonplaceholder.typicode.com/users

## Tools Used
- Web Browser
- Browser Developer Tools
- Public Test API
- GitHub for documentation

## Scope
The analysis focuses on identifying potential security risks in publicly accessible API endpoints. The testing includes observing API responses and checking for authentication and data exposure issues.

## Methodology
1. Selected a public API endpoint for testing.
2. Sent a request to the API using a web browser.
3. Observed the API response data returned in JSON format.
4. Identified potential security risks such as public data exposure.
5. Documented the risks, impacts, and recommended solutions.

## Identified Risks
- Public data accessible without authentication.
- No visible rate limiting.
- Possible data exposure.

## Risk Severity
Medium

## Business Impact
If sensitive data is exposed through APIs without authentication, attackers may collect user information which could lead to privacy issues and data misuse.

## Remediation Suggestions
- Implement authentication mechanisms such as API keys or tokens.
- Apply rate limiting to prevent abuse.
- Restrict access to sensitive endpoints.
- Validate all API inputs.

## Evidence
Screenshots of API requests and responses are provided in the screenshots folder.
