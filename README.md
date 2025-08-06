# PHISHING-ANALYSIS



This repository contains a project focused on analyzing a sample phishing email to identify its fraudulent characteristics and report the findings.

**Methodology & Process The analysis was conducted following these steps:**

1. Obtain a Sample: A sample phishing email was acquired for analysis.

2. Examine Sender Address: The sender's email address and domain were checked for signs of spoofing.

3. Analyze Language: The email body was inspected for urgent, threatening, or unprofessional language

4. Check for Errors: The email was reviewed for spelling and grammatical mistakes.

5. Inspect Links: All hyperlinks were examined by hovering to reveal the true destination URL without clicking.

6. Summarize Findings: All identified phishing traits were compiled into the final analysis report below

● Web Browser: To inspect hyperlink destinations without clicking(In the PC or laptop by moving cursor on the link we can check the masked url.)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**This is an email recived by me, i just opened the email and in the right top i went to see orignal...
There we can see the Sender IP, domain and few more details.**


![img alt](https://github.com/swamy-2006/PHISHING-ANALYSIS/blob/80536aa34b01130465bf89531072de64c6872d70/WhatsApp%20Image%202025-08-06%20at%2008.06.56_829b5809.jpg)




From the IP address we can get the location of the service which they have sent through 
[WhatIsMyIPAddress](https://whatismyipaddress.com)

From there we can confirm the location of genrated email.
Also from the domain name we can do dnslookup.

*Anatomy of a Legitimate Email Header*
Email headers contain crucial security information that helps verify a sender's authenticity. The following analysis of a legitimate email from 

Cisco Networking Academy  demonstrates the key authentication checks that a safe email will pass, providing a clear baseline for identifying phishing attempts.

**SPF (Sender Policy Framework): PASS**
SPF checks whether an email was sent from a server authorized by the domain owner.


What this means: The email passed the SPF check because the sending server's IP address (54.240.11.131) is on the official list of servers allowed to send mail for netacad.com. This is the first sign that the sender is not spoofed.

**DKIM (DomainKeys Identified Mail): PASS**
DKIM adds a tamper-proof digital signature to the email, proving it genuinely came from the sender and that its contents were not altered in transit.


What this means: The email passed the DKIM check with the domain netacad.com. This confirms the message's authenticity and integrity, making it highly trustworthy.

**DMARC (Domain-based Message Authentication, Reporting, and Conformance): PASS**
DMARC is a policy that tells receiving email servers how to handle messages that fail SPF or DKIM. A PASS means the email successfully met the sender's strict authentication requirements.


What this means: Since the email passed SPF and DKIM, it automatically passed DMARC. This confirms the email adheres to the highest standards of email authentication

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# PHISHED EMAILS
***[NOTE:This phished email is CREATED ONE , url genrated by zphisher tool in the linux, the both sender and reciver is myself here]***
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


In some phishing emails the urls will be masked 
like this:
![img alt]()












This is a classic example of a phishing scam. Here is a detailed breakdown of all the red flags, formatted for your GitHub repository.

Phishing Analysis: The "Free Instagram Followers" Scam
This analysis dissects a phishing email that impersonates Meta and Instagram to trick users into clicking a malicious link. The email uses several common social engineering and deception tactics.

**1. The Mismatched and Malicious URL**
This is the most critical piece of evidence that proves the email is a scam.

The Bait: The link text displayed in the email is https://instagram.com/free-followers/limited. This looks plausible and uses the official instagram.com domain to build trust.

The Switch: However, as shown in the second image, when you hover your mouse over the "Keep Account" button, the browser reveals the actual destination URL: [getfreefollowers-instagram/cloudfareed@is.gd/6fytu456](getfreefollowers-instagram/cloudfareed@is.gd/6fytu456)

Analysis: This is a classic phishing technique. The real link has nothing to do with Instagram. It points to a suspicious, shortened URL (is.gd), which is designed to hide the true destination—a malicious website built to steal your account credentials.

**2. Social Engineering: An Offer That's Too Good to Be True**
The entire premise of the email is a powerful social engineering tactic.

The Lure: The subject line, "GET FREE INSTAGRAM FOLLOWERS INSTANTLY!", is designed to grab your attention by appealing to a common desire for social media popularity.

Analysis: Legitimate companies like Meta or Instagram do not offer free followers. Such promises are almost always a red flag for a scam. Attackers use these exciting offers to make you act impulsively without thinking critically about the email's legitimacy.

**3. Unprofessional Language and Greeting**
The email's content contains several signs that it is not from a professional source.

Generic Greeting: It starts with "Hello, Hi INSTAGRAM USER." A real company would address you by your specific username. This generic greeting indicates a mass email sent to many people.

Awkward Phrasing: The sentence, "I am a Working Professional in meta," is unnatural and not the kind of language a corporation would use in an official communication.

**4. Deceptive Use of Branding**
The attacker uses official logos to make the email appear legitimate at first glance.

The Tactic: The email includes the official logos for both Meta and Instagram.

*Analysis: While these logos look real, they are easy to copy and paste. When combined with all the other red flags (especially the mismatched URL), the use of these logos is clearly an attempt to build false trust and deceive the recipient.*




In the PC or laptop by moving cursor on the link we can check the masked url.

We can paste the link which is copied from the email which is appearing to be legit but not in the website or a tool called [VIRUS TOTAL](https://virustotal.com)





-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The detailed Analysis of an example phishing email is done here

**[NOTE: GENRATED USING an AI]**

[ANALYSIS](https://github.com/swamy-2006/PHISHING-ANALYSIS/blob/main/sample_email_phishing.html)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
***FAQ and DIFFERENT METHODS***

 

*1. What is phishing?*
Phishing is a type of cyber attack where criminals impersonate a legitimate organization or person to trick you into revealing sensitive information, such as passwords, credit card numbers, or personal details.

*2. How to identify a phishing email?*
Look for these common red flags:

  1.Mismatched URLs: Hover your mouse over a link to see the actual destination URL. If it doesn't match the link's text or the supposed sender, it's a major red flag.

  2.Urgent or Threatening Language: Phrases like "Urgent Action Required" or "Your Account Will Be Suspended" are used to create panic.

  3.Spelling and Grammar Errors: Professional companies rarely send emails with obvious mistakes.
  
  4.Suspicious Sender Address: Look for slight misspellings in the domain name (e.g., microsft.com instead of microsoft.com).

  5.Generic Greetings: A legitimate company will usually address you by your name, not "Dear Valued Customer."

  6.Unexpected Attachments: Be wary of any attachments you weren't expecting, especially .zip or .exe files.

*3. What is email spoofing?*

Email spoofing is the act of forging a sender's email address to make it appear as if the email came from a trusted source, like your bank or a well-known company.

**4. Why are phishing emails dangerous?**

They are dangerous because they can lead to:

  1.Identity Theft: Attackers can steal your personal information to impersonate you.

  2.Financial Loss: They can gain access to your bank or credit card accounts.

  3.Malware Infections: Clicking a malicious link or attachment can install viruses, spyware, or ransomware on your device.

  4.Compromised Accounts: Attackers can take over your email, social media, or work accounts.

**5. How can you verify the sender's authenticity?**

The most reliable method is to analyze the email header and check its SPF, DKIM, and DMARC records. If all three of these security checks "PASS," the sender is authentic. You can also contact the sender through a separate, trusted channel (like their official website or phone number) to confirm if they sent the email.

**6. What tools can analyze email headers?**

There are several free online tools available, including:

  1.MXToolbox Email Header Analyzer

  2.Google Admin Toolbox Messageheader

  3.WhatIsMyIP.com Email Header Analyzer


**7. What actions should be taken on suspected phishing emails?**

Do NOT click any links or download any attachments.

  1.Do NOT reply to the email.

  2.Report it. Use the "Report Phishing" or "Report Spam" option in your email client.

  3.Delete the email from your inbox.

**8. How do attackers use social engineering in phishing?**
They manipulate human emotions and psychology to bypass critical thinking. Common tactics include:

  1.Creating Urgency/Fear: "Your account has been compromised! Act now!"

  2.Appealing to Greed/Curiosity: "You've won a prize!" or "Click here to get free followers!"

  3.Impersonating Authority: Pretending to be from a government agency, your boss, or tech support.

  4.Building Trust: Using official-looking logos and personalized information to appear legitimate.

  
  ------------------------------------------------------------------------------------------------





