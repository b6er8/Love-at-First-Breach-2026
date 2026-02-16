# Hidden Deep Into my Heart
![alt text](letter.png)

![alt text](site.png)

Not much to go off of, so lets do some classic enumeration !

- Check robots.txt and sitemap.xml

- Run nmap and gobuster in the meantime

---

![alt text](robots.txt.png)

*we'll take note of this for now*

---

gobuster is still running but nmap is done, only thing worth mentioning is :

![alt text](<hidden dir.png>)

(Run Nmap with the default scripts if you don't get the same results)

![alt text](<getting close.png>)

oooh so we're making some progress !

---

Gobuster is still going for longer than it should so lets repoint it towards the new dir we found

![alt text](<even closer.png>)

what do we have here !

---

I've been trying to bruteforce this page for wayyyy too long than I should have, then I remembered the robots.txt from earlier! Use it as a password, with the username admin and you should get the flag !
