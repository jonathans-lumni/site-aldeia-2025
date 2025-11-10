# Guia de Hospedagem do Site da Aldeia

## Opções Recomendadas para Hospedagem

### 1. **Netlify** (Recomendado - Mais Fácil)
**Vantagens:**
- ✅ Gratuito para sites estáticos
- ✅ Deploy muito simples (arrastar e soltar ou via Git)
- ✅ HTTPS automático
- ✅ CDN global (site rápido em qualquer lugar)
- ✅ Fácil adicionar domínio próprio depois
- ✅ Sem necessidade de servidor

**Como usar:**
1. Acesse [netlify.com](https://www.netlify.com)
2. Crie uma conta gratuita
3. Arraste a pasta do site para a área de deploy
4. Seu site estará online em segundos com um link tipo: `seu-site.netlify.app`
5. Para adicionar seu domínio: vá em "Domain settings" → "Add custom domain" → digite `aldeiaescola.com.br`

**Custo:** Gratuito (plano básico é suficiente)

---

### 2. **Vercel** (Alternativa Excelente)
**Vantagens:**
- ✅ Gratuito
- ✅ Deploy automático via Git
- ✅ HTTPS automático
- ✅ Muito rápido
- ✅ Fácil adicionar domínio

**Como usar:**
1. Acesse [vercel.com](https://vercel.com)
2. Crie conta gratuita
3. Conecte com GitHub (ou faça upload direto)
4. Site online imediatamente
5. Para domínio: Settings → Domains → Add

**Custo:** Gratuito

---

### 3. **GitHub Pages** (Gratuito e Simples)
**Vantagens:**
- ✅ Totalmente gratuito
- ✅ Integração com GitHub
- ✅ HTTPS automático
- ✅ Pode usar domínio próprio

**Como usar:**
1. Crie conta no [GitHub](https://github.com)
2. Crie um repositório
3. Faça upload dos arquivos
4. Vá em Settings → Pages → escolha a branch
5. Site ficará em: `seu-usuario.github.io/nome-repositorio`
6. Para domínio: adicione arquivo `CNAME` com seu domínio

**Custo:** Gratuito

---

### 4. **Hospedagem Tradicional (Hostinger, HostGator, etc.)**
**Vantagens:**
- ✅ Controle total
- ✅ Suporte em português
- ✅ Já vem com domínio em alguns planos

**Desvantagens:**
- ⚠️ Requer conhecimento de FTP
- ⚠️ Mais complexo que as opções acima
- ⚠️ Geralmente pago (R$ 10-30/mês)

**Como usar:**
1. Contrate um plano de hospedagem
2. Acesse via FTP (FileZilla, por exemplo)
3. Faça upload de todos os arquivos para a pasta `public_html` ou `www`
4. Configure o domínio no painel

**Custo:** R$ 10-30/mês

---

## Recomendação Final

**Para começar rápido e fácil:** Use **Netlify**
- É gratuito
- Deploy em segundos
- Fácil adicionar domínio depois
- Não precisa de conhecimento técnico avançado

**Passo a passo Netlify:**

1. **Acesse:** https://www.netlify.com
2. **Clique em:** "Sign up" (pode usar email ou GitHub)
3. **No painel:** Arraste a pasta completa do site para a área "Want to deploy a new site without connecting to Git? Drag and drop your site output folder here"
4. **Aguarde:** O site será publicado automaticamente
5. **Você receberá:** Um link tipo `aleatorio-123.netlify.app`
6. **Para adicionar seu domínio:**
   - Vá em "Site settings"
   - Clique em "Domain management"
   - Clique em "Add custom domain"
   - Digite: `aldeiaescola.com.br`
   - Siga as instruções para configurar o DNS no seu provedor de domínio

**Configuração do DNS (quando adicionar domínio):**
No seu provedor de domínio (Registro.br, GoDaddy, etc.), adicione:
- Tipo: `A` ou `CNAME`
- Valor: O que o Netlify fornecer (geralmente um IP ou `cname.netlify.com`)

---

## Migração Futura para Domínio Próprio

Todas as opções acima permitem adicionar domínio próprio facilmente:

1. **Netlify/Vercel:** Basta adicionar o domínio nas configurações
2. **GitHub Pages:** Adicione arquivo `CNAME` com o domínio
3. **Hospedagem tradicional:** Já vem configurado

**Importante:** Quando adicionar o domínio, atualize também:
- O arquivo `sitemap.xml` (URLs)
- As meta tags `og:url` e `canonical` em cada página HTML
- O structured data (JSON-LD) com a URL correta

---

## Dúvidas?

Se precisar de ajuda com o deploy ou configuração do domínio, posso ajudar com os passos específicos!

