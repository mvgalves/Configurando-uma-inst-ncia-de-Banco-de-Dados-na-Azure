# ☁️ Configuração de Banco de Dados na Microsoft Azure

Este repositório contém resumos, anotações e dicas práticas sobre o processo de criação e configuração de instâncias de banco de dados na plataforma Microsoft Azure. O conteúdo foi desenvolvido como parte do desafio prático da DIO.

---

## 🎯 Objetivo

Praticar o provisionamento e a configuração de um banco de dados na nuvem utilizando os serviços do Azure, aprendendo a gerenciar instâncias, autenticação, firewall e conexões externas de forma segura e eficiente.

---

## 🔧 Etapas Realizadas

1. **Criação da conta na Azure**  
   Registro inicial com uma conta Microsoft. A Azure oferece um crédito gratuito para novos usuários.

2. **Acesso ao portal Azure**  
   Navegação até o [portal.azure.com](https://portal.azure.com/), onde todos os recursos podem ser criados e gerenciados.

3. **Criação de uma instância de Banco de Dados**  
   Utilização da opção **"Banco de Dados SQL"** para criar uma nova instância com um servidor lógico associado.

4. **Configuração do Banco de Dados**
   - Definição do nome do banco e servidor
   - Escolha do modelo de compra (uso geral, básico, etc.)
   - Configuração de login e senha do administrador do servidor

5. **Configuração do Firewall e Rede**
   - Adição do IP local à lista de permissões
   - Habilitação de acesso de serviços do Azure se necessário

6. **Conexão ao Banco de Dados**
   - Utilização de ferramentas como Azure Data Studio ou SQL Server Management Studio (SSMS)
   - Teste de conexão com o host, usuário e senha definidos

7. **Gerenciamento e Monitoramento**
   - Acompanhamento de métricas de desempenho
   - Backup automático e restauração

---

## 🧠 Conceitos Importantes

- **Servidor Lógico do SQL Azure**  
  Container que hospeda uma ou mais bases de dados, com um ponto único de acesso via IP ou nome DNS.

- **Modelo de Compra (DTU vs vCore)**  
  Define o desempenho, escalabilidade e custo da instância.

- **Camadas de Serviço**  
  - Básica: ideal para testes e desenvolvimento
  - Standard: uso de produção com carga moderada
  - Premium: cargas intensas e missão crítica

- **Configuração de Firewall**  
  Garante que somente IPs autorizados consigam acessar a instância.

- **Conexão Segura (SSL/TLS)**  
  Protege os dados em trânsito entre a aplicação e o banco de dados.

---

## 📝 Dicas Úteis

- Utilize **nomenclaturas padronizadas** para bancos e servidores
- Crie **grupos de recursos** para organizar seus recursos
- Faça **testes de conexão** antes de começar a usar o banco em produção
- **Encerre ou exclua recursos** após o uso para evitar cobranças
- Utilize o **Azure Data Studio** para consultas rápidas e gerenciamento

---

## 📚 Fontes e Referências

- [Portal da Microsoft Azure](https://portal.azure.com/)
- [Documentação Oficial do Azure SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/)
- Curso da [DIO - Digital Innovation One](https://web.dio.me/)

---

## 🚀 Autor

Desenvolvido por Marcus Vinicius
