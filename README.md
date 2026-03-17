# 🎀 Convite Helena

Página web de convite em vídeo para a Helena — exibe um vídeo em tela cheia, otimizado para dispositivos móveis, com fundo preto e sem distrações visuais.

## ✨ Funcionalidades

- **Vídeo em tela cheia** — responsivo, sem distorção, centralizado na tela
- **Autoplay inteligente** — tenta reproduzir com som automaticamente; caso o navegador bloqueie, inicia mutado e exibe um botão elegante para ativar o áudio
- **Compatível com mobile** — layout otimizado para celulares e tablets
- **Múltiplos formatos** — suporte a MP4, WebM e OGG como fallback
- **Sem controles visíveis** — experiência limpa e imersiva

## 📁 Estrutura do Projeto

```
Convite Helena/
├── index.html        # Página principal com player de vídeo
├── static/
│   ├── video.mp4     # Vídeo do convite (formato principal)
│   └── fundo.jpg     # Imagem de fundo
└── README.md
```

## 🚀 Como Usar

1. Coloque o vídeo do convite na pasta `static/` com o nome `video.mp4`
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Para compartilhar, hospede os arquivos em qualquer servidor web estático (GitHub Pages, Netlify, Vercel, etc.)

## 📱 Compatibilidade

| Navegador         | Suporte |
|--------------------|---------|
| Chrome (mobile/desktop) | ✅ |
| Safari (iOS/macOS)      | ✅ |
| Firefox                 | ✅ |
| Edge                    | ✅ |
| Samsung Internet        | ✅ |

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — layout com Flexbox, animações com `@keyframes`
- **JavaScript** — lógica de autoplay e ativação de áudio

## 📝 Notas

- Em dispositivos móveis, a maioria dos navegadores bloqueia o autoplay com som. O overlay com ícone de som aparece automaticamente nesses casos, pedindo um toque do usuário para ativar o áudio.
- O vídeo utiliza `object-fit: contain` para manter a proporção original sem cortar ou distorcer a imagem.
