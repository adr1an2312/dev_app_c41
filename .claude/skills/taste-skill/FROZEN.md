# Eingefrorene Kopie

Kopie von Leonxlnx/taste-skill@6010f91 (skills/taste-skill), Stand 2026-10-21. Wird nicht automatisch aktualisiert.

Lokale Änderungen zur Härtung gegen Prompt Injection:

- `disable-model-invocation: true` in `SKILL.md`: Der Skill läuft nur, wenn er ausdrücklich mit `/taste-skill` aufgerufen wird.
- `scripts/assets.mjs` entfernt: Das Skript hat Bildtitel und Beschreibungen aus dem Internet (Openverse, Wikimedia, Museen, NASA) in die Sitzung geholt. Ohne es arbeitet der Skill komplett offline.

Updates nur nach Durchsicht des Diffs gegen einen festen Upstream-Commit.
