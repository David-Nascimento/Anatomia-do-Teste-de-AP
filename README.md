# Anatomia do Teste de API

Trilha de estudo de QA com lições interativas: do Enter na barra de endereço até o teste vermelho no pipeline. Em cada lição você roda, quebra de propósito e confere o que entendeu.

## Lições

| # | Lição | O que cobre |
|---|-------|-------------|
| 01 | [O caminho do request](licoes/01-caminho-do-request.html) | DNS, TCP, TLS, request e resposta, com a saída do `curl -v` e falhas para provocar |
| 02 | [Os expects de um teste](licoes/02-os-expects-de-um-teste.html) | Um teste em Jest com cinco conferências; quebre a API e veja qual expect pega cada bug |
| 03 | [Lendo um teste que falhou](licoes/03-lendo-um-teste-que-falhou.html) | Quatro passos para ler a saída do runner e cinco casos para diagnosticar a causa |
| 04 | Status codes na prática | Em breve |
| 05 | Flaky tests | Em breve |
| 06 | Pirâmide de testes | Em breve |

## Como abrir

São páginas HTML estáticas, sem build e sem dependências. Abra o `index.html` no navegador ou publique pelo GitHub Pages:

**Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**

## Estrutura

```
index.html        página inicial da trilha
licoes/           uma página por lição
```

Os domínios, dados e tempos das lições são simulados para estudo.
