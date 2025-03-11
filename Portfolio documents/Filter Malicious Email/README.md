# Filtering Malicious Emails to Find If They Are Real or Fake

## Scenario: 
You’re a security analyst at an investment firm called **Imaginary Bank**.

An executive at the firm recently received a spear phishing email that appears to come from the board of Imaginary Bank.  
**Spear phishing** is a malicious email attack targeting a specific user or group of users, appearing to originate from a trusted source.

In this case, the executive is being asked to install new collaboration software, **ExecuTalk**.

The executive suspects this email might be a phishing attempt because **ExecuTalk** was never mentioned during the last board meeting.  
They've forwarded the message to your team to verify if it’s legitimate.  
Your supervisor has tasked you with investigating the message and determining whether it should be quarantined.

---

### Email Details:

- **From:** imaginarybank@gmail.org
- **Sent:** Saturday, December 21, 2019 15:05:05
- **To:** cfo@imaginarybank.com
- **Subject:** RE: You are been added to an ecsecutiv's groups

---

### Email Body:

Conglaturations! You have been added to a collaboration group ‘Execs.’

Downlode ExecuTalk to your computer.

Mac® | Windows® | Android™

You're team needs you! This invitation will expire in 48 hours so act quickly.

Sincerely,
ExecuTalk©
All rights reserved.

markdown
Copy

---

## Analysis:

When analyzing the above email, the following can be deduced:

1. **Email Sender’s Legitimacy:**  
   The email is sent from a source whose address seems legitimate (`imaginarybank@gmail.org`), but that can easily be spoofed in phishing attacks.

2. **Subject/Title Issues:**  
   The subject line, **"You are been added to an ecsecutiv's groups"**, contains grammar issues, which is unusual for professional emails. Specifically:
   - **"You are been"** should be **"You have been"**.
   - **"ecsecutiv's"** should be **"executive's"**.
   
3. **Spelling Mistakes in the Body:**
   - **"Conglaturations!"** should be **"Congratulations!"**.
   - **"Downlode"** should be **"Download"**.
   
   Such mistakes are common red flags, especially in emails from companies or organizations that would typically have their communications proofread.

4. **Psychological Manipulation:**  
   The email uses language designed to provoke urgency and action:
   - **"You're team needs you! This invitation will expire in 48 hours so act quickly."**
   - This type of language is intended to push the recipient to act quickly, without properly verifying the legitimacy of the email.

---

## Conclusion:

Due to all of these factors—such as the suspicious sender, the spelling/grammar errors, and the urgent call to action—**this is most definitely a phishing attempt** aimed at gaining access to the executive's privileges.

### Recommendations:
- **Quarantine** the email immediately.
- **Do not** download any attachments or click on any links in the message.
- **Alert** the executive and your security team about the phishing attempt.
- **Report** the email to your organization's email security service for further analysis.

---
