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

## 