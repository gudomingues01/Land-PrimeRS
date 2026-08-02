# PRIME RS

Site da PRIME RS para apresentação do estoque, venda e intermediação de veículos.

## Publicação no GitHub Pages

O projeto gera uma versão estática completa, incluindo `index.html`, e publica automaticamente pelo GitHub Actions.

No GitHub, abra **Settings → Pages** e, em **Source**, selecione **GitHub Actions**. Depois envie os arquivos do projeto para a branch `main`.

O endereço será:

https://gudomingues01.github.io/Land-PrimeRS/

## Desenvolvimento local

```bash
npm install
npm run dev
```

Para gerar a mesma versão estática localmente dentro de `docs/`:

```bash
npm run build:pages
```
