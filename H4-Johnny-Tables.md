# Johnny Tables
## x) Read and Summarize 
# OWASP Top 10 

The OWASP Top 10 is a list of the most serious security risks in web applications. Fixing these issues helps developers and security teams protect websites from hackers.

## 1. Broken Access Control (A01:2021)
- **Biggest security risk now.**
- Happens when users can access **admin panels or data they shouldn't**.

### Examples:
- Regular users get **admin access**.
- Someone **views or changes** other people’s data.

### How to Prevent It:
- Check **permissions on the server side** (not just in the browser).
- Use a **default-deny rule** (block access unless allowed).
- Add **multi-factor authentication** (extra login security).

---

## 2. Security Misconfiguration (A05:2021)
- Happens when systems are **set up poorly**, making them easy targets.

### Examples:
- **Unprotected files and directories**.
- **Default passwords** left unchanged.
- **Old, outdated software**.

### How to Prevent It:
- **Regularly check** security settings.
- Remove **unneeded features and accounts**.
- Keep **software updated** with patches.

---

## 3. Vulnerable & Outdated Components (A06:2021)
- Using **old or weak software** parts can let hackers in.

### Examples:
- Using an **old library or framework** with known weaknesses.
- **Big security flaws** like the **Heartbleed bug in OpenSSL**.

### How to Prevent It:
- Keep an **updated list** of all software used.
- Use **security tools** to check for vulnerabilities.
- Download components from **trusted sources** and update them often.

---

## 4. Injection Attacks (A03:2021)
- Hackers insert **bad data** into a website’s database or commands.

### Examples:
- **SQL injection:** A hacker tricks a database into revealing information.
- **Command injection:** Running harmful system commands.
- **LDAP injection:** Bypassing login or stealing user details.

### How to Prevent It:
- Use **prepared statements** in databases.
- Escape **special characters** to prevent code execution.
- Only allow **approved input** (whitelist validation).

---

By understanding and fixing these problems, developers can make web applications much safer from cyber attacks.
