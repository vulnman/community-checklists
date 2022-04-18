Web applications can contain unlinked files.

##### gobuster
```bash
gobuster -w /usr/share/seclists/Discovery/common.txt -u https://example.com -x php,aspx,asp,txt,json,zip
```