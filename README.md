# Aline Roxo — site

Site estático de apresentação para manicure e pedicure. Feito com HTML, CSS e JavaScript, sem dependências ou etapa de compilação.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos desta pasta para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois salve.

O GitHub Pages publicará o site usando o arquivo `index.html` na raiz. Pode levar alguns minutos para o primeiro deploy ficar disponível.

## Personalização

- O telefone do WhatsApp e as mensagens de contato ficam no JavaScript ao final de `index.html`.
- Cores, fontes, layout e adaptação para celular estão no bloco `<style>` do mesmo arquivo.
- As fotografias e fontes são carregadas de serviços externos; precisam de conexão à internet para aparecer.

## Arquivos

- `index.html` — página completa do site.
- `.nojekyll` — evita processamento desnecessário do GitHub Pages.
- `.gitignore` — ignora arquivos locais comuns que não devem ser enviados.
