# iDrugs-api

---
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

## Endpoints
<p>
    https://idrugsapi.herokuapp.com
    https://idrugsapi.herokuapp.com/idrugs-api/{info}
    {info} -> type - product - user
</p>

### Sobre esse Projeto
<p>
    Projeto em desenvolvimento com fins academicos
    <br/>
    Esse projeto é responsável por cadastrar, editar, excluir e listar tudo referente a farmácia, assim como remédios e seus funcionarios.
</p>

### Para rodar seu ambiente deve possuir:
1. Git Bash <br/>
https://gitforwindows.org/

2. Python: <br/>
https://www.python.org/ <br/>

3. IDE da sua escolha (Recomendo PyCharm) <br/>
https://www.jetbrains.com/pt-br/pycharm/


### Criando ambiente virtual - Opcional

- Com projeto já clonado, abra o terminal de sua preferência e execute:
```
python -m venv ./venv
```
- Ative seu ambiente virtual, de acordo com o seu Sistema Operacional: <br/>

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
```
.\venv\Scripts\activate
```
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ou ![Mac OS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
```
source venv/bin/activate
```

### Rodando projeto

<p>
    Caso tenha criado ou não seu ambiente virtual (RECOMENDO A CRIAÇÃO).
    Você poderá instalar as dependências depois rodar o projeto
</p>

```
pip install -r requirements.txt
python app.py
```
