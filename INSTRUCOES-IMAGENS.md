# Instruções para Adicionar Imagens

## Logo
1. Copie o arquivo `Logo - Aldeia.png` para `assets/images/logo-aldeia.png`

## Fotos da Aldeia
Copie as seguintes fotos da pasta `fotos-aldeia/` para `assets/images/`:

- `1.jpg` → `assets/images/1.jpg`
- `2.jpg` → `assets/images/2.jpg`
- `5.JPG` → `assets/images/5.JPG`
- `7.jpg` → `assets/images/7.jpg`

**Nota**: Se algumas fotos estiverem no formato HEIC, você precisará convertê-las para JPG antes de usá-las no site.

## Imagens do Blog
Para as imagens do blog funcionarem corretamente, você pode:
1. Usar as mesmas fotos da Aldeia
2. Ou criar imagens específicas para cada post do blog e salvá-las em:
   - `assets/images/blog-1.jpg`
   - `assets/images/blog-2.jpg`
   - `assets/images/blog-3.jpg`

## Estrutura de Pastas Final

```
assets/
  images/
    logo-aldeia.png
    fotos-aldeia/
      1.jpg
      2.jpg
      5.JPG
      7.jpg
    blog-1.jpg (opcional)
    blog-2.jpg (opcional)
    blog-3.jpg (opcional)
```

## Comandos PowerShell (se necessário)

```powershell
# Criar diretório para fotos
New-Item -ItemType Directory -Force -Path "assets\images\fotos-aldeia"

# Copiar logo
Copy-Item "Logo - Aldeia.png" -Destination "assets\images\logo-aldeia.png"

# Copiar fotos (exemplo)
Copy-Item "fotos-aldeia\1.jpg" -Destination "assets\images\fotos-aldeia\1.jpg"
Copy-Item "fotos-aldeia\2.jpg" -Destination "assets\images\fotos-aldeia\2.jpg"
Copy-Item "fotos-aldeia\5.JPG" -Destination "assets\images\fotos-aldeia\5.JPG"
Copy-Item "fotos-aldeia\7.jpg" -Destination "assets\images\fotos-aldeia\7.jpg"
```

