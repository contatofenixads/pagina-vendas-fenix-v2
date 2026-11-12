# 🔥 Fênix Ads - Landing Page de Vendas

Landing page de alta conversão para serviços de presença online (Google Meu Negócio, Site Profissional, Link na Bio).

## 🎯 Objetivo

Converter visitantes em leads qualificados através de um quiz/formulário que filtra clientes ideais (MEIs, lojistas e pequenos comerciantes das cidades de Limeira, Americana, Piracicaba e Campinas).

## 📁 Estrutura

```
vendas-fenix/
├── index.html          # Landing page principal
├── README.md          # Este arquivo
├── .gitignore         # Arquivos ignorados pelo Git
├── vercel.json        # Configuração Vercel
└── LICENSE            # Licença do projeto
```

## 🚀 Deploy

### Vercel (Recomendado)

1. Conecte seu repositório GitHub ao Vercel
2. Configure as variáveis de ambiente (se houver)
3. Deploy automático a cada push para `main`

```bash
npm i -g vercel
vercel
```

### Deploy Manual

```bash
# Local
python -m http.server 8000

# Acesse: http://localhost:8000
```

## 📋 Características

✅ Design responsivo (mobile-first)
✅ Alta conversão com CTA claro
✅ Formulário com WhatsApp integration
✅ FAQ interativo
✅ Social proof
✅ Preços transparentes
✅ Rápido (sem dependências externas)
✅ SEO otimizado

## 🎨 Paleta de Cores

- **Primária**: #667eea (Roxo)
- **Secundária**: #764ba2 (Roxo Escuro)
- **Sucesso**: #28a745 (Verde)
- **Erro**: #dc3545 (Vermelho)
- **Fundo**: #f8f9fa (Cinza Claro)

## 🔧 Customização

### Mudar número WhatsApp

Abra `index.html` e procure por:
```javascript
const whatsappLink = `https://wa.me/5585988888888?text=...`;
```

Substitua `5585988888888` pelo seu número (com código do país, sem espaços).

### Mudar cidades

No formulário `<select id="city">`, adicione ou remova opções conforme necessário.

### Mudar preços

Localize as seções de pricing (Buscando por "R$") e atualize os valores.

## 📊 Rastreamento

Para adicionar Google Analytics:

```html
<!-- No final do </head> -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXX');
</script>
```

## 📱 Dispositivos Testados

✅ iPhone (Safari)
✅ Android (Chrome)
✅ Desktop (Chrome, Firefox, Safari, Edge)
✅ Tablet

## 🤝 Contribuição

Este é um projeto privado. Consulte o proprietário antes de fazer alterações.

## 📄 Licença

MIT License - Agência Fênix Ads

---

**Desenvolvido com ❤️ em Campinas, São Paulo**
