<h1 align="center">IWOCE-PTVulnerable</h1>
<h4 align="center">Intelligent Wireless OUTDOOR CPE/AP path traversal vulnerable.</h4>

## Information
Exploit Title: Intelligent Wireless OUTDOOR CPE/AP path traversal<br>
Date 10.9.2021<br>
Author: I2rys<br>
Version: N900-360-AP-V5.7-Build20210304134416

## Reproduce
1. Visit any Intelligent Wireless OUTDOOR CPE/AP login page with this version **N900-360-AP-V5.7-Build20210304134416**.
2. On the link you will see a page query, now replace login.html to ../../../etc/passwd
3. You will see that we were able to access the file that contains passwords.

## License
MIT © I2rys
