# ABISSO — Enhanced Version

Roguelike multiplayer in tempo reale, senza server, in un unico file.

- 🎬 Video originale: https://www.youtube.com/watch?v=Pxu4IHBrLTU
- 🎮 Gioco originale: https://www.youdev.it/games/abisso.html
- 🚀 Questa versione: (https://sanciopanza88.github.io/Abisso-Enhanced-Version/)
## Come si gioca

1. Apri `abisso.html` in un browser moderno.
2. Scegli nome, classe e stanza, poi scendi nell'abisso.
3. Per giocare con altri condividi l'indirizzo (stessa stanza = stesso mondo).

## Miglioramenti rispetto all'originale

- **Grafica**: sprite PNG al posto degli emoji (eroi, mostri, mercante, forzieri), animazioni di attacco, respiro, ombre, ambientazione curata (pavimenti, muri, bagliori).
- **Torce e luci**: le stanze sono illuminate da torce tremolanti, visibili solo nelle zone esplorate.
- **Suoni**: effetti sonori e musiche generate al volo (nessun file audio), pulsante per silenziare.
- **Effetti visivi**: particelle, esplosioni, polvere ai passi, fendenti d'arma, schermo che trema.
- **Minimappa**: mostra mappa esplorata, scale, forzieri, mercante e compagni (tasto M).
- **Frecce ai bordi**: indicano dove sono i compagni fuori schermo.
- **Flash di danno**: lo schermo si tinge di rosso dal lato da cui arriva il colpo.
- **Multiplayer più affidabile**: connessioni più stabili, e se due mondi si dividono si ricongiungono da soli.
- **Qualità della vita**: barra HP nuova con flash, toast di benvenuto, clic sullo zoom per azzerarlo, pulsante d'interazione per il touch.

## Comandi

| Tasto | Azione |
|---|---|
| `WASD` / frecce | Movimento |
| `Spazio` | Attacco |
| `E` | Interagisci (forziere, scale, mercante, rianima) |
| `Q` | Pozione |
| `R` | Pozione di mana |
| `F` | Abilità di classe |
| `Invio` | Chat |
| `M` | Minimappa |

## Idee scartate / in sospeso

- **Animazioni multi-frame** per zombie e topo: i disegni (frame PNG) sono
  pronti in `assets/anim/`, ma non sono ancora usate nel gioco (il progetto è
  tornato agli sprite singoli). Non tutte le texture presenti nella cartella
  `assets` sono quindi implementate.
- Durante lo sviluppo alcune idee sono state provate e abbandonate (ad esempio
  l'animazione a più fotogrammi dello zombie), per evitare complicazioni.

## Bug

Progetto in evoluzione: il gioco presenterà sicuramente dei bug. Il
multiplayer dipende dalla rete (VPN, relay, firewall) e in condizioni
particolari i giocatori possono non vedersi subito; il gioco cerca comunque di
ricongiungere i mondi da solo. Se trovi un problema, segnalalo aprendo una
issue sul repository.
