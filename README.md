# Azure-Cognitive-Search-Utilizando-AI-Search-para-indexa-o-e-consulta-de-Dados
Realizar acesso no portal  Página inicial - Microsoft Azure
Crie um novo recurso: No painel esquerdo, clique em "Criar um recurso". Na barra de pesquisa, digite "Azure Cognitive Search". Selecione "Azure Cognitive Search" nos resultados.
 

 Configuração do serviço: Clique no botão "Criar". Preencha as informações necessárias, como nome do serviço, assinatura, grupo de recursos, localização, versão do serviço, etc.

 

Escolha o tipo de preço (Básico, Padrão ou Armazenamento Avançado). Configure a escala (níveis de capacidade e réplicas) com base nas necessidades do seu aplicativo



 

Em camada de preços clicar em alterar o tipo de preço e selecionar o plano básico 



 

 

 
•	Revisar e criar: Revise as configurações e clique em "Revisar + criar".
•	Criar o Azure AI Search: Depois de revisar, clique em "Criar" para provisionar o serviço.
•	Aguardar a implantação: Aguarde até que o serviço seja implantado com êxito. Você receberá uma notificação quando estiver pronto para uso. Usar o Azure AI Search:


Proxima etapa criar um recurso de IA 
https://portal.azure.com/#home
Criar um recurso>IA + Machine Learning> Azure AI services
 

Selecionar assinatura 
Preencher o campo grupo de recursos ( caso não  tenha criar um novo )
Em Detalhes da Instancia preencher os campos Região e definir um  nome 
No campo tipo de preço deixar em Standard S0
 
 
Clicar em examinar+criar depois em criar e aguarda a implantação 

 

Criação de conta de armazenamento 
Em Serviços do Azure  clicar em Storange Accounts ( Contas de Armazenamentos)  , selecionar a opção criar
 

 


 

Detalhes da instância
Nome da conta de armazenamento
 
O nome deve ser exclusivo entre todos os nomes de contas de armazenamento existentes no Azure. Ele deve ter de 3 a 24 caracteres e pode conter somente letras em caixa baixa e números.

Em performance deixar marcado a opção ( Standard
 

Em Redundância deixar em LRS ( armazenamento com redundância local )
  
Examinar + Criar > Criar em aguardar a implantação
 
 

Após a conta criada ir nas configurações 
 
E marcar a opção Transparência segura necessária para permitir acesso anomino ao blob em clicar em salvar na parte superior 
Proximo passo 
Nas categorias ir em Data Management ( Gerenciamentos de dados) > lifecycle management (gerenciamento de ciclo de vida) 

 

Em  Data Storage ( Gerenciamento de dados ) > Container
 

Em + Conteiner criar  o nome como coffeereviews e criar 
 

 
 

