# Cobra Fácil - protótipo funcional

Aplicativo web responsivo para testar gestão de clientes, empréstimos, pagamentos e cobranças via WhatsApp.

## Executar

Abra `index.html` ou inicie um servidor estático:

```bash
python3 -m http.server 8080
```

Acesse `http://localhost:8080`.

## Publicar com GitHub Pages

Em **Settings > Pages**, selecione **Deploy from a branch**, escolha `main` e a pasta `/ (root)`. O GitHub exibirá o endereço público quando a publicação terminar.

## Escopo da demonstração

- Dashboard financeiro
- Clientes e busca
- Cadastro rápido de cliente
- Empréstimos com juros simples, compostos ou fixos
- Registro de pagamentos
- Cobrança por link do WhatsApp
- Persistência local no navegador
- Layout responsivo e manifesto PWA

## Limitações

Esta versão é um protótipo local-first, sem autenticação ou banco remoto. Não use para dados reais até adicionar backend, criptografia, autorização por organização, auditoria, backups e adequação jurídica/LGPD.