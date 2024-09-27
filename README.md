LyricSnap

LyricSnap is a program that searches for song lyrics on th internet and displays or saves them along with translations (if available). The program uses Google search to find the lyrics on the Letras.mus.br website and displays the results in a stylized format in the terminal using the `rich` library.

Features

- Searches for song lyrics through Google.
- Displays the lyrics and translation (if available) in the terminal.
- Option to save the lyrics and translation in a text file.
- Stylized interface with borders and colors.

Requirements

LyricSnap was developed to run on Python 3 and depends on the following libraries:

- requests — To make HTTP requests.
- beautifulsoup4 — To process HTML and extract information.
- rich — To stylize the terminal output.

 Installing Dependencies

Run the following command to install the required dependencies:

```bash
pip install requests beautifulsoup4 rich

How to Use

Running the Script

1. Execution Permissions: First, make sure the script has execution permissions:

chmod +x ./lyricsnap

2. Interactive Mode: To run the program and display the lyrics and translations directly in the terminal:

./lyricsnap

The program will ask you to enter the song title and the artist name.

3. Save Lyrics and Translation to File: To save the lyrics and translation to a text file in the lyrics folder:

./lyricsnap -f

Execution Example

$ ./lyricsnap
Enter the song title: Imagine
Enter the singer's name: John Lennon

This will display the lyrics of the song "Imagine" by John Lennon directly in the terminal.

 Example of Saving

$ ./lyricsnap -f
Enter the song title: Imagine
Enter the singer's name: John Lennon
Done...
Lyrics saved in lyrics/Imagine_John_Lennon.txt

The lyrics will be saved in the file lyrics/Imagine_John_Lennon.txt with the translation (if available).

Code Structure

showBanner(title, content): Displays a stylized panel with title and content in the terminal.

getWebPage(url): Makes a request to the URL and returns the HTML content.

googleSearch(keywords): Performs a search on Google and returns the first valid result.

findLetrasURL(baseURL, soup): Filters the Google results to find a valid link on the letras.mus.br website.

findLyrics(url): Extracts the lyrics and translation from the Letras page.

getMusicData(page): Extracts the title and artist name from the song page.

 formatLyrics(lyric): Formats the lyrics and translation, removing unnecessary HTML tags.

main(mode): Controls the flow of the program, allowing display in the terminal or saving to a file.

Possible Errors

"Some error occurred...": This can occur if the internet connection fails or if Google does not return relevant results.

"The search did not generate any results": Check if you spelled the artist name and song title correctly.

Contributing

Feel free to contribute improvements, bug fixes or new features. To contribute:

1. Fork the repository.

2. Create a branch with your feature/fix: git checkout -b my-feature.

3. Commit your changes: git commit -m 'My new feature'.

4. Push your branch: git push origin my-feature.

5. Open a Pull Request.

 License

This project is licensed under the MIT License - see the LICENSE file for more details.

Summary of Contents:
- Title and Introduction: Describes what LyricSnap does.
- Features: Explains what the program offers.
- Requirements and Installation: Information on how to set up the environment.
- Usage: Detailed instructions for running the program.
- Code Structure: Explanation of the main components.
- Possible Errors: Examples of errors and how to deal with them.
- Contribution and License: Information on how to contribute and the project license.













LyricSnap

LyricSnap é um programa que busca letras de músicas na internet e as exibe ou salva junto com as traduções (se disponíveis). O programa utiliza a pesquisa no Google para encontrar a letra da música no site Letras.mus.br e exibe os resultados de forma estilizada no terminal usando a biblioteca `rich`.

Funcionalidades

- Busca letras de músicas através do Google.
- Exibe a letra e a tradução (se disponível) no terminal.
- Opção de salvar a letra e a tradução em um arquivo de texto.
- Interface estilizada com bordas e cores.

Requisitos

O LyricSnap foi desenvolvido para ser executado em Python 3 e depende das seguintes bibliotecas:

- requests — Para realizar requisições HTTP.
- beautifulsoup4 — Para processar HTML e extrair informações.
- rich — Para estilizar a saída do terminal.

Instalação das Dependências

Execute o seguinte comando para instalar as dependências necessárias:

```bash
pip install requests beautifulsoup4 rich

Como Usar

Executando o Script

1. Permissões de Execução: Primeiro, certifique-se de que o script tem permissões de execução:

chmod +x ./lyricsnap


2. Modo Interativo: Para executar o programa e exibir as letras e traduções diretamente no terminal:

./lyricsnap

O programa pedirá que você insira o título da música e o nome do artista.


3. Salvar Letra e Tradução em Arquivo: Para salvar a letra e a tradução em um arquivo de texto na pasta lyrics:

./lyricsnap -f



Exemplo de Execução

$ ./lyricsnap
Enter the song title: Imagine
Enter the singer's name: John Lennon

Isso exibirá a letra da música "Imagine" de John Lennon diretamente no terminal.

Exemplo de Salvamento

$ ./lyricsnap -f
Enter the song title: Imagine
Enter the singer's name: John Lennon
Done...
Lyrics saved in lyrics/Imagine_John_Lennon.txt

A letra será salva no arquivo lyrics/Imagine_John_Lennon.txt com a tradução (se disponível).

Estrutura do Código

showBanner(title, content): Exibe um painel estilizado com título e conteúdo no terminal.

getWebPage(url): Faz uma requisição à URL e retorna o conteúdo HTML.

googleSearch(keywords): Realiza uma busca no Google e retorna o primeiro resultado válido.

findLetrasURL(baseURL, soup): Filtra os resultados do Google para encontrar um link válido no site letras.mus.br.

findLyrics(url): Extrai a letra e a tradução da página do Letras.

getMusicData(page): Extrai o título e o nome do artista da página da música.

formatLyrics(lyric): Formata a letra e a tradução, removendo tags HTML desnecessárias.

main(mode): Controla o fluxo do programa, permitindo a exibição no terminal ou o salvamento em arquivo.


Possíveis Erros

"Some error occurred...": Isso pode ocorrer se a conexão com a internet falhar ou se o Google não retornar resultados relevantes.

"The search did not generate any results": Verifique se você escreveu corretamente o nome do artista e o título da música.


Contribuindo

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Para contribuir:

1. Faça um fork do repositório.


2. Crie um branch com sua feature/correção: git checkout -b minha-feature.


3. Faça commit de suas alterações: git commit -m 'Minha nova feature'.


4. Envie seu branch: git push origin minha-feature.


5. Abra um Pull Request.



Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo LICENSE para obter mais detalhes.

Resumo do Conteúdo:
- Título e Introdução: Descreve o que o LyricSnap faz.
- Funcionalidades: Explica o que o programa oferece.
- Requisitos e Instalação: Informações sobre como configurar o ambiente.
- Uso: Instruções detalhadas para executar o programa.
- Estrutura do Código: Explicação dos principais componentes.
- Possíveis Erros: Exemplos de erros e como lidar com eles.
- Contribuição e Licença: Informações sobre como contribuir e licença do projeto.
