1.qual problema percebeu ao realizar tais alterações;

R= O problema é que a mensagem "Dados obtidos do servidor" é exibida primeiro do que os conteúdos serem obtidos da requisição.

2.explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;

R= Chamadas assíncronas quando realizadas não impedem que outros processos sejam executados, por isso a mensagem é exibida primeiro do que o conteúdo mesmo sendo colocada posteriormente, pois quando o script é executado ele chama a função request, mas não fica esperando a resposta do servidor terminar para continuar executando, por isso a mensagem é exibida.
