# curso-alura-arquitetura-css
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
- Devemos utilizar classes css no lugar de seletores HTML para estilizar os elementos da página.
- É uma boa prática separarmos cada "pedaço" do nosso site em arquivos diferentes, por exemplo, separando o arquivo css em: `cabecalho.css, menu/menu-lista.css, menu/menu-item.css e menu/menu-link.css`.
- A ideia de criar um arquivo CSS para cada elemento da página tem um nome: Atomic Design, que consiste, basicamente, em um modelo de organizar os componentes, pastas e a estrutura do nosso CSS a partir do princípio de átomos, onde um átomo é toda tag HTML.
  - `Àtomo`: por exemplo, em um formulário de pesquisa um átomo seria uma `label` ou`input` ou um `button`.
  - `Moléculas`: por exemplo, seria a junção `label`, `input` e um `button`, ou seja, um formulário de pesquisa.
  - `Organismo`: um conjunto de Moléculas.
  - `Template`: um conjunto de Organismos.

