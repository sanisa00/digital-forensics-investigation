# Digital Forensics Investigation

## Overview
This project simulates a digital forensics investigation, performed as part of the Security Blue Team’s Blue Team Junior Analyst Pathway. The focus was to analyze a disk image for evidence of data exfiltration and uncover malicious activity using forensic tools.

## Key Findings
- Located hidden files and corrected mismatched file extensions (e.g., `.xml` to `.png`).
- Extracted steganographic data embedded within image files using Steghide.
- Uncovered employee credentials stored within steganographic files.
- Performed brute-force and dictionary attacks to crack password-protected ZIP archives.

## Tools Used
- **Kali Linux**: For disk image analysis and CLI operations.
- **Steghide**: For extracting embedded data from image files.
- **fcrackzip**: For brute-force and dictionary-based ZIP password cracking.

## Steps
1. Enroll into Security Blue Team’s Blue Team Junior Analyst Pathway.
2. Access the disk image files provided in the **Course Capstone** here: [Activity: File System Analysis]( https://elearning.securityblue.team/home/courses/free-courses/introduction-to-digital-forensics#content#course-capstone#course-capstone#challenge-brief).
3. Analyze the disk image using Linux CLI commands to locate hidden files and correct mismatched file extensions.
4. Use Steghide to extract embedded credentials from image files.
5. Perform password cracking on ZIP archives using fcrackzip and the rockyou.txt wordlist.
6. Summarize findings.

## Learning Outcomes
- Strengthened practical skills in disk image analysis, steganography, and metadata extraction.
- Gained experience in identifying and analyzing evidence of data exfiltration.
- Improved understanding of digital forensics investigation workflows and tools.
