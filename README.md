Grupo: 
- Dayana Souza - 117211056
- Ricardo Ferreira - 113112300
- Samara Matias - 113210883

1 - Considerações Iniciais 

Este projeto procura avaliar um sistema de abastecimento de combustíveis de um posto, o qual prevê o tempo de duração
para abastecer de acordo com a fila de clientes e com a bomba escolhida.
Diante disso, iremos modelar o sistema e criar os possíveis cenários para avaliar como ele se comporta de acordo com 
as diferentes situações. O primeiro cenário é o padrão onde não ocorrem imprevistos, os atendentes não demoram no 
atendimento ao cliente evitando a geração de filas. Um outro cenário é onde o funcionário tem algum problema no atendimento
(problemas com a maquineta do cartão, por exemplo) causando a retomada dos cálculos, e o tempo de espera pode aumentar, 
resultando numa fila. 

2 - Descrição

No modelo os clientes chegam ao posto e esperam ser chamados de acordo com o tamanho da fila. Quando forem chamados escolhem
a bomba dentre as disponíveis que são: Bomba 1 - gasolina, Bomba 2 - gasolina e álcool ou Bomba 3 - gasolina, álcool e diesel,
portanto deve ser levado em consideração para a escolha da bomba o combustível ao qual eles desejam abastecer seu veículo. 
Em seguida realizam o pagamento e saem liberando o espaço para o próximo cliente da fila. Por outro lado, caso os atendentes,
ou o próprio cliente gerar algum atraso, o sistema terá que recalcular o tempo de espera dos consumidores. Por fim, o sistema
aplica todos os parâmetros ao modelo e retorna para a administração do posto a duração do tempo de atendimento. 	




