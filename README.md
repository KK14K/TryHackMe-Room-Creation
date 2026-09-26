# Smuggler's Paradise — TryHackMe Room

A TryHackMe room I designed and authored, teaching HTTP Request Smuggling through a
hands-on, guided walkthrough.

**Room link:** https://tryhackme.com/jr/testingscL

## Objective

Teaches learners how mismatched request parsing between a reverse proxy and a
backend server can be exploited to smuggle a hidden request past inspection —
ending in bypassing an admin panel via a crafted raw HTTP request.

## Key Concepts Covered

- HTTP protocol structure and behavior
- Content-Length vs. Transfer-Encoding parsing discrepancies
- HTTP Request Smuggling attack vectors
- Real-world impact: auth bypass, cache poisoning, data theft
- Manually crafting and sending raw HTTP requests (netcat)

## Room Structure

11 tasks, progressing from theory to hands-on exploitation:

1. Room Overview
2. Prerequisites (vulnerable Node.js server setup — AttackBox or local VM)
3. What is HTTP?
4. What is a Proxy and Backend Server?
5. What is HTTP Request Smuggling?
6. Reconnaissance (nmap, curl, whatweb)
7. Crafting an HTTP Request Smuggle
8. Exploit Vulnerability (reach `/admin`, retrieve flag)
9. Mitigation Techniques
10. Cleanup
11. Room Summary

Each task (aside from the intro/setup tasks) includes MCQs to reinforce the
concept before moving on.

## What This Repo Contains

- `smugglers-paradise-room-report.pdf` — full room report: design rationale, task
  breakdown, all questions/answers, and reflection on building it
- *(add here if included: `server.js` — the vulnerable Node.js server used in the room)*

> Note: the flag isn't reproduced here to keep the room intact for anyone who wants
> to attempt it — see the full report for the complete walkthrough.

## Why I Built This

HTTP Request Smuggling is a frequently misunderstood vulnerability class. This room
breaks it down for beginners using analogies (front-desk/manager for proxy/backend,
nested envelopes for smuggled requests) while still requiring hands-on exploitation
with real tools (netcat, nmap, curl) rather than just multiple-choice theory.