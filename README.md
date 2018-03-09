# Teste prático - Desenvolvedor Android

[![Biologia Total](https://www.biologiatotal.com.br/pages/biologiatotal/template/home/assets/images/logo-colorido.png)](https://www.biologiatotal.com.br/)

**Desenvolver uma aplicação Android, de preferência utilizando Kotlin, além de todas as outras extensões, aplicações, bibliotecas e ferramentas que desejar utilizar.**
O objetivo desta avaliação é medir o nível de conhecimento do candidato nas áreas em que a vaga será exigida.

# Escopo
Deve-se desenvolver uma aplicação mobile em Android,  de preferência utilizando Kotlin, que contenha 2 telas, consumindo informações de uma API já desenvolvida, resolvendo o problema descrito abaixo. Fique a vontade para explorar todo o seu conhecimento em interface gráfica, automação, build ou qualquer outra ferramenta.

# Cenário fictício
O Biologia Total está lançando uma aplicação mobile em Android (Kotlin) que exiba uma lista de áreas de estudo (Bioquímica, Botânica, Cinemática, etc). Para isso, basta fazer uma requisição em nossa API na URL http://backend-alpha.biologiatotal.com.br/v2/admin/areas?start=0&end=999, exibindo seu título (title) e o nome da disciplina (subject -> title). 

Ao clicar em uma área de estudo, deve-se exibir uma nova tela com as videoaulas existentes da área de estudo selecionada, em forma de lista, exibindo o título (title). Para isso, basta enviar uma requisição em nossa API na URL http://backend-alpha.biologiatotal.com.br/v2/admin/lessons?filter={"area":{"value":"**5a9fae2d90b8623f0344471b**","modifier":"Igual","type":"id"}}  , por exemplo, onde o parâmetro value deve ser substituído pelo atributo id das áreas de estudo, como por exemplo 5a9fae2d90b8623f0344471b (Ecologia), 5a9fae2d90b8623f03444749 (Eletricidade), entre outros.

# Observações
- Não é necessário desenvover tela de login / autenticação. 
 

# Instruções:
- Ao finalizar, disponibilize seu código-fonte no GITHUB e nos envie o endereço, além do arquivo apk da aplicação.

# Plus ++ 
- Um aplicativo que exiba as informações (Lista de áreas e tela de videoaulas) offline (sem conexão à internet), após um primeiro acesso online, seria um plus...

# Observações:

- Não tenha pressa, mas não seja tão perfeccionista! O que será avaliado será a qualidade do código, não a velocidade de desenvolvimento.  
- Se não for possível terminar todas as funcionalidades, não tem problema. Nos envie mesmo assim.
- Seu código-fonte não precisa ser bonito ou ter um UX excelente. Você pode optar por templates para a UI, ou componentes nativos, se assim desejar.
- Não precisa ser complexo, com varias lib’s e etc. O legal é usar o necessário para ter um código de qualidade e de fácil evolução. 
- Lembrando: código de qualidade, você pode e deve fazer o que achar necessário para isso, mesmo que não esteja listado aqui. 

Em caso de dúvidas, envie-nos um e-mail para daniel@biologiatotal.com.br ou abra uma issue neste repositório.

Queremos você em nossa equipe!
