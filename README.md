# desafio-servicos-de-telefonia

## Primeiro projeto | Verificação de Serviço Contratado
### Descrição
Uma concessionária de telecomunicações oferece quatro tipos de serviços: telefonia móvel, telefonia fixa, banda larga e TV por assinatura. Para facilitar o atendimento ao cliente, é necessário implementar um programa que verifique se um cliente específico contratou um determinado serviço. Por exemplo, quando um cliente liga para a central de atendimento e menciona um serviço, o atendente deve ser capaz de rapidamente verificar se esse serviço está contratado pelo cliente.

### Entrada
A entrada deve receber duas linhas. A primeira linha contém o nome do serviço a ser verificado (por exemplo, "movel", "fixa", "banda larga", "tv"). A segunda linha contém o nome do cliente seguido pelos serviços que ele contratou, todos separados por vírgulas (por exemplo, "Alice,movel,fixa").

### Saída
Deverá retornar "Sim" se o cliente contratou o serviço e "Nao" caso contrário.

### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada 1 **:** Entrada 2 | Saída
--|--
movel **:** Alice,movel,fixa|	Sim
fixa **:** Bob,movel,tv |	Nao
tv **:** Carol,movel,fixa,tv	| Sim

## Segundo projeto | Verificação de Contratação de Combo Completo

### Descrição
Implemente um sistema que verifique se um cliente de uma empresa de telecomunicações contratou um combo completo de serviços. Um combo completo inclui os três serviços principais oferecidos pela empresa: telefonia móvel, banda larga e TV por assinatura. O sistema deve ler uma lista de serviços contratados pelo cliente e determinar se todos os serviços necessários estão incluídos. Caso todos os três serviços estejam presentes, o sistema deve retornar "Combo Completo". Se faltar qualquer um dos serviços, o sistema deve retornar "Combo Incompleto".

### Entrada
A entrada consiste em uma string contendo uma lista de serviços contratados pelo cliente, separados por vírgula. Os serviços possíveis são "movel" para telefonia móvel, "banda larga" para serviços de internet e "tv" para TV por assinatura.

### Saída
A saída do programa deve ser uma única linha contendo:

"Combo Completo" se o cliente contratou todos os três serviços.
"Combo Incompleto" caso contrário.
### Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada |	Saída
--|--
movel,banda larga,tv |	Combo Completo
movel,tv |	Combo Incompleto
banda larga,tv,movel |	Combo Completo