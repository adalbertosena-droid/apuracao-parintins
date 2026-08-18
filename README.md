# Apuração Parintins — Google Pages + Google Cast

## Estrutura
- `index.html` — sistema principal (Sender)
- `receiver/index.html` — Custom Web Receiver para Google Cast

## Publicação
1. Crie um repositório público no GitHub.
2. Envie todo o conteúdo desta pasta mantendo a estrutura.
3. Ative GitHub Pages em Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Abra a URL HTTPS publicada.

## Google Cast
No `index.html`, procure por `PARINTINS_CAST_APP_ID` e substitua:
`REPLACE_WITH_YOUR_CAST_APP_ID`
pelo Application ID do Custom Web Receiver criado no Google Cast Developer Console.

O Receiver estará em:
`https://SEU_USUARIO.github.io/apuracao-parintins/receiver/`

A URL acima precisa ser HTTPS e acessível pela TV/Chromecast.

## Importante
O GitHub Pages publica o conteúdo do repositório. Não coloque senhas, tokens privados ou chaves secretas no repositório.
