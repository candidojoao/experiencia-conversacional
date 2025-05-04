# Chat da FURIA CS2 — Projeto Front-End

Este é um mini chat temático da FURIA Esports feito com HTML, CSS e JavaScript puro, a ideia é simples: uma interface estilizada, com respostas automáticas do bot, sons customizados e um toque da identidade visual da FURIA eSports!

---

## Primeiras orientações

### 1. Clonar o repositório

```bash
git clone https://github.com/candidojoao/experiencia-conversacional
cd chat-furia-cs
```

---

## Como rodar o projeto

1. Não tem segredo: o projeto é 100% client-side.
2. Basta abrir o arquivo `index.html` no navegador (pode dar dois cliques ou abrir com VS Code).
3. O chat já estará funcionando localmente.

---

## O que este projeto faz?

- Interface de chat estilizada no tema da FURIA.
- Bot que responde perguntas sobre o time (próximos jogos, elenco, história, etc).
- Campo de input com envio por botão ou tecla Enter.
- Efeito sonoro (tipo “headshot”) quando o bot responde.
- Link externo para ver próximos jogos/resultados.
- Totalmente responsivo e com visual moderno.

---

## Tecnologias usadas

- `HTML5` — marcação da estrutura
- `CSS3` — estilização com gradientes, sombras e responsividade
- `JavaScript` — lógica do bot e interação com DOM
- Nenhuma dependência externa: tudo no puro talento

---

## Estrutura de Arquivos

```bash
chat-furia-cs/
│
├── index.html            # Página principal
├── headshot.mp3          # Áudio de efeito
├── furia-resultados.html # Página de resultados (opcional)
└── README.md             # Este arquivo
```

---

## Comentários sobre o código

> O projeto está inteiramente comentado direto no HTML, CSS e JS.  
> A ideia é que qualquer pessoa que abra o código entenda rapidamente o que está rolando, sem precisar de documentação técnica chata.

Exemplo de comentário usado no projeto:

```js
// Se o usuário digitar "jogo" ou "partida", o bot responde com a próxima partida
if (msg.includes('jogo') || msg.includes('partida')) {
  return 'O próximo confronto da FURIA é contra a NAVI no sábado às 18h! 🔥';
}
```

---

## Créditos e Inspiração

- Logo oficial da FURIA: [Wikipédia](https://pt.wikipedia.org/wiki/Furia_Esports)
- Áudio `headshot.mp3`: qualquer efeito sonoro leve (pode ser customizado)
- Layout inspirado na identidade dark/clean da FURIA

---

## Contribuindo...

Quer melhorar o bot? Adicionar integração com API real da HLTV? Fique à vontade

1. Fork o projeto
2. Crie sua branch com a melhoria:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit e push:
   ```bash
   git commit -m 'feat: nova resposta do bot'
   git push origin minha-feature
   ```
4. Abre um pull request :))

---

## Screenshot

> (Adicione aqui uma imagem do projeto rodando. (pode usar o atalho no VS Code)
