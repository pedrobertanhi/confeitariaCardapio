# Caramelo Pâtisserie

Cardápio digital desenvolvido em grupo para uma confeitaria. O site apresenta a marca, os produtos disponíveis e páginas individuais com descrição, tamanho e cálculo de preço.

![Uploading image.png…]()


## Funcionalidades

- Página inicial com apresentação da confeitaria e produtos em destaque.
- Catálogo carregado dinamicamente a partir de um arquivo JSON.
- Página de detalhes acessada pelo identificador de cada produto.
- Seleção de tamanho com atualização automática do preço.
- Página institucional sobre a confeitaria.
- Mapa incorporado e atalhos para Instagram e WhatsApp.
- Menu adaptado para telas menores.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- JSON para armazenar os dados dos produtos
- Google Maps incorporado

## Executar localmente

O catálogo utiliza `fetch` para carregar o arquivo `scripts/data.json`. Por isso, execute o projeto por meio de um servidor local:

```bash
git clone https://github.com/pedrobertanhi/confeitariaCardapio.git
cd confeitariaCardapio
python -m http.server 8000
```

Depois, acesse **http://localhost:8000/**.

Também é possível usar extensões como **Live Server** no Visual Studio Code.

## Estrutura do projeto

| Caminho | Conteúdo |
| --- | --- |
| `index.html` | Página inicial da confeitaria |
| `loja.html` | Catálogo completo de produtos |
| `produto.html` | Detalhes e seleção de tamanho |
| `sobre.html` | Página institucional |
| `scripts/data.json` | Produtos, descrições, preços e imagens |
| `scripts/script.js` | Carregamento e montagem do catálogo |
| `scripts/product.js` | Busca do produto e cálculo por tamanho |
| `styles/` | Estilos separados por página e componente |
| `assets/` | Fotos, ícones e elementos gráficos |

## Estado atual

Este é um projeto de front-end para apresentação de cardápio. Ele não possui backend, autenticação, estoque persistente ou processamento de pedidos e pagamentos. Algumas imagens do catálogo usam endereços externos e podem deixar de carregar caso a origem altere ou remova os arquivos.

## Autor

Repositório mantido por [Pedro Bertanhi](https://github.com/pedrobertanhi).
