# Projeto C.R.U.D.: Flask + BootStrap

> Este é um projeto simples de um gerenciador de disciplinas, eventos e aulas desenvolvido com Flask + BootStrap. O aplicativo permite criar, editar, listar e excluir. Armazenando os dados em arquivos JSON.


## :bricks: Estrutura do Projeto

```plaintext
project/
│
├── templates/
│   ├── modelo.html
│   ├── index.html
│   ├── disciplinas.html
│   ├── disciplinas-add.html
│   ├── disciplinas-edit.html
│   ├── eventos.html
│   ├── eventos-add.html
│   └── eventos-edit.html
│
├── static/
│   ├── css/
│   │   ├── styles.css
│   │   └── bootstrap.min.css
│   │
│   ├── img/
│   │   └── form-icon.png
│   │
│   └── js/
│       └── bootstrap.min.js
├── app.py
├── disciplinas.json
└── aulas-eventos.json
```


## :triangular_flag_on_post: Requisitos da Build

- Python 3.12.3
- Flask
- BootStrap


## :technologist: Instalação

1. Clone (Bash)
```plaintext
  git clone https://github.com/seu-usuario/gerenciador-eventos.git
  cd gerenciador-eventos
```
2. Ambiente Virtual
```plaintext
python -m venv venv
venv\Scripts\activate
source venv/bin/activate
```
3. Flask
```plaintext
pip install Flask
```
4. BootStrap
> [!WARNING]
> Os arquivos do B.S. utilizados já estão inclusos nos arquivos do projeto.


## :running_man: Como Iniciar

1. Bash (Dentro do diretório do projeto)
```plaintext
python app.py
```
2. Abra a URL no navegador
```plaintext
http://127.0.0.1:5000/eventos
```


## :wrench: Funcionalidades

- Criar
- Visualizar
- Editar
- Apagar


## :books: Estrutura dos dados

- Disciplinas
```plaintext
{
    "Disciplinas": [
        {
            "nome": "nome",
            "descricao": "Breve Descrição",
            "carga": "Quantidade de horas"
        }
    ]
}
```
- Aulas/Eventos
```plaintext
{
    "eventos": [
        {
            "data": "dd/mm/aaaa",
            "descricao": "Breve Descrição",
            "tipo": "evento / aula"
        }
    ]
}
```


## :octocat: Desenvolvedores/Contribuintes

|  [Feliphe Blatt](https://github.com/Feliphe-Blatt) | [Cristiane Nunes](https://github.com/cristiane-nunes-git)
| :---: | :---: 
