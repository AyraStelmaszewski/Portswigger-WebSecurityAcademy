# Most common web app vulnerabilities <br>
In this series, I'll break down several common web application security flaws using plain language, devoid of practical examples, focusing solely on theoretical explanations. <br>
From SQL injection to cross-site scripting, we'll explore these vulnerabilities to enhance understanding without diving into practical exploitation.

========================================================================
## Horizontal privilege escalation
Horizontal privilege escalation occurs if a user is able to gain access to resources belonging to another user, instead of their own resources of that type. <br>
For example, if an employee can access the records of other employees as well as their own, then this is horizontal privilege escalation. <br>
Horizontal privilege escalation attacks may use similar types of exploit methods to vertical privilege escalation.

## Vertical privilege esccalation 
If the attacker targets an administrative user and compromises their account, then they can gain administrative access and so perform vertical privilege escalation. 

## Authentication vulnerabilities
Authentication vulnerabilities occurs when an attacker try to bypass permissions who determineprocess of verifying that a user is who they claim to be.

## Authorization vulnerabilities
Authorization vulnerabilities occurs when an attacker try to bypass permissions who determine what they are authorized to do. For example, they may be authorized to access personal information about other users, or perform actions such as deleting another user's account. 

## Server-side request forgery
Server-side request forgery is a web security vulnerability that allows an attacker to cause the server-side application to make requests to an unintended location. <br>
In a typical SSRF attack, the attacker might cause the server to make a connection to internal-only services within the organization's infrastructure. <br> In other cases, they may be able to force the server to connect to arbitrary external systems. 

## File upload vulnerabilities
File upload vulnerabilities are when a web server allows users to upload files to its filesystem without sufficiently validating things like their name, type, contents, or size.

## Command injection 
A command injection permits the execution of arbitrary operating system commands by an attacker on the server hosting an application. <br> As a result, the application and all its data can be fully compromised. <br> The execution of these commands typically allows the attacker to gain unauthorized access or control over the application's environment and underlying system.

## SQL Injection 
SQL injection (SQLi) is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. This can allow an attacker to view data that they are not normally able to retrieve.

## Mass assignment vulnerabilities
Mass assignment (also known as auto-binding) can inadvertently create hidden parameters. It occurs when software frameworks automatically bind request parameters to fields on an internal object. Mass assignment may therefore result in the application supporting parameters that were never intended to be processed by the developer.

## Server-side parameter pollution
Some systems contain internal APIs that aren't directly accessible from the internet. Server-side parameter pollution occurs when a website embeds user input in a server-side request to an internal API without adequate encoding.



