BUG-001: Quantidade do produto não pode ser aumentada além de 2 no carrinho

Ambiente


Site: https://academybugs.com
Navegador: Todos os navegadores testados
Data: 11/07/2026


Tipo de problema

Funcional

Severidade

Alta

Frequência

Sempre (100% de reprodução)

Passos para reproduzir


Acessar https://academybugs.com
Clicar no link "Encontrar erros" na barra de navegação
Adicionar um ou mais produtos ao carrinho
Clicar no link "Ver carrinho" no topo da página
Definir a quantidade do produto para 3 ou mais
Clicar em "Atualizar"


Resultado esperado

A quantidade do produto deve ser atualizada para o valor definido (3 ou mais).

Resultado obtido

Ao clicar em "Atualizar", a quantidade volta automaticamente para 2, ignorando o valor inserido pelo usuário.

Evidência

<img width="1667" height="937" alt="1" src="https://github.com/user-attachments/assets/78fc9d6b-92b2-402d-970b-f99caf6a0279" />



https://github.com/user-attachments/assets/e4cdd64c-6720-4c52-ac1a-c54307c9068e


Observações

Esse bug impacta diretamente a experiência de compra — um usuário que precise de 3+ unidades do mesmo produto não consegue concluir a compra na quantidade desejada, o que pode gerar perda de venda.


