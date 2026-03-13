# Felipe Marta Batista - Portfólio

Portfólio pessoal desenvolvido com HTML5 e Tailwind CSS, hospedado no GitHub Pages.

## 🔗 Link do Site

[https://batistafelipe.github.io](https://batistafelipe.github.io)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Framework CSS utilitário (via CDN)
- **Google Fonts** - Fonte Inter
- **GitHub Pages** - Hospedagem gratuita

## 📋 Seções do Site

1. **Header** - Navegação fixa com links para as seções
2. **Hero** - Apresentação inicial
3. **Sobre Mim** - Descrição profissional
4. **Experiência** - Histórico profissional e educacional
5. **Habilidades** - Tecnologias e ferramentas
6. **Projetos** - Portfolio de projetos desenvolvidos
7. **Contato** - Links para e-mail, LinkedIn e GitHub

## 🚀 Como Rodar Localmente

### Opção 1: Abrir direto no navegador

1. Clone o repositório:

   ```bash
   git clone https://github.com/BatistaFelipe/BatistaFelipe.github.io.git
   ```

2. Entre na pasta:

   ```bash
   cd BatistaFelipe.github.io
   ```

3. Abra o arquivo `index.html` no navegador:
   - **Windows**: Clique duas vezes no arquivo
   - **Linux/Mac**: `open index.html` ou `xdg-open index.html`

### Opção 2: Usar um servidor local (recomendado)

Com Python 3:

```bash
python -m http.server 8000
```

Com Node.js (instale o `http-server`):

```bash
npx http-server -p 8000
```

Depois acesse: `http://localhost:8000`

## 📁 Estrutura de Arquivos

```
BatistaFelipe.github.io/
├── index.html          # Página principal
├── CNAME               # Configuração de domínio customizado
└── img/
    ├── favicon.ico     # Ícone do site (otimizado: 16, 32 e 48px)
    ├── profile.png     # Foto de perfil (fallback para navegadores antigos)
    └── profile.webp    # Foto de perfil em WebP (formato moderno e leve)
```

## ⚡ Otimizações Aplicadas

| Item | Antes | Depois | Redução |
|------|-------|--------|---------|
| `profile.png` | 359 KB | 66 KB | −82% |
| `profile.webp` | — | 5 KB | novo |
| `favicon.ico` | 141 KB | 1 KB | −99% |
| HTML semântico | `<main>` só no hero | `<main>` em todo o conteúdo | corrigido |
| Acessibilidade | sem `aria-expanded` | `aria-expanded` no menu mobile | corrigido |
| SEO | sem `canonical` | `<link rel="canonical">` | adicionado |

## 📞 Contato

- **E-mail**: [felipemartabatista@gmail.com](mailto:felipemartabatista@gmail.com)
- **LinkedIn**: [felipe-batista-b42364156](https://linkedin.com/in/felipe-batista-b42364156)
- **GitHub**: [BatistaFelipe](https://github.com/BatistaFelipe)

## 📄 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

---

**Desenvolvido com ❤️ por Felipe Marta Batista**
