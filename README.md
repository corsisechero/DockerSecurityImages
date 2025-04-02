# DockerSecurityImages
Docker Images for Penetration Testing &amp; Security

Questa guida raccoglie le immagini Docker ufficiali e di terze parti per ambienti di penetration testing e laboratori di sicurezza.

---

## 1. Official Kali Linux
L'immagine ufficiale di Kali Linux.
```bash
docker pull kalilinux/kali-rolling
```

---

## 2. Official OWASP ZAP
Strumento per l'analisi della sicurezza delle applicazioni web.  
```bash
docker pull zaproxy/zaproxy
```

---

## 3. Official WPScan
Strumento per la scansione delle vulnerabilità di WordPress.
```bash
docker pull wpscanteam/wpscan
```

---

## 4. Docker Metasploit
Framework per l'exploit e il penetration testing.
```bash
docker pull metasploitframework/metasploit-framework
```

---

## 5. Damn Vulnerable Web Application (DVWA)
Applicazione web volutamente vulnerabile per scopi didattici.
```bash
docker pull citizenstig/dvwa
```

---

## 6. Vulnerable WordPress Installation
Installazione vulnerabile di WordPress per test di sicurezza.
```bash
docker pull eystsen/vulnerablewordpress
```

---

## 7. Vulnerability as a Service: Shellshock
Contenitore per testare la vulnerabilità Shellshock (CVE-2014-6271).
```bash
docker pull hmlio/vaas-cve-2014-6271
```

---

## 8. Vulnerability as a Service: Heartbleed
Contenitore per testare la vulnerabilità Heartbleed (CVE-2014-0160).
```bash
docker pull hmlio/vaas-cve-2014-0160
```

---

## 9. Security Ninjas
Laboratorio interattivo per l'apprendimento della sicurezza informatica.
```bash
docker pull opendns/security-ninjas
```

---

## 10. Arch Linux Penetration Tester
Contenitore di Arch Linux per il penetration testing.
```bash
docker pull noncetonic/archlinux-pentest-lxde
```

---

## 11. Docker Bench for Security
Script per controllare le best practice di sicurezza sui container Docker.
```bash
docker pull diogomonica/docker-bench-security
```

---

## 12. OWASP Security Shepherd
Progetto OWASP per l'addestramento alla sicurezza.
```bash
docker pull ismisepaul/securityshepherd
```

---

## 13. OWASP WebGoat Project
Ambiente didattico per apprendere le vulnerabilità comuni.
```bash
docker pull danmx/docker-owasp-webgoat
```

---

## 14. OWASP Mutillidae II Web Pen-Test Practice Application
Applicazione vulnerabile per esercitazioni di penetration testing.
```bash
docker pull citizenstig/nowasp
```

---

## 15. Metasploitable 2
Macchina virtuale vulnerabile per test di sicurezza.
```bash
docker pull tleemcjr/metasploitable2
```

---

## 16. Sqli-Labs
Laboratorio di vulnerabilità SQL Injection.
```bash
docker pull acgpiano/sqli-labs
```

---

## 17. bwapp
Applicazione web con molteplici vulnerabilità.
```bash
docker pull raesene/bwapp
```

### Metodo Alternativo (Consigliato)
Installazione tramite script PentestLab.
```bash
git clone https://github.com/eystsen/pentestlab.git
cd pentestLab
./pentestLab.sh --h
```

---

Questa raccolta di contenitori offre un ambiente completo per l'apprendimento e la pratica del penetration testing.  
Buon divertimento e buon hacking etico!
```
