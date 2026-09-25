# Sistema de Controle de Estoque e Vendas — Windows

Versão executável para Windows do projeto de portfólio **Sistema de Controle de Estoque e Vendas**.

## Como usar

1. Baixe o arquivo `EstoqueVendas.exe`.
2. Abra o arquivo e aguarde alguns segundos na primeira execução.
3. O sistema abrirá automaticamente no navegador.
4. Mantenha a janela de controle aberta enquanto estiver usando o sistema.
5. Clique em **OK** nessa janela para encerrar o servidor local.

### Acesso inicial

- **Usuário:** `demo`
- **Senha:** `demo1234`

Não é necessário instalar Python, Django ou banco de dados.

## Dados locais

Os dados ficam armazenados em:

```text
%LOCALAPPDATA%\EstoqueVendas
```

Assim, cadastros, vendas e movimentações permanecem disponíveis após fechar ou atualizar o executável.

## Funcionalidades

- autenticação;
- dashboard com indicadores;
- categorias, produtos e clientes;
- vendas com múltiplos itens;
- baixa automática de estoque;
- entradas e saídas manuais;
- busca, filtros e histórico de movimentações.

## Segurança do Windows

Este executável ainda não possui assinatura digital. O Windows SmartScreen pode exibir um aviso de **editor desconhecido** na primeira execução.

## Código-fonte

A versão web completa e seu código-fonte permanecem disponíveis em:

[periclesac/sistema-controle-estoque-vendas](https://github.com/periclesac/sistema-controle-estoque-vendas)
