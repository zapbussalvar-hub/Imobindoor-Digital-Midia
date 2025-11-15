# ImobIndoor - Imopar & Imoel (zapbussalvar-hub)

Repositório para rodar o sistema de mídia indoor (tela de elevador) utilizando **GitHub Pages**.

- Painel de Controle (Imopar): `imopai.html`
- Player da Tela do Elevador (Imoel): `imoel.html`
- Página inicial/atalhos: `index.html`
- Playlist de mídias: `playlist.txt`
- Pasta de mídias (depois que você criar): `media/`

## 1. Como publicar no GitHub Pages

1. Acesse o repositório: `https://github.com/zapbussalvar-hub/Imobindoor`
2. Envie estes arquivos para a raiz do repositório:
   - `index.html`
   - `imopai.html`
   - `imoel.html`
   - `playlist.txt`
3. Vá em **Settings › Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` e pasta `/ (root)`

O site ficará disponível em:

- `https://zapbussalvar-hub.github.io/Imobindoor/`

## 2. Controlando as mídias do elevador

1. No repositório, crie a pasta `media/` (via **Add file › Create new file**, nome `media/.keep`).
2. Envie suas imagens e vídeos para dentro de `media/` (**Upload files**).
3. Edite o arquivo `playlist.txt` e coloque um arquivo por linha, por exemplo:

   ```txt
   banner_condominio.jpg
   oferta_supermercado.png
   video_lancamento.mp4
   ```

4. Salve o arquivo (**Commit changes**).

A TV Box, ao abrir `https://zapbussalvar-hub.github.io/Imobindoor/imoel.html`, irá:
- Ler o `playlist.txt`
- Tocar cada arquivo da pasta `media/` que você listou, em loop

## 3. Usar na TV Box MX9

1. Conecte a TV Box à internet.
2. Abra o navegador da TV.
3. Digite: `https://zapbussalvar-hub.github.io/Imobindoor/imoel.html`
4. Coloque em **tela cheia**.

Pronto: a tela do elevador estará rodando seu conteúdo real, sem simulação.
