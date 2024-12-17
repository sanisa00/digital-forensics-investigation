# Digital Forensics Investigation

## Overview
This project simulates a digital forensics investigation, performed as part of the Security Blue Team’s Blue Team Junior Analyst Pathway. The focus was to analyze a disk image for evidence of data exfiltration and uncover malicious activity using forensic tools.

## Key Findings
- Identified hidden files and corrected mismatched file extensions (e.g., `.xml` to `.png`).
- Extracted steganographic data embedded within image files using Steghide.
- Uncovered employee credentials stored within steganographic files.
- Performed brute-force and dictionary attacks to crack password-protected ZIP archives.

## Tools Used
- **Kali Linux**: For disk image analysis and CLI operations.
- **Steghide**: For extracting embedded data from image files.
- **fcrackzip**: For brute-force and dictionary-based ZIP password cracking.
- **Security Blue Team Labs**: For providing disk image files and simulated scenarios.

## Steps
1. Accessed a provided disk image from the Security Blue Team’s Blue Team Junior Analyst Pathway.
2. Analyzed the image using Linux CLI commands to locate hidden and mismatched files.
3. Used Steghide to extract embedded credentials from image files.
4. Performed password cracking on ZIP archives using fcrackzip and the rockyou.txt wordlist.
5. Compiled findings into a detailed report with evidence.

## Learning Outcomes
- Gained practical experience in disk image analysis and steganography techniques.
- Strengthened skills in metadata analysis and password cracking.
- Enhanced understanding of data exfiltration and forensic investigation workflows.

## How to Replicate
1. Enroll in the [Security Blue Team’s Blue Team Junior Analyst Pathway](https://securityblue.team/).
2. Download the disk image provided in the relevant lab.
3. Follow the analysis steps outlined in this repository’s guide, using the recommended tools.

## Visual Evidence
![Forensics Screenshot](Screenshots/forensics_analysis.png)
