# Licenças no GitHub

Neste artigo vamos percorrer algumas licenças mais usadas e mais comuns no GitHub.

# O Que são Licenças

Quando criado um projeto e publicado no GitHub, o projeto não tem nada especificamente descrito o que se pode fazer nele ou não. 
A licença veio para impor limites nisso, portanto é bem importante avaliar bem em qual licença usar em seu projeto.
Se você não colocar nenhuma licença no seu projeto serão aplicadas as leis padrão de copyright, 
o que significa que você detém todos os direitos de seu código-fonte e ninguém poderá reproduzir, 
distribuir ou criar derivativos de seu trabalho.

## Declarações

A maioria das licenças tem essas declarações:

1. O software pode ser modificado, utilizado comercialmente e distribuído.
2. O software pode ser modificado e utilizado em particular.
3. Uma licença e um aviso de direitos autorais devem ser incluídos no software.
4. Os autores do software não fornecem nenhuma garantia com o software e não são responsáveis por nada.

# Tipos Principais de Licenças

No mundo das licenças existem dois tipos mais convencionais de licenças open source: **Copyleft** e **Permissivas**.
Em resumo as Licenças Permissivas tem poucas restrições de uso enquanto as Licenças Copyleft tem mais regras a serem seguidas.

## Licenças Copyleft
As Licenças Copyleft permitem o uso e distribuição do projeto, mas desde certas condições sejam seguidas.
Dentro do Copyleft, ainda tem mais duas subdivisões de categorias strong (forte) e weak (fraca).

### - Licenças Copyleft fortes:

 As aplicações derivadas que estão sob a licença *Copyleft forte*, tem que obrigatóriamente estar com a mesma licença da aplicação principal. Por exemplo, se alguém modifica e distribui a aplicação sob uma licença GPL, ele também deve disponibilizar o código-fonte e licenciar suas modificações sob a mesma licença GPL.

### - Licenças Copyleft fracas:

No caso  da aplicação ser *fraca*, a derivação não necessariamente precisará estar sob a mesma licença, dependendo do tipo de trabalho derivado.


## Licenças Permissivas

Nas *Licenças Permissivas*, seu enfoque é na permissão aos usuários a liberdade de utilizar, modificar e distribuir o software com restrições mínimas. Essas licenças são mais voltadas para incentivar a colaboração e promover o uso e a adoção generalizados de software de código aberto. Em contraponto com as *Licenças Copyleft*, que exigem que o código-fonte dos trabalhos derivados também sejam distribuídos sob os mesmos termos de licença, já as licenças permissivas impõem muito menos restrições aos desenvolvedores e às suas contribuições proprietárias para a base de código do software.

As *Licenças Permissivas* por terem muito pouca restrição, por sua simplicidade, facilidade de uso e requisitos mínimos para desenvolvedores, é uma escolha muito popular tanto para desenvolvedores individuais quanto para organizações.

# Exemplos de Licenças

Agora vamos ver algumas Licenças mais populares no contexto de licenciamento de software e desenvolvimento de código aberto:

## GNU (General Public License ) – Licença Pública Geral, versão 3 (GPLv3)

A GPLv3 é uma opção para quem quer deixar o código aberto mas ao mesmo tempo ter sua segurança. Essa licença é uma das mais **restritivas**.

Suas principais cláusulas:

- O seu código-fonte deve ser **obrigatóriamente** público sempre que uma distribuição da aplicação é feita, ou seja, se você lançar uma aplicação que utiliza essa licença você obrigatóriamente deve torná-lo público.
- Modificações na aplicação devem sempre serem lançadas com a mesma licença.
- Mudanças no código-fonte devem ser sempre **documentadas**.
- Se o material patenteado for usado na criação do software, ela concede aos usuários o direito de usá-lo. Se o usuário processar alguém pelo uso do material patenteado, ele perde o direito de usar o software.

> A licença do seu código-fonte deve ser compatível com a licença do código-fonte aberto ao qual você está vinculado. Por exemplo, se seu código for proprietário, você não terá permissão para usar uma biblioteca sob a licença GPL. É aqui que as pessoas tendem a cometer mais erros.


Alguns projetos famosos com esta licença são o [Bash](https://www.gnu.org/software/bash/), [GIMP](https://www.gimp.org/) e o [Linux](https://br-linux.org/) (GPLv2).

## Apache License 2.0

Em relação à licença anterior essa aqui é bem mais flexibilidade aos usuários. Como podemos ver a seguir:

- O código-fonte não precisa ser necessariamente público quando a distribuição do software é feita.
- As modificações no software podem ser liberadas sob qualquer licença.
- Mudanças feitas no código-fonte precisam ser documentadas.
- Oferece a mesma proteção de uso de patente da GPLv3 como vimos acima.
- Proíbe explicitamente o uso de nomes de marcas registradas encontrados no projeto.


Alguns projetos famosos com esta licença são o [Android](https://www.android.com/), [Apache](https://www.apache.org/) e o [Swift](https://developer.apple.com/swift/).

## Distribuição de Software da Berkeley (BSD - Berkeley Software Distribution)

A BSD tem duas versões principais, a de 2 cláusulas e a de 3 cláusulas. TOdas as duas oferecem mais flexibilidade para os usuários do que a Licença Apache 2.0.
A seguir as regras adotadas por ela:

- O código-fonte não precisa ser necessariamente público quando a distribuição do software é feita.
- Modificações podem ser lançadas sob qualquer licença.
- Mudanças feitas no código-fonte não precisam ser documentadas.
- Não tem nenhuma posição em relação ao uso de patentes.
- A licença e os direitos de uso precisam ser incluídos na documentação da versão compilada do código-fonte.
- O BSD 3-clause afirma que os nomes dos autores e colaboradores nãopodem ser usados ​​para promover produtos derivados do software sem permissão explícita.


Alguns projetos famosos com esta licença são o [Go](https://golang.org/), [Pure.css](https://purecss.io/) e o [Sentry](https://sentry.io/welcome/).

## MIT License

E por último e não mais importante a licença **MIT** que é uma das mais populares por ser a mais permissiva de todas, além de ser a mais famosa. 
Comparado às demais, ela oferece pouquíssima proteção aos autores do software. 
A seguir vai as principais cláusulas:

- O código-fonte não precisa ser necessariamente público quando a distribuição do software é feita.
- Modificações podem ser lançadas sob qualquer licença.
- Mudanças feitas no código-fonte não precisam ser documentadas.
- Não tem nenhuma posição em relação ao uso de patentes.

Um grande projeto com essa licença é o próprio [Training Center](https://github.com/training-center)! Além disso, há outros famosos como o: [jQuery](https://jquery.com/), [Bootstrap](http://getbootstrap.com/) e o [Rails](http://rubyonrails.org/).


Por fim, aqui a baixo está um diagrama que demonstra de forma resumida cada uma das licenças:

![Diagrama sobre as licenças]()

