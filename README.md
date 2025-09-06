# Desafio 1 Code Girls
Esse repositório tem como objetivo organizar o aprendizado do módulo 1 e do módulo 2 do curso Santander Code Girls - AWS 

# Módulo 1: Introdução à AWS e ao Universo da Computação em Nuvem

Nesse módulo ja aprendi de cara que a AWS (Amazon Web Services) é a maior provedora de seriços na nuvem do mercado, estando presente em 33 regiões com mais de 100 zonas de disponibilidades. Quando falamos de serviço na nuvem quer dizer que são serviços que podemos acessar via internet sem nos preocuparmos com parte fisica e infraestrutura (ou seja, economida de tempo e custos).
A Amazon lançou a AWS em 2006 como resposta para as necessidades de serviços de infraestrutura na nuvem, aplicando primeiramente na própria empresa.

Por ser pioneira na área, a AWS é a nuvem mais segura, confiável e abrangente, oferecendo mais de 200 serviços em todo o mundo. Sua principal ideia é oferecer os serviços e cobrar apenas pelo seu uso, garantindo vários benefícios como disponibilidade, segurança e escalabilidade. 

Dentro do menu de serviços da AWS, exitem 3 modelos que os classificam:
- IaaS (Infraestrutura como serviço) -> é quando a provedora da nuvem garante toda a infraestrutura básica de TI, como servidores fisicos, configurações de rede, armazenamento inicial, etc... e o cliente se preocupa apenas com configurações de sistema operacional, dados, softwares, aplicações, etc. Um exemplo é o Amazon EC2, nesse caso a AWS garante a infraestrutura, mas o cliente que decide se sua máquina virtual terá um linux ou Windows e será responsaável por todo o resto que fizer com a sua instância.

- PaaS (Plataforma como serviço) -> é quando a provedora da nuvem garante, além da infraestrutura básica, também uma plataforma completa para desenvolver, executar e gerenciar aplicações sem se preocupar com gerenciamento de servidores, nesse caso o cliente se preocupa apenas em subir seus códigos e dados. Exemplo disso é o AWS Lambda que é usado para aplicações completas.

- SaaS (Software como Serviço) -> é quando a provedora da nuvem oferece tudo pronto para o cliente e ele só precisa usar, sem se preocupar com nenhum tipo de configuração. Um exemplo é o Amazon Quicksight que gera vizualização de dados a partir de bases que ele consome do Amazon Athena ou arquivos.csv

# Seja Bem-vindo a AWS
Após a criação da conta na AWS, a primeira boa prática que deve ser feita é guardar o usuário master root e criar um usuário adminitrador para navegar na plataforma através do serviço IAM (Identity Accesses Manager), além de configurar a autentificação MFA (Multi-Factor Authentication) para login no console.

O IAM é o serviço da AWS responsável por gerenciar usuários e grupos da cloud. Através dele o adminitrador atribui as políticas aos grupos de usuários e gerencia o que cada um pode ou não fazer dentro da AWS. Então, pensando no contexto de uma organização, os funcionários só tem acessos a serviços dentro do seu escopo de atividade, partindo do princípio do minimo privilégio.

Como a AWS apenas cobra pelo seu uso, é interessante a partir do momento em que começar a navergar por ela, configurar alertas de custos no serviço de gerenciamento de cobranças e custos dentro da plataforma, para estabelecer um limite de recursos que esteja disposto a gastar e receber notificações em seu e-mail para quando esse limite estiver perto de ser ultrapassado.

# Formas de acessar AWS
Existem 3 principais formas de acessarmos a AWS:
- A principal e mais famosa é pela interface acessando o site pela web, onde temos a facilidade de navegação e recursos visuais.
- Dentro da interface web, existe a possibilidade de acessar os recursos pelo AWS ClouShell que é semelhante a um prompt de comando
- Por fim, temo o AWS CLI, que é o acesso por linha de comando, que rejeita a necessidade de abrir a interface. Nesse caso, conseguimos acessar os recursos da AWS instalando o AWS CLI pelo site oficial em conjunto com o Git Bash. Obs: para funcionar o acesso, é necessário criar uma chave de acesso no IAM 







