# Brainstorming · Brainstorming — Claude Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Claude Skill](https://img.shields.io/badge/Claude-Skill-D97757)

**[Português](#português) · [English](#english)**

---

## Português

Uma [skill](#o-que-é-uma-skill) para o **Claude** (Claude Code, app Claude e claude.ai).

### O que faz

Brainstorming sobre **qualquer tema** — presentes, nomes, eventos, negócios, conteúdos, soluções para um problema. O Claude pensa em muitas direções diferentes (a óbvia, a criativa, a barata, a ousada) e entrega só as **2 a 3 melhores e mais distintas entre si**, cada uma concreta o suficiente para pôr em prática amanhã.

### Quando é ativada

O Claude usa-a sozinho quando pedes algo como:

- "Ideias para o aniversário do meu pai"
- "Ajuda-me a pensar num nome para a loja"
- "Não sei o que fazer com o jardim"
- "Dá-me sugestões para um vídeo do YouTube"

Também a podes chamar diretamente com `/brainstorming`.

### O que recebes

Cada ideia vem sempre com:

- O que é
- Porque funciona
- Como pôr em prática
- Custo / esforço
- Atenção a

No fim, o Claude diz qual recomenda e porquê, e oferece-se para aprofundar.

Vê um exemplo completo em [`examples/exemplo.md`](examples/exemplo.md).

### Detalhes

- Se faltar algo essencial (ex.: orçamento), faz uma única pergunta curta; senão assume valores razoáveis e diz quais.
- Para apps/jogos novos, funcionalidades ou monetização, cede o lugar às skills especializadas da família.
- Responde na língua em que escreves — as instruções estão em português, mas funciona em qualquer língua.

### Instalação

**Claude Code (para todos os teus projetos)**

```bash
git clone https://github.com/mozuraa/claude-skill-brainstorming.git ~/.claude/skills/brainstorming
```

**Claude Code (só num projeto)** — dentro da pasta do projeto:

```bash
git clone https://github.com/mozuraa/claude-skill-brainstorming.git .claude/skills/brainstorming
```

Abre uma sessão nova para a skill ser carregada.

**App Claude / claude.ai**

1. Nesta página, carrega em **Code → Download ZIP**.
2. No Claude, abre as **Definições** e procura a secção **Skills** (em *Capacidades*).
3. Carrega o ZIP. A skill fica disponível nas tuas conversas.

> As skills personalizadas precisam de estar ativadas na tua conta/organização.

### Atualizar

```bash
cd ~/.claude/skills/brainstorming && git pull
```

### O que é uma skill?

Uma skill é uma pasta com um ficheiro `SKILL.md`: um nome, uma descrição de quando deve ser usada e instruções. O Claude lê só a descrição até ela ser útil; quando o pedido encaixa, carrega as instruções e segue-as. Não instala programas nem corre código — é só texto.

### Estrutura

```
claude-skill-brainstorming/
├── SKILL.md            # a skill (nome, descrição e instruções)
├── examples/
│   └── exemplo.md      # exemplo de pedido e resposta
├── README.md
├── CHANGELOG.md
└── LICENSE
```

### Família de skills de ideias

| Skill | Para quê |
|---|---|
| [`ideias-apps`](https://github.com/mozuraa/claude-skill-ideias-apps) | Ideias de apps e jogos |
| [`ideias-funcionalidades`](https://github.com/mozuraa/claude-skill-ideias-funcionalidades) | Ideias de funcionalidades |
| [`ideias-monetizacao`](https://github.com/mozuraa/claude-skill-ideias-monetizacao) | Ideias de monetização |
| [`brainstorming`](https://github.com/mozuraa/claude-skill-brainstorming) *(esta)* | Brainstorming |

### Contribuir

Sugestões e melhorias são bem-vindas: abre uma *issue* ou um *pull request*. Se a skill não se ativou quando devia (ou ativou quando não devia), diz qual foi o pedido — ajuda a afinar a descrição.

### Licença

[MIT](LICENSE) — podes usar, alterar e partilhar livremente, mantendo o aviso de licença.

---

## English

A [skill](#what-is-a-skill) for **Claude** (Claude Code, the Claude app and claude.ai).

### What it does

Brainstorming on **any topic** — gifts, names, events, businesses, content, solutions to a problem. Claude explores many directions (the obvious, the creative, the cheap, the bold) and delivers only the **2–3 best and most distinct**, each concrete enough to act on tomorrow.

### When it triggers

Claude uses it on its own when you ask things like:

- "Ideas for my dad's birthday"
- "Help me come up with a name for my shop"
- "I don't know what to do with my garden"
- "Give me ideas for a YouTube video"

You can also call it directly with `/brainstorming`.

### What you get

Every idea always includes:

- What it is
- Why it works
- How to do it
- Cost / effort
- Watch out for

At the end, Claude says which one it recommends and why, and offers to go deeper.

See a full example in [`examples/exemplo.md`](examples/exemplo.md) (in Portuguese).

### Details

- If something essential is missing (e.g. budget) it asks one short question; otherwise it assumes sensible values and says which.
- For new apps/games, features or monetization, it defers to the specialised skills in this family.
- Replies in the language you write in — the instructions are in Portuguese, but it works in any language.

### Installation

**Claude Code (all your projects)**

```bash
git clone https://github.com/mozuraa/claude-skill-brainstorming.git ~/.claude/skills/brainstorming
```

**Claude Code (one project only)** — from the project folder:

```bash
git clone https://github.com/mozuraa/claude-skill-brainstorming.git .claude/skills/brainstorming
```

Start a new session so the skill is loaded.

**Claude app / claude.ai**

1. On this page, click **Code → Download ZIP**.
2. In Claude, open **Settings** and find the **Skills** section (under *Capabilities*).
3. Upload the ZIP. The skill becomes available in your chats.

> Custom skills must be enabled for your account/organization.

### Updating

```bash
cd ~/.claude/skills/brainstorming && git pull
```

### What is a skill?

A skill is a folder with a `SKILL.md` file: a name, a description of when it should be used, and instructions. Claude only reads the description until it becomes relevant; when a request matches, it loads the instructions and follows them. It installs no programs and runs no code — it's just text.

### Idea skills family

| Skill | What for |
|---|---|
| [`ideias-apps`](https://github.com/mozuraa/claude-skill-ideias-apps) | App & game ideas |
| [`ideias-funcionalidades`](https://github.com/mozuraa/claude-skill-ideias-funcionalidades) | Feature ideas |
| [`ideias-monetizacao`](https://github.com/mozuraa/claude-skill-ideias-monetizacao) | Monetization ideas |
| [`brainstorming`](https://github.com/mozuraa/claude-skill-brainstorming) *(this one)* | Brainstorming |

### Contributing

Suggestions and improvements are welcome: open an issue or a pull request. If the skill didn't trigger when it should have (or did when it shouldn't), share the prompt — it helps tune the description.

### License

[MIT](LICENSE) — free to use, modify and share, keeping the license notice.
