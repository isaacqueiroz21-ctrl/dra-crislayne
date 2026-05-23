# Site Dra. Cryslaine Tavares — link-in-bio

Site estático (HTML + CSS) pra colocar na bio do Instagram da Dra. Cryslaine Tavares
([@dra.cryslainetavares](https://instagram.com/dra.cryslainetavares)) — Caruaru-PE.

## Estrutura

```
dra-crislayne/
├── index.html      # Estrutura e textos do site
├── style.css       # Visual (cores, espaçamentos)
├── images/
│   └── perfil.jpg  # Foto profissional da Dra. (substituir o placeholder SVG)
└── favicon.ico     # Ícone da aba do navegador (opcional)
```

## Dados aplicados

- **Nome**: Dra. Cryslaine Tavares
- **CRO**: CRO-PE 15717
- **Cidade**: Caruaru-PE
- **WhatsApp**: (81) 97304-8350 → link `wa.me/5581973048350`
- **Instagram**: [@dra.cryslainetavares](https://instagram.com/dra.cryslainetavares)
- **Endereço**: Tv. Mario Pederneira, 296 — Salgado, Caruaru-PE, CEP 55018-561
- **Especialidades**: Clínica geral (adulto e infantil), Clareamento dental,
  Pós-graduanda em Ortodontia

## O que ainda falta

- Salvar a foto profissional da Dra. como `images/perfil.jpg`
  (botão direito na foto enviada → "Salvar como" → nomear `perfil.jpg`).

## Trocar a foto de perfil

1. Salva a foto profissional como `perfil.jpg` dentro da pasta `images/`
   (substituindo o placeholder SVG).
2. No `index.html`, troca `images/perfil.svg` por `images/perfil.jpg`
   (são 2 ocorrências: `<img>` no hero e a meta tag `og:image`).
3. **Importante**: comprime a foto antes de subir. Use
   [tinyjpg.com](https://tinyjpg.com) — meta de 100-150KB.

## Conformidade CFO (importante)

Este site segue a Resolução CFO 118/2012 e o Código de Ética Odontológico:

- ✅ Nome completo e CRO em destaque (hero + footer)
- ❌ NÃO usar fotos de antes/depois de pacientes
- ❌ NÃO prometer resultado ou "garantia"
- ❌ NÃO divulgar preços de procedimentos
- ❌ NÃO usar depoimentos de pacientes
- ❌ NÃO usar termos sensacionalistas ("o melhor", "o único")

Se você quiser adicionar conteúdo novo, revisar contra essa lista antes.

## Testar localmente

Dá pra abrir o `index.html` direto no navegador (duplo clique).

Para testar no celular (preview rápido):
1. Suba no Vercel (próximo passo) OU
2. No PC, abra o DevTools (F12) → ícone de celular (Ctrl+Shift+M) →
   escolha "iPhone 12" → recarrega.

## Deploy no Vercel (grátis)

**Opção 1 — Arrastar pasta (mais simples):**
1. Acesse [vercel.com/new](https://vercel.com/new) → logue com Google.
2. Arraste a pasta `dra-crislayne` inteira pra área de upload.
3. Clica em "Deploy".
4. Em ~30 segundos sai a URL: `dra-crislayne.vercel.app`.

**Opção 2 — via CLI:**
```
npm i -g vercel
cd c:\Users\SUPORTE\Desktop\dra-crislayne
vercel --prod
```

## Dominio próprio (opcional)

Se quiser `draclislayne.com.br` em vez de `.vercel.app`:
1. Compra o domínio no [Registro.br](https://registro.br) (~R$40/ano).
2. No painel do Vercel → projeto → Settings → Domains → adiciona o domínio.
3. Configura o DNS apontando pro Vercel (ele mostra os registros A/CNAME).
