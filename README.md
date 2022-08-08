# x-ng

#### Feature:

Nginx as frontend with panindex as disquise.

### Deploy:

Deploy brook on replit.
Change Language to "Bash",Choose "Import from GitHub".

<a href="https://replit.com/github/gityzon/bk-ng">
  <img alt="Run on Repl.it" src="https://replit.com/badge/github/github/gityzon" style="height: 40px; width: 190px;" />
</a>

#### For edu:

1. Creat a Bash-language project.

2. Copy these code to Replit's Shell and ←

   `git clone https://github.com/gityzon/x-ng && mv -b x-ng/* ./ && mv -b x-ng/.[^.]* ./ && rm -rf *~ && rm -rf x-ng`

3. After "Loading Nix environment..." is done, ▶RUN!!!

   

   If you use mobile phone,please set the UA of Browser as "Desktop" or maybe replit can not work.

# Environment

You need add Secrets(System environment variables) like:

### key: "uuid"

### value: "your own uuid"

The secrets is private so you don't need to worry about leaking your data.

# Clients

You can find all clients from:
[**this page**](https://xtls.github.io/Xray-docs-next/document/level-0/ch08-xray-clients.html#_8-2-%E5%AE%A2%E6%88%B7%E7%AB%AF%E4%B8%8E%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E6%AD%A3%E7%A1%AE%E8%BF%9E%E6%8E%A5)

# Usage

- id:"uuid"
- host:"your replit url"
- port:443
- stream-network:ws
- security:none
- ws-path:/23333
- tls:tls

# Sleep

May the service sleep,you need a web monitor like UptimeRobot to keep it work.
https://uptimerobot.com



# Good luck!
