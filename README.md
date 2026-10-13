# Restaurante Zambonato

Site de uma página do Restaurante Zambonato (Ijuí, RS). HTML puro, sem build.

## Arquivos
- `index.html`: o site completo (CSS e JS no próprio arquivo)
- `404.html`: página de erro
- `robots.txt`: libera os buscadores
- `.nojekyll`: faz o GitHub Pages servir os arquivos como estão

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `zambonato`).
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
5. Em 1 a 2 minutos o site abre em `https://SEU-USUARIO.github.io/zambonato/`.

## Domínio próprio (opcional)
1. Compre o domínio (ex.: `zambonato.com.br`).
2. Em **Settings > Pages > Custom domain**, digite o domínio e salve.
3. No painel do domínio, crie estes registros DNS:
   - `A` apontando para `185.199.108.153`, `185.199.109.153`, `185.199.110.153` e `185.199.111.153`
   - `CNAME` de `www` apontando para `SEU-USUARIO.github.io`
4. Marque **Enforce HTTPS** quando a opção liberar.

## Editar informações
Abra `index.html` e procure:
- WhatsApp: `5555991933734`
- Horários: bloco "Horários"
- Cardápio: seção `id="cardapio"`
- Instagram: `instagram.com/restaurante_zambonato`
