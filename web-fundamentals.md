# Web Fundamentals

## Objective
The purpose of this room was to understand how web technologies function, including how websites are delivered, how browsers interact with servers, and how web communication works. This knowledge is essential in ethical hacking, as many attacks target web applications.

---

## How the Web Works
Web applications operate on a client-server model, where a client (browser) sends requests to a server, and the server responds with the requested resources.
In ethical hacking, understanding this interaction is critical. Attackers analyze how requests are made and how servers respond in order to identify weaknesses such as improper input handling or misconfigured endpoints.

---

## HTTP Requests and Responses
HTTP is the protocol used for communication between clients and web servers. A client sends a request, and the server returns a response containing data such as HTML, JSON, or other resources.
From an ethical hacking perspective, HTTP requests are a primary attack surface. Attackers manipulate requests to test how applications handle input, often leading to vulnerabilities such as injection attacks or authentication bypasses.

---

## URLs and Parameters
A URL specifies the location of a resource on the web and may include parameters used to pass data to the server.


In ethical hacking, URL parameters are commonly tested for vulnerabilities. Attackers may modify parameters to access unauthorized data or exploit weaknesses such as insecure direct object references (IDOR).

---

## Status Codes
HTTP responses include status codes that indicate the result of a request.
Understanding status codes helps ethical hackers identify how an application behaves. For example, different responses may reveal valid endpoints, hidden resources, or server misconfigurations.

---

## Cookies and Sessions
Cookies are used to store data on the client side, often related to session management and authentication.
In ethical hacking, cookies are critical because they may contain session identifiers. If improperly secured, attackers can exploit them through session hijacking or replay attacks to gain unauthorized access.

---

## Practical Relevance to Ethical Hacking
The concepts covered in this room are directly applicable to web application security testing.

Understanding web fundamentals allows an ethical hacker to
- Intercept and modify HTTP requests
- Identify vulnerable input fields
- Analyze authentication mechanisms
- Discover exposed endpoints and resources

---

## Conclusion
This room provided a foundational understanding of how web applications function. These concepts are essential for identifying and exploiting web-based vulnerabilities, making them a critical part of ethical hacking and penetration testing.
