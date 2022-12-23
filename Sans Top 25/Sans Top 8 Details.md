# SANS Top 8

The SANS Top 25 is a list of the most critical security weaknesses that organizations should address in order to protect themselves from cyber threats. These vulnerabilities, if left unaddressed, can lead to significant data breaches, financial losses, and reputational damage.

1. ### Injection
Injection vulnerabilities occur when an attacker is able to send malicious input to an application, which is then executed as a command or query. This can allow the attacker to access sensitive data or take control of a system. Common types of injection vulnerabilities include SQL injection, where an attacker can execute malicious SQL commands, and command injection, where an attacker can execute commands on the underlying operating system.

2. ### Broken authentication and session management
Authentication refers to the process of verifying the identity of a user or system, while session management refers to the process of tracking a user's activity during a session. Weaknesses in authentication and session management can allow attackers to gain unauthorized access to a system or to take over a user's session. This can occur through the use of weak passwords, the reuse of passwords, the lack of proper password hashing, or the failure to properly terminate a user's session after they have logged out.

3. ### Cross-site scripting (XSS)
Cross-site scripting (XSS) vulnerabilities occur when an attacker is able to inject malicious code into a website, which is then executed by a victim's web browser. This can allow the attacker to steal sensitive information, such as login credentials or financial data, or to perform other malicious actions on behalf of the victim. XSS vulnerabilities can occur when an application fails to properly sanitize user input or when it includes user input in the output of a page without proper encoding.

4. ### Insecure direct object references
Insecure direct object references occur when an application exposes a reference to an internal object, such as a file or database record, without proper authorization checks. This can allow an attacker to access sensitive data or to perform unauthorized actions. To prevent insecure direct object references, it is important to ensure that proper authorization checks are in place and that internal objects are not exposed directly to users.

5. ### Security misconfiguration
Security misconfiguration occurs when an application or system is improperly configured, leading to vulnerabilities that can be exploited by attackers. This can include the use of default or weak passwords, the exposure of unnecessary ports or services, or the lack of proper access controls. To prevent security misconfiguration, it is important to properly configure systems and applications and to follow best practices for securing them.

6. ### Sensitive data discovery
Sensitive data discovery refers to the process of finding and accessing sensitive data, such as financial or personal information, that is stored on a system. This can occur through the use of unsecured storage locations, the exposure of sensitive data through web application interfaces, or the lack of proper access controls. To prevent sensitive data discovery, it is important to properly secure data storage locations and to implement proper access controls.

7. ### Cross-site request forgery (CSRF)
Cross-site request forgery (CSRF) vulnerabilities occur when an attacker is able to trick a victim into making an unintended request to a website. This can allow the attacker to perform actions on behalf of the victim, such as changing their password or making a purchase. To prevent CSRF vulnerabilities, it is important to implement proper protection measures, such as CSRF tokens, on all forms and actions that are sensitive or that have a significant impact.

8. ### Using components with known vulnerabilities
Using components with known vulnerabilities refers to the use of third-party libraries or frameworks that have known vulnerabilities that have not been properly addressed. These vulnerabilities can be exploited by attackers to gain access to a system or to perform other malicious actions. To prevent this, it is important to regularly update components and libraries to the latest versions and to ensure that any known vulnerabilities have been properly addressed.