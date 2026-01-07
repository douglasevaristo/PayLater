# PayLater

PayLater e um app simples para te ajudar a decidir qual cartao usar hoje, baseado no prazo ate a fatura fechar. Tudo acontece localmente no navegador: nada vai para a nuvem.

## Por que existe

Eu queria uma forma rapida de ver qual cartao me dava mais prazo sem depender de apps que salvam dados em servidores. O PayLater resolve isso com um visual direto e foco total em privacidade.

## Como funciona

- Voce cadastra seus cartoes com bandeira, banco, fechamento e pagamento.
- O app calcula a proxima data de fechamento e quantos dias faltam.
- Os cartoes sao ordenados para destacar o melhor prazo no topo.
- Os dados ficam salvos no seu navegador via `localStorage`.

## Principais recursos

- Cadastro e edicao de cartoes.
- Destaque do prazo ate a proxima fatura.
- Escolha de cor do cartao.
- Exportar e importar dados em JSON.
- Interface leve, responsiva e focada em leitura rapida.

## Estrutura do projeto

- `index.html`: App completo (HTML, CSS e JS em um unico arquivo).
- `brand/`: Logos das bandeiras.
- `icon.png`: Icone do app.

## Rodar localmente

1) Abra o `index.html` no seu navegador.
2) Pronto: o app funciona offline.

## Privacidade

Todos os dados sao armazenados localmente no seu navegador. Nao ha envio de informacoes para servidores externos.

## Exportacao e backup

Use o botao "Exportar dados" para gerar um JSON e guardar seu historico. Para restaurar, use "Importar dados" e selecione o arquivo.

## Licenca

Uso pessoal. Se quiser contribuir, manda uma mensagem :)
