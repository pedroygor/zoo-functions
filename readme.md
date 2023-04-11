# Zoo Functions

O projeto _Zoo Functions_ foi desenvolvido durante o curso de Desenvolvimento Web Full-Stack da Trybe. O objetivo deste projeto é implementar funções em JavaScript que realizem operações comuns em um zoológico.

## Funções implementadas

As seguintes funções foram implementadas neste projeto:

- `countEntrants(entrants)`: calcula o número de entradas para o zoológico, com base na idade de cada visitante.
- `calculateEntry(entrants)`: calcula o custo total da entrada no zoológico, com base no número de visitantes e nos preços dos ingressos.
- `countAnimals(animal)`: conta o número de animais no zoológico de acordo com a espécie e, opcionalmente, o sexo.
- `getAnimalMap(options)`: retorna um objeto que mapeia as espécies de animais por área geográfica no zoológico, opcionalmente incluindo os nomes dos animais e classificando-os por nome ou sexo.
- `getAnimalsOlderThan(animal, age)`: verifica se todos os animais de uma determinada espécie no zoológico têm uma idade maior ou igual à especificada.
- `getEmployeeByName`: retorna o objeto de funcionário correspondente ao nome fornecido.
- `getEmployeesCoverage`: retorna um array com as informações de cobertura de todos os funcionários ou de um funcionário específico, se fornecido.
- `getOldestFromFirstSpecies`: retorna um array com informações do animal mais velho da primeira espécie do funcionário correspondente ao ID fornecido.
- `getOpeningHours`: retorna uma mensagem indicando se o zoológico está aberto ou fechado em um determinado dia e horário.
- `getRelatedEmployees`: retorna uma lista de funcionários que são gerenciados pelo gerente correspondente ao ID fornecido.
- `getSchedule(scheduleTarget)`: retorna horário de funcionamento ou espécies disponíveis no zoológico. Sem argumento, retorna todas informações.
- `getSpeciesByIds(...ids)`: retorna um array com as espécies correspondentes aos ids fornecidos.
- `handlerElephants(param)`: retorna informações sobre elefantes do zoológico. Argumento pode ser "count", "names" ou "averageAge", ou undefined.

## Tecnologias utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- JavaScript
- Jest (para testes unitários)

## Considerações finais

Este projeto foi uma oportunidade para aplicar os conceitos aprendidos durante o curso de Desenvolvimento Web Full-Stack da Trybe e para desenvolver habilidades de resolução de problemas em JavaScript. Espero que possa ser útil para outras pessoas interessadas em desenvolver funções para manipulação de dados de um zoológico.
