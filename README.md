# Espec-NewFutbol
Especificação de apis criado com RAML para definir as regras da api principal


Introdução ao RAML
Quando desenvolvemos uma API temos que levar em consideração que ela vai fornecer uma interface para que outros sistemas consigam se comunicar com nosso sistema através dela, quanto mais claro for o contrato dela maior será a chance da API ser bem sucedida.
Através da abordagem Contract-First é possível lançar uma previa da API antes mesmo de implementa-la, inclusive fornecer um endpoint que permite a simulação das operações mesmo fase do design, antes mesmo de pensar em questões técnicas como linguagem ou servidor, com isso possível antecipar alguma mudança futura, pois é possível obter o feedback de quem for consumi-la.
De acordo com a regra de Meyers, quanto antes for resolvido um desvio mais barato deverá custar a sua correção:

O RAML foi desenvolvido para nos ajudar nessa questão, com ele é possível criar o contrato de uma API utilizando uma sintaxe bem enxuta e objetiva.

Utilizando o RAML com o Anypoint Platform é possível:
Fazer a especificação do contrato
Realizar testes através de mock
Gerar um portal de documentação da API
Compartilhar essa documentação
Realizar a geração do código de forma automática a partir do RAML, existem plug-ins para diversas linguagens.
