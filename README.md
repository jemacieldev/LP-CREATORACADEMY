# Creator Academy | FMU + PlayNest

Landing page do **Creator Academy**, curso de criação de conteúdo digital realizado em parceria entre o **Centro Universitário FMU | FIAM-FAAM** e a **PlayNest**.

**[Ver a página no ar](https://fmu-content.s3.us-east-1.amazonaws.com/FMU/EAD/CREATOR_ACADEMY/LP-CreatorAcademy/index.html)**

![Preview da landing page do Creator Academy](assets/preview.png)

## Sobre o projeto

A página apresenta o curso para os estudantes: o que é, para quem serve, o que se aprende, quem ensina e como se inscrever. Ela conduz o visitante por uma sequência de seções, do contexto de mercado até a chamada para inscrição.

## Meu papel

Fui responsável pelo desenvolvimento front-end: estrutura em HTML, estilos, responsividade e as interações da página.

## Destaques

- **Quiz "Descubra seu perfil criador".** Perguntas em sequência com barra de progresso e resultado ao final, escrito em JavaScript puro.
- **Vídeos que reagem à rolagem.** Os players só tocam quando estão visíveis na tela e pausam quando o visitante sai da área.
- **Animações de entrada.** As seções aparecem conforme a rolagem, com `IntersectionObserver`, e os indicadores numéricos contam até o valor final.
- **Jornada em 7 passos e perguntas frequentes.** Conteúdo longo organizado em etapas e em blocos que abrem e fecham.
- **Layout responsivo.** Quatro pontos de quebra, de telas largas até celulares.
- **Acessibilidade.** Link para pular direto ao conteúdo, rótulos `aria` nos elementos interativos e animações desativadas para quem configura o sistema com `prefers-reduced-motion`.
- **SEO.** Dados estruturados em JSON-LD (schema.org) para descrever o curso aos buscadores.

## Tecnologias

- **HTML5** semântico
- **CSS3**, com variáveis para cores e espaçamentos
- **JavaScript** puro, sem bibliotecas
- **Cloudflare Stream** para os vídeos de apresentação
- **AWS S3** para a hospedagem

## Como executar localmente

```bash
git clone https://github.com/jemacieldev/LP-CREATORACADEMY.git
cd LP-CREATORACADEMY
```

Abra o arquivo `index.html` no navegador ou use a extensão **Live Server** no Visual Studio Code.

## Estrutura do projeto

```text
LP-CREATORACADEMY/
├── assets/
│   └── preview.png     imagem de capa deste README
├── icons/              imagens usadas na página
├── index.html          estrutura e scripts da página
├── style.css           estilos
└── README.md
```

## Equipe do projeto

| Integrante              | Atuação                   |
| ----------------------- | ------------------------- |
| Jessica Maciel da Silva | Desenvolvimento Front-end |
| Kamis Hora              | Desenvolvimento Back-end  |

## Créditos

Projeto desenvolvido colaborativamente para a apresentação institucional do **Creator Academy**, uma parceria entre o Centro Universitário FMU | FIAM-FAAM e a PlayNest.

As marcas, logotipos e demais elementos institucionais mencionados pertencem aos seus respectivos titulares.

Os vídeos da página não fazem parte deste repositório: são carregados diretamente da hospedagem oficial do projeto.
