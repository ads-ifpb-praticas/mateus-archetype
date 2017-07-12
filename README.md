---Como instalar o archetype--
Passo 1: clone o seguinte repositorio https://github.com/ads-ifpb-praticas/mateus-archetype

Passo 2: Na pasta que você acabou de clonar prossiga para “/target/generated-sources/archetype” e execute “mvn install” para instalar o archetype no seu repositório local.

Passo 3: Para verificar a instalação, execute ” mvn archetype:generate -DarchetypeCatalog=local “. Este comando busca por archetypes no seu catálogo local e deverá exibir o archetype que acabou de ser criado. E você poderá selecionar por o índice de archetypes o que você deseja utilizar, então digita tal índice e começa a configurar todos os dados do seu novo projeto;
