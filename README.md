# GoldExpOverlay

A real-time overlay for **Spirit Vale** that tracks gold, experience, and farming stats — all in a compact, always-on-top window.

---

## Features

- **Gold tracking** — current gold, farm per hour, 5-minute window, net profit
- **Base & Job EXP** — live EXP percentage, %/h rate, 5-minute gains, ETA to next level
- **Session timer** — elapsed time in hh:mm:ss
- **Goals** — set target level, job level, and gold; see ETA for each
- **Auto-update** — the overlay checks for new versions on startup and updates itself automatically
- **License system** — access is controlled per-machine via a unique ID

---

## How to Get Access

1. Download and run `GoldExpOverlay.exe`
2. A window will appear showing your unique ID — click **Copiar ID** to copy it
3. Join our Discord and request access: **[https://discord.gg/mGsYTNbrgY](https://discord.gg/mGsYTNbrgY)**
4. Send your ID to an admin
5. Once approved, restart the overlay — it will open automatically

### Price

| Option | Cost |
|--------|------|
| In-game gold | 1,000,000 (1kk) |
| Real money | $4.99 USD |

---

## Como Obter Acesso

1. Baixe e execute o `GoldExpOverlay.exe`
2. Uma janela vai aparecer mostrando seu ID unico — clique em **Copiar ID** para copia-lo
3. Entre no nosso Discord e solicite acesso: **[https://discord.gg/mGsYTNbrgY](https://discord.gg/mGsYTNbrgY)**
4. Envie seu ID para um administrador
5. Apos aprovado, reinicie o overlay — ele abrira automaticamente

### Preco

| Opcao | Custo |
|-------|-------|
| Gold no jogo | 1.000.000 (1kk) |
| Dinheiro real | $4.99 USD |

---

## Usage

1. Launch `GoldExpOverlay.exe`
2. The overlay appears in the top-right corner of your screen
3. **Drag** the overlay to reposition it
4. Click **Reset** to reset session stats
5. Click **Meta** to set goals (target level, job level, gold amount)

The overlay automatically attaches to the game and starts tracking. If the game is not running, it will keep waiting and attach when it launches.

---

## Stats Explained

| Stat | Description |
|------|-------------|
| **Sessao** | Session duration (hh:mm:ss) |
| **Gold** | Current gold amount |
| **Farm/h** | Gold farmed this session, per hour rate |
| **5min** | Gold gained in the last 5 minutes |
| **Liquido** | Net gold (income minus expenses) |
| **Exp %** | Current EXP percentage toward next level |
| **%/h** | EXP gained per hour as a percentage |
| **5min %** | EXP gained in last 5 minutes as a percentage |
| **ETA** | Estimated time to next level (hh:mm) |
| **Metas** | Goals with ETA to reach them |

---

## Technical

- Built with Python, Tkinter, and PyInstaller
- Reads game memory via pointer chains (IL2CPP)
- No game files are modified — read-only memory access
- Auto-updates from this repository

---

## Support

For questions, issues, or access requests, join our Discord:

[https://discord.gg/mGsYTNbrgY](https://discord.gg/mGsYTNbrgY)
