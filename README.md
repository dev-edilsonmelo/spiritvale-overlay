# GoldExpOverlay

Um overlay em tempo real para **Spirit Vale** que rastreia gold, experiencia e estatisticas de farm — tudo em uma janela compacta, sempre visivel.

---

## Funcionalidades

- **Rastreamento de Gold** — gold atual, farm por hora, janela de 5 minutos, lucro liquido
- **Exp Base e Classe** — porcentagem de EXP ao vivo, taxa %/h, ganhos de 5 minutos, ETA para o proximo nivel
- **Tempo de sessao** — tempo decorrido em hh:mm:ss
- **Metas** — defina nivel alvo, nivel de classe e gold; veja o ETA para cada um
- **Auto-atualizacao** — o overlay verifica novas versoes ao iniciar e se atualiza automaticamente
- **Sistema de licenca** — o acesso e controlado por maquina atraves de um ID unico

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
| Dinheiro real | R$ 4,99 |

---

## Como Usar

1. Execute o `GoldExpOverlay.exe`
2. O overlay aparece no canto superior direito da tela
3. **Arraste** o overlay para reposiciona-lo
4. Clique em **Reset** para reiniciar as estatisticas da sessao
5. Clique em **Meta** para definir metas (nivel alvo, nivel de classe, quantidade de gold)

O overlay se conecta automaticamente ao jogo e comeca a rastrear. Se o jogo nao estiver aberto, ele vai esperar e se conectar quando o jogo for iniciado.

---

## Estatisticas

| Stat | Descricao |
|------|-----------|
| **Sessao** | Tempo de sessao (hh:mm:ss) |
| **Gold** | Quantidade de gold atual |
| **Farm/h** | Gold farmado na sessao, taxa por hora |
| **5min** | Gold ganho nos ultimos 5 minutos |
| **Liquido** | Gold liquido (ganhos menos gastos) |
| **Exp %** | Porcentagem atual de EXP para o proximo nivel |
| **%/h** | EXP ganha por hora em porcentagem |
| **5min %** | EXP ganha nos ultimos 5 minutos em porcentagem |
| **ETA** | Tempo estimado para o proximo nivel (hh:mm) |
| **Metas** | Metas com ETA para alcancar |

---

## Tecnico

- Feito com Python, Tkinter e PyInstaller
- Le a memoria do jogo via cadeias de ponteiros (IL2CPP)
- Nenhum arquivo do jogo e modificado — acesso somente leitura
- Auto-atualizacao a partir deste repositorio

---

## Suporte

Para duvidas, problemas ou solicitacoes de acesso, entre no nosso Discord:

[https://discord.gg/mGsYTNbrgY](https://discord.gg/mGsYTNbrgY)
