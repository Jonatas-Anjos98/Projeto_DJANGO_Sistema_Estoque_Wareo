# Projeto Wareo

## Descrição
Wareo é um sistema simples e eficiente para gestão de produtos, desenvolvido com Django Admin. Permite cadastrar, editar, excluir e controlar o estoque, preço e disponibilidade de produtos, facilitando a administração para pequenos negócios e freelancers. Desenvolvimento rápido e interface intuitiva.

## Funcionalidades
- Cadastro completo de produtos (nome, descrição, preço e estoque)
- Edição e atualização fácil dos dados dos produtos
- Exclusão segura dos produtos
- Visualização detalhada dos produtos cadastrados
- Controle e monitoramento do estoque em tempo real
- Busca e filtros para rápida localização de produtos
- Interface administrativa amigável usando Django Admin
- Validação básica de dados para garantir integridade
- Gerenciamento de usuários com permissões básicas
- Ordenação dos produtos por nome, preço e estoque
- (Opcional) Histórico de alterações de produtos
- (Opcional) Exportação de dados para análise externa

## Tecnologias Utilizadas
- Python
- Django Framework
- Django Admin (interface de administração pronta)
- Banco de dados SQLite (padrão) ou outro configurável

## Como Usar
1. Clone o repositório
2. Crie um ambiente virtual Python
3. Instale as dependências: `pip install -r requirements.txt`
4. Rode as migrações: `python manage.py migrate`
5. Crie um superusuário: `python manage.py createsuperuser`
6. Inicie o servidor: `python manage.py runserver`
7. Acesse a interface administrativa em `http://localhost:8000/admin` e comece a gerenciar seus produtos

## Contribuição
Contribuições são bem-vindas! Para colaborar, faça um fork do projeto, crie sua branch com a funcionalidade desejada e envie um pull request.

## Licença
Projeto open source para fins educativos e comerciais.


