# Smuggler's Paradise — TryHackMe Room

A TryHackMe room I designed and authored, teaching **HTTP Request Smuggling** through a hands-on, guided walkthrough.

**Room link:** [https://tryhackme.com](https://tryhackme.com)

---

## Objective
Teaches learners how mismatched request parsing between a reverse proxy and a backend server can be exploited to smuggle a hidden request past inspection—ending in bypassing an admin panel via a crafted raw HTTP request.

## Key Concepts Covered
* **HTTP Protocol:** Structure and behavior.
* **Discrepancies:** Content-Length vs. Transfer-Encoding parsing.
* **Attack Vectors:** HTTP Request Smuggling methodologies.
* **Real-World Impact:** Auth bypass, cache poisoning, and data theft.
* **Exploitation:** Manually crafting and sending raw HTTP requests using `netcat`.

---

## Room Structure
The room consists of **11 tasks**, progressing smoothly from theory to hands-on exploitation:

1. **Room Overview**
2. **Prerequisites** (vulnerable Node.js server setup — AttackBox or local VM)
3. **What is HTTP?**
4. **What is a Proxy and Backend Server?**
5. **What is HTTP Request Smuggling?**
6. **Reconnaissance** (`nmap`, `curl`, `whatweb`)
7. **Crafting an HTTP Request Smuggle**
8. **Exploit Vulnerability** (reach `/admin`, retrieve flag)
9. **Mitigation Techniques**
10. **Cleanup**
11. **Room Summary**

> *Note: Each task (aside from the intro/setup tasks) includes MCQs to reinforce the concepts before moving on.*

---

## What This Repo Contains
* `smugglers-paradise-room-report.pdf` — Full room report: design rationale, task breakdown, all questions/answers, and reflection on building it.
* `server.js` — The vulnerable Node.js server used in the room.

> *Note: The flag is not reproduced here to keep the room intact for anyone who wants to attempt it. See the full report for the complete walkthrough.*

---

## Why I Built This
HTTP Request Smuggling is a frequently misunderstood vulnerability class. This room breaks it down for beginners using clear analogies (like a front-desk/manager setup for proxy/backend, or nested envelopes for smuggled requests) while still requiring hands-on exploitation with real tools (`netcat`, `nmap`, `curl`) rather than just multiple-choice theory.
