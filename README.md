[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

[contributors-shield]: https://img.shields.io/github/contributors/J-o-n-a-s/LinkedInAutomacaoConvites.svg?style=for-the-badge
[contributors-url]: https://github.com/J-o-n-a-s/LinkedInAutomacaoConvites/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/J-o-n-a-s/LinkedInAutomacaoConvites.svg?style=for-the-badge
[forks-url]: https://github.com/J-o-n-a-s/LinkedInAutomacaoConvites/network/members
[stars-shield]: https://img.shields.io/github/stars/J-o-n-a-s/LinkedInAutomacaoConvites.svg?style=for-the-badge
[stars-url]: https://github.com/J-o-n-a-s/LinkedInAutomacaoConvites/stargazers
[issues-shield]: https://img.shields.io/github/issues/J-o-n-a-s/LinkedInAutomacaoConvites.svg?style=for-the-badge
[issues-url]: https://github.com/J-o-n-a-s/LinkedInAutomacaoConvites/issues
[license-shield]: https://img.shields.io/github/license/J-o-n-a-s/LinkedInAutomacaoConvites.svg?style=for-the-badge
[license-url]: https://github.com/J-o-n-a-s/LinkedInAutomacaoConvites/blob/master/LICENSE

**SEJA BEM-VINDO A ESTE REPOSITÓRIO!!!**

-------------

**Instruções**

 - *Fork* este repositório;
 - Clone seu repositório *forked*;
 - Adicione seus scripts;
 - *Commit & Push*;
 - Crie um *pull request*;
 - Dê uma estrela para este repositório;
 - Aguarde que o seu *pull request* solicitado vire um *merge*;
 - Comemore, seu primeiro passo para o mundo de código aberto e continue contribuindo.

## Introdução

A ideia desse aplicativo é  que ele seja super simples e intuitivo de utilizar.

## Descrição do projeto

Solicitar, de forma automatizada, convite de usuários do LinkedIn de acordo com a palavra chave de pesquisa digitada na aplicação.

O campo 3 é a palavra chave de pesquisa, por exemplo se você inserir RH, vai ser procurado pessoas que possuem o cargo de RH para fazer conexões.

**Observações:**

 - O arquivo executavel serve para quem apenas quiser usar sem se preocupar em programar. Caso seja este seu interesse, todos os demais arquivos podem ser excluídos para não ficar ocupando espaço do seu computador em vão ;)
 - O arquivo setup.py é apenas para gerar o arquivo executavel, o ignore ;)

### Bibliotecas e recursos utilizados

 - Time -> Para adição de tempo e registro do início, fim e duração do processo;
 - Tkinter -> Para utilização da caixa de diálogo de seleção de diretório para exportação de arquivo;
 - Random -> Para geração de valores randomicos.
 - Selenium -> Framework portátil para testar aplicativos web.
 - cx_Freeze -> Para criação de arquivo executável;
 - PySimpleGUI -> Interface gráfica;
 - validate_email -> Para validação do e-mail inserido.

### Funcionamento do programa

1. Insira o login do seu LinkedIn;
2. Insira sua senha;
3. A palavra chave para pesquisa.

## Instalação e execução do projeto

 - `pip install poetry` para instalar o gerenciador de pacotes;
 - `poetry install` para que o poetry instale os pacotes usados no projeto;
 - `poetry shell` para que o poetry crie um ambiente virtual;
 - `python src/app.py` para executar o projeto.

## Licença

MIT License
