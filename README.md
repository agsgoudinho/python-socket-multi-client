O chat foi feito com multthreads para gerenciar vários clientes simultaneamente.

Após clonar o repositório

Entre na pasta do projeto e execute o script server.py

$ python server.py

Depois execute em até 10 terminais diferentes o script client.py

$ python client.py

O Server aceita até 10 conexões, a partir do momento em que for executado vai aguardar por conexões na porta 9000.

No cliente apos enviar uma mensagem ele já vai ficar aguardando a entrada de mais dados. Ao apresenta uma mensagem a visualização ficou um pouco estranha, mas basta digitar outra mensagem e dar enter.

Para remover um cliente do chat basta enviar a mensagem (see ya).