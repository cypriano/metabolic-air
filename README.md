# Metabolic Air — IAAC

**Air_** é um almanaque do ar em preto e branco: um site-galeria que estuda o ar como elemento arquitetônico.

- **Volume I — O estado gasoso:** 63 pranchas sobre fenômenos do ar na natureza, física, química, biologia, microbiologia, fauna, flora e técnica.
- **Volume II — O ar no edifício:** 26 dispositivos e estratégias de projeto, cada um ligado ao fenômeno de origem.
- **Volume III — Referências:** 24 obras de arte e arquitetura que usam o ar como material, com ano, autoria e fotos.

O site é bilíngue (PT/EN), tem fichas detalhadas por prancha e um mural pessoal de pranchas salvas.

## Estrutura

```
index.html     página completa (HTML, CSS e JS num só arquivo)
photos.json    fotos curadas por prancha, com autor, licença e link da fonte
img/           fotos (redimensionadas para 1400 px) do Wikimedia Commons
vercel.json    cache das imagens no Vercel
```

Sem build: qualquer servidor estático serve a pasta.

## Créditos das fotos

Todas as fotos vêm do [Wikimedia Commons](https://commons.wikimedia.org) sob licenças livres (CC BY, CC BY-SA ou domínio público). Autor, licença e link de cada imagem estão em `photos.json` e aparecem na ficha de cada prancha. As imagens são exibidas em preto e branco no site; os arquivos originais estão em cor.
