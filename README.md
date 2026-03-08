# Okružno takmičenje iz matematike - 3. razred

Analiza rezultata Okružnog takmičenja iz matematike za 3. razred, Beograd, 08.03.2026.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/msrdjan/mat-2026-okruzno-3-razred/blob/main/rezultati-analiza.ipynb)

## Podaci

Izvor: [Preliminarni rezultati (PDF)](https://www.ilijabircanin.edu.rs/wp-content/uploads/2026/03/OkruznoTakmicenje-Rezultati-3.razred.pdf)

- 153 učenika
- 5 zadataka, svaki po 20 poena (ukupno 100)

## Sadržaj analize

| Sekcija | Opis |
|---------|------|
| Prvih 10 učenika | Rang-lista najboljih |
| Distribucija rezultata | Histogram sa medijanom |
| Rang-lista po broju poena | Svi rezultati sa pozicijama |
| Najbolje škole | Po proseku, minimum 2 učenika |
| Najbolji nastavnici | Po proseku, minimum 2 učenika |
| Uspešnost po zadacima | Prosečni poeni po zadatku |
| Percentili (CDF) | Kumulativna distribucija |
| Violin plot po zadatku | Raspodela poena za svaki zadatak |
| Težina i diskriminativnost | Analiza kvaliteta zadataka |
| Sastav rezultata (top 30) | Slagani grafikon po zadacima |
| Korelacija zadataka | Matrica korelacija |
| Poređenje škola (box plot) | Raspon rezultata po školi |
| Tabela percentila | Poeni -> percentil |
| Kompletna rang-lista | Svi učenici sa bojama po rangu |

## Pokretanje

Notebook se može otvoriti direktno u Google Colab (kliknite "Open in Colab" badge iznad). Sve potrebne biblioteke se instaliraju automatski, a podaci se preuzimaju iz PDF-a.

Za lokalno pokretanje:

```bash
uv sync
uv run jupyter notebook rezultati-analiza.ipynb
```
