Frutos de Goiás - Sistema de Gerenciamento
Este é um sistema de desktop desenvolvido em Java para gerenciar as operações da Frutos de Goiás. A aplicação utiliza a biblioteca Swing para a interface gráfica e o banco de dados PostgreSQL para o armazenamento persistente de dados.

🚀 Funcionalidades
Cadastro de Produtos: Registro completo de picolés, sorvetes e outros itens.

Controle de Estoque: Monitoramento de entradas e saídas de mercadorias.

Gestão de Vendas: Interface para registro de transações em tempo real.

Relatórios: Visualização de dados sobre vendas e inventário.

Conexão com Banco de Dados: Persistência robusta utilizando PostgreSQL.

🛠 Tecnologias Utilizadas
Linguagem: Java (JDK 17 ou superior)

Interface Gráfica: Java Swing

Banco de Dados: PostgreSQL

Gerenciamento de Dependências: Maven ou Gradle

Driver JDBC: PostgreSQL JDBC Driver

Flyway


vaeenma
📋 Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:

Java JDK 17+

PostgreSQL (versão 12 ou superior)

Uma IDE de sua preferência (IntelliJ IDEA, Eclipse ou NetBeans)

🔧 Configuração do Banco de Dados
Crie um banco de dados chamado frutos_de_goias.

Execute o script SQL (caso possua um arquivo .sql) ou crie as tabelas necessárias. Exemplo básico:

SQL
CREATE TABLE produtos (
    id SERIAL PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    preco DECIMAL(10, 2) NOT NULL,
    quantidade_estoque INTEGER NOT NULL
);
No código Java, certifique-se de configurar a classe de conexão (ConnectionFactory ou similar) com suas credenciais:

URL: jdbc:postgresql://localhost:5432/postgres

Usuário: seu_usuario

Senha: sua_senha

📦 Como Executar
Clone este repositório:

Bash
git clone https://github.com/seu-usuario/frutos-de-goias.git
Abra o projeto na sua IDE.

Importe as dependências do Maven.

Execute a classe principal (geralmente Main.java ou LoginView.java).

Desenvolvido por [Vinicius Leonel da Silva]
