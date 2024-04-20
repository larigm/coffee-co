# coffee-co
Lista de verificação | Indicadores de Desempenho (ID) dos Resultados de Aprendizagem (RA)
RA1 - Utilização Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos.
ID0 - Prototipa interfaces adaptáveis ​​para no mínimo os tamanhos de tela mobile e desktop, usando ferramentas de design como Figma, Quant UX ou Sketch.
ID 01 - Implemente um layout responsivo de uma página web utilizando um Framework CSS, como Bootstrap ou Tailwind, que se adapta especificamente a diferentes tamanhos de tela e dispositivos.
ID 02 - Utilize técnicas avançadas de CSS, como Flexbox ou Grid Layout, para criar layouts responsivos e fluidos em diferentes resoluções de tela.
ID 03 - Utilize os componentes CSS e JavaScript oferecidos por um Framework CSS, como cartões, modais ou carrosséis, aplicando estilos personalizados conforme o necessário.
ID 04 - Implemente um layout fluido e responsivo utilizando unidades de viewport relativas (vw, vh) em vez de unidades fixas (px) para criar uma experiência de usuário consistente em diferentes dispositivos e tamanhos de tela.
ID 05 - Implemente animações em elementos da página, como hover, fadeIn/fadeOut, slideIn/slideOut, utilizando animações CSS ou bibliotecas de animação, como o Animate.css, para fornecer feedback visual ao usuário e criar uma experiência interativa.
ID 06 - Cria transições personalizadas entre diferentes estados da página ou elementos, como mudanças de layout, alterações de cor ou exibição/ocultação de elementos, usando Transições CSS ou Animação CSS, para melhorar a usabilidade e a aparência da aplicação.
ID 07 - Aplicar um Design System consistente, definindo diretrizes de estilo, núcleos, tipografia e padrões de componentes que são seguidos em toda a aplicação, garantindo uma experiência de usuário uniforme e atraente.
RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado do cliente, utilizando a API do HTML e expressões regulares (REGEX).
ID 08 - Implementa tratamento de formulários no lado cliente com apresentação de mensagens de erro ou sucesso, utilizando os recursos da API do HTML, como validação de campos obrigatórios, tipo de entrada e limites de caracteres, garantindo que os dados inseridos sejam válidos antes de sendo enviados para o servidor.
ID 09 - Aplicar expressões regulares (REGEX) de forma eficiente para realizar validações customizadas nos campos de formulários, como formatos específicos de e-mail, telefone, dados ou outros padrões personalizados definidos pelos requisitos do projeto.
ID 10 - Incorpora elementos de listagem, como checkbox, radio ou select, de maneira eficiente em formulários web, possibilitando a seleção e coleta precisa de dados pelos usuários.
ID 11 - Realiza a escrita e leitura de dados no Web Storage, permitindo a persistência de informações entre sessões de usuário e fornecendo uma maneira eficaz de armazenar dados localmente no navegador.
RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web, incluindo Node.js, NPM e linters para garantir a qualidade do código, juntamento com boas práticas de versionamento e organização de projetos.
ID 12 - Configure melhore um ambiente de desenvolvimento usando Node.js e NPM para gerenciar pacotes e dependências do projeto, facilitando a instalação e o uso de bibliotecas e ferramentas de terceiros.
ID 13 - Utilize linters, como ESLint ou Stylelint, para analisar e corrigir automaticamente problemas de código, incluindo erros de sintaxe, estilo e boas práticas, garantindo a qualidade e consistência do código do projeto.
ID 14 - Adota boas práticas de versionamento utilizando sistemas como Git, criando e gerenciando repositórios com filiais adequadas.
ID 15 - Utilize técnicas de minificação e otimização de recursos, como minificação de CSS e JavaScript e otimização de imagens, para melhorar o desempenho e o tempo de carregamento do site ou aplicação.
ID 16 - Organizar os arquivos do projeto em uma estrutura consistente, lógica e modular, facilitando a localização, manutenção e escalabilidade.
ID 17 - Utilize as metodologias BEM (Block Element Modifier) ​​ou SMACSS (Scalable and Modular Architecture for CSS) para organizar e estruturar os estilos CSS de forma eficiente, garantindo a reutilização de estilos, a legibilidade do código e a manutenção sustentável do projeto.
RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade das páginas web.
ID 18 - Utilize a biblioteca jQuery para manipular o DOM e aprimorar a interatividade das páginas web, implementando funcionalidades como eventos, animações e manipulação de elementos HTML de forma eficiente.
ID 19 - Selecionado e integra com sucesso um plugin jQuery, como o jQuery Mask Plugin ou outro plugin relevante para o projeto, a fim de melhorar a funcionalidade ou a aparência de elementos específicos em uma página web.
ID 20 - Utiliza bibliotecas de componentes web, como Lit, para criar componentes reutilizáveis ​​e encapsulados, melhorando a modularidade e a manutenibilidade das páginas web.
ID 21 - Utilize uma biblioteca de componentes pronta, como Material Web Components ou outra de sua escolha, ou então, algum componente independente (standalone) a fim de oferecer funcionalidades específicas sem a necessidade de estar integrado a uma biblioteca completa.
RA5 - Efetuar requisições assíncronas para uma API falsa e APIs públicas, permitindo a obtenção e manipulação de dados de forma dinâmica.
ID 22 - Realiza requisições assíncronas para APIs públicas, utilizando conceitos específicos como AJAX, Fetch API ou bibliotecas, para obter dados dinâmicos e realizar a manipulação e exibição dos resultados na página web.
ID 23 - Realiza requisições assíncronas para uma API falsa utilizando conceitos específicos como AJAX, Fetch API ou bibliotecas, para manipular dados e exibir os resultados na página web.
Manual de execução
Clonar o repositório comgit clone
Fazer checkout no branch developque contém as modificações mais recentes
Abra o projeto no editor Visual Studio Code (VS Code)
Abra um terminal pelo VSCode ou qualquer terminal do seu Sistema Operacional apontando para o diretório raiz do projeto
Instalar as dependências contidas nopackage.json
Comando:npm i
(Opcional) Instale o JSON Server globalmente disponível emhttps://www.npmjs.com/package/json-server
Comando:npm i -g json-server
É opcional porque a dependência já vem cadastrada no arquivo package.jsonpara instalação local na pastanode_modules
Execute uma API Fake (JSON Server) através de um dos seguintes comandos:
Execução via script registrado no package.json:npm run json:server:routes
Ou via Execução explícita:json-server --watch db.json --routes routes.json
O comando para execução do JSON Server deve ser aplicado no diretório raiz do projeto, ou seja, que contém o arquivo db.jsone routes.json.
Por padrão, a aplicação JSON Server executa no endereçolocalhost:3000
Executar o projeto frontend.
