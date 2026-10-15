# STREAMVERSE

Streaming estilo Netflix — protótipo funcional e leve (3 arquivos, sem frameworks).

## Arquivos
- `index.html` — site: banner hero carrossel, fileiras de pôsteres, busca, My List, modal com player embed
- `admin.html` — painel admin (senha padrão `admin123`): cadastro de vídeos, busca TMDB, export/import JSON
- `data.js` — catálogo demo (usado até o admin salvar o catálogo real)

## Como usar
1. Abra `admin.html`, entre com a senha e cole sua **chave TMDB (v3)** no passo 1 → "Testar"
2. No passo 2, digite o nome do filme/série → o TMDB preenche título, ano, nota, gênero, sinopse, pôster e fundo
3. Cole o **link do vídeo** (YouTube watch/youtu.be/Shorts ou Google Drive — convertido para embed automaticamente), marque as fileiras e salve
4. Abra `index.html`: os banners são clicáveis e abrem a janela com as informações + botão de player

## Notas
- O catálogo fica no `localStorage` do navegador (uso pessoal/teste). Use **Exportar/Importar JSON** no admin para fazer backup ou migrar de navegador.
- Para publicar: GitHub Pages (Settings → Pages) ou qualquer hospedagem estática.
