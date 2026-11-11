# Projeto FAROL — site institucional

**F**ortalecimento, **A**colhimento e **R**ede de **O**rientação e Proteção à **L**iberdade de Crianças e Adolescentes.

Site institucional, responsivo e estático do Projeto FAROL, um projeto de graduação extensionista do curso de Direito da ESAMC Uberlândia (2026).

## Estrutura

```
index.html          página única (HTML + CSS + JS embutidos)
assets/
  logo-*.svg        logo completo (versões branca e azul-marinho)
  icon-*.svg        símbolo do farol
  word-*.svg        logotipo "FAROL"
  equipe/*.webp     fotos da equipe
```

## Rodar localmente

```bash
python -m http.server 8000
```

Depois, abra http://localhost:8000.

## Publicar com o GitHub Pages

Em **Settings → Pages**, escolha **Deploy from a branch**, depois a branch `main` e a pasta `/ (root)`.

## Configurações

- **E-mail de contato:** preencha `CONTATO_EMAIL` no final do `index.html` para que o botão "Fale com a equipe" abra o e-mail.
- **Identidade visual:** azul-marinho `#11324D`, azul acinzentado `#6B88A6`, azul gelo `#E6ECF2`, dourado `#D4AF37` e creme `#F3E7CA`. Títulos em Marcellus e texto em Poppins.

> O FAROL é uma iniciativa educativa. Ele não recebe denúncias e não substitui os órgãos da rede de proteção.
> Em caso de emergência, ligue **190**. Para denunciar violações de direitos, use o **Disque 100**.
