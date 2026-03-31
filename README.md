<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=2000&pause=500&color=00ff00&background=000000&center=true&vCenter=true&width=1010&height=50&lines=Nuknov;Just+A+Tech;root@Nuknov:~%23+whoami;Cybersecurity+Enthusiast;Ethical+Hacker;OSINT+Specialist;Dorking+Techs" alt="Terminal is Typing Active" />

</div>

```ruby
███╗   ██╗██╗   ██╗██╗  ██╗███╗   ██╗ ██████╗ ██╗   ██╗
████╗  ██║██║   ██║██║ ██╔╝████╗  ██║██╔═══██╗██║   ██║
██╔██╗ ██║██║   ██║█████╔╝ ██╔██╗ ██║██║   ██║██║   ██║
██║╚██╗██║██║   ██║██╔═██╗ ██║╚██╗██║██║   ██║╚██╗ ██╔╝
██║ ╚████║╚██████╔╝██║  ██╗██║ ╚████║╚██████╔╝ ╚████╔╝ 
╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝   ╚═══╝  
                                                        v1.0

  [+] Status: CONNECTED
  [+] User: Nuknov [admin@github]
  [+] Location: github.com
  [+] IP: 127.0.0.1
  [!] Access Level: Root (/)
───────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# whoami && id
Nuknov
uid=0(root) gid=0(root) groups=0(root),27(sudo),1000(kali)

root@Nuknov:~# echo $USER_INFO
Cybersecurity Enthusiast | Ethical Hacker
Specializing in penetration testing, vulnerability research, and secure coding
Current Focus: CVE Research and Mobile Security
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# cat /etc/skills/skills.conf
> Programming: Python, C, C++, Java, Bash, Assembly
> Security: Penetration Testing, Network Security, Vulnerability Research
> Tools: Git, vscode, Metasploit, Netcat, MSYS2
> Systems: Linux, Windows, ParrotOS
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# env | grep -i "sec\|hack\|recon\|tool"
EDITOR=vim
SHELL=/bin/zsh
TERM=xterm-256color
RECON_MODE=passive
EXPLOIT_DB=/opt/exploitdb
WORDLIST=/usr/share/wordlists/rockyou.txt
PROXY=socks5://127.0.0.1:9050
CVE_FEED=https://nvd.nist.gov/feeds/json/cve
BURP_PORT=8080
OSINT_API_KEY=[REDACTED]
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# ls -la /home/Nuknov/projects/
total 96
drwxr-xr-x 12 Nuknov Nuknov 4096 Jan 26 16:09 .
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 ..
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 Java 3x3 Inverse Matrix
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 Defacement
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 USB Data Collector
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 Chrome History Decrypter
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 Chrome History Forensic
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 WP-ReconX Extension
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 DeConfigro
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 ScreenPulse
drwxr-xr-x  3 Nuknov Nuknov 4096 Jan 26 16:09 Ilumu Extension Tool
drwxr-xr-x  3 Nuknov Nuknov 4096 Feb 26 16:09 Study.lol/SmartStudy-AI Extension
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# git log --oneline --graph --all
* 9f3a1c2 (HEAD -> main) fix: patched buffer overflow in DeConfigro
* 7b82de1 feat: added stealth mode to USB Data Collector
* 4c91fa3 feat: WP-ReconX v2.1 — fingerprint bypass
* 3d70bc0 fix: Chrome History Decrypter — AES-256 key handling
* 1a2b3c4 init: SmartStudy-AI Extension scaffold
| * 0xdeadb (origin/dev) chore: cleaned OSINT module traces
|/
* 0000000 init: repository initialized

[i] 6 commits ahead of origin
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# systemctl status active-projects
● active-projects.service - Active Development Projects
   Loaded: loaded (/etc/systemd/system/active-projects.service; enabled)
   Active: active (running) since 2026-01-26 16:09:25 UTC; 24h ago

Main PID: 1337 (project-manager)
   Tasks: 12 (limit: 4915)
   Memory: 256.8M
   CGroup: /system.slice/active-projects.service
           ├─1337 DeConfigro
           ├─1338 Chrome History Decrypter
           ├─1339 WP-ReconX Extension
           ├─1340 Ilumu Extension
           ├─1341 Screen Pulse
           ├─1342 USB Data Collector
           ├─1343 SmartStudy-AI Extension
           └─1344 ChatGPT Vulnerability
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# ps aux | grep -E "recon|scan|exploit"
USER     PID  %CPU %MEM  COMMAND
Nuknov  1337  2.4  1.1   ./DeConfigro --silent
Nuknov  1338  0.8  0.4   python3 chrome_forensic.py
Nuknov  1339  3.1  2.0   ruby wp_reconx.rb --stealth
Nuknov  1340  0.2  0.1   bash ilumu.sh --passive
Nuknov  4444  0.0  0.0   nc -lvnp 4444   [LISTENING]

[!] 5 active processes detected
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# nmap -sV --open -T4 localhost
Starting Nmap 7.94 ( https://nmap.org )
Scan report for localhost (127.0.0.1)
Host is up (0.00012s latency).

PORT     STATE  SERVICE     VERSION
22/tcp   open   ssh         OpenSSH 9.2
80/tcp   open   http        Apache 2.4.57
443/tcp  open   ssl/https   nginx 1.24.0
1337/tcp open   waste       Nuknov-C2-Framework
4444/tcp open   krb524      [REDACTED]

[+] 5 open ports discovered
[!] Suspicious service on port 1337 — flagged for review
───────────────────────────────────────────────────────────────────
```

```ruby
root@Nuknov:~# crontab -l
# Nuknov Task Scheduler
# ┌─ min ┬─ hour ┬─ day ┬─ month ┬─ weekday

  0  3   *  *  1   ./scripts/recon_sweep.sh       # Weekly recon
  */30 * *  *  *   ./scripts/log_cleanup.sh        # Clear traces
  0  0   *  *  *   ./scripts/vuln_scan.py          # Daily CVE check
  15 9   *  *  5   ./scripts/report_gen.sh         # Friday reports

[+] 4 active cron jobs loaded
───────────────────────────────────────────────────────────────────
```

```ruby
[!] Warning: Unauthorized access detected. Tracking source...
```

```ruby
root@Nuknov:~# cat /etc/motd
╔════════════════════════════════════════════════════════════════════════════╗
║  "The darkest port scan is brighter than the comfort of ignorance."        ║
║  "The quieter you become, the more you are able to hear."                  ║
║  "To find a flaw, you must first doubt the surface."                       ║  
║                                                                            ║
║                                                                            ║
║  Ethical hacking is about making the digital world safer for everyone.     ║
║  Research responsibly. Disclose ethically. Code with purpose.              ║
╚════════════════════════════════════════════════════════════════════════════╝

root@Nuknov:~# disclaimer
[!] All repositories and tools are intended solely for educational and ethical testing purposes.
[!] I do not support or encourage any form of illegal or unethical use of the code.
[!] Use responsibly in labs, simulations, and learning environments only.
[!] All tools are intended solely for simulation and introductory educational use only.

[-] Connection to github.com closed.
───────────────────────────────────────────────────────────────────────────

root@Nuknov:~# uptime
 16:09:25 up 365 days, 12:34, 7 users, load average: 0.15, 0.10, 0.08

root@Nuknov:~# logout
[i] Session terminated gracefully
[i] All security protocols maintained
[i] Ethical hacking guidelines enforced
```

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0,000000,00ff00&height=300&section=header&text=Nuknov&fontSize=90&fontColor=00ff00&animation=fadeIn&fontAlignY=38&desc=Cybersecurity%20Enthusiast%20|%20Ethical%20Hacker%20|%20Programmer&descSize=20&descAlignY=60&bgColor=000000" alt="Nuknov Header" />

</div>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Nuknov&theme=github-dark&hide_border=true&bg_color=000000&color=00ff00&line=33ff33&point=00ff00" alt="Activity Graph" />

<p align="center">
  <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api?username=Nuknov&show_icons=true&hide_border=true&bg_color=000000&title_color=00ff00&icon_color=00ff00&text_color=33ff33&ring_color=00ff00" alt="GitHub Stats" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Nuknov&hide_border=true&background=000000&ring=00ff00&fire=00ff00&currStreakLabel=00ff00&sideLabels=33ff33&dates=33ff33&currStreakNum=00ff00&sideNums=33ff33" alt="Streak Stats" />
</p>
