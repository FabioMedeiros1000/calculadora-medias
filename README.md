# Sobre o Projeto

Este projeto consiste em uma calculadora de médias, que ajuda a determinar a situação de aprovação dos alunos com base nas suas notas.

## Funcionalidades

- **Nota Mínima**:
  - Ao entrar no site, será solicitado que você informe a nota mínima necessária para aprovação.

- **Campos de Entrada**:
  - **Nome da Atividade**: Campo para inserir o nome da atividade. Não pode ser repetido.
  - **Nota**: Campo para inserir a nota da atividade.

- **Botão de Cadastrar Atividade**:
  - Adiciona a atividade à tabela. 
  - Se o nome da atividade já existir, um alerta informará que uma atividade com o mesmo nome já foi adicionada.

- **Tabela de Atividades**:
  - Após adicionar uma atividade, a tabela será preenchida com as informações fornecidas.
  - **Coluna Aprovado**:
    - Exibe <img src="images/aprovado.png" alt="Ícone Aprovado" width="20" height="20"> se a nota for igual ou superior à nota mínima.
    - Exibe <img src="images/reprovado.png" alt="Ícone Reprovado" width="20" height="20"> se a nota for inferior à nota mínima.

- **Cálculo da Média Final**:
  - A média final das notas fornecidas é calculada e atualizada à medida que novas atividades são cadastradas.
  - A situação do aluno (aprovado ou reprovado) é determinada com base na média final.

## Link do Projeto

- [Calculadora de Médias](https://calculadora-medias-nu.vercel.app/)
