# aws-challenges 💚
Desafios para candidatos(as) para vagas do time infraestrutura AWS


## Introducao
[Keep it simple](https://pt.wikipedia.org/wiki/Princ%C3%ADpio_KISS), entendemos que você possui suas prioridades e nossa proposta com esse desafio é ter uma idéia de como você faz seus códigos, toma suas decisões arquiteturais e o seu conhecimento geral sobre os assuntos abordados.

Seu desafio precisa estar versionado no Github, em um repositório público ou privado (vamos te passar usuários do Github para compartilhar a solução se for a sua preferência).

A documentação é primordial e vamos nos guiar por ela, então documente os passos no README do projeto ;-)

A aplicação deve ser fácil de ser executada localmente
Não tem problema se você não conseguir finalizar tudo! Não deixe de enviar seu desafio por isso!

Temos alguns entregáveis que vão nos ajudar a entender em que ponto você está tecnicamente. Será muito legal se você nos mandar ao menos o entregável 1 completo, mas se isso não for possível, não deixe de mandar o case até onde conseguiu, queremos ver o seu código e a sua linha de raciocínio, avaliamos tudo ;-)
Temos um entregável que chamamos de **plus**, e será muito legal se você chegar até lá \o/

## Entregável 1

- Desenvolver uma API na linguagem de sua preferência sem se preocupar com camada de persistência.
- Um Dockerfile para essa API para conseguirmos subí-la localmente.
- Uma pipeline de CI para essa API utilizando Github Actions ou algum outro de sua preferência.
- Subir a aplicação na AWS (provavelmente você terá que assinar uma conta free tier ou se aproveitar de limites gratuitos oferecidos pelo cloud provider).
- Criar o terraform para sua aplicação
- Criar a pipeline de CD para essa API utilizando tecnologia de sua preferência
- Criar um relatório da entrega sobre o motivo da escolha de determinada tecnologia

> **Warning**
>: Apesar de sua simplicidade, trate a aplicação como algo que fosse ser usado no mundo real. Não deve haver duplicidade de dados, por exemplo. A API deve retornar os dados de forma correta e consistente. Mesmo as coisas simples precisam de atenção e qualidade 💚


## Entregável 2
 - Configurar o monitoramento da aplicação utilizando a tecnologia que preferir, definindo alertas importantes
 - Torne sua aplicação clusterizada
 - Disponha do monitoramento do cluster


## Plus ##

Configure o deploy utilizando uma tecnologia provida pela AWS


## Tecnologias que usamos e voce pode se inspirar
Aqui dentro do time temos algumas tecnologias que usamos no dia-a-dia e gostaríamos de validar seu conhecimento nas mesmas, sendo elas:
 - [ ] Terraform
 - [ ] Git
 - [ ] Github Actions
 - [ ] AWS ECS
 - [ ] AWS EKS
 - [ ] Golang
 - [ ] CodeDeploy
 - [ ] Cloudwatch

Estas são as tecnologias que usamos, mas sinta-se a vontade para trazer quaisquer nova tecnologia que julgar pertinente para o case apresentado, estamos de braços abertos a novos conhecimentos 💚


## Definicao final de Entrega
- [ ] Repositório no github com a infraestrutura e a aplicação
- [ ] Relatório da Entrega em README  
- [ ] Endpoint acessível da aplicação
