# 🔒 Vulnerability Assessment Report

## 📌 Objective
Use free tools to identify common vulnerabilities on a local computer system.

## 🛠 Tools Used
- **OpenVAS Community Edition** (Free vulnerability scanner)  
- **Nessus Essentials** (Free vulnerability scanner)

## 📂 Deliverables
- Vulnerability scan report with identified issues
- Documentation of critical vulnerabilities
- Screenshots of scan results

---

## 🚀 Steps Followed

1. Install Scanner
   - Installed [OpenVAS Community Edition](https://www.greenbone.net/en/community-edition/)  
   - Alternatively, installed [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials)

2. **Configure Scan Target**
   - Target set as local machine IP (`127.0.0.1` / `localhost`)

3. **Run Full Vulnerability Scan**
   - Initiated a complete system scan
   - Duration: ~30–60 minutes

4. **Review Results**
   - Examined generated report
   - Identified vulnerabilities categorized by severity (Low, Medium, High, Critical)

5. **Research Fixes**
   - Looked up simple mitigations for discovered issues
   - Documented recommended actions

6. **Document Critical Vulnerabilities**
   - Highlighted the most severe findings
   - Suggested remediation steps

7. **Screenshots**
   - Captured scan results for reference

---

## 📊 Example Report Structure

| Vulnerability ID | Severity | Description | Suggested Fix |
|------------------|----------|-------------|---------------|
| CVE-2021-12345   | High     | Outdated OpenSSL version | Update OpenSSL to latest version |
| CVE-2020-6789    | Medium   | Weak SSH configuration | Disable weak ciphers in `sshd_config` |
| CVE-2019-11111   | Critical | Unpatched Windows service | Apply latest Microsoft security updates |


---

## ✅ Key Takeaways
- Regular vulnerability scanning helps identify and mitigate risks early.
- Free tools like OpenVAS and Nessus Essentials provide strong baseline security checks.
- Documenting and fixing critical vulnerabilities is essential for maintaining system security.

---

## 📜 License
This project is licensed under the MIT License – feel free to use and adapt.
