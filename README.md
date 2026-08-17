# README — MV Motoparts E-commerce

## 🚀 Sobre o projeto

E-commerce da **MV Motopeças**, desenvolvido para venda online de peças e acessórios para motocicletas.

🌐 **Produção:** https://www.mvmotoparts.com.br/
📦 **Repositório:** https://github.com/waldersonff/MV-Motoparts-Eccomerce

## ✨ Funcionalidades

* Catálogo de produtos
* Busca por produtos e códigos
* Navegação por categorias
* Filtros e ordenação
* Página individual de produto
* Promoções e controle de estoque
* Favoritos
* Comparação de produtos
* Carrinho persistente
* Checkout
* Consulta de pedidos
* Área do cliente
* Histórico de pedidos
* Recuperação de senha
* Integração com Mercado Pago
* Webhook para processamento de pagamentos
* Integração com WhatsApp
* Envio de notificações por e-mail
* Integração com Melhor Envio
* Sitemap e robots.txt
* Feed para Google Merchant
* Analytics e relatórios
* Importação e gerenciamento de produtos
* Painel administrativo
* Gestão de estoque
* Gestão de pedidos
* Gestão de banners e marketing

## 🛠️ Tecnologias

### Frontend

* Next.js 16
* React 19
* TypeScript
* Tailwind CSS 4

### Backend

* Next.js App Router
* Server Actions
* Route Handlers

### Banco e autenticação

* Supabase
* Supabase Auth
* Row Level Security

### Integrações

* Mercado Pago
* Resend
* Melhor Envio
* WhatsApp

### Bibliotecas

* Recharts
* XLSX
* ESLint

## 📁 Estrutura

```text
.
├── app/
│   ├── actions/
│   ├── admin/
│   ├── api/
│   ├── carrinho/
│   ├── categoria/
│   ├── checkout/
│   ├── favoritos/
│   ├── login/
│   ├── minha-conta/
│   ├── produto/
│   └── ...
├── components/
├── lib/
├── services/
├── supabase/
├── types/
├── public/
├── package.json
├── next.config.ts
├── postcss.config.mjs
└── tsconfig.json
```


O banco contempla produtos, pedidos, itens de pedidos, perfis de clientes, favoritos, carrinhos, movimentações de estoque, histórico de alterações e regras de busca.

## 🔐 Segurança

O projeto utiliza mecanismos como:

* Supabase Auth
* Controle de acesso administrativo
* Row Level Security
* Validação de webhook do Mercado Pago
* Validação de valor e moeda do pagamento
* Variáveis de ambiente para segredos

## 📌 Status

Projeto em desenvolvimento e evolução contínua.

## 👨‍💻 Autor

**Walderson Farias Freitas**

GitHub: https://github.com/waldersonff
