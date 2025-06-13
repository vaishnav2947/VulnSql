# SQL Injection Vulnerability Lab

## Overview

This project is an educational, interactive SQL Injection vulnerability lab designed to help learners explore advanced SQL injection attack techniques in a safe environment without a real backend. It covers three key challenges:

1. **Basic SQL Injection (Login Bypass):** Exploit simple tautology injection to bypass authentication.
2. **Union-Based SQL Injection:** Extract data from multiple tables via UNION SELECT injection.
3. **Blind SQL Injection:** Infer secret information bit-by-bit through Boolean and time-based injections.

The lab simulates vulnerable backend logic using JavaScript in a single static HTML page (`index.html`), enabling hands-on practice of SQLi concepts directly in the browser.

## Features

- Realistic, vulnerable SQL query simulation without backend dependencies.
- Interactive forms for practicing injection payloads.
- Informative hints guiding thoughtful exploration.
- Clean, modern, responsive UI focused on usability and learning.
- Accessible design with semantic HTML and ARIA attributes.

## How to Use

### Locally

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Explore the three challenges via the navigation links at the top.
4. Follow hints and experiment with injection payloads in each form.
5. Observe simulated "database" responses to understand how injections affect queries.

## Learning Outcomes

After completing this lab, you will be able to:

- Recognize common SQL injection vulnerabilities in web applications.
- Understand how SQL injection attacks work on different query types.
- Craft injection payloads for bypassing authentication and extracting data.
- Appreciate the importance of defensive programming against SQL injection.
- Gain practical problem-solving experience with real-world inspired challenges.

## Disclaimer

This lab is for educational and ethical learning purposes only. Do NOT use these techniques on unauthorized systems or in a malicious manner.

## License

This project is provided as-is under the MIT License.

---

Happy hacking and learning!

---

# Contact

For questions or feedback, open an issue on the repository or contact the maintainer.

