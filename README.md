# Diário do Sobrevivente

> Portfólio pessoal do **Agnello "Gonello" Henrique** — um diário de sobrevivência em forma de site, com estética gótica de brasa e musgo.

Um site sobre mim: quem eu sou, os jogos que me prendem, os animes que curto, o meu setup e por onde me encontrar. Tudo embrulhado numa atmosfera de apocalipse sombrio — fogueira acesa, brasas subindo pela tela e o registro de quantos dias eu venho resistindo.

**Acesse ao vivo:** `https://philfino98.github.io/SEU-REPOSITORIO/`

---

## O que tem aqui

- **Sobre** — quem é o Gonello: dev front-end, baiano, fã de sobrevivência e estratégia. Um painel (HUD) mostra minha idade e os dias de sobrevivência calculados automaticamente desde a data de nascimento, além do meu status na Twitch em tempo real.
- **Ao vivo** — quando estou transmitindo na Twitch, a live e o chat aparecem direto aqui no site. Tem um selo que alterna entre **ao vivo** e **offline** sozinho, e um **mini player flutuante** que te acompanha enquanto você rola a página.
- **Jogos** — minha coleção, de soulslikes implacáveis a sandboxes de sobrevivência e construção. Cada card abre os detalhes do jogo, e o meu favorito fica em destaque: **Project Zomboid**.
- **Animes & Mangás** — os títulos que marcaram, com destaque pra saga **JoJo's Bizarre Adventure** (favorito: Parte 5, *Golden Wind*).
- **Setup / Inventário** — meu arsenal de batalha: notebook, mouse, headset, microfone, controles e monitor, cada um com a ficha técnica.
- **Contato** — todas as minhas redes reunidas num lugar só.

---

## Destaques

- Brasas animadas subindo pela tela inteira, geradas via JavaScript.
- Cabeçalho fixo com indicador deslizante e marcação automática da seção atual conforme você rola.
- Contadores que sobem sozinhos (idade, dias de sobrevivência, nº de jogos e de animes).
- Cards que abrem janelas (modais) com a capa e a descrição de cada item.
- Integração com a Twitch: player e chat embutidos, status **online/offline** em tempo real e mini player flutuante.
- Animações suaves de "rolar e aparecer".
- Totalmente responsivo — funciona bem no computador e no celular.

---

## Identidade visual

Paleta gótica de "diário de sobrevivência", em tons de brasa e musgo:

| Cor | Hex | Uso |
|-----|-----|-----|
| Fundo | `#13140e` | base escura |
| Brasa | `#ef7d3a` | destaque principal |
| Musgo | `#9aa85a` | "ao vivo" / acentos |
| Ferrugem | `#c0432f` | "offline" / alertas |
| Texto | `#e8e2d0` | leitura |

Tipografia em serifada (Georgia) para os títulos e monoespaçada para os detalhes técnicos.

---

## Tecnologias

- **HTML5**, **CSS3** e **JavaScript** puro (vanilla) — sem frameworks, sem dependências externas.
- Hospedado no **GitHub Pages**.
- Integração com a **Twitch** (player + chat) e com o **decapi.me** (status da live).

Sem build e sem `npm install`: é só HTML, CSS e JS prontos pra servir.

---

## Estrutura

```
.
├── portfolio.html      # a página inteira (HTML + CSS + JS num arquivo só)
└── imagens/            # capas dos jogos e animes
```

---

## Como rodar

**Online:** já está no ar pelo GitHub Pages.

**Local:** como a live da Twitch só carrega a partir de um domínio, o ideal é servir os arquivos em vez de abrir direto:

```bash
# com Python instalado
python -m http.server
# depois abra http://localhost:8000/portfolio.html
```

Abrir o arquivo com dois cliques funciona pra tudo, menos a transmissão da Twitch.

> Dica: pra o site abrir já na raiz do GitHub Pages, renomeie `portfolio.html` para `index.html`.

---

## Onde me encontrar

- **Twitch:** [philfino98](https://www.twitch.tv/philfino98)
- **Instagram:** [@oficialagnellohenrique](https://www.instagram.com/oficialagnellohenrique/)
- **GitHub:** [Philfino98](https://github.com/Philfino98)
- **X:** [@Philfino98](https://x.com/Philfino98)
- **Discord:** [servidor](https://discord.gg/NQnAhPhuCD)

---

> Projeto pessoal e sem fins comerciais. Todos os nomes, marcas, logos, personagens e capas de jogos e animes citados aqui pertencem aos seus respectivos criadores e detentores de direitos.
