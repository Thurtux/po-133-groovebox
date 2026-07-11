# PO-133 Groovebox

Groovebox web inspirada nos **Pocket Operators** e no **EP-133 K.O. II** da Teenage Engineering.

Um único arquivo HTML, zero dependências — todos os sons são sintetizados em tempo real com a Web Audio API.

## Recursos

- **28 sons sintetizados**: 12 beats (bumbo, bumbo 808, caixas, palma, chimbais, shaker, tons, rim, cowbell), 8 graves (sub estilo 808 + baixo ácido) e 8 sintetizadores (lead + pluck)
- **Sequenciador de 16 passos** estilo Pocket Operator, uma trilha por som
- **4 slots de sample**: grave até 4 segundos com o microfone e sequencie como qualquer outro som
- **BPM de 50 a 240**, padrão salvo automaticamente no navegador
- **Otimizado para celular**: resposta imediata ao toque, barra de transporte fixa, vibração ao tocar os pads
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
