#Abschlussprojekt M223

Hierbei handelt es sich um eine API für die Verwaltung eines "co working space", wobei die meisten Anforderungen vom Lehrer des Moduls 223 bereitgestellt werden.
Die Nutzer können sich registrieren und anmelden und ihre jeweiligen Plätze buchen. 
Es gibt 3 Rollen: Admins, Mitglieder und Besucher. 
Admins sind Administratoren, Mitglieder sind registrierte Besucher, die sich angemeldet haben, und Besucher sind nicht autorisierte Nutzer, die die Website besuchen.

#Programm starten

1. Das Projekt in Visual Studio Code öffnen
2. Das Projekt in einem DevContainer neu-öffnen
3. Das Projekt mit dem Command: `Quarkus: Debug current quarkus project`
4. Mit erfolgreichem Start ist das Projekt unter http://localhost:8080 erreichbar

#Datenbank Administration
Über http://localhost:5050 ist PgAdmin4 erreichbar. Dies ist ein Datenbankverwaltungsprogramm.
Der Benutzername lautet `zli@example.com` und das Passwort lautet `zli*123`

Die folgenden Daten werden dann benötigt zum die Verbindung herzustellen:
- Hostname/address: `db`
- Port: `5432`
- Maintenance database: `postgres`
- Username: `postgres`
- Password: `postgres`