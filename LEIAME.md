# Paróquia Santa Sofia — PWA Completo

## Arquivos
```
paroquia-santa-sofia/
├── index.html      ← Site completo (todas as 12 páginas)
├── manifest.json   ← Config PWA (ícones, tema, atalhos)
├── sw.js           ← Service Worker (funciona offline)
└── icons/          ← Crie esta pasta
    ├── icon-192.png
    └── icon-512.png
```

## Criar os Ícones
Use a imagem da Cruz ou logo da paróquia (quadrada) e exporte em:
- 192×192 px → icon-192.png
- 512×512 px → icon-512.png

Ferramenta gratuita: https://realfavicongenerator.net

## Hospedar (Gratuito com HTTPS)

### Netlify (mais fácil — arrastar e soltar)
1. Acesse https://netlify.com → crie conta grátis
2. Arraste a pasta `paroquia-santa-sofia` para o painel
3. Pronto! URL automática como `santa-sofia.netlify.app`

### GitHub Pages
1. Crie repositório público em https://github.com
2. Faça upload de todos os arquivos
3. Settings → Pages → Branch: main / root
4. Site em: `https://usuario.github.io/repositorio`

### Vercel
1. https://vercel.com → conecte GitHub ou faça upload
2. Deploy automático

> ⚠️ O PWA EXIGE HTTPS para funcionar. Netlify, Vercel e GitHub Pages já fornecem HTTPS gratuito.

## Instalar no celular

**Android (Chrome):**
Toque no banner "Instalar App" que aparece automaticamente,
ou: menu (⋮) → Adicionar à tela inicial

**iOS (Safari):**
Compartilhar (□↑) → Adicionar à Tela de Início

**Desktop (Chrome/Edge):**
Ícone (⊕) na barra de endereços → Instalar

## Personalizar

- **Horários reais:** Edite os `<td>` na seção `page-horarios`
- **Endereço/telefone:** Edite `page-contato`
- **PIX:** Edite a chave PIX em `page-doacoes`
- **Avisos:** Edite os cards em `page-home` e `page-noticias`
- **Pároco atual:** Acrescente na história ou no contato
- **Fotos reais:** Substitua os SVGs por `<img>` nas galerias

---
*Pascom Santa Sofia — Cosmos, RJ*
