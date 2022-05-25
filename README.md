## APS-5-SEMESTRE
#    Instalações necessárias para executar o projeto:
#        - Python
#        - MySQL -> para o servidor se conectar
#        Executar os seguintes comandos no CMD:
#            - pip install eel
#            - pip install mysql.connector 
#    Se a versão do Python for 3.7 ou superior e estiver dando erro no pip install a cima:
#        Executar os seguintes comandos no CMD:
#            - pip install pipwin
#            - pipwin install eel
#            - pipwin install mysql.conector
#    Depois de instaladas as dependências e bibliotecas, deve-se configurar o banco de dados. Após concluir as configurações iniciais, deve executar os scripts do arquivo "script APS DB.sql" (as tabelas para controle e gerenciamento de dados da aplicação serão criadas);
#    Na sequência, executar o arquivo servidor.py: Ele irá printar o IP que será utilizado e solicitará um número de porta (que pode ser colocado qualquer um), vamos tomar como exemplo a PORT 65432. Logo em seguida, será solicitado o login do banco de dados, que foi configurado anteriormente. Após o retorno de sucesso de conexão com o banco de dados, o arquivo "main.py" deve ser executado, ainda no CMD ele irá solicitar uma porta para ser aberta, vamos tomar como exemplo a PORT 8001 e depois de inserir a porta, abrirá uma tela de browser para efetuar a conexão com o servidor(deve ser colocado o IP que foi fornecido no console da execução do servidor e a PORT fornecida), após isso, o usuário pode fazer o login e navegar na aplicação.
