<h1>☁️ Como configurar uma instância de Banco de Dados no Azure</h1>
🔹 <b>1. Acessar o Portal Azure</b>

- Acessar o site: https://portal.azure.com
- Fazer login com sua conta Microsoft/Azure

🔹 <b>2. Criar um recurso de Banco de Dados</b>
- No menu lateral, clicar em "Criar um recurso"
- Selecionar "Banco de Dados" → por exemplo, "SQL Database"

🔹 <b>3. Configurar as Informações Básicas</b>
- Assinatura e Grupo de Recursos (crie um novo se necessário)
- Nome do Banco de Dados
- Servidor SQL (pode criar um novo):
  - Nome do servidor
  - Login de administrador
  - Senha e localização (região geográfica)

🔹 <b>4. Escolher o Tipo de Camada/Desempenho</b>
- Escolher o modelo de compra:
  - DTU (Basic, Standard, Premium) ou
  - vCore (proporcional à CPU/memória)
- Definir tamanho, redundância, e escalabilidade

🔹 <b>5. Configurar Recursos Adicionais (Opcional)</b>
- Backup automatizado
- Alta disponibilidade
- Redundância geográfica
- Segurança (Azure Defender, criptografia etc.)

🔹 <b>6. Revisar e Criar</b>
- Clicar em "Revisar + criar"
- Verificar todas as configurações
- Clicar em "Criar"

🔹 <b>7. Conectar ao Banco de Dados</b>
- Após a implantação, ir até o recurso criado
- Configurar as regras de firewall para permitir conexões (por IP)
- Copiar a string de conexão para usar em aplicativos, SQL Server Management Studio (SSMS), Visual Studio ou Azure Data Studio
