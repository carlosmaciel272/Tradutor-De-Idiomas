# Descrição
- Um script escrito em python, baseado em TUI, que traduz textos em diferentes idiomas.
- O projeto utiliza uma biblioteca padrão do python, que consome APIs como DeepL, BingTranslated para realizar a tradução.  

# Requisitos
## Ambiente Virtual
Antes de tudo, caso o seu SO seja linux, instale um o pacote `python-virtualenv`. Isso serve para quando o python instalar as dependências do projeto, não instalar junto com as dependências do sistema operacional.
## Biblioteca translated
Depois instale a biblioteca `translated` usando o gerenciador de pacotes do Python `pip`
```bash
pip install translated
```
## Executando
1. Clone esse repositório (tenha o `git` instalado no seu computador) 
2. Entre na pasta do repositório clonado `cd Tradutor-De-Idiomas`
3. Depois execute o projeto:   
```bash
python language_translate.py --from_lang TRADUZIR DE --to_lang PARA   
```
3.1 Substitua `TRADUZIR DE` pela sigla do idioma do texto que você vai inserir, pode ser `pt-br`. E susbstitua `PARA` pelo idioma que o texto deve ser traduzido, por exemplo `en` para english

4. Dê enter e então vai aparecer um input para você inserir o texto, digite o texto que você quer que seja traduzido e depois espere a execução do script.
