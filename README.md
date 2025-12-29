# SEMED - Página Informativa

Página informativa estática da Secretaria Municipal de Educação (SEMED).

## 📋 Descrição

Site institucional desenvolvido com HTML, CSS e Tailwind CSS, apresentando informações sobre a SEMED, programas educacionais e materiais para download.

## 🚀 Tecnologias

- HTML5
- CSS3
- Tailwind CSS (via CDN)
- Font Awesome (ícones)
- JavaScript (vanilla)

## 📁 Estrutura de Arquivos

```
├── index.html              # Página principal
├── custom-semed.css        # Estilos personalizados SEMED
├── styles.css              # CSS original (para desenvolvimento Django)
├── images/
│   └── logos/              # Logos da SEMED
├── downloads/              # Pasta com arquivos para download
│   ├── manual-gestor-semed.pdf
│   ├── calendario-escolar-semed.pdf
│   ├── formularios-semed.xlsx
│   ├── apresentacao-institucional-semed.pptx
│   ├── plano-municipal-educacao-semed.pdf
│   └── legislacao-educacional-semed.pdf
└── README.md
```

## 🎨 Paleta de Cores

- **Primary**: #2E8B57 (Verde)
- **Secondary**: #17a2b8 (Azul)
- **Success**: #28a745
- **Error**: #dc3545
- **Warning**: #ffc107
- **Info**: #17a2b8

## 📦 Como Usar

### Visualização Local

Simplesmente abra o arquivo `index.html` em um navegador web.

### Deploy no GitHub Pages

1. Faça commit dos arquivos:
```bash
git add .
git commit -m "feat: página informativa SEMED"
git push origin main
```

2. Ative o GitHub Pages:
   - Vá em Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Clique em Save

3. A página estará disponível em: `https://[seu-usuario].github.io/[nome-do-repo]`

## 📥 Arquivos de Download

Os arquivos na pasta `downloads/` são placeholders. Substitua-os pelos arquivos reais mantendo os mesmos nomes:

- `manual-gestor-semed.pdf` - Manual para gestores escolares
- `calendario-escolar-semed.pdf` - Calendário escolar oficial
- `formularios-semed.xlsx` - Formulários e documentos
- `apresentacao-institucional-semed.pptx` - Apresentação institucional
- `plano-municipal-educacao-semed.pdf` - Plano Municipal de Educação
- `legislacao-educacional-semed.pdf` - Legislação educacional

## 🖼️ Logos

Coloque os logos da SEMED na pasta `images/logos/`:

- `logo-semed.png` - Logo principal
- `logo-semed.svg` - Logo em formato vetorial (opcional)
- `logo-semed-white.png` - Logo branco para fundos escuros
- `favicon.ico` - Favicon para o navegador
- `brasao-municipio.png` - Brasão do município (opcional)

## 🔧 Personalização

Para personalizar cores e estilos, edite o arquivo `custom-semed.css`.

### Alterar Cores Principais

```css
:root {
    --semed-primary: #2E8B57;        /* Verde principal */
    --semed-secondary: #17a2b8;      /* Azul secundário */
}
```

## 📱 Responsividade

O site é totalmente responsivo e se adapta a:
- Desktop (1024px+)
- Tablet (768px - 1023px)
- Mobile (< 768px)

## 🎯 Seções da Página

1. **Hero** - Banner principal com título e chamadas para ação
2. **Estatísticas** - Números da educação municipal
3. **Sobre** - Missão e visão da SEMED
4. **Recursos** - Programas e serviços oferecidos
5. **Downloads** - Materiais e documentos disponíveis
6. **Contato** - Formulário e informações de contato

## 🤝 Contribuindo

Para fazer alterações:

1. Edite o arquivo `index.html` para conteúdo
2. Edite o arquivo `custom-semed.css` para estilos
3. Adicione novos arquivos na pasta `downloads/`
4. Adicione logos na pasta `images/logos/`

## 📄 Licença

Este projeto é de propriedade da Secretaria Municipal de Educação (SEMED).

---

Desenvolvido para a Secretaria Municipal de Educação - 2025
