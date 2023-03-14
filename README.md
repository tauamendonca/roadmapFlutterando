# Flutter Roadmap 2023

<i>V. 2.3.0 - Março 2023 - por Jacob Moura e Tauã Mendonça</i>
### Powered by 

<img src='https://miro.medium.com/max/1134/1*CTBedeQiWb4-75peW1IF3w.png' height=60>

<br>

## **`1.` Sobre o Roadmap**
<details open><Summary><i>[Ocultar o conteúdo]</i></Summary>
</p>

O roadmap, nascido no início de 2022, é uma trilha orientativa com o objetivo de `sugerir um caminho para os iniciantes em Dart e Flutter` a partir do conhecimento da comunidade de conteúdos gratuitos disponíveis na internet.  

É necessário observar que somente utilizar o Roadmap `NÃO` substitui a documentação do Dart ou do Flutter e é complementar a ela e a cursos, sejam gratuitos ou pagos. 

O intuito é somente guiar os novos (e as vezes até antigos) devs que queiram aprender o framework Flutter a linguagem Dart.

A Flutterando  ser um caminho comprovado, que forma e já formou profissionais da área com grande sucesso.
</p>

</details>

<br>

<!-- ## **`2.` O Roadmap em imagem** -->

## **`2.` Preparando suas bases**

<details><Summary><i>[Ver o conteúdo]</i></Summary>
</p>

Esteja você começando agora ou tendo já um mínimo de conhecimento sobre o que é programação, ainda assim é importante trabalhar seus conhecimentos básicos. 

Recomendamos primeiramente assistir [o vídeo abaixo](https://www.youtube.com/watch?v=BTENKdRVS2U) antes de iniciar, especialmente se você é uma pessoa novata na programação em geral.

[![Código Fonte TV](https://markdown-videos.deta.dev/youtube/BTENKdRVS2U)](https://www.youtube.com/watch?v=BTENKdRVS2U)


</p>

## `2.1` Ambiente de Trabalho

<details><Summary><i>[Ver o conteúdo]</i></Summary>
</p>

### `2.1.1` O que é uma IDE?
A IDE é onde você irá fazer seus códigos. Para entender um pouco mais sobre o que é uma IDE dê uma olhada neste [artigo da Codeesh](https://coodesh.com/blog/dicionario/o-que-e-ide/).

#### | *IDEs online prontas para uso:* |
Algumas IDEs online podem te ajudar a começar seus estudos sem necessitar instalar as ferramentas necessárias para desenvolver na sua máquina. São elas: 

<details><Summary><i>Dartpad</i></Summary>
Recomendamos começar com a IDE online [Dartpad](https://www.dartpad.dev), por ser acessível em quase qualquer navegador e ter toda a capacidade necessária para seu início de estudos. Ela é capaz de trabalhar com Dart E com Flutter, embora algumas bibliotecas (códigos externos) não estejam disponíveis para uso. 
</details>

<details><Summary>Zapp.run</Summary>
Outra IDE online útil no início e depois é o [Zapp.run](https://zapp.run), similar a uma mistura do Dartpad com o Visual Studio Code, e capaz de emular seus projetos Flutter. No entanto, perceba que ele é melhor utilizado com uma boa conexão à internet e tem algumas limitações se comparados a uma IDE mais completa como o Visual Studio Code. 
</details>

<br>

#### < *IDE Recomendada* >
Para trabalhar no dia a dia com desenvolvimento geral (Android, Web, Linux, Windows, embarcados - Arm, etc) recomendamos o 
[Visual Studio Code](https://code.visualstudio.com/) - por ser mais leve e ter diversos recursos extras que podem auxiliar no desenvolvimento, além de ter grande liberdade para personalização. 

No entanto, para trabalhar com Macs e Iphones você deverá utilizar o XCode e um Mac para nas últimas etapas do desenvolvimento do seu app. Entenda que isso é uma necessidade de hardware, mas o código em si não sofre muitas alterações, e é possível aprender a base e preparar o código utilizando somente um computador com outra plataforma (seja Windows ou Linux).


<br>

### `2.1.2` Instalando Dart e Flutter na sua máquina

<!-- TODO: Fazer um checklist com os links de instalação e um passo a passo simples  -->

```
0) Instale o Git

1) Instale o Dart
1.1) Coloque o diretório do dart nas variáveis de ambiente

2) Instale o Android Studio
2.1) Use o Android Studio para instalar o android sdk e android cli
2.2 A) (Opcional) instale o Java SDK separadamente (as instalações mais recentes do Android Studio já vem com o Java SDK junto)
2.2 B) (Não opcional) Coloque o JAVA_HOME nas suas variáveis de ambiente

3) Instale o Flutter
3.1) Coloque o diretório do Flutter em suas variáveis de ambiente

4) Instale o VSCode
4.1) Instale as extensões Flutter e Dart da Google para o VSCode

5) (Opcional) Instale as Ferramentas de Build para Visual Studio (não confundir com o próprio Visual Studio ou com o VSCode) para trabalhar com Windows

(Opcional) Utilize o Android Studio para emulação, instale um dispositivo emulado através do assistente dele

(Opcional) Instale a extensão Material Icons Theme, para melhor visualizar suas pastas e dê uma olhada nas seguintes extensões: GitLens e ErrorLens, especialmente esta última pois aponta a linha onde está ocorrendo o erro de código. 
```

</p>

</details>

<br>

## `2.2` Lógica de Programação

Precisamos entender como criar algorítmos, por tanto, antes de realmente colocar a mão no código, é importante estudar um pouco sobre Lógica de programação.

Nessa etapa não é necessário saber nenhuma linguagem.

- [Curso de lógica de programação](https://www.youtube.com/watch?v=8mei6uVttho&list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV).
- [Curso Lógica de Programação Completo 2021](https://www.youtube.com/watch?v=iF2MdbrTiBM)

<br>

## `2.3` Programação Orientada a Objetos (POO)

O Flutter usa o Dart de forma declarativa. Isso significa que o desenvolvedor usa linguagem de programação para desenhar telas em vez de linguagem de marcação como HTML, XML ou XAML.
Por esse motivo é recomendado que o desenvolvedor já domine os conceitos de P.O.O. e Lógica de programação.

Não tenha medo de aprender 2 ou 3 linguagens a mais para dominar esse [paradigma de programação]().

É inclusive recomendado aprender um pouco sobre o Java, pois é uma linguagem que utiliza exclusivamente a POO, forçando-o a entender toda a base desse paradigma. Também é uma linguagem utilizada para aplicações nativas em Android, entre outras, então continuará sendo um conhecimento interessante para sua jornada.  

- [Programação Orientada a Objetos (POO) - Deivid Willyan ](https://www.youtube.com/watch?v=STdkaNVUKYs)
- [Programação Orientada a Objetos (POO)](https://www.youtube.com/watch?v=QY0Kdg83orY)
- [Curso de programação oriendada a objetos](https://www.youtube.com/watch?v=KlIL63MeyMY&list=PLHz_AreHm4dkqe2aR0tQK74m8SFe-aGsY)

<br>

## `2.4` GIT

Git é um sistema de controle de versões que pode ser utilizado para registrar o histórico de edições de qualquer tipo de arquivo. Pense em algo como um "Save Point" em um jogo ou como o botão Salvar, mas guardando o que foi modificado e por quem foi. O conteúdo abaixo irá ajudá-lo a compreender melhor o que é e como usá-lo. 
Consideramos importante saber isto antes de começar para que você possa utilizá-lo durante seus estudos.

- [Git para desenvolvedores Flutter](https://www.youtube.com/watch?v=Kx3M6XUpcFE)
- [Trabalhando com FORKS no GIT e GITHUB!](https://www.youtube.com/watch?v=osE-7OXqFCI)

P.S.: Não confunda Git com Github ou Gitlab. Esses dois últimos são - de forma básica - plataformas onde você pode utilizar Git para guardar seus projetos.
</details>

<br>

## **`3.` Dart**

<details><Summary><i>[Ver o conteúdo]</i></Summary>
</p>

Dart é a [linguagem de programação]() por trás do [framework]() Flutter.

Sem saber utilizar Dart poucas serão as chances de  

Assista primeiro:

- [Dart (a linguagem do Flutter)](https://www.youtube.com/watch?v=i7IzlVImHEc)
- [Por que o Flutter usa o Dart (Ative as legendas)](https://www.youtube.com/watch?v=5F-6n_2XWR8)
- [Dart (a linguagem do Flutter) em 50 minutos](https://www.youtube.com/watch?v=NZNO6xW5icQ)

https://www.youtube.com/watch?v=NrO0CJCbYLA

É importante ressaltar que o Dart sofreu mudanças consideráveis na segunda metade de 2021, e receberá mudanças a partir do dia 25 de Janeiro (previsto), por tanto, não é recomendado para iniciantes os cursos gravados antes de julho de 2021. Atualizaremos o roadmap conforme estas forem ocorrendo, mas sigam a [documentação do Dart](https://dart.dev/guides) pois esta sempre estará atualizada. 


**CURSOS GRATUITOS**:

- [Curso de Dart (Deivid Willyan)](https://www.youtube.com/watch?v=PgRv_aeqf-4&list=PLRpTFz5_57cseSiszvssXO7HKVzOsrI77)

**CURSOS PAGOS**:

- [Lógica de programação com Dart (Flutterando Masterclass)](https://masterclass.flutterando.com.br/public/products/e141c9c5-0b60-4e0e-96f1-e31d433e2a09)

**DOCUMENTAÇÃO**:

- [Dart doc](https://dart.dev/guides/language/language-tour)

Não pule essa etapa, pois conhecer a base do Dart será o principal diferencial para desenvolver em Flutter.


</details>

<br>

## **`4.` Flutter**

<details><Summary><i>[Ver o conteúdo]</i></Summary>
</p>

Após seguir os passos da sessão anterior, chegou a hora de usar as ferramentas do SDK. Se não conhece o Flutter, leia [ESTE ARTIGO](https://www.freecodecamp.org/portuguese/news/o-que-e-o-flutter-e-por-que-voce-deve-conhece-lo/).

Leu? Já conhecia o Flutter? Por onde você pode começar?
Vamos lá para o roadmap em si. Ao final, colocaremos alguns links de cursos conhecidos e recomendados, alguns gratuitos e alguns pagos. O Flutter e o Dart tem um grande número de criadores de conteúdo que disponibilizam muito material e é difícil manter esse artigo sempre atualizado, então se conhece alguém com um bom conteúdo, pode mandar sua sugestão pelo github para nós.  


## Flutter Widget

https://www.youtube.com/watch?v=lHhRhPV--G0

https://www.youtube.com/watch?v=I9ceqw5Ny-4

- [Flutter Widget of the Week](https://www.youtube.com/playlist?list=PLjxrf2q8roU23XGwz3Km7sQZFTdB996iG)

## Widgets nativos

Tudo no Flutter é Widget.

A tela de um aplicativo Flutter é constituida pela união de outros widgets nativos.

- Domine os principais widgets de alinhamento: **(Column, Row, Stack)**.
- Entenda o funcionamento do **Container**.
- Teste todos os widgets disponível [NESSE CATÁLOGO](https://docs.flutter.dev/reference/widgets).

## Criação de widgets

Existem três formas de criar widgets customizados, o StatelessWidget, StatefulWidget e InheritedWidget. A diferênça entre os três deve ser a primeira coisa que um novo desenvolvedor Flutter deve aprender.

## Componentização de widget

Após aprender a criar widgets customizados, o desenvolvedor deve aprender a dividir esses widgets em arquivos separados para que possa facilitar a compreenção de outras pessoas que estarão lendo o código posteriomente.

Algumas dicas sobre isso:

- Tente ter um arquivo por Widget.
- Reflita o nome do Widget no nome do arquivo: Ex: HomePage(home_page.dart).

## Widgets de inputs, conteúdo gratuito

- [Flutter Curso 2022 #7 - Criação de widgets](https://www.youtube.com/watch?v=u6Q60aDbE_E)
- [AULÃO: Criação de formulários](https://www.youtube.com/watch?v=5SIw8bXiP7o)
- [Formulários e validação no Flutter](https://www.youtube.com/watch?v=q5pcOL-lZ4I)
- [Flutter Curso 2022 #22 - Máscara](https://www.youtube.com/watch?v=xSa3S-TJJww)


### Cursos para Membros

- [FLUTTER AULÃO - Formulários do jeito certo](https://www.youtube.com/watch?v=yjKvlMAtpC4)
- [Tudo sobre Máscaras](https://www.youtube.com/watch?v=sjQLmibDEu4)
- [Tudo sobre animações no Flutter](https://www.youtube.com/watch?v=XM-8UTkFr4c&t=3108s)

## Consumo de APIs externas
### Cursos para Membros

- [AULÃO: Consumo de APIs (Flutterando)](https://www.youtube.com/watch?v=PUQEd7xRldM)
### Cursos gratuito

- [Curso de Flutter #40 - [API] Consumindo API externa (http))](https://www.youtube.com/watch?v=vjeK_oc5cXQ)
- [HTTP e DIO no Flutter para Conectar API REST)](https://www.youtube.com/watch?v=66Lv8aIxtuA)
- [Como consumir uma API usando Flutter de forma gratuita!](https://www.youtube.com/watch?v=wEgT7cgW-ss)

## Domine o Provider

O Provider é a recomendação da equipe do Flutter para quem está iniciando no mundo Flutter para gerenciar estados e injeção de dependência.

- [AULÃO sobre o Provider(Flutterando)](https://www.youtube.com/watch?v=VhsqMahAmOk)
- [Provider em 10 minutos (Renato Mota)](https://www.youtube.com/watch?v=Gm8QuYvOTwE)
- [Como utilizar o Provider e o ChangeNotifier(Prof. Diego Antunes)](https://www.youtube.com/watch?v=xDdAXmAUt6c)
- [Flutter Provider for Beginners (Inglês)](https://www.youtube.com/watch?v=P47JJU6dlcA)

## Aprenda alguns Design Patterns

Padrões de projetos sÃo importantes para o trabalho em equipe.

- [Repository Pattern no Flutter (balta.io)](https://www.youtube.com/watch?v=Q05t3mgaMfk)
- [CopyWIth](https://blog.flutterando.com.br/o-padr%C3%A3o-copywith-no-flutter-dart-267e3d218ffc)
- [Injeção de dependências (Flutterando)](https://www.youtube.com/watch?v=KpPnDHpgHnA&t=60s)
- [MVC, MVP e MVVM no Flutter (Flutterando)](https://www.youtube.com/watch?v=WgadnZcujuc)

## Testes de unidade

### Cursos para Membros

- [AULÃO sobre testes de unidade (Flutterando)](https://www.youtube.com/watch?v=BLHPRg8ickY)

### Cursos gratuito

- [Um programador confiável (Elemar Jr)](https://www.youtube.com/watch?v=XSdT2myLlw4)
- [Semana do Flutter sobre testes (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-etEtbvgDnO40SYKOSktCj4)

## Gerência de estado

O StatefulWidget concede ao Widget a possibilidade de gerenciar o próprio estado. Mas as vezes é necessário mudar o estado de vários widgets em uma ação. Para isso, existe alguns padrões para auxiliar nisso.

https://www.youtube.com/watch?v=3tm-R7ymwhc

- [AULÃO sobre gerência de estado (Flutterando)](https://www.youtube.com/watch?v=_F0GI2dnt-g)
- [ValueNotifier. A reatividade mais rápida do Flutter](https://www.youtube.com/watch?v=S1PgnMqVgsM)
- [Curso de gerência de estadi com ValueNotifier (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-eG0eVkHu2IaO48TljxPjPq)
- [AULÃO sobre Triple (Flutterando)](https://www.youtube.com/watch?v=CS97q2PwjSo)
- [Curso de Flutter #6 - Estados (StatelessWidget)](https://www.youtube.com/watch?v=4CCW_cdVBQg)
- [Curso de Flutter #8 - Estados (StatefulWidget)](https://www.youtube.com/watch?v=8-mnyze0gKw)

### Cursos para Membros

- [AULÃO sobre BLoC (Flutterando)](https://www.youtube.com/watch?v=UB28e59GmK8)
- [AULÃO sobre MobX (Flutterando)](https://www.youtube.com/watch?v=Z6U6L9e8gmE)

## Arquitetura

A arquitetura de um projeto define a vida útil do mesmo. Todo app tem alguma arquitetura, mesmo que o desenvolvedor não tenha pensado nisso.

### Cursos para Membros

- [AULÃO sobre Clean Architecture (Flutterando)](https://www.youtube.com/watch?v=fABLC2fxQwg)
- [Li o Clean Architecture 2 vezes!!! Dá pra aplicar no Flutter?](https://www.youtube.com/watch?v=VacEeKvY2bg&list=PLlBnICoI-g-d-v_fWlkZX2HRgHHPnJx9s)

### Cursos gratuito

- [Playlist sobre Clean Dart (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-v_fWlkZX2HRgHHPnJx9s)
- [Curso sobre Arquitetura (Deivid Willyan)](https://www.youtube.com/playlist?list=PLRpTFz5_57cvCYRhHUui2Bis-5Ybh78TS)

## Conhecimento sobre InheritedWidget

- [Flutter Curso 2022 #12 - Primeira e última aula sobre InheritedWidget](https://www.youtube.com/watch?v=aTbuuvSq-Gs)



## Cursos gratuitos

- [Como aprender Flutter em 2022?](https://www.youtube.com/watch?v=85eg7P1se4Y)
- [Flutter Curso 2022 (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-fuy5jZiCufhFip1BlBswI7)
- [Catálogo de Widgets](https://docs.flutter.dev/reference/widgets)

## Cursos pagos

- [Flutter para iniciantes](https://masterclass.flutterando.com.br/flutter-iniciante-2)
- [Curso de Flutter (COD3R)](https://flutterando.page.link/rniX)

