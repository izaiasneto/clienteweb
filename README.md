# ClienteWeb
+  Projeto Java Web da Disciplina Trabalho Individual em Engenharia de Software  ministrada pelo professor Raoni Kulesza
  onde consiste na implementação de um Servlet além dos tratamentos dos métodos doDelete() e doPut(). 
  + Equipe: 
   Izaias de Medeiros Neto,
   Larissa Pereira de Oliveira,
   Glauber Ferreira Angelo

1) Qual a diferença entre Servlets e JSP?

JSP ( Java Server Pages ): foi criado para contornar algumas das limitações no desenvolvimento com Servlets. O JSP é usado para servir conteúdo dinâmico para o usuário, usando lógica e dados do lado do servidor. 
Servlets: são módulos que ampliam a funcionalidade de servidores baseados em requisições/respostas.
2) Explique o que são os redirecionamentos num JSP/Servlet ? Explique a diferença entre os métodos request.forward() e response.sendRedirect().

O redirecionamento é usado para redirect resources para diferentes servidores ou domínios enviando um header de volta ao navegador/cliente. Este header contém o URL do recurso a ser redirecionado pelo navegador. Em seguida, o navegador inicia uma nova solicitação para o URL fornecido. Essa solicitação de encaminhamento é usada para encaminhar aos resources disponíveis no servidor de onde a chamada é feita. Essa transferência de controle é feita internamente pelo contêiner e o navegador/cliente não está envolvido.
O controle pode ser encaminhado para resources disponíveis no servidor de onde a chamada é feita. Essa transferência de controle é feita internamente pelo contêiner e o navegador. Essa é a principal diferença entre forward e sendRedirect. Quando o encaminhamento é feito, os objects originais de solicitação e resposta são transferidos juntamente com parâmetros adicionais, se necessário.
