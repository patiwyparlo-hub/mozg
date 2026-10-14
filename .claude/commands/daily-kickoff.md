---
description: Poranny start dnia – podsumowanie wczoraj, pytania o dzień, plan w daily/
---

Prowadzisz mój poranny kickoff. Pisz po polsku, krótko, listami. Dzisiejsza data: !`date +%Y-%m-%d`.

## 1. Kontekst
- Znajdź najnowszy plik w `daily/` sprzed dzisiaj (zwykle wczorajszy; po weekendzie może być starszy) i przeczytaj go.
- Przeczytaj `todo.md`.
- Jeśli w tym folderze lub w projektach z CLAUDE.md jest repozytorium z kodem z remote na GitHubie, sprawdź moje otwarte issues i PR-y przez `gh` (np. `gh issue list --assignee @me`, `gh pr list --author @me`). Jeśli takiego repo nie ma, pomiń ten krok bez komentarza.

Pokaż krótkie podsumowanie (maks. ~8 punktów):
- co wczoraj zrobione / niedokończone,
- co wisi w `## Open` w todo.md (najważniejsze),
- issues/PR-y z GitHuba (jeśli są).

## 2. Pytania
Zadaj mi te pytania w jednej wiadomości i poczekaj na odpowiedź:
1. Energia dziś 1–5?
2. Must-dos – co MUSI się dziś wydarzyć?
3. Spotkania – jakie i o której?
4. Fokus dnia – jedna główna rzecz?
5. Blokery – co mnie blokuje?
6. Co mi chodzi po głowie?

## 3. Plan
Zapisz plan w `daily/RRRR-MM-DD.md` (dzisiejsza data). Jeśli plik już istnieje – dopisz, nie nadpisuj. Format:

```
# RRRR-MM-DD

**Energia:** X/5
**Fokus:** ...

## Spotkania
- HH:MM – ...

## Zadania
- [ ] ...

## Blokery
- ...

## W głowie
- ...
```

Liczba zadań zależy od energii:
- 1–2 → maks. 2–3 zadania (tylko must-dos + 1 lekkie),
- 3 → 3–5 zadań,
- 4–5 → 5–7 zadań.

Uwzględnij spotkania przy liczeniu czasu. Rzeczy z „w głowie”, które są zadaniami lub pomysłami, dopisz też do `todo.md` (`## Open`) lub `ideas/` z datą.

## 4. Start
Na koniec powiedz jednym-dwoma zdaniami, **od czego zacząć** i dlaczego.
