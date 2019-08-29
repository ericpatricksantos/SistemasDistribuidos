# Sistemas Distribuidos

## Jogo: Quem sou eu?

A ordem dos mestres será a ordem de chegada na sala. O primeiro será quem responde e os outros quem pergunta. Depois de acabar a rodada o próximo mestre será o próximo na fila da ordem de chegada.O mínimo de jogadores para início de uma rodada será 3 e o máximo será 5. Para um jogador ser considerado vencedor ele deverá igualar ou superar 100 pontos. Cada acerto contabilizará ao usuário 20 pontos.

O mestre receberá uma palavra aleatória e os outros usuários perguntarão cada um na sua vez para o mestre. 
O mestre responderá sim ou não para as perguntas do usuários.
As respostas serão enviadas para todos os usuários. O primeiro que acertar, a rodada termina e o sistema verifica se o usuário ganhou se não outra rodada inicia. 

Componentes:<br>
Cliente: regra do jogo
Servidor: escolher quem vai jogar, processar os dados dos usuários
Banco de dados: armazenar as palavras 

Linguagem: Java

Testes:<br>
O mestre caiu a conexão ou saiu do jogo: espera 1 minuto e se ele não voltar começa outra partida<br>
O usuário que pergunta caiu: espera 1 minuto e se ele não voltar verifica a quantidade de usuários se for inferior a quantidade mínima inicia outra partida se não continua a partida sem o usuário.<br>
Demonstrar que muitos clientes podem acessar o serviço ao mesmo tempo, sem comportamentos estranhos.<br>
Mostrar que as funcionalidades estão funcionando.<br>
