# Projet-azure-vm
Documentando a criação de uma VM na Azure

Acessar o Portal: Faça login em portal.azure.com.

Pesquise "Assinaturas caso não esteja na sua cara"

1 Criar a assinatura ou usar uma existente

2.Criar o grupo de Recursos: Dentro do grupo de recursos opção Criar, ou na barra de pesquisa, digite Máquinas Virtuais e selecione a opção. Clique em Criar e depois em "Máquina virtual".

3.Configurações Básicas:

Assinatura e Grupo de Recursos: Escolha sua assinatura, escolha o novo grupo de recursos criado.


De um nome para a maquina virtual.

Escolha uma região geograficamente próxima, no meu caso de testes eu escolho East Us

Opções de Disponibilidade: como é um estudo eu coloquei nenhuma.

Selecione o sistema operacional desejado.

Escolha o tamanho da VM com base no seu planejamento.

Defina um nome de usuário e senha (ou chave SSH para Linux).

Permita as portas necessárias (ex: RDP para Windows, SSH para Linux).

4. Discos: Configure o tipo e tamanho do disco do sistema operacional e adicione discos de dados, se necessário.

5. Rede: Configure a Rede Virtual, Sub-rede, IP Público (se for o caso) e o Grupo de Segurança de Rede (Deixei no básico).

6.Gerenciamento: Como estou fazendo apenas um laboratorio eu deixei como estava.

7.Avançado: Como estou fazendo apenas um laboratorio eu deixei como estava.

8.Tags: Adicionei tags para organização e gerenciamento de custos. (mesmo sabendo que vou apagar na sequencia)

9.Revisar + Criar: Revise todas as configurações e clique em Criar.
