# Screenshots

This folder contains all screenshots taken during the penetration test, numbered in sequence from lab setup through post-exploitation.

| # | Filename | Description |
|---|----------|-------------|
| 01 | 01_Kali-linux-lab-setup.png | Kali Linux VMware configuration |
| 02 | 02_Metasploit2-lab-setup.png | Metasploitable2 VMware configuration |
| 03 | 03_ping_connectivity.png | Network connectivity confirmed |
| 04 | 04_nmap_detailed_scan.png | Full service version scan |
| 05 | 05_nmap_vuln_scan.png | NSE vulnerability scan — vsftpd CVE flagged |
| 06 | 06_enum4linux_output.png | SMB enumeration output |
| 07 | 07_nikto_scan.png | Web server vulnerability scan |
| 08 | 08_vsftpd_module_configured.png | vsftpd exploit — root shell obtained |
| 09 | 09_samba_exploitation.png | Samba exploit — root shell + shadow dump |
| 10 | 10_metasploitable2_webpage.png | Target web server default page |
| 11 | 11_metasploitable2_login_page.png | DVWA login page |
| 12 | 12_sql_injection_query.png | Normal SQL query baseline |
| 13 | 13_sql_injection_attack.png | OR-based SQLi — all users dumped |
| 14 | 14_dvwa_sqli_hashes.png | UNION SQLi — password hashes extracted |
| 15 | 15_hashes_cracked.png | Hashcat — admin MD5 hash cracked |
| 16 | 16_post_enum_netstat_ps.png | netstat + ps aux output |
| 17 | 17_post_enum_suid_find.png | SUID binary enumeration |
| 18 | 18_shadow_dump.png | /etc/shadow contents dumped |
| 19 | 19_john_cracked.png | John the Ripper — 3 passwords cracked |