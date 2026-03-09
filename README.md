# -FUTURE_CS_02
"Cyber Security Internship - Task 2:  "Phishing Email Detection &amp; Awareness System"

🛡️ Phishing Email Detection & Awareness System
📝 Project Overview
This repository contains a forensic analysis of a real-world phishing email as part of my Future Interns Cybersecurity Internship (Task 02). The goal of this project is to demonstrate the technical and visual methods used to identify, analyze, and classify malicious email threats.

🔍 Technical Analysis Features
 Email Header Forensics: Analyzing MTA hops and routing paths to trace the true origin of the email.

 Authentication Audit: Verifying SPF, DKIM, and DMARC records using professional tools like MXToolbox.

 Visual Indicator Mapping: Identifying psychological triggers, geographic scare tactics, and identity deception.

⚠️ Risk Classification: Categorizing the threat level based on technical evidence and potential organizational impact.

🛠️ Tools Used
 Google Admin Toolbox: For message header analysis.

 MXToolbox: For SPF, DKIM, and DMARC authentication checks.

 Canva: For designing the final forensic report and awareness guidelines.

📂 Repository Structure
 /Report: Contains the full PDF forensic analysis of the Microsoft "Unusual Sign-in" lure.

 /Screenshots: Technical evidence including header logs and authentication failure reports.

📖 README.md: Project documentation and overview.

🚨 Key Findings
The analyzed lure was identified as a Critical Risk credential harvesting attempt. Despite professional branding, the email failed all primary authentication protocols and contained a malicious mailto: link hidden behind a "Report The User" button.
