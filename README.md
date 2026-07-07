# Hash-Chat
Este notebook converte uma base de mensagens JSON em uma estrutura de blockchain básica utilizando hashes SHA-256. 

Validador de Integridade via Hash (SHA-256) 

Pense no dia a dia do processamento de cotações de seguro auto ou na organização do fluxo de renovações. Nesses processos, a precisão das informações e a garantia de que os dados não foram adulterados são fundamentais para aprovar ou não um contrato. O projeto de Hash-Chat faz exatamente isso, mas para um histórico de mensagens, funcionando como um sistema de arquivamento à prova de fraudes. 

O código funciona, de maneira resumida, da seguinte forma: 

Impressão Digital (Hash): Cada mensagem é transformada em um código matemático único. Se alguém alterar uma única letra ou vírgula no texto, esse código muda completamente. 

A Corrente (Blockchain): As mensagens são "amarradas" umas às outras. A segunda mensagem carrega o código da primeira, a terceira carrega o código da segunda, e assim por diante. 

Sistema Antifraude: Se um fraudador tentar modificar uma mensagem antiga, o código dela vai mudar e deixará de bater com o registro das mensagens seguintes. Isso "quebra" a corrente e o sistema acusa a fraude imediatamente. 

Basicamente, é um arquivo interligado onde uma informação tranca a anterior, tornando impossível alterar dados do passado sem que o erro seja detectado na hora. 
