# <p style="text-align: center;">O que é um desenvolvedor WEB? R: web develovers são pessoas que codificam sites na rede

- As bases de construção para um site são as linguagens HTML, CSS e Javascript

    - <strong>HTML</strong> (HyperText markup language) - Controla qual o conteúdo da página

    - <strong>CSS</strong> (Cascading Style Sheets) - Define os estilos que serão aplicados na página
    
    - <strong>Javascript</strong> - Permite interatividade e mobilidade á página

- <strong>Lógica pro trás de um web site</strong>:

    Quando se busca um site, ocorre uma chamada por seu endereço para os servidores que o mantêm, que por sua vez enviam uma cópia para o dispositivo ligante. O endereço chamado se chama URL
<hr>

# <p style="text-align: center;">URL (Uniform Resource Locator)

Endereço unificado na rede para cada página, formado por diversas partes:
- <strong>http/https</strong>: protocolo de trasferencia de hipertextos/protocolo de trasferencia de hipertextos seguro
    - <em>
        <p style="font-size: smaller;">Na prática, a diferença se dá pela encriptação dos dados para uma conexão mais segura</p>
    </em>
- <strong>Domínio</strong>: identificador de endereço exclusivo para uma página na rede, é por ele que usuários normalmente acessam as páginas
- <strong>Caminho/Path</strong>: representam uma guia de subpáginas em um site, para não ser necessário ir sempre a aba de inicio para transitar em um site
<hr>

# <p style="text-align: center;">IP  (Internet Protocol/endereço IP)
- Um identificador único para os servidores encontrarem as páginas
<hr>

# <p style="text-align: center;">servidores DNS
- Intermediador que migra a URL para um código IP durante uma pesquisa
<hr>

# <p style="text-align: center; font-weight:1000;">Html

 <p style="font-size: smaller; text-align: center;"><em>Linguagem que dita quais conteúdos estarão  presentes na página, bem como titulos, divisões, seções, paragrafos, imagens, audios, videos, animações, etc.</em>

<p style="text-align: center";>- Principais elementos que a compõem-

- <strong>&lt;!DOCTYPE html&gt;</strong> : sinaliza para o navegador quam versão está sendo utilizada, atualmente apenas serve para marcar o arquivo como html 
- <strong>&lt;html&gt;</strong> : elemento root do arquivo, tudo está dentro dele
    - <strong>&lt;head&gt;</strong> : armazena os <strong>metadados</strong> da página (infos sobre estilo, script e ferramentas auxiliares)
    - <strong>&lt;title&gt;</strong> : define o titulo da página
    - <strong>&lt;link herf="link" rel="tipo"&gt;</strong> : abriga referências externas de estilo ou script para a página
    - <strong>&lt;body&gt;</strong> : abriga todo o conteúdo do site que será apresentado ao usuário
    - <strong>&lt;header&gt;</strong> : assistente de divisão do topo da página
    - <strong>&lt;main&gt; </strong>: assistente de divisão do meio da página    
        - <strong>&lt;h1-h6&gt;</strong> : titulos e subtitulos
        - <strong>&lt;p&gt;</strong> : paragrafos
        - <strong>&lt;a&gt;</strong> : links
        - <strong>&lt;img&gt;</strong> : imagens
        - <strong>&lt;ol e ul/menu&gt;</strong> : listas ordenadas e não ordenadas (&lt;li&gt; : elemento da lista)
        
        - <strong>&lt;article&gt;</strong> : representa uma composição separada de uma página
        - <strong>&lt;nav&gt;</strong> : seção destinada a links de navegação/ menus
        - <strong>&lt;section&gt;</strong> : seção genêrica de divisão de conteúdos na página
        - <strong>&lt;div&gt;</strong> : container genêrica de agrupamento ou estilização
        - <strong>&lt;table&gt;</strong> : abertura de uma tabela
            - <strong>&lt;thead&gt;</strong> : cabeçalho da tabela
                - <strong>&lt;caption&gt;</strong> :  legenda/titulo da tabela
                - <strong>&lt;th&gt;</strong> : elemento informativo
            - <strong>&lt;tbody&gt;</strong> : corpo da tabela
                - <strong>&lt;td&gt;</strong> : dado relevante
            - <strong>&lt;tfoot&gt;</strong> : rodapé da tabela
        - <strong>&lt;form&gt;</strong> : abertura de um formulário
        - <strong>&lt;footer&gt;</strong> : assistente de divisão do final da página
<hr>

# <p style="text-align: center;">comentários em html
    para introduzir comentários em html usasse a marcação <!--comentário-->;
<hr>

# <p style="text-align: center;">Fontes em html

Fontes ditam a aparência dos simbolos utilizados na página, mais comumente das letras

- Atributos das fontes
    - font-size: ligado ao tamanho das letras
    - font-family: dita o estilo e forma das letras
    - font-weight: representa o peso das letras
    - font-style: estilos expecificos para letras

- para mais tipos de fonts, recomenda-se buscas na rede
<hr>

# <p style="text-align: center;">links

        <a href="link" rel="">

- Links ou ancoras são resursos interagíveis que permitem o usuário transitar entre sites, baixar conteúdos e muitas outras possibilidades.
    - Para acessas páginas de um mesmo produto, aconselhasse utilizar: 
        - &lt;a href="página interna" rel="internal"&gt;
    - Para acessas páginas externas ao conteúdo anterior, aconselhasse utilizar:
         - &lt;a href="página externa" rel="external" target="_blank"&gt;
    - Para acessar downloads, utilize:
        - &lt;a href="path" download="arquivo" type="formato do arquivo"&gt;
<hr>

# <p style="text-align: center;">Imagens

        <img src="path.tipo" alt="descrição">

- Marcadores vazios que mostram conteúdos guardados em seus atributos, mais expecificamente o <strong>src=""</strong>, o atributo <strong>alt=""</strong> quarda uma guia de texto que descreve a imagem.

<hr>

# <p style="text-align: center;">Listas

Listas são elementos que podem organizar itens de forma ordenada ou não, normalmente utilizadas para itens de menus, links ou itens genêricos

    lista ordenada              Lista não ordenada

        <ol>                            <ul>
            <li>                            <li>
            <li>                            <li>
            <li>                            <li>
        <ol>                            <ul>

- O marcador <strong>&lt;ol&gt;</strong> representa o inicio de uma lista ordenada, já <strong>&lt;ul&gt;</strong> inicia a lista não ordenada. Todos os elementos de uma lista são precedidos por um marcador <strong>&lt;li&gt;</strong> sem fechamento

- Para alterar a forma dos dots de cada elemento de uma lista, ordenada ou não, utiliza-se o atributo type, sucedido pela forma desejada.
<hr>

# <p style="text-align: center; font-weight:1000;">CSS

  <p style="font-size: smaller; text-align: center;"> Linguagem de estilização em camada, capaz de aplicar diversas regras de estilização em cascata

- Essa linguagem pode ser aplicada de diversas maneiras, suas três principais são:
    - Inline: aplicasse o atributo style dentro de um marcador HTML e defini-se as caracteristicas desejadas
        - Essa abordagem afeta apenas um elemento.
    - Internamente: criando a marcação style no head do arquivo e organizando as caracteristicas no mesmo arquivo
        - As alterações feitas de modo generalizado citando apenas classes ou tipos afetam todo o código
    - Links externos: criando link no head e arquivos .css para manter os dois conteúdos separados
        - É possivel criar mais de um arquivo e melhora a organização no geral
<hr>

# <p style="text-align: center;"> Comentários em css
     Para introduzir comentários às CSS, utiliza-se: /* comentário */

<hr>

# <p style="text-align: center">Seletores em CSS
Seletores identificam qual(is) elementos serão alterados com as caracteristicas entregues
- Tipos de tag

        CSS: p { ... }  --->  <p>...</p>
    - Seleciona todas as tags HTML desse tipo
- ID

        CSS: p#id { ... }  --->  <p id="id">...</p>
    - Seleciona apenas o elemento que possui aquele id
- Classe

        CSS: p.classe { ... }  --->  <p class="classe">...</p>
    - Seleciona todos os elementos que possuem essa classe    
- Attributo

        CSS: [src] { ... }  --->  <img src="...">
    - Seleciona todos os elementos que possuem aquele atributo
- Universal

        CSS: * { ... } ---> <p>....</p> <img ...> <div>...</div>
    - Seleciona todos os elementos do arquivo
- Grupo/Lista de seletores

        CSS: p, p.classe, p#id { ... }  --->  <p>...</p> <p class="classe">...</p> <p id="id">...</p> 
    - Seleciona todos os elementos que baterem com alguma dessas características
<hr>

# <p style="text-align: center">Pseudo-classes em CSS
Especifica o estado do elemento para que os estilos sejam aplicados

- <strong>Estado de exibição</strong>: 
    - Fullscreen: elemento em tela cheia
    - Picture-in-picture: elemento em minimização sobreposto por outro elemento
- <strong>Estado de entrada</strong>: usado em elementos de formulários
    - <strong>autofill</strong>: entrada preenchida automaticamente
    - <strong>checked</strong>: caixa de seleção ativa
    - <strong>disable</strong>: elemento desabilitado
    - <strong>enable</strong>: elemento habilitado
    - <strong>optional</strong>: elemento de resposta opcional no formulário
    - placeholder-shown: exibindo texto de espaço reservado
    - read-only: não pode ser alterado
    - <strong>required</strong>: elemento requerido pelo formulário
- <strong>Linguagem</strong>:
    - lang(parametro): baseia-se no idioma do elemento
- <strong>Links e direcionadores</strong>:
    - <strong>link</strong>: não visitados
    - <strong>visited</strong>: visitados
    - any-link: ambos
    - local-link: páginas/paths de um mesmo site
    - <strong>target</strong>: destino
    - target-within: destino e relacionados
    - scope: relacionados
- <strong>Estado da mídia</strong>:
    - <strong>playing</strong>: tocando
    - <strong>paused</strong>: pausado
- <strong>Estado temporal</strong>:
    - current: sendo exibido
    - past: anterior
    - future: proximo
- <strong>Parentais</strong>:
    - <strong>root</strong>: a raiz do documento, geralmente HTML
    - empty: sem descendentes
    - <strong>nth-child(parametro)</strong>: escolhe descendentes baseado em um parametro
    - first-child: primeiro descendente exibido
    - last-child: ultimo descendente exibido
    - only-child: elemento com descendente único
    - nth-of-type: escolhe os elementos daquele tipo baseado em um parametro
    - first-of-type: primeiro elemento daquele tipo
    - last-of-type: ultimo elemetno daquele tipo
- <strong>Ação do usuário</strong>:
    - <strong>active</strong>: ativado pelo usuário
    - <strong>hover</strong>: selecionado ou com o mouse por cima
    - <strong>focus</strong>: tem foco na exibição
    - focus-visible: tem foco e atenção do usuário
    - focus-within: elemento focado e seus descendentes
- <strong>Funcionais</strong>: seguem uma lógica para serem encontrados
    - <strong>where()</strong>: cria uma cadeia multipla de seletores, se qualquer um deles for seguido, o elemento é alterado pelo estilo
<hr>

# <p style="text-align: center"> Box model

Representação dos elementos para os comandos CSS, dividindo as áreas em margin, border, padding e conteúdo
- <strong>margin</strong>: área externa ao elemento, determina a distância entre ele e outros elementos
- <strong>border</strong>: linha que representa o final da área do conteúdo
- <strong>padding</strong>: área entre a borda e o conteúdo
- <strong>conteúdo</strong>: os elementos do arquivo HTML
<hr>

# <p style="text-align: center"> Displays block vs inline

        display: block;
        display: inline;
        display: inline-block;

Atributo que dita se um marcador cosumirá todo o espaço em sua volta ou se será tratado como em uma linha, utilizando apenas seu espaço

- Elementos inline não apresentam margins, apenas paddings, mesmo quando organizados
- Para apresentar ambas as características, ter margins e paddins e ainda ser encaixado em uma linha, utilizamos o atribulo <strong>display: "inline-block"</strong>;
<hr>

# <p style="text-align: center"> Margin collapsing em elemento inline-block
O collapso de margens ocorre quando apenas o maior valor de margem vertical é respeitado entre os elementos, sem somar seus valores
- Ocorrem apenas com margins verticais.
<hr>

# <p style="text-align: center"> Box shadow

        box-shadow: bottom left spreading cor;
        box-text: bottom left spreading cor;
- Cria um efeito de sombra em volta do elemento ou do conteúdo
<hr>

# <p style="text-align: center;"> Peculiaridades

- Elementos aninhados herdam as regras de seus containers
- O elemento mais especifico dita a regra vigente
- dentro dos seletores, uma regra escrita diversas vezes recebe a ultima escrita como a vigente
- O atributo <strong>text-align</strong> não centraliza a tag, mas sim seu conteúdo, tornando possível centralizar uma tag que é conteúdo de outra tag com esse comando
- É possivel dar margens verticais negativas para elementos como imagens, o que as faz "subir dentro de seu container"
<hr>

# <p style="text-align: center"> Git & gitHub

- <strong>Git</strong>: Ferramenta de versionamento local que permite armazenar e modificar diferentes versões de um código
    - <strong>Diretório</strong>: pasta do projeto
    - <strong>Repositório</strong>: todos os arquivos e pastas adicionados e versionados
        - <strong>Commits</strong>: Snapshot ( é o registro do estado de um sistema, aplicação ou arquivos em determinado ponto no tempo em formato de imagem )
        - <strong>Branch</strong>: local de armazenamento de um commit dentro de um repositório, permitindo maior organização dentro do diretório
- <strong>gitHub</strong>: Rede social que serve para salvar seus versionamentos de modo publico ou privado em servidores, permitindo colaborações entre devs
<hr>

# <p style="text-align: center"> GUI & CLI

- <strong>Gui</strong> (graphic user interface): interface visual que permite interação entre a maquina e o usuário

- <strong>Cli</strong> (command line interface): interface de texto que permite comandar a maquina por meio de comandos
    - No Windows chamamos de <strong>prompt</strong>
    - No Mac apelidamos de <strong>z shell</strong>
<hr>