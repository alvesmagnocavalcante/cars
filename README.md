Gerenciamento de Carros - Django Web App

Este é um projeto Django que permite o gerenciamento de carros, incluindo operações como visualizar a lista de carros, adicionar um novo carro, visualizar detalhes de um carro, 
atualizar informações de um carro e excluir um carro.

Funcionalidades Principais:

1. Listagem de Carros:
   - Visualiza a lista de todos os carros cadastrados.
   - Permite filtrar os carros por modelo através de uma barra de pesquisa.

2. Detalhes do Carro:
   - Visualiza detalhes específicos de um carro, incluindo informações como modelo, ano, cor, etc.

3. Adição de Novo Carro:
   - Permite adicionar um novo carro ao sistema através de um formulário.

4. Atualização de Carro:
   - Permite atualizar as informações de um carro existente através de um formulário de edição.

5. Exclusão de Carro:
   - Permite excluir um carro existente do sistema.

Classes de Visualização (Views):

1. CarsListView:
   - Classe de visualização que lista todos os carros cadastrados.
   - Implementa uma funcionalidade de filtro por modelo de carro.

2. CarDetailView:
   - Classe de visualização que mostra os detalhes de um carro específico.

3. NewCarCreateView:
   - Classe de visualização para criar um novo carro.
   - Requer autenticação de usuário.

4. CarUpdateView:
   - Classe de visualização para atualizar informações de um carro existente.
   - Requer autenticação de usuário.

5. CarDeleteView:
   - Classe de visualização para excluir um carro existente.
   - Requer autenticação de usuário.

Requisitos e Dependências:

- Python 3.x
- Django

Como Executar o Projeto:

1. Clone o repositório para sua máquina local.
2. Instale as dependências utilizando o pip:
   ```
   pip install -r requirements.txt
   ```
3. Execute as migrações do banco de dados:
   ```
   python manage.py migrate
   ```
4. Inicie o servidor de desenvolvimento:
   ```
   python manage.py runserver
   ```
5. Acesse a aplicação através do navegador web em http://localhost:8000/cars/.
