## 📖 Blog 

Este projeto foi feito no curso "Desenvolvedor Back-end Python" da EBAC. Um blog simples, mas funcional em Django. 

Dentre as funcionalidades pode-se criar posts, e comenta-los. Os comentários são permitidos ou não pelo administrador, para evitar conteúdos inapropriados. 

![Captura de tela de 2022-07-26 15-25-09](https://user-images.githubusercontent.com/78339857/181085782-9e67c58c-946f-4e04-b7b9-c4d02840d437.png)
![Captura de tela de 2022-07-26 15-25-42](https://user-images.githubusercontent.com/78339857/181086249-e87ddded-9179-45b7-aad5-ba03fbeae5bd.png)

### 🔨 Como executar:

* Clone o repositório e vá para a sua pasta:
```
$ git clone https://github.com/RakelMacedo/blog-ebac.git

$ cd blog-ebac/
```
<br>

* Agora, vamos criar o nosso ambiente virtual e ativa-lo:
```bash
$ python3 -m venv venv

$ source venv/bin/activate
```

<br>

* Em seguida, vamos baixar nossas bibliotecas com:
```bash
$ pip install -r requirements.txt
```

<br>

* Vamos criar a estrutura no banco de dados:
``` 
python manage.py migrate
``` 

<br>

* Vamos criar um super usuario para poder controlar o coteúdo do Blog através do Django Admin:
```bash
$ python3 manage.py createsuperuser
```
Preencha as informações com seus dados e não se esqueça do seu *usuário* e *senha*. 

<br>

* Agora vamos iniciar nosso servidor:
```bash
$ python3 manage.py runserver
```
<br>

Acesse http://127.0.0.1:8000/home/ para ir para a página principal do nosso Blog. 

Acesse http://127.0.0.1:8000/admin/ para ir para a interface de administrador do Django, utilize seu usuário e senha para entrar.

<br>

### ✅ Prontinho! Você esta pronto para utilizar nosso Blog. Faça bom uso e fique avontade =)
