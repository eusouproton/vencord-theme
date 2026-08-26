# Koz — Vencord Theme

Tema pessoal para Vencord/Discord baseado no Chillax, com visual transparente/frosted glass e wallpaper da Rem.

## Estrutura

```text
vencord-theme/
├── koz/
│   ├── koz.theme.css
│   ├── chillax-core-lite.css
│   ├── blurple-recolor-lite.css
│   └── README.md
├── rem.jpg
└── README.md
```

## Arquivos

- `koz/koz.theme.css` — ponto de entrada do tema.
- `koz/chillax-core-lite.css` — camada principal de transparência e superfícies do Chillax adaptadas para o tema.
- `koz/blurple-recolor-lite.css` — recolorização usada pelo tema.
- `koz/README.md` — documentação específica do tema.
- `rem.jpg` — wallpaper usado pelo tema.

## Instalação

No Vencord, use a URL abaixo como tema remoto:

```text
https://raw.githubusercontent.com/eusouproton/vencord-theme/main/koz/koz.theme.css
```

## Direção visual

- Wallpaper da Rem permanece nítido.
- Superfícies do Discord ficam translúcidas.
- O blur é aplicado de forma localizada, principalmente em superfícies de perfil/popout.
- Avatar, banner e imagens do perfil não recebem blur.
- Dependências externas do Chillax são mantidas apenas quando necessárias.

## Desenvolvimento

As alterações específicas do tema devem ficar dentro de `koz/`. O `rem.jpg` permanece na raiz para facilitar o carregamento pelo tema.
