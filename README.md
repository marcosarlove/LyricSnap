
```markdown
# 🎵 LyricSnap - Song Lyrics Finder

![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

LyricSnap is a command-line tool that searches for song lyrics and translations from Letras.mus.br, displaying them in a beautifully formatted way or saving to a file.

## ✨ Features

- 🔍 Google-powered lyrics search
- 🎨 Beautiful terminal output with `rich` library
- 💾 Option to save lyrics to text files
- 🌍 Supports translations (when available)
- 🐍 Simple Python implementation

## 📦 Installation

### Prerequisites
- Python 3.8+
- pip package manager

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Make executable:
```bash
chmod +x lyricsnap.py
```

## 🚀 Usage

### Interactive mode (displays in terminal):
```bash
./lyricsnap.py
```

### Save to file mode:
```bash
./lyricsnap.py -f
```

## 📷 Screenshot

![LyricSnap in action](https://i.imgur.com/EXAMPLE.png) *(example screenshot)*

## 🛠️ Code Structure

| Function | Description |
|----------|-------------|
| `show_banner()` | Displays styled banners in terminal |
| `google_search()` | Performs Google search for lyrics |
| `find_lyrics()` | Extracts lyrics and translations |
| `format_lyrics()` | Cleans and formats lyrics text |

## ⚠️ Common Issues

1. **No results found**:
   - Check your internet connection
   - Verify song title and artist spelling

2. **Module errors**:
   ```bash
   pip install --upgrade -r requirements.txt
   ```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

Author: Marcos Arlove
Project Link: [https://github.com/marcosarlove/lyricsnap](https://github.com/marcosarlove/lyricsnap)









```markdown
# 🎵 LyricSnap - Buscador de Letras de Música

![Versão Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Licença](https://img.shields.io/badge/license-MIT-green.svg)

O LyricSnap é uma ferramenta de linha de comando que busca letras de música e traduções no Letras.mus.br, exibindo-as de forma bonita no terminal ou salvando em arquivo.

## ✨ Funcionalidades

- 🔍 Busca de letras usando o Google
- 🎨 Exibição estilizada no terminal com a biblioteca `rich`
- 💾 Opção para salvar letras em arquivos de texto
- 🌍 Suporte a traduções (quando disponíveis)
- 🐍 Implementação simples em Python

## 📦 Instalação

### Pré-requisitos
- Python 3.8+
- Gerenciador de pacotes pip

### Instale as dependências:
```bash
pip install -r requirements.txt
```

### Torne o script executável:
```bash
chmod +x lyricsnap.py
```

## 🚀 Como Usar

### Modo interativo (exibe no terminal):
```bash
./lyricsnap.py
```

### Modo para salvar em arquivo:
```bash
./lyricsnap.py -f
```

## 📷 Captura de Tela

![LyricSnap em ação](https://i.imgur.com/EXAMPLE.png) *(exemplo de screenshot)*

## 🛠️ Estrutura do Código

| Função | Descrição |
|--------|-----------|
| `show_banner()` | Exibe banners estilizados no terminal |
| `google_search()` | Realiza buscas no Google por letras |
| `find_lyrics()` | Extrai letras e traduções |
| `format_lyrics()` | Limpa e formata o texto das letras |

## ⚠️ Problemas Comuns

1. **Nenhum resultado encontrado**:
   - Verifique sua conexão com a internet
   - Confira a grafia do título e artista

2. **Erros de módulos**:
   ```bash
   pip install --upgrade -r requirements.txt
   ```

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/FeatureIncrivel`)
3. Commit suas mudanças (`git commit -m 'Adiciona alguma feature incrível'`)
4. Push para a branch (`git push origin feature/FeatureIncrivel`)
5. Abra um Pull Request

## 📜 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## 📧 Contato

Autor: Marcos Arlove  
Link do Projeto: [https://github.com/marcosarlove/lyricsnap](https://github.com/marcosarlove/lyricsnap)
```
