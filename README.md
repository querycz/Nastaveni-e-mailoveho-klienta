# Nastavení e-mailového klienta ✉️

## Obecné
- _POP3/IMAP server:_	mail.domena.tld nebo mail.fortion.net (port 143, šifrování TLS/SSL)
- _SMTP server:_ smtp.domena.tld nebo smtp.fortion.net (port 587, vyžadována autorizace, volitelné STARTTLS)
- _Webmail:_ https://webmail.domena.tld nebo https://webmail.fortion.net
- _Uživatelské jméno:_ cokoliv@domena.tld

## macOS
- IMAP/SMTP viz výše
- _Automatically manage connection settings:_ ☑️

## iOS/iPadOS

### Outgoing mail server
- _Use SSL:_ ☑️
- _Authentication:_ Password
- _Server port_: 587

### Incoming settings
- _Use SSL:_ ☑️
- _Authentication:_ Password
- _IMAP Path Prefix:_ /
- _Server port_: 993

## Gmail
- _Nastavení_ –> _Účty a import_
  - _Odesílat poštu jako_
  - _Zkontrolovat poštu z jiných účtů_

### Odesílání e-mailů
- _Odesílat poštu jako_ –> _Přidat další emailovou adresu_
- _Jméno:_ Jméno Příjmení
- _E-mail:_ cokoliv@domena.tld
- _Považovat za alias:_ ☑️
- _Server SMTP:_ viz výše
- _Port:_ 587
- _Zabezpečené připojení pomocí protokolu TLS_

### Příjem e-mailů
- _Zkontrolovat poštu z jiných účtů_ –> _Přidat e-mailový účet_
- _Importovat e-maily z mého druhého účtu (POP3)_
- _Uživatelské jméno:_ cokoli@domena.tld
- _POP server:_ viz výše
- _Port:_ 110

## Outlook
- _Server příchozí pošty požaduje ověření:_ ☑️
- _POP3 server:_ viz výše
- _SMTP server:_ viz výše
- Přihlašovací údaje jak pro POP3, tak SMTP: název schránky, např. cokoliv@domena.tld

## Thunderbird

### IMAP
- _Port:_ 143
- _SSL:_ STARTTLS
- _Autentizace:_ Heslo

### SMTP
- _Port:_ 587
- _SSL:_ Žádné
- _Autentizace:_ Heslo
