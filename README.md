# Cardoz0 — Site oficial de links

Site estático para a bio do Instagram, pronto para publicar gratuitamente no **GitHub Pages**.

## Conteúdo

- `index.html`: página responsiva, com fundo cinza-escuro, textos e links.
- `assets/logo.png`: brasão original utilizado no perfil.
- `.nojekyll`: configuração para servir os arquivos diretamente no GitHub Pages.

## Publicar no GitHub Pages (sem programação)

1. Entre em https://github.com/new e crie um repositório **público**, por exemplo `cardoz0-links`.
2. Abra o repositório e escolha **Add file → Upload files**.
3. Envie `index.html`, `.nojekyll` e a pasta `assets` com `logo.png`. Se a interface não permitir enviar a pasta diretamente, arraste os arquivos e confira que `logo.png` ficou no caminho `assets/logo.png` (ou crie a pasta pelo editor do GitHub).
4. Clique em **Commit changes**.
5. Vá a **Settings → Pages → Build and deployment**.
6. Em **Source**, escolha **Deploy from a branch**; selecione **main** e **/(root)** e salve.
7. Após a publicação, acesse `https://SEU-USUARIO.github.io/cardoz0-links/` (substitua `SEU-USUARIO` pelo nome real da sua conta e o final pelo nome escolhido para o repositório).

> Se quiser o endereço `https://SEU-USUARIO.github.io/`, o repositório deve se chamar exatamente `SEU-USUARIO.github.io`.

## Testar

Abra `index.html` no navegador. A imagem será carregada a partir de `assets/logo.png`, então mantenha a estrutura de pastas.

## Links incluídos

- YouTube: https://www.youtube.com/@Lipe.Cardoz0
- GitHub: https://github.com/KaiCardoz0
- LinkedIn: https://www.linkedin.com/in/felipe-cardoso-748617366/
- X: https://x.com/Lipe_Cardoz0

Sem necessidade de instalar bibliotecas ou executar build. As fontes do Google são opcionais e usam fallback local.
