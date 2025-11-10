# Instruções para Fazer Push do Site para o GitHub

## Opção 1: Usar Personal Access Token (Recomendado)

1. Acesse: https://github.com/settings/tokens
2. Clique em "Generate new token" > "Generate new token (classic)"
3. Dê um nome para o token (ex.: "site-aldeia-push")
4. Selecione o escopo: marque **todas as opções de `repo`**
5. Clique em "Generate token"
6. **Copie o token gerado** (você não poderá vê-lo novamente!)
7. Execute no terminal:

```powershell
git push -u origin main
```

Quando solicitado:
- **Username**: seu nome de usuário do GitHub (jonathans-lumni)
- **Password**: cole o token que você copiou (não use sua senha)

## Opção 2: Verificar se o Repositório Existe

1. Acesse: https://github.com/jonathans-lumni?tab=repositories
2. Verifique se o repositório `site-aldeia-2025` aparece na lista
3. Se não aparecer, crie novamente em: https://github.com/new
4. Certifique-se de que o nome está exatamente: `site-aldeia-2025`
5. Não marque nenhuma opção (README, .gitignore, license)
6. Clique em "Create repository"

## Opção 3: Usar GitHub Desktop

1. Instale o GitHub Desktop: https://desktop.github.com/
2. Abra o GitHub Desktop
3. File > Add Local Repository
4. Selecione a pasta: `C:\Users\jonsc\Documents\Back-up\Trabalho\Alvor\Aldeia\Site novo`
5. Clique em "Publish repository"
6. Selecione o repositório `site-aldeia-2025`
7. Clique em "Publish repository"

## Status Atual

- ✅ Repositório Git inicializado
- ✅ Arquivos commitados
- ✅ Remote configurado: `https://github.com/jonathans-lumni/site-aldeia-2025.git`
- ⏳ Aguardando push para o GitHub

## Comandos Úteis

Verificar status:
```powershell
git status
```

Verificar remote:
```powershell
git remote -v
```

Verificar commits:
```powershell
git log --oneline
```

