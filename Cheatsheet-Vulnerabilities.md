# Most commun web app vulnerabilities <br>
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
