# mp3-player-commands

# Comandi per lettore MP3 GD3800

Questi comandi permettono di controllare le funzioni di base del lettore MP3 GD3800.

| Funzione            | Comando HEX            |
|---------------------|------------------------|
| **Play loop**       | `7E 03 07 01 EF`       |
| **Stop loop**       | `7E 03 07 00 EF`       |
| **Play**            | `7E 02 01 EF`          |
| **Pause**           | `7E 02 02 EF`          |
| **Stop**            | `7E 02 0E EF`          |
| **Play/Pause toggle** | `7E 02 0F EF`       |
| **Play Random** - Start | `7E 03 08 01 EF`  |
| **Play Random** - Stop  | `7E 03 08 00 EF`  |
| **Reset / Restart** | `7E 02 0B EF`          |
| **Volume UP**       | `7E 02 05 EF`          |
| **Volume DOWN**     | `7E 02 06 EF`          |

## Note
- Ogni comando deve essere inviato al lettore MP3 esattamente come descritto.
- La terminazione `EF` segnala la fine di ciascun comando.
