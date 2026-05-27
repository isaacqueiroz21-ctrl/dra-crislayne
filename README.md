# Site Dra. Cryslaine Tavares — link-in-bio

Site estático (HTML + CSS) pra colocar na bio do Instagram da Dra. Cryslaine Tavares
([@dra.cryslainetavares](https://instagram.com/dra.cryslainetavares)) — Caruaru-PE.

- **Produção**: [dra-cryslaine.vercel.app](https://dra-cryslaine.vercel.app)
- **Repo**: [github.com/isaacqueiroz21-ctrl/dra-crislayne](https://github.com/isaacqueiroz21-ctrl/dra-crislayne)

## Estrutura

```
dra-crislayne/
├── index.html         # Estrutura e textos do site
├── style.css          # Visual (cores, espaçamentos, tipografia)
├── images/
│   └── perfil.jpg     # Foto profissional da Dra.
├── .gitignore
└── README.md
```

## Dados aplicados

- **Nome**: Dra. Cryslaine Tavares
- **CRO**: CRO-PE 15717
- **Cidade**: Caruaru-PE
- **WhatsApp**: (81) 97304-8350 → link `wa.me/5581973048350`
- **Instagram**: [@dra.cryslainetavares](https://instagram.com/dra.cryslainetavares)
- **Endereço**: Tv. Mario Pederneira, 296 — Salgado, Caruaru-PE, CEP 55018-561
- **Especialidades**: Clínica geral (adulto e infantil), Expert em Clareamento
  dental, Pós-graduanda em Ortodontia
- **Horário**: Atendimento somente com hora marcada

## Identidade visual

- **Tipografia**: Cormorant Garamond (display) + Inter (body)
- **Paleta**: bege `#f4ede3` + preto `#0c0a09` + dourado `#b8956a` + vinho `#4a0e16`
- **Mobile-first**, responsivo a partir de 480px

## Workflow de deploy (automático)

Pipeline: **edita arquivo** → **git commit** → **git push** → **Vercel
publica em ~30s automaticamente**. Sem comando manual.

### Editando o site

1. Abre o arquivo (`index.html`, `style.css` etc.) no editor
2. Salva
3. Roda no PowerShell, dentro da pasta do projeto:
   ```
   git add .
   git commit -m "descrição curta da mudança"
   git push
   ```
4. Em 30s a mudança está em `dra-crislayne.vercel.app`

### Testar antes de fazer push

Abre o `index.html` direto no navegador (duplo clique) — vê o resultado local.
Pra simular mobile: DevTools (F12) → ícone celular (Ctrl+Shift+M) → iPhone 12.

## Conformidade CFO

Site segue Resolução CFO 196/2019 e Código de Ética Odontológico:

- ✅ Nome completo e CRO em destaque (hero + footer)
- ❌ Sem fotos de antes/depois de pacientes
- ❌ Sem promessa de resultado ou "garantia"
- ❌ Sem divulgação de preços de procedimentos
- ❌ Sem depoimentos de pacientes
- ❌ Sem termos sensacionalistas

Antes de adicionar conteúdo novo, revisar contra essa lista.

## Domínio próprio (opcional)

Pra trocar `dra-crislayne.vercel.app` por algo tipo `dracryslaine.com.br`:

1. Compra o domínio no [Registro.br](https://registro.br) (~R$ 40/ano)
2. Vercel → projeto → Settings → Domains → adiciona o domínio
3. Configura o DNS apontando pro Vercel (registros A/CNAME que ele mostra)
