## Roadmap básico spring-boot

O objetivo deste roadmap é orientar um caminho de estudo naquilo que considero essencial no uso do framework spring/spring-boot no dia a dia.



### O que é o Spring Framework

Hoje em dia é bem comum ter o primeiro contato com o spring framework através do incrível projeto [spring-boot](https://spring.io/projects/spring-boot)
porém é importante ter em mente que o Spring criou um verdadeiro ecossistema para desenvolvimento em java (hoje não só java, groovy e kotlin também são suportados).


Para ter uma noção dos que o ecossistema spring pode entregar a sua melhor referência continua sendo o [site oficial](https://spring.io/) 👌

Acostumesse também a sempre consultar a documentação oficial do spring, ela será sua melhor aliada no dia a dia, 
digasse de passagem que a documentação do spring é uma das melhores e mais bem organizadas que conheço.

Costumamos perder horas procurando informações na internet quando a documentação oficial sempre tem informações relevantes 🧐

Link = https://docs.spring.io/spring-framework/docs/current/reference/html/index.html

### Injeção de dependências no spring

Os conceitos de _inversão de controle_ e _injeção de dependências_ são pontos fundamentais para o desenvolvimento nos dias atuais.

Tão importantes que estes conceitos vão além do mundo spring e estão presentes em vários outros framework bem conhecidos como mercado como 
no .netcore no mundo c#, no laveral para php entre vários outros.

Em resumo para explicar o conceito podemos dizer o seguinte:

A _injeção de dependência_ é uma forma de se aplicar o princípio da _inversão de controle_.

Ok, mas então o que é este princípio da _inversão de controle__ ❓

Seguem alguns links que podem ajudar no entendimento: 

- https://docs.microsoft.com/pt-BR/dotnet/architecture/modern-web-apps-azure/architectural-principles#dependency-inversion
- https://pt.wikipedia.org/wiki/Princ%C3%ADpio_da_invers%C3%A3o_de_depend%C3%AAncia

E como o spring aplicação a injeção de dependência ? Consulte o link a seguir 

- https://www.baeldung.com/constructor-injection-in-spring


### Básico sobre apis e REST

Saber como construir uma api é definitivamente um dos conhecimentos mais importantes que você precisa ter no mercado de trabalho hoje em dia.

Mais importante do que saber construir a api é fazê-la ser simples, prática para uso e aderente ao modelo REST. Para aprender um pouco mais sobre REST recomendo a leitura desta documentação da microssoft:
- https://docs.microsoft.com/pt-br/azure/architecture/best-practices/api-design


Uma vez que você tenha aprendido o básico sobre rest, que tal fazer uma primeira api seguindo a documentação do spring boot ?
 - https://spring.io/guides/gs/rest-service/

> Recomendo que você inicie o projeto pelo [spring initilzr](https://start.spring.io/) para que você já se acostume com esta fantastica ferramenta que permite gerar projetos spring rapidamente.
