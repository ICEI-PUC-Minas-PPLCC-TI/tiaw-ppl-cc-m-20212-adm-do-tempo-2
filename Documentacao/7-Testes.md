# Avaliação da Aplicação

<span style="color:red">Pré-requisitos: <a href="6-Implementação.md"> Projeto da Solução</a></span>


O processo de realização dos testes da solução desenvolvida está documentado na seção que se segue e traz os planos de testes de software e de usabilidade, na sequência, o registro dos testes realizados.

## Plano de Testes

Requisitos para realização do teste:
Site publicado na Internet
Navegador da Internet - Chrome, Firefox ou Edge
Conectividade de Internet para acesso às plataformas (APIs)

Os testes funcionais a serem realizados no aplicativo são descritos a seguir.

Caso de Teste
CT-01 - Criação de Usuário e Login
Requisitos Associados
RF-01 - Deve ser possível, na página inicial, pelo cabeçalho clicar no botão de login e 
ir para a página de login
RF-02 - Deve ser possível, na página de login, o login do usuário e 
um link para o cadastro de usuário que será salvo no localStorage
Objetivo do Teste
Verificar se está sendo possível a criação de usuário e seu login
Passos
1) Acessar o Navegador
2) Informar o endereço do Site
3) Entrar na página principal, no cabeçalho e clicar no Login
4) Realizar o Login se o usuário já estiver cadastrado, se não clicar no link para fazer o cadastro
5) Quando o usuário for cadastrado, ir para a página de login
6) Realizar o login, se tudo estiver certo ir para a página Inicial
-Critérios de Êxito
>Deve ser apresentado uma página inicial, nela terá um cabeçalho,
>nesse cabeçalho o usuário deve clicar no login e ir para a página de login,
>Na página de login o usuário terá a opção de fazer o login, se o usuário já existir,
>senão clicar no link para entrar na página de cadastro de usuário e fazer o cadastro,
>ao terminar o cadastro o usuário vai ser direcionado a página de login
>e então realizar o login e ser direcionado a página inicial onde no menu mostrará a frase 
> "Olá (nome do usuário que efetuou o login)"

Caso de Teste
CT-02 - Criação de tarefas e exclusão
Requisitos Associados
RF-03 - O site deve permitir ao usuário que estiver logado, na página de tarefas, a criação de tarefas em formato de formulário que aparecem as tarefas
criadas
Objetivo do Teste
Verificar se está sendo possível a criação de tarefas
Passos
1) Acessar o Navegador
2) Informar o endereço do Site
3) Realizar o login
4) Ir para a página de tarefas
5) Criar a tarefa formulário colocando o nome da tarefa
6) Excluir a tarefa desejada a ser excluída clicando na imagem de lixo na tarefa em deseja excluir
-Critérios de Êxito
>A página deve apresentar um formulário editável com as tarefas criadas pelo usuário,
>ao clicar no texto da tarefa criada ela terá seu nome cortado e será considerada como concluída,
>ao clicar na imagem do lixo ela será excluída e não irá aparecer na tela.

Caso de Teste
CT-03 - Desempenho
Requisitos Associados
RF-04 - O site deve mostrar ao usuário, na página desempenho, um gráfico que mostra as tarefas concluídas e não concluídas
Objetivo do Teste
Verificar se está sendo possível a leitura do texto criado pelos desenvolvedores do site
Passos
1) Acessar o Navegador
2) Informar o endereço do Site
3) Entrar na página Desempenho
4) Visualizar o gráfico em forma de pizza
-Critérios de Êxito
>A página deve apresentar um gráfico descrevendo o desempenho do usuário 
>em uma relação de porcentagem em que mostra a porcentagem de tarefas completas e tarefas incompletas


## Avaliação

