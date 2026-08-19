# Antworten

## 1. Was gewinnen wir mit dem Commit-Hook?

Durch den Commit-Hook erhalten wir einheitliche und nachvollziehbare Commit-Messages, die automatisch dem Conventional-Commits-Format entsprechen und einem Ticket zugeordnet werden können. Fehlerhafte Commit-Messages werden bereits vor dem Erstellen des Commits verhindert.

## 2. Welche Probleme seht ihr mit dieser Lösung?

Der Hook läuft nur lokal und kann beispielsweise mit `git commit --no-verify` umgangen werden. Außerdem funktioniert die automatische Einrichtung nur, wenn Entwickler die vorgesehene Installation, beispielsweise `npm install`, ausführen.
