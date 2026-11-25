# Eval recortes-cliente-e-producao

## Prompt

> Monte uma lista para aprovação do cliente e, depois da aprovação explícita,
> uma versão operacional para produção da mesma demanda.

## Resultado esperado

A versão do cliente contém somente nome, redes e defesa. A versão operacional
é criada somente após aprovação e contém apenas os dados logísticos necessários,
com endereço cadastrado sinalizado como não confirmado quando aplicável. Não
altera estoque, envio, monitoramento de posts ou a planilha de origem.

Executar em tarefa limpa com fixtures sintéticas. Escritas exigem aprovação,
releitura e segunda execução. Não remover testes automaticamente.
