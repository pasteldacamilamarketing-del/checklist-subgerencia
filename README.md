# 🥟 Koncluí – Pastel da Camila

Sistema operacional de checklists digitais para gestão de franquias.

## 🚀 Acesso

Hospedado via Netlify. Abrir direto no navegador — sem instalação, sem build.

## 👥 Usuários

| Login | Role | Acesso |
|---|---|---|
| `gabriela` | Subgerente | Checklist do turno |
| `vitoria` | Subgerente | Checklist do turno |
| `bruna` | Suporte | Painel CEO + Checklist |
| `camila` | CEO | Painel gerencial completo |

> Senha padrão inicial: `123456`  
> O sistema exige troca de senha no primeiro acesso.

## 📦 Estrutura

```
konclui/
├── public/
│   └── index.html       ← app completo (single file)
├── netlify.toml         ← config de deploy
├── .gitignore
└── README.md
```

## 🔧 Stack

- React 18 via CDN
- Babel standalone via CDN
- localStorage para persistência
- Webhook Make para notificações por email

## 🔮 Próximos passos

- [ ] Banco de dados Supabase (persistência real)
- [ ] Notificações WhatsApp automáticas
- [ ] Multi-unidade / rede de franquias
- [ ] App nativo iOS/Android

---

**Powered by Koncluí** · Checklists e Gestão Operacional para Restaurantes
