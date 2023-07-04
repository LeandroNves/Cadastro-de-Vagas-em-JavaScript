# Cadastro de Vagas em JavaScript
Código JavaScript que implementa um sistema simples de cadastro de vagas de emprego.

## Funcionalidades

1. **Listar vagas disponíveis**: O usuário pode visualizar todas as vagas de emprego cadastradas, exibindo o índice da vaga, o nome da vaga e a quantidade de candidatos inscritos.

2. **Criar uma nova vaga**: O usuário pode criar uma nova vaga informando o nome, a descrição e a data limite. Uma vez confirmada a criação, a vaga é adicionada à lista de vagas disponíveis.

3. **Visualizar uma vaga**: O usuário pode selecionar uma vaga pelo índice e visualizar suas informações, incluindo nome, descrição, data limite e quantidade de candidatos inscritos.

4. **Inscrever um(a) candidato(a)**: O usuário pode inscrever um candidato em uma vaga específica. Ele informa o nome do candidato e o índice da vaga desejada. Após a confirmação, o candidato é adicionado à lista de candidatos da vaga.

5. **Excluir uma vaga**: O usuário pode excluir uma vaga selecionada pelo índice. Ele é solicitado a confirmar a exclusão, e caso seja confirmado, a vaga é removida da lista de vagas disponíveis.

6. **Sair**: O usuário pode sair do programa a qualquer momento, encerrando a execução.

## Utilização

O programa é executado em um ambiente JavaScript. Após a execução, um menu é exibido ao usuário com as diferentes opções. O usuário pode selecionar uma opção digitando o número correspondente. O programa executa a ação correspondente à opção escolhida e continua exibindo o menu até que a opção "6" (Sair) seja escolhida.

O código utiliza recursos como `prompt`  e `alert`  para interagir com o usuário e exibir informações. As vagas de emprego são armazenadas em um array chamado `vagas`, onde cada vaga é representada como um objeto contendo informações como nome, descrição, data limite e uma lista de candidatos.

## Personalização

Este código serve como uma base para um sistema de cadastro de vagas de emprego e pode ser personalizado e expandido de acordo com as necessidades. Por exemplo, podem ser adicionadas validações de entrada de dados, recursos de persistência de dados, interface gráfica, entre outros.

Sinta-se à vontade para utilizar e adaptar este código de acordo com suas necessidades. Espero que ele seja útil na implementação de um sistema de cadastro de vagas de emprego simples e funcional.
