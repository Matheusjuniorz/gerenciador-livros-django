# 📚 Gerenciador de Livros com Django

Um sistema completo de gerenciamento de livros feito com Django.  
Permite cadastrar, listar, visualizar e fazer upload de capas de livros, com interface amigável e painel administrativo poderoso.

![Capa](https://via.placeholder.com/800x300?text=Gerenciador+de+Livros+Django)

---

## 🚀 Funcionalidades

- ✅ Cadastro de livros com título, autor, ano, editora e imagem da capa  
- ✅ Listagem pública com Bootstrap  
- ✅ Página de detalhes do livro  
- ✅ Upload e exibição de imagem  
- ✅ Painel administrativo completo com filtros, busca e ordenação  
- ✅ Sistema modular com Django (views, forms, models, admin)  
- ✅ Personalização do Django Admin  
- ✅ Organização com boas práticas de código

---

## 🛠 Tecnologias utilizadas

| Tecnologia      | Descrição                          |
|-----------------|------------------------------------|
| 🐍 Python        | Linguagem de programação           |
| 🌐 Django        | Framework web principal            |
| 🎨 Bootstrap     | Estilo responsivo nos templates    |
| 🖼 Pillow        | Manipulação de imagens (ImageField)|
| 📂 HTML / CSS    | Estrutura e estilo das páginas     |

---

## 📁 Estrutura do projeto

```
meuprojeto/
├── livros/
│   ├── migrations/
│   ├── templates/
│   │   └── livros/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── media/                 # Uploads de capas
├── meuprojeto/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
└── manage.py
```

---

## ⚙️ Como rodar o projeto localmente

1. **Clone o repositório:**

```bash
git clone https://github.com/Matheusjuniorz/gerenciador-livros-django.git
cd gerenciador-livros-django
```

2. **Crie e ative o ambiente virtual:**

```bash
python -m venv venv
venv\Scripts\activate  # no Windows
# ou
source venv/bin/activate  # no Linux/Mac
```

3. **Instale as dependências:**

```bash
pip install -r requirements.txt
```

> Se não tiver o `requirements.txt`, use:
```bash
pip install django pillow
```

4. **Execute as migrações e crie o banco:**

```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Crie um superusuário (admin):**

```bash
python manage.py createsuperuser
```

6. **Rode o servidor local:**

```bash
python manage.py runserver
```

7. Acesse:
- 📘 App: `http://127.0.0.1:8000/livros/`
- 🔐 Admin: `http://127.0.0.1:8000/admin/`

---

## 👨‍💻 Autor

**Matheus Junior Batista de Lara Pinho**  
📍 Cuiabá - MT  
📧 batistam032@gmail.com  
🎓 Engenharia de Software - Faculdade Anhanguera

---

## 📄 Licença

Este projeto está sob a licença MIT.  
Sinta-se à vontade para usar, modificar e compartilhar!

---

## 💡 Contribuição

Pull requests e sugestões são bem-vindos!  
Vamos evoluir esse projeto juntos. 😄

---


