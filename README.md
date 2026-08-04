# Portfólio — Hugo Melo Carvalho

Portfólio pessoal de Hugo Melo Carvalho, desenvolvedor full stack em formação. Site estático de página única que reúne projetos, stack, experiência e canais de contato.

🔗 **Acesse:** [LINK-VERCEL-AQUI]

<!-- Preview opcional: adicione um screenshot chamado preview.png na raiz e descomente a linha abaixo -->
<!-- ![Preview do portfólio](./preview.png) -->

## 📌 Sobre

Sou estudante de Ciência da Computação com foco em desenvolvimento web full stack. Este site apresenta meu projeto em destaque (**Contrataí**, SaaS de RH com IA), outros projetos em produção, minha stack, experiência profissional e um FAQ voltado tanto a recrutadores quanto a clientes de projetos sob encomenda. O contato principal é via WhatsApp, com CV disponível para download.

## 🛠 Stack técnica do site

Feito com o essencial, sem framework e sem etapa de build — por opção:

- **HTML5** semântico
- **CSS3** — custom properties (variáveis), CSS Grid e Flexbox, design responsivo
- **JavaScript vanilla** — `IntersectionObserver` para o scroll reveal e o terminal animado do hero, sem nenhuma dependência externa
- **Google Fonts** (Space Grotesk, Inter, JetBrains Mono) — único recurso carregado de fora

Zero-build, zero-framework, zero-dependência de propósito: carrega rápido, não tem passo de compilação e não há biblioteca que possa quebrar.

## 📁 Estrutura de arquivos

```
.
├── index.html                  # todo o site (HTML + CSS + JS inline)
├── hugo-foto.jpeg              # foto do hero
└── CV-Hugo-Melo-Carvalho.pdf   # currículo para download
```

Os três arquivos precisam ficar **juntos na raiz** no deploy: a foto e o CV são referenciados por caminho relativo simples dentro do `index.html`.

## 💻 Como rodar localmente

Como é um site estático, basta uma das opções:

- **Abrir direto:** dê duplo clique no `index.html` (ou arraste para o navegador).
- **Servir localmente** (recomendado, evita restrições de caminho):
  ```bash
  python3 -m http.server
  ```
  e acesse `http://localhost:8000`. Alternativa: extensão **Live Server** do VS Code.

## 🚀 Deploy

Hospedado na **Vercel** como site estático. Não há configuração de build: a Vercel serve os arquivos da raiz diretamente.

## 🧭 Seções do site

| Âncora | Conteúdo |
|---|---|
| `#sobre` | Quem sou, formação e forma de trabalhar |
| `#diferenciais` | "Como eu trabalho" — pontos fortes em cards |
| `#stack` | Tecnologias que uso no dia a dia |
| `#projeto` | Projeto em destaque: Contrataí |
| `#outros-projetos` | Outros projetos em produção (agendamento, agenda, bolão) |
| `#experiencia` | Linha do tempo profissional e cursos |
| `#faq` | Perguntas frequentes (vaga CLT/estágio e freelance) |
| `#contato` | Canais de contato e download do CV |

## 📬 Contato

- **E-mail:** hugomelo742@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/hugo-melo-dev/
- **GitHub:** https://github.com/hugordm

## 📄 Licença e uso

O código é livre para servir de inspiração e estudo. Peço apenas que **não reutilize diretamente minha foto, meu currículo ou meu conteúdo pessoal** (textos, projetos e informações de contato).
