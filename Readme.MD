# Analisis Perancangan Sistem Informasi
**Pertemuan 5 (4/30/2024)**

## Diagram Jaringan

| Pekerjaan | Pendahuluan | Waktu (Hari) | ES | EF | LS | LF |
| :---: | :----: | :----: | :----: | :----: | :----: | :----: |
| A | - | 10 |  |  |  |  |
| B | - | 6 |  |  |  |  |
| C | - | 17 |  |  |  |  |
| D | A | 4 |  |  |  |  |
| E | A | 25 |  |  |  |  |
| F | E | 10 |  |  |  |  |
| G | D, F | 8 |  |  |  |  |
| H | B, C | 2 |  |  |  |  |
| I | G, H | 6 |  |  |  |  |

- Buattukan Diagram Jaringan
- Tentukan ES, EF, LS, EF
- Tentukan Jalur Kritis

Tentukan Jalur Kritis :

'''mermaid
  Flowchart LR

  I((START)) -->|10| A((A))
  A -->|4| D((D))
  D -->|8| G((G))
  G -->|6| J((I))
  A -->|25| E((E))
  E -->|10| F((F))
  F -->|8| G((G)) 
  I -->|6| B((B))
  B -->|2| H((H))
  I -->|17| C((C))
  C -->|2| H
  H -->|6| J
'''
