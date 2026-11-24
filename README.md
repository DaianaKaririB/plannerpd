# PlannerPD

Planejamento semanal de demandas de UX/UI.

## Como colocar no ar (GitHub Pages)

1. No GitHub, crie um repositório novo (ex.: `plannerpd`). Pode ser público.
2. Clique em **Add file → Upload files**, envie o arquivo `index.html` (e este `README.md`, se quiser) e clique em **Commit changes**.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**; em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
5. Em 1–2 minutos o site fica disponível em `https://SEU-USUARIO.github.io/plannerpd/`.

## Onde ficam os dados

- Tudo o que você cadastra fica salvo **no navegador do aparelho** (localStorage). Nada é enviado para servidor nenhum.
- Quem abrir o link vê o site, mas **não vê os seus dados** — cada navegador tem os seus.
- Fechar ou recarregar a página não apaga nada. Limpar os dados do navegador, usar aba anônima ou trocar de aparelho, sim.

## Backup

Use o botão de **download** (seta para baixo) no topo do site:

- **Baixar arquivo**: salva um `.json` com sistemas, demandas, responsável e esquema de cores.
- **Importar arquivo** ou **colar texto**: restaura um backup (substitui os dados atuais).

Faça backup de vez em quando e use-o para levar os dados para outro aparelho.

## Atualizar o site

Envie um novo `index.html` pelo mesmo caminho (**Add file → Upload files**). Os dados salvos no navegador continuam lá.
