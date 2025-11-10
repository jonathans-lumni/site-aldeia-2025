# Site Aldeia - Escola de Educação Infantil

Site institucional da Aldeia, escola de educação infantil em São José dos Campos - SP.

## 🎯 Características

- **Design Moderno e Responsivo**: Site totalmente adaptável para desktop, tablet e mobile
- **Otimizado para SEO**: Meta tags, structured data (Schema.org), sitemap.xml e robots.txt
- **Performance**: Código otimizado e carregamento rápido
- **Acessibilidade**: Estrutura semântica HTML5 e boas práticas de acessibilidade

## 📁 Estrutura do Projeto

```
├── index.html              # Página principal
├── assets/
│   ├── css/
│   │   └── style.css      # Estilos do site
│   └── js/
│       └── script.js       # JavaScript do site
├── sitemap.xml            # Sitemap para SEO
├── robots.txt             # Arquivo para bots de busca
└── README.md              # Este arquivo
```

## 🚀 Como Usar

### Visualização Local

1. Abra o arquivo `index.html` em um navegador web moderno
2. Para melhor experiência, utilize um servidor local:
   - **VS Code**: Use a extensão "Live Server"
   - **Python**: Execute `python -m http.server 8000`
   - **Node.js**: Use `npx serve` ou `npx http-server`

### Deploy

1. Faça upload de todos os arquivos para o servidor web
2. Certifique-se de que o servidor está configurado para servir arquivos estáticos
3. Configure o domínio `aldeiaescola.com.br` para apontar para o servidor
4. Ative HTTPS (certificado SSL)

## ✨ Funcionalidades

### Seções do Site

- **Hero**: Banner principal com chamada para ação
- **Sobre**: Apresentação da escola e suas crenças
- **Nossa Aldeia**: Descrição dos espaços físicos
- **Pedagogia**: Pilares educacionais (Vínculo Afetivo, Autonomia, Natureza)
- **Blog**: Últimos artigos publicados
- **Contato**: Formulário de contato e informações
- **Trabalhe Conosco**: Informações para candidatos

### Recursos Interativos

- Menu responsivo para mobile
- Formulário de contato com validação
- Scroll suave entre seções
- Animações na rolagem (fade in)
- Header que muda ao rolar a página
- Links ativos baseados na seção visível

## 🔧 Personalização

### Cores

As cores podem ser ajustadas no arquivo `assets/css/style.css` nas variáveis CSS:

```css
:root {
    --primary-color: #8B6F47;
    --primary-dark: #6B5333;
    --primary-light: #A68B66;
    --secondary-color: #D4A574;
    --accent-color: #E8D5B7;
    /* ... */
}
```

### Fontes

O site utiliza:
- **Títulos**: Playfair Display (Google Fonts)
- **Texto**: Poppins (Google Fonts)

Para alterar, edite o `index.html` e `style.css`.

### Imagens

Substitua os placeholders de imagem por fotos reais da escola. Os placeholders estão marcados com a classe `.image-placeholder`.

## 📧 Formulário de Contato

O formulário de contato está configurado para enviar dados. Você precisará:

1. Configurar um endpoint de API para receber os dados
2. Atualizar o código em `assets/js/script.js` na função de submit do formulário
3. Ou integrar com um serviço como:
   - Formspree
   - Netlify Forms
   - Google Forms
   - EmailJS

### Exemplo com EmailJS

```javascript
// No script.js, substitua a função de submit
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', contactForm)
    .then(() => {
        // Sucesso
    }, (error) => {
        // Erro
    });
```

## 🔍 SEO

### Otimizações Implementadas

- ✅ Meta tags (description, keywords, Open Graph, Twitter Cards)
- ✅ Structured Data (Schema.org) - EducationalOrganization
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ URLs semânticas
- ✅ Títulos hierárquicos (H1, H2, H3)
- ✅ Alt text para imagens (adicionar quando inserir imagens reais)
- ✅ Links canônicos

### Próximos Passos para SEO

1. **Google Search Console**: Adicionar e verificar o site
2. **Google Analytics**: Adicionar código de rastreamento
3. **Imagens**: Adicionar alt text descritivo em todas as imagens
4. **Conteúdo**: Expandir conteúdo com palavras-chave relevantes
5. **Links Internos**: Adicionar mais links internos entre páginas
6. **Velocidade**: Otimizar imagens e usar lazy loading
7. **Mobile-Friendly**: Testar no Google Mobile-Friendly Test

## 📱 Redes Sociais

Links configurados para:
- Instagram: @aldeiaeducacaoinfantil
- Facebook: aldeiaeducacaoinfantil
- YouTube: @aldeiaeducacaoinfantil

Certifique-se de que os links estão corretos e atualize se necessário.

## 📞 Informações de Contato

- **Endereço**: Rua Fagundes Varela, 340 - Vila Betania - São José dos Campos/SP
- **Telefone**: (12) 98139-2323
- **E-mail**: atendimento@aldeiaescola.com.br
- **Horário**: 7:30 - 18:00, de segunda a sexta-feira

## 🛠️ Manutenção

### Atualizar Conteúdo

- Edite diretamente o `index.html` para mudanças de texto
- Edite `assets/css/style.css` para mudanças de estilo
- Edite `assets/js/script.js` para mudanças de funcionalidade

### Adicionar Posts do Blog

Quando houver uma página de blog dedicada, adicione os novos posts ao HTML ou crie um sistema de CMS.

## 📄 Licença

Todos os direitos reservados - Aldeia Escola © 2024

## 👨‍💻 Desenvolvimento

Site desenvolvido seguindo as melhores práticas de:
- HTML5 Semântico
- CSS3 Moderno (Flexbox, Grid, Variables)
- JavaScript Vanilla
- SEO e Acessibilidade
- Design Responsivo Mobile-First

---

**Versão**: 1.0.0  
**Última atualização**: 2024

