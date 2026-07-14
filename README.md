# PO-133 Groovebox

Groovebox web inspirada nos **Pocket Operators** e no **EP-133 K.O. II** da Teenage Engineering.

Um único arquivo HTML, zero dependências — todos os sons são sintetizados em tempo real com a Web Audio API.

## Recursos

- **28 sons sintetizados**: 12 beats (bumbo, bumbo 808, caixas, palma, chimbais, shaker, tons, rim, cowbell), 8 graves (sub estilo 808 + baixo ácido) e 8 sintetizadores (lead + pluck)
- **6 kits de gênero** (clássico, rap, trap, pop, funk, eletro): os mesmos pads mudam de timbre conforme o estilo, e o botão RITMO PRONTO carrega o groove típico com o BPM certo
- **Sequenciador de 16 ou 32 passos** estilo Pocket Operator, uma trilha por som
- **Teclado sintetizador polifônico** com 5 motores (analog, quadra, FM, pluck, cordas), glissando, filtro, envelope, reverb de convolução e eco sincronizado com o BPM
- **Gravação do teclado no beat**: arme ● GRAVAR, dê play e toque — as notas entram quantizadas no compasso e ficam em loop
- **4 slots de sample**: grave até 4 segundos com o microfone, ou use ● RESAMPLE para capturar o que está tocando
- **6 temas de cores + 4 cores personalizáveis** (destaque, painel, pads, display)
- **BPM de 50 a 240**, tudo salvo automaticamente no navegador
- **Otimizado para celular**: resposta imediata ao toque, barra de transporte fixa, zoom bloqueado, vibração nos pads, som funciona com o iPhone no silencioso
- **Atalhos no PC**: `1–8 q w e r` beats · `a s d f` sub · `g h j k` acid · `z x c v` lead · `b n m ,` pluck · `espaço` play/stop

## Como usar

1. Toque num som para tocá-lo e selecioná-lo
2. Marque os passos da sequência
3. Aperte **PLAY**

## Rodando localmente

Abra o `index.html` no navegador. Para gravar samples com o microfone é preciso servir via `localhost` ou HTTPS:

```bash
npx serve .
```
