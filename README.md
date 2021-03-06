# curso-alura-arquitetura-css
<p>
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/my-study-area/curso-alura-arquitetura-css">
    <a href="https://github.com/my-study-area">
        <img alt="Made by" src="https://img.shields.io/badge/made%20by-adriano%20avelino-gree">
    </a>
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/my-study-area/curso-alura-arquitetura-css">
    <a href="https://github.com/EliasGcf/readme-template/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/my-study-area/curso-alura-arquitetura-css">
    </a>
</p>
Curso de Arquitetura CSS: Descomplicando os problemas

## Módulo 01 - Layout base e Estilização de cabeçalho
### Aula 01.01 - Preparando o ambiente
- layout: [Layout](https://www.figma.com/file/0gMF5BPgplPYqQA6Om1T1sk9/alura-bootstrap?node-id=0%3A1)

### Aula 01.02 - Introdução
- O projeto será desenvolvido usando a metodologia `Atomic Design`.
- Serão utilizadas Metodologias de nomenclatura das classes.

### Aula 01.03 - Conhecendo o projeto
- No diretório `assets` ficam os arquivos estáticos
- O arquivo `normalize.css` é o responsável por resetar estilos do nosso navegador.
- o arquivo `reset.css` é referente aos estilos que desejamos que sejam padrão em todos os navegadores, mas que não estão presentes no `normalize.css`. Por exemplo, usaremos na nossa aplicação a fonte padrão **Roboto**.

### Aula 01.04 - Criando o cabeçalho
- Normalmente a construção do site segue a sequência de cima para baixo, por exemplo, cabeçalho, corpo e por último o rodapé.

### Aula 01.05 - Estilizando o cabeçalho

### Aula 01.06 - Simplificando os seletores
- Devemos utilizar classes css no lugar de seletores HTML para estilizar os elementos da página.
- É uma boa prática separarmos cada "pedaço" do nosso site em arquivos diferentes, por exemplo, separando o arquivo css em: `cabecalho.css, menu/menu-lista.css, menu/menu-item.css e menu/menu-link.css`.
- A ideia de criar um arquivo CSS para cada elemento da página tem um nome: Atomic Design, que consiste, basicamente, em um modelo de organizar os componentes, pastas e a estrutura do nosso CSS a partir do princípio de átomos, onde um átomo é toda tag HTML.
  - `Àtomo`: por exemplo, em um formulário de pesquisa um átomo seria uma `label` ou`input` ou um `button`.
  - `Moléculas`: por exemplo, seria a junção `label`, `input` e um `button`, ou seja, um formulário de pesquisa.
  - `Organismo`: um conjunto de Moléculas.
  - `Template`: um conjunto de Organismos.

### Aula 01.07 - Criando seletores simples
- Para criar um seletor simples, que seja possível sobrescrever e fácil de entender devemos usar classes.Ex: `.titulo {}`

### Aula 01.08 - Faça como eu fiz na aula

### Aula 01.09 - O que aprendemos?
- a utilizar seletores CSS mais simples;
- a organizar a estruturar os arquivos css do projeto;
- Metodologia Atomic Design.

## Módulo 02 - Estilização de Banner e Sobre
### Aula 02.01 - Projeto da aula anterior

### Aula 02.02 - Criando o banner e sobre
- `BEM`: _Block_, _Element_ e _Modifier_, ou seja, "_bloco, elemento e modificador_", os três pilares da metodologia BEM.

### Aula 02.03 - Estilizando o banner

### Aula 02.04 - Para saber mais

### Aula 02.05 - Estilizando o sobre
- Não é necessário aplicar a metodologia `BEM` para nomenclatura de arquivos. Ex: uma classe chamada `.sobre__titulo` não precisar estar inserida num arquivo chamado `sobre__titulo.css`. Pode-se utilizar o nome de arquivo `sobre-titulo.css`.

### Aula 02.06 - Metodologia BEM
De acordo com a metodologia BEM, como podemos nomear a classe de um elemento cabecalho, que é filho de um painel?  
`R:` `.painel__cabecalho {}`, estamos criando um bloco chamado **painel** e separando seu filho **cabecalho** com dois underlines.

### Aula 02.07 - Faça como eu fiz na aula

### Aula 02.08 - O que aprendemos?
- Um padrão para nomear as classes de CSS;
- Conhecemos a metodologia BEM.

## Módulo 03 - Estilização das Receitas
### Aula 03.01 - Projeto da aula anterior

### Aula 03.02 - Preparando o ambiente

### Aula 03.03 - Estruturando as receitas

### Aula 03.04 - Estilizando as receitas

### Aula 03.05 - Organizando o CSS do painel
Pensando em um componente de painel com cabeçalho, título, descrição e botão, como podemos organizar esses arquivos?  
`R:` Para melhor organização e manutenção do projetos CSS, estudamos que podemos utilizar a metodologia Atomic Design, que consiste na criação de um arquivo .css para cada elemento dos nossos componentes.
```
painel/cabecalho.css
painel/titulo.css
painel/descricao.css
painel/botao.css
```

### Aula 03.06 - Faça como eu fiz na aula

### Aula 03.07 - O que aprendemos?
- Organização e estrutura de arquivos .css;
- Separação de responsabilidades;
- Criar e manter arquivos menores.

## Módulo 04 - Estilização do Quem Somos
### Aula 04.01 - Projeto da aula anterior

### Aula 04.02 - Preparando o ambiente

### Aula 04.03 - Estruturando o quem somos

### Aula 04.04 - Estilizando quem somos
- Para nomearmos arquivos de classes com nomes compostos, como por exemplo `quem-somos`, devemos utilizar o padrão `camel case` ficando da seguinte forma: `quemSomos.css`, `quemSomos-titulo.css` e `quemSomos-descricao.css`.

### Aula 04.05 - Estilizando as pessoas

### Aula 04.06 - Boas práticas com imagens
- É uma boa prática mantermos as propriedades em ordem alfabética.
- É interessante usarmos imagens ilustrativas no HTML. As imagens das receitas têm relevância e devem ser mantidas no HTML, mas o banner é somente uma ilustração. Sendo assim, vamos substituí-lo por uma `<div>`.
- A propriedade `background: url('../../img/banner.jpg') no-repeat center / cover;` substitui as propriedades   `background-image: url('../../img/banner.jpg');`,
`background-repeat: no-repeat;`, `background-position: center;` e `background-size: cover;`.

### Aula 04.07 - Referenciando imagens
- Algumas vezes, podemos ter dúvidas sobre o que deve estar em CSS e o que deve estar em HTML. Talvez, a mais comum seja sobre imagens: devemos referenciá-las em CSS ou diretamente no HTML?

- Um arquivo CSS é responsável por estilização e o HTML é responsável por informação. Ou seja, no primeiro definimos "como" e no segundo "o que" será visualizado.

Onde podemos importar e referenciar nossas imagens?  
`R:` Podemos importá-las no CSS e atribuir o estilo à uma classe e por meio da classe mostrar as imagens.Por tratar de imagens ilustrativas, sabemos que os estilos devem estar em nosso CSS.

### Aula 04.08 - Faça como eu fiz na aula

### Aula 04.09 - O que aprendemos?
- Imagens ilustrativas devem estar referenciadas em nossos arquivos .css
- Boas práticas com importação de imagens;
- A manter as estilizações nos arquivos de estilo.

## Módulo 05 - Estilização do Rodapé e Responsividade
### Aula 05.01 - Projeto da aula anterior

### Aula 05.02 - Criando o rodapé

### Aula 05.03 - Deixando o site responsivo

### Aula 05.04 - Finalizando a responsividade

### Aula 05.05 - Site responsivo
Muitas vezes, focamos em criar um site para pessoas que utilizam computadores e acabamos nos esquecendo das que usam celulares ou tablets. Com isso, nossos sites podem quebrar ou ficar ruim para utilização em pequenos dispositivos.

Como podemos resolver esse problema?

`R:` Tornar o site responsivo, de forma que se adapte aos diferentes tamanhos de tela.

### Aula 05.06 - Faça como eu fiz na aula

### Aula 05.07 - Conclusão

### Aula 05.08 - O que aprendemos?
- Tornar um site responsivo;
- Como configurar a adaptação do site a diferentes tamanhos de tela.
