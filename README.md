# Igreja Betesda

Site institucional estático da Igreja Betesda Central. Reúne informações sobre a igreja e permite navegar por páginas de história, ministérios, pequenos grupos, eventos, temas anuais e contato.

## Funcionalidades

- Páginas institucionais e páginas individuais dos ministérios.
- Listagem de eventos e páginas de detalhes selecionadas pelo parâmetro `id` da URL.
- Detalhes de pequenos grupos e galerias selecionados pelo parâmetro `grupo`.
- Galerias de imagens com visualização ampliada (lightbox) nas páginas que as incluem.
- Links externos para redes sociais e localização.

## Tecnologias

- HTML5, CSS3 e JavaScript.
- Bootstrap 5 e Bootstrap Icons, carregados por CDN. As versões referenciadas variam entre as páginas.


## Estrutura do projeto

```text
.
├── index.html
├── assets/
│   └── images/       # Logo e imagens de eventos, ministérios, grupos e temas
├── css/
│   └── style.css     # Estilos compartilhados
├── js/
│   └── main.js       # Dados e interações de eventos, grupos e galerias
└── pages/
    ├── *.html        # Páginas institucionais e de conteúdo
    └── ministerios/  # Páginas individuais dos ministérios
```

## Pré-requisitos

- Navegador atualizado.
- Acesso à internet para carregar Bootstrap, Bootstrap Icons e conteúdos externos incorporados nas páginas.



## Instalação e execução

Não é necessária instalação de dependências. Abra o arquivo `index.html` em um navegador. É necessária conexão com a internet para carregar Bootstrap, Bootstrap Icons e conteúdos externos.

## Acessos principais

- Início: `/`
- Sobre e história: `/pages/sobre.html` e `/pages/historia.html`
- Ministérios: `/pages/ministerios.html`
- Pequenos grupos: `/pages/pequenos-grupos.html`
- Eventos: `/pages/eventos.html`
- Detalhe de evento: `/pages/evento.html?id=retiro-mib`
- Detalhe de pequeno grupo: `/pages/pg.html?grupo=sintonia`
- Temas e contato: `/pages/temas.html` e `/pages/contato.html`
- Página de um ministério: `/pages/ministerios/betesda-kids.html`

Os parâmetros `id` e `grupo` correspondem a dados definidos no JavaScript; valores não cadastrados não representam registros disponíveis.

## Público beneficiado

O público atendido é a comunidade religiosa da Igreja Betesda Central, em Quixeramobim, Ceará, incluindo membros, participantes dos ministérios e pequenos grupos, visitantes e pessoas que procuram informações sobre a igreja. A instituição apresenta no site atividades como cultos, ministérios, pequenos grupos, eventos, acolhimento e ações do Betesda Social.

## Interação realizada

A proposta surgiu de contato direto com Michael, que já havia manifestado a necessidade de um serviço para a igreja. Conversações foram feitas bem como o levantamento das necessidades e confirmação da proposta. Com o levantamento dos requisitos foi dada inicio a implementação direta.

## Problema identificado

Falta de controle das informações e divugações, solução implementada: Centralizar toda a comunicação institucional (eventos, ministérios, pequenos grupos e contatos) em um único ponto de acesso público, eliminating a dependência de redes sociais ou avisos fragmentados. Ao adotar uma arquitetura de páginas estáticas, a aplicação resolve o problema de comunicação da igreja com custo zero de infraestrutura inicial, alta velocidade de carregamento e manutenção simplificada.

## Escopo da primeira versão

A primeira versão tem como objetivo disponibilizar informações institucionais em um site multipágina. Inclui páginas sobre a igreja e sua história, listagens e páginas individuais de ministérios, pequenos grupos, temas anuais, eventos e contato, além de galerias de imagens e navegação entre páginas.

O escopo é informativo e estático: não há backend, banco de dados, autenticação, painel administrativo ou envio de formulários ao servidor. O conteúdo e os dados usados para montar detalhes de eventos e pequenos grupos estão nos próprios arquivos do projeto; alterações são feitas diretamente neles.