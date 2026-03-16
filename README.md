# 🧹 Markeri | Discord Bot

Umjesto da odmah banujete problematične korisnike, pošaljite ih na **markere**. Markeri Bot nudi inovativan sistem discipline koji omogućava moderatorima da izoluju korisnike i privremeno im oduzmu privilegije, uz mogućnost automatizovanog povratka rola.

> Više informacija na web stranici: https://seekiii.github.io/markeri-bot/

## Funkcionalnosti

- **Automatski Setup**: Bot sam kreira potrebne kanale, role i permisije.
- **Sistem Rola**: Sigurno spremanje korisnikovih rola prije slanja na markere.
- **Brzo Skidanje**: Jednostavno vraćanje svih prethodnih privilegija jednim klikom/komandom.
- **Prilagođavanje**: Mogućnost promjene identiteta bota (nickname, avatar, banner) direktno kroz komande.

## Instalacija

1. **Pozovite bota** na vaš server putem [ovog linka](https://discord.com/oauth2/authorize?client_id=1455500391205834885).
2. Pokrenite `/postavke setup` kako bi bot kreirao potrebnu infrastrukturu.
3. Osigurajte da je **Markeri Bot rola** iznad rola koje želite da bot skida/vraća u hijerarhiji servera.

## Lista Komandi

### Postavke i Konfiguracija
| Komanda | Opis |
| :--- | :--- |
| `/postavke setup` | Automatski postavlja marker kanale, role i permisije. |
| `/postavke setup-restart` | Briše postojeće postavke i ponovno kreira cijeli sistem. |
| `/postavke bot nickname` | Promjena nadimka bota na serveru. |
| `/postavke bot avatar` | Promjena avatara bota na serveru. |
| `/postavke bot banner` | Promjena bannera bota na serveru. |

### Upravljanje Markerima
| Komanda | Opis |
| :--- | :--- |
| `/markeri daj` | Šalje korisnika na markere (gubi role, dobija marker rolu). |
| `/markeri skini` | Skida markere i vraća korisniku sve prethodne role. |
| `/markeri dodaj` | Dodaje dodatne markere korisniku koji je već kažnjen. |
| `/markeri oduzmi` | Smanjuje broj markera (bez vraćanja rola). |
