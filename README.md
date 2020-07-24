# springboot
Udemy SpringBoot Course - 2020

## Spring Concepts

É framework Java criado com o objetivo de facilitar o desenvolvimento de aplicações e que explora, para isso, os conceitos de inversão de controle e injeção de dependências.

Ao adotá-lo, temos à nossa disposição uma tecnologia que nos fornece não apenas recursos necessários à grande parte das aplicações, como módulos para persistência de dados, integração, segurança, testes, desenvolvimento web, como também um conceito a seguir que nos permite criar soluções menos acopladas, mais coesas e, consequentemente, mais fáceis de compreender e manter. O **Spring foi criado por causa das dificuldades que os programadores enfrentavam ao criar determinado tipo de aplicação**, mais precisamente, aplicações corporativas.

1.  O Spring **não precisa de um servidor de aplicação para funcionar**. Fazendo uso apenas da JVM, o Spring traz para o programador recursos que antes só estavam disponíveis para soluções corporativas;
2. Com Spring também passamos a **utilizar apenas aquilo que é necessário para o projeto**.
3. Outro diferencial é que ele é **baseado na inversão de controle e injeção de dependência**, fornecendo para isso um container, que representa o núcleo do framework e que é responsável por criar e gerenciar os componentes da aplicação, os quais são comumente chamados de beans.

Para entender esses conceitos, saiba que a Inversão de Controle (IoC - *Inversion of Control*) permite delegar a outro elemento o controle sobre como e quando um objeto deve ser criado e quando um método deve ser executado, por exemplo. Assim, essas responsabilidades, isto é, o controle sobre a execução de alguns comportamentos, passa a ser gerenciado por esse elemento, não cabendo mais a nós, programadores, definirmos isso.

No caso do Spring, chamamos esse elemento de container. Temos, assim, o princípio da inversão do controle. Para melhor compreensão, vejamos um exemplo à parte: Ao construir a interface gráfica com Swing, não precisamos ficar verificando se o usuário clicou em um botão. Precisamos apenas implementar uma ação para aquele botão e pronto. Assim que ele for clicado, essa ação será executada sem que precisemos nos preocupar com isso.

E a Injeção de Dependência? A Injeção de Dependência (DI - *Dependency Injection*) é uma das maneiras de implementar a Inversão de Controle. Com a Injeção de Dependência a classe deixa de se preocupar em como resolver as suas dependências. Ela passa a manter o foco apenas no uso dos recursos das dependências para realizar as tarefas que precisa. E isso leva a uma das características mais conhecidas quando programamos com Spring: não precisamos utilizar o new para criar os objetos por ele gerenciados, pois isso passa a ser feito pelo framework.