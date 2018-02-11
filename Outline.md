# Thesis outline
----
## Sections
1. Introduction to operating systems & operating system security
2. Why operating security is important
3. Methods of securing operating systems
4. Effects of user-level software and hardware on operating system security
5. Case study of various operating system exploits/vulnerabilities
6. Analysis of current research and innovations in operating system security
7. Conclusion

## 1. Introduction to Operating Systems and Operating System Security
This section should give a brief history of operating systems and how security has factored into the development of them.

## 2. Why Operating System Security is Important
This section should outline the impact of operating system security on users, businesses, governments, and other relevant entities.

Possible examples:
	1. WannaCry (EternalBlue)
	2. Petya

## 3. Effects of User-Level Software and Hardware on Operating System Security
This section should discuss:

1. How user-level software and permissions associated with them impact the design of operating systems
2. How hardware affects operating system security (talk about Meltdown/Spectre & Intel ME here?)

## 4. Methods of Securing Operating Systems
This section will discuss:

1. Various researched areas of operating system security
	1. Address Space Layout Randomization
	2. Permissions/Capabilities
	3. Fault Tolerance
	4. Stack Protection
	5. Memory Protection
	6. Rings
	7. Formalization
2. How they are applied to the operating system during development
3. What exploit/vulnerability they are meant to protect against
4. Any problems associated with them

## 5. Case Study of Various Operating System Exploits/Vulnerabilities
This section presents:

1. Many different exploits/vulnerabilities in different operating systems (Windows, Linux (+ Android)/Unix, and macOS)
2. Description of the exploit/vulnerability
3. The severity
4. How the exploit/vulnerabilities were discovered
5. The amount of devices affected if applicable
6. What was done to patch the exploit/vulnerability, with code & discussion of it if possible

Picks:

1. Dirty CoW
2. 

## 6. Analysis of Current Research and Innovations in Operating System Security
This section discusses:

1. Recent literature on the topic of operating system security
2. Innovations in programming languages/tools
3. Examples of them in practice (RedoxOS/TockOS?) 

## 7. Conclusion
Wrap up everything