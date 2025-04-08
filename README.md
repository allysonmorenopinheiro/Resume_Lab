# Resume_Lab
 Este repositório contém um breve resumo das lições aprendidas durante o desenvolvimento do lab na DIO
 -> Passo 1: Acessar o Portal do Azure

1. **Acesse a página do Azure:** Abra um navegador e vá para [portal.azure.com](https://portal.azure.com).
2. **Faça login:** Utilize suas credenciais da conta Azure.

Passo 2: Criar uma nova máquina virtual

1. **Clique em "Criar um recurso":** No canto superior esquerdo do portal, clique em "Criar um recurso".
2. **Selecione "Máquina Virtual":** Na seção "Compute", procure por "Máquina Virtual" e clique nele.

-> Passo 3: Configurar a máquina virtual

1. **Escolher a assinatura:** Se você possui mais de uma assinatura Azure, selecione a que deseja usar.
2. **Criar um novo grupo de recursos** ou selecionar um existente: Um grupo de recursos é um contêiner que mantém os recursos relacionados de uma solução do Azure.
3. **Definir o nome da máquina virtual:** Escolha um nome exclusivo para sua VM.
4. **Selecionar a região:** Escolha a região onde sua VM será hospedada. Isso pode afetar a latência e a performance.
5. **Escolher a imagem do sistema operacional:** Selecione a imagem do SO que deseja usar (por exemplo, Windows Server, Ubuntu, etc.).
6. **Escolher o tamanho da máquina:** Defina o tamanho da máquina virtual com base na quantidade de CPUs e memória que você precisa.

-> Passo 4: Configurar as credenciais

1. **Definir o nome de usuário e senha:** Forneça um nome de usuário e uma senha para acessar a máquina virtual.
2. **Configurações de autenticação:** Você também pode optar por usar uma chave SSH em vez de uma senha, se preferir.

-> Passo 5: Configurações adicionais

1. **Configurações de rede:** Configure a rede virtual e o grupo de segurança de rede. O Azure geralmente cria uma rede virtual padrão para você.
2. **Configurações de disco:** Escolha o tipo de disco (SSD, HDD) e o tamanho do disco.
3. **Outras configurações:** Você pode configurar opções como monitoramento, backups, e integrar com outros serviços do Azure.

-> Passo 6: Revisar e criar

1. **Revisar as configurações:** Verifique todas as informações que você inseriu.
2. **Clique em "Criar":** Se tudo estiver correto, clique no botão "Criar". O Azure começará a implantar sua máquina virtual.

-> Passo 7: Conectar-se à máquina virtual

1. **Após a criação, acesse a máquina virtual:** Vá até o painel de controle da sua máquina virtual no portal do Azure.
2. **Clique em "Conectar":** Você terá a opção de conectar via RDP (para Windows) ou SSH (para Linux). Siga as instruções para se conectar.

-> Considerações finais 

- Certifique-se de entender os custos associados ao uso de machine learning, pois eles podem variar com base na configuração e uso.
- Consulte a documentação da Azure para configurações mais avançadas e melhores práticas.
