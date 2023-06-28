# Devops

# Azure Questions

1. Quais são os principais serviços de nuvem oferecidos pela Microsoft Azure?
2. Explique o que é uma conta de armazenamento do Azure e mencione os tipos disponíveis.
3. Como você pode implantar um aplicativo em uma Máquina Virtual (VM) do Azure?
4. Qual é a diferença entre Azure Functions e Azure Logic Apps?
5. Descreva o processo de configuração de alta disponibilidade para um aplicativo na Azure.
6. Quais são as etapas envolvidas na implantação de um aplicativo usando Azure DevOps?
7. Como você pode garantir a segurança dos recursos na Azure Cloud?
8. O que é o Azure DevTest Labs e como ele pode ser usado?
9. Mencione algumas práticas recomendadas para o gerenciamento de custos na Azure Cloud.
10. Explique o que é o Azure Kubernetes Service (AKS) e como ele é usado para orquestração de contêineres.

# Casos de teste que você pode considerar para o cenário proposto:

## Caso de teste 1:
1. Provisionar uma Máquina Virtual (VM) do Azure com o sistema operacional desejado.
2. Instalar o ambiente Node.js na VM.
3. Configurar e iniciar o serviço MySQL na VM.
4. Transferir os arquivos do aplicativo Node.js para a VM.
5. Instalar as dependências do aplicativo usando o npm (gerenciador de pacotes do Node.js).
6. Configurar as variáveis de ambiente necessárias para o aplicativo, como credenciais de banco de dados.
7. Executar o aplicativo Node.js na VM, garantindo que ele esteja acessível localmente.

## Caso de teste 2:
1. Configurar um grupo de segurança de rede (Network Security Group) no Azure para permitir o tráfego na porta 80.
2. Configurar as regras de entrada e saída no grupo de segurança de rede para permitir a comunicação entre a VM e o mundo externo.
3. Atribuir um endereço IP público à VM para que ela seja acessível publicamente.
4. Configurar a regra de redirecionamento de porta (port forwarding) na VM para direcionar as solicitações na porta 80 para o aplicativo Node.js em execução.

## Caso de teste 3:
1. Provisionar um serviço de banco de dados MySQL no Azure, como o Azure Database for MySQL.
2. Configurar as credenciais de acesso ao banco de dados e permitir o acesso à VM onde o aplicativo Node.js está sendo executado.
3. Configurar as variáveis de ambiente no aplicativo Node.js para usar as informações de conexão corretas com o banco de dados MySQL.
4. Testar a conexão entre o aplicativo Node.js e o banco de dados, garantindo que o aplicativo consiga ler e gravar dados corretamente.

# Casos de teste que você pode considerar para a implementação de Azure Functions:

## Caso de teste 1:
1. Crie uma nova Azure Function com um gatilho HTTP.
2. Implemente a lógica necessária para receber solicitações HTTP e retornar uma resposta adequada.
3. Teste a função chamando sua URL de gatilho HTTP e verifique se a resposta está correta.
4. Verifique se a função está sendo dimensionada automaticamente com base na carga de solicitações recebidas.

## Caso de teste 2:
1. Crie uma Azure Function com um gatilho de armazenamento de blob.
2. Implemente a lógica necessária para processar automaticamente um novo blob quando ele for adicionado ao armazenamento.
3. Carregue um novo blob no armazenamento e verifique se a função é acionada e executa a lógica correta.
4. Verifique se a função é capaz de lidar com o processamento em lote de múltiplos blobs simultaneamente.

## Caso de teste 3:
1. Crie uma Azure Function com um gatilho de tempo (timer trigger).
2. Implemente a lógica necessária para executar determinadas tarefas em intervalos regulares.
3. Verifique se a função é acionada corretamente de acordo com o cronograma definido.
4. Verifique se a função executa as tarefas esperadas e se lida corretamente com quaisquer erros ou exceções.

## Caso de teste 4:
1. Crie uma Azure Function com um gatilho de fila.
2. Implemente a lógica necessária para processar mensagens em uma fila de mensagens.
3. Coloque mensagens na fila e verifique se a função é acionada para processá-las.
4. Verifique se a função é capaz de lidar com diferentes tipos de mensagens e executa a lógica correta para cada uma delas.

