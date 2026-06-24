# Metodika

## Zdroj dat
- Daktela API v6
- Kanály: `activitiesCall`, `activitiesEmail`, `activitiesChat`, `activitiesSms`
- Období tohoto běhu: 2026-03-01 až 2026-06-24

## Jak jsou účty rozdělené
- **Human** = lidské účty vhodné pro personální srovnání
- **Shared** = sdílené / provozní účty (např. Klinika)
- **System** = systémové / API účty

## Co znamenají čísla
- `total_contacts` = součet hovorů, e-mailů, chatů a SMS přiřazených konkrétnímu účtu
- `active_days` = počet dnů, kdy měl účet aspoň jednu přiřazenou interakci
- `call_answer_rate` = podíl přijatých / answered hovorů z celkových hovorů na účtu
- `avg_contacts_per_active_day` = průměr interakcí v aktivních dnech

## Omezení
- Nepřiřazené položky nejsou započtené do výkonu konkrétních lidí
- Objem interakcí není automaticky kvalita ani produktivita
- Sdílené účty jsou z hlavního srovnání vyřazené, aby nedeformovaly pořadí lidí
