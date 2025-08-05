**Elevate Labs Internship - Task 2: Phishing Email Analysis**
Objective
This repository contains the deliverables for Task 2 of the Elevate Labs Cybersecurity Internship. The objective of this task was to analyze a suspicious email sample, identify its phishing characteristics, and produce a report summarizing the findings.

Methodology
To complete this task, I followed a systematic approach based on the mini-guide provided in the assignment:

Obtained a Sample Phishing Email: I sourced a realistic phishing email sample to serve as the subject of the analysis.

Examined Sender Details: The sender's email address and domain were closely inspected for signs of spoofing or impersonation.

Analyzed Email Headers: The email headers were extracted and analyzed using an online header analyzer to uncover discrepancies in the email's origin and path.

Inspected Links and Attachments: I checked for suspicious links and attachments, paying close attention to any mismatched URLs between the display text and the actual destination.

Identified Social Engineering Tactics: The email body was reviewed for urgent language, threats, and other psychological triggers designed to pressure the recipient.

Checked for Errors: The email's content was checked for grammatical and spelling errors, which are common indicators of a fraudulent message.

Documented Findings: All identified phishing traits and indicators were documented to form a comprehensive analysis report.

Findings: Phishing Indicators Report
Based on the analysis of the sample email, the following phishing characteristics were identified:

Sender Spoofing: The sender's email address (amazon-security@billing-update.com) was clearly not from a legitimate Amazon domain (amazon.com). This is a classic example of email spoofing designed to trick the recipient into believing the email is from a trusted source.

Urgent and Threatening Language: The subject line, Urgent: Your Amazon Account Is Suspended!, and the email body, which threatened "permanent deactivation" if no action was taken, created a false sense of urgency. This is a key social engineering tactic to bypass critical thinking.

Generic Greeting: The email began with a generic "Dear Customer" greeting instead of using my personal name. Legitimate companies typically use a personalized greeting when communicating with account holders.

Mismatched URL: The visible hyperlink text, "Click Here to Verify Your Account," appeared to lead to a legitimate Amazon page. However, upon inspection, the actual URL linked to a different, malicious domain (http://amazon.secure-verify-account.net/login). This is the most direct attempt to steal user credentials.

Tools Used
Sample Phishing Email: A publicly available, non-malicious sample email for educational purposes.

Online Email Header Analyzer: A free online tool used to parse and interpret the email's headers.

Key Learnings
This task reinforced my understanding of common phishing tactics and the importance of a multi-faceted approach to email threat analysis. I gained practical experience in identifying key indicators beyond just the sender's name, such as analyzing email headers and inspecting the true destination of hyperlinks. This skill is fundamental to my career as a cybersecurity aspirant.
