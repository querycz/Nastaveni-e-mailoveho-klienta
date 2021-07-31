# Nastavení mailového klienta

## Obecné
- POP3/IMAP server:	mail.domena.tld nebo mail.fortion.net (port 143, šifrování TLS/SSL)
- SMTP server:	smtp.domena.tld nebo smtp.fortion.net (port 587, vyžadována autorizace, volitelné STARTTLS)
- Webmail:	https://webmail.domena.tld nebo https://webmail.fortion.net
- Uživatelské jméno:	cokoliv@domena.tld

## iOS/iPadOS


## Gmail

V Gmailu je vpravo nahoře Nastavení a v něm záložka Účty a import, kde je potřeba nastavit dvě věci:
### Odesílání e-mailů
V té záložce Účty a import najít část Odesílat poštu jako: kliknout na Přidat další emailovou adresu
Otevře se nové okno a v něm postupně vyplnit:
Jméno .. tj. to, které se zobrazí příjemci mailu --> Vojta Růžička
Email .. zadat ten na doméně Superhub.cz --> vojta@superhub.cz
Považovat za alias klidně nechat zaškrtlé
Kliknout na Další krok a na dalším screenu vyplnit:
Server SMTP .. do inputu vložit: smtp.fortion.net
Port .. nastavit na: 587
Uživatelské jméno .. zase email Superhub mail --> vojta@superhub.cz
Heslo .. zadat heslo k Superhub mailu (posílám znovu seznam dole)
Nechat zabezpečení TLS
Kliknout na Uložit změny
Tím je nastavení odesílání hotovo. Případně se dá nastavit výchozí adresa, ze které se maily mají odesílat, tj. ta sekce Při odpovídání na zprávu.

### Příjem e-mailů
Na stejné záložce Účty a import najít sekci Zkontrolovat poštu z jiných účtů a kliknout na Přidat e-mailový účet.
Zase vyskočí nové okno, kde se vyplní:
Emailová adresa .. zase ta s doménou Superhub.cz --> vojta@superhub.cz
Kliknout na tlačítko Další
Vybrat Importovat e-maily z mého druhého účtu (POP3) a kliknout na Další
Vyplnit:
Uživatelské jméno .. zopakovat Superhub mail --> vojta@superhub.cz
Heslo .. zase to k Superhub mailu (viz. dole)
POP server .. vložit: mail.fortion.net
Port .. vybrat 110
Checkboxy pod tím ovlivňují jen chování přijatých mailů, to je na uživateli, jak si nastaví.
Kliknout na Uložit
To je vše..




## Outlook
- "Server příchozí pošty požaduje ověření:" Ano

POP3 server: mail.fortion.net
SMTP server: smtp.fortion.net

„Server příchozí pošty požaduje ověření“ – ANO
Přihlašovací údaje jak pro POP3, tak SMTP: název schránky, např. sebek@clovis.cz, heslo viz dokument


## Thunderbird
