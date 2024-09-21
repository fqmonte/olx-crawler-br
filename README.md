
# OLX Crawler.br

OLX Crawler.br é um projeto de web scraping desenvolvido com Node.js e Puppeteer para extrair informações de anúncios no site OLX. O crawler captura dados como preço, descrição e imagens dos anúncios de produtos, proporcionando uma maneira automatizada de obter informações diretamente da plataforma OLX.

## Funcionalidades

- **Coleta de Preço**: O crawler extrai o preço dos produtos listados no OLX.
- **Descrição do Produto**: Captura a descrição detalhada de cada anúncio.
- **Imagens**: Faz o download ou captura as URLs das imagens associadas aos anúncios.
- **Automatização**: Usa o Puppeteer para automatizar a navegação e extração de dados de forma confiável.
- **Personalização**: É possível ajustar as URLs e categorias a serem rastreadas para adequar a coleta de dados aos seus requisitos.

## Tecnologias Utilizadas

- **Node.js**: Plataforma para executar o JavaScript no servidor.
- **Puppeteer**: Biblioteca de automação para controle de navegadores, usada para acessar e extrair dados do site OLX.
- **JavaScript**: Linguagem principal para o desenvolvimento do projeto.

## Pré-requisitos

- **Node.js** (v12 ou superior)
- **npm** ou **yarn** para gerenciar pacotes

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/olx-crawler-br.git
   ```

2. Navegue até a pasta do projeto:

   ```bash
   cd olx-crawler-br
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

   ou, se estiver usando o Yarn:

   ```bash
   yarn install
   ```

## Uso

1. Para iniciar o crawler, execute o seguinte comando:

   ```bash
   node index.js
   ```

2. Certifique-se de personalizar a URL de acordo com os produtos que deseja rastrear.

3. Os dados coletados, como preço, descrição e URLs das imagens, serão exibidos no console ou salvos em um arquivo, dependendo da configuração.

## Configuração

- A URL da página de busca do OLX pode ser configurada diretamente no código.
- Também é possível ajustar o intervalo entre as requisições e a profundidade da coleta, modificando as configurações no script principal.

## Contribuições

Sinta-se à vontade para enviar pull requests ou abrir issues para sugerir melhorias e correções.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
