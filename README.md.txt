# Gerenciador de Livros com Django

Um sistema web simples para gerenciar informações sobre livros, incluindo funcionalidades de cadastro, listagem e visualização de detalhes. Desenvolvido com Django, este projeto serve como um exemplo prático de uma aplicação web básica utilizando o framework.

---

## Funcionalidades ✨

* Cadastro de Livros: Adicione novos livros ao sistema com título, autor, ano de publicação, editora e capa.
* Listagem de Livros: Visualize todos os livros cadastrados em uma lista organizada.
* Detalhes do Livro: Acesse uma página dedicada para ver informações mais detalhadas de cada livro.
* Painel Administrativo Customizado: Gerencie os livros e outras informações do banco de dados através do painel de administração do Django, com personalizações na exibição da lista de livros.

---

## Tecnologias Utilizadas 🚀

* Python 3.x
* Django 5.x
* SQLite3 (Banco de dados padrão do Django para desenvolvimento)
* HTML5
* CSS3 (Estilização básica)

---

## Como Rodar o Projeto (Passo a Passo) ⚙️

Siga estas instruções para configurar e executar o projeto em sua máquina local.

### Pré-requisitos

Certifique-se de ter o Python 3.x e o `pip` (gerenciador de pacotes do Python) instalados.

### 1. Clonar o Repositório

```bash
git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
cd SEU_REPOSITORIO # ou cd meuprojeto se você já renomeou a pasta

2. Criar e Ativar o Ambiente Virtual (Recomendado)

python -m venv venv
# No Windows:
.\venv\Scripts\activate
# No macOS/Linux:
source venv/bin/activate

3. Instalar as Dependências

pip install -r requirements.txt

4. Configurar o Banco de Dados

Aplique as migrações para criar as tabelas no banco de dados:

python manage.py makemigrations
python manage.py migrate

5. Criar um Superusuário (para acessar o Admin)

python manage.py createsuperuser

Siga as instruções no terminal para criar seu usuário e senha de administrador.

6. Iniciar o Servidor de Desenvolvimento

python manage.py runserver

7. Acessar a Aplicação
Abra seu navegador e acesse:

Painel Administrativo: http://127.0.0.1:8000/admin/ (Faça login com o superusuário criado)

Listagem de Livros: http://127.0.0.1:8000/livros/lista/

Cadastro de Livros: http://127.0.0.1:8000/livros/cadastrar/

ontribuição 🤝
Contribuições são bem-vindas! Se você tiver sugestões ou quiser melhorar o projeto, sinta-se à vontade para:

Fazer um Fork do repositório.

Criar uma nova branch (git checkout -b feature/minha-feature).

Fazer suas alterações e commitar (git commit -m 'Adiciona nova feature X').

Fazer Push para a branch (git push origin feature/minha-feature).

Abrir um Pull Request.

Licença) 📄
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato 📧
Se tiver alguma dúvida ou sugestão, entre em contato:

Nome: Matheus

Email: batistam032@gmail.gmail@com 

Seu LinkedIn : https://www.linkedin.com/in/matheus-junior-z/