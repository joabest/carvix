# CARVIX
Site institucional — Forros, Divisórias, Drywall e Construção a Seco.

## Acessos
- Site: `/`
- Painel administrativo: `/admin/`
- O painel mostra leads e logs gravados pelo navegador atual.

## Painel /admin
O painel exibe data, nome, contato, serviço, fonte/referenciador, UTMs, página de origem e mensagem. A seção **Logs do site** registra eventos locais como lead recebido, abertura/fechamento do chatbot e alteração de idioma.

> Importante: esta versão é estática e usa `localStorage`. Portanto, o painel não é um backend central e não possui autenticação segura. Para produção, conectar a uma API/banco e autenticação server-side.

## Identidade e tema
- Light: `logo.svg`
- Dark/rodapé: `logo-carvix-dark.svg`
- Tema automático por `prefers-color-scheme`
- Favicons: `favicon.ico`, 16x16, 32x32, Apple Touch e Android 192/512

## Idiomas
Português (PT), English (EN) e Español (ES), com preferência salva no navegador.
