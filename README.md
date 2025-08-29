# Componentes de Arquitetura do Azure - 1° Lab do Módulo 2
Este repositório contém o material prático do **1° laboratório do Módulo 2** do curso AZ-900, focado em componentes de arquitetura e criação de recursos básicos na nuvem.
## Objetivos do Lab
- Visualizar o **mapa de regiões do Azure** utilizando o [datacenters.microsoft.com.br](https://datacenters.microsoft.com.br).  
- Criar e gerenciar **Grupos de Recursos**.  
- Explorar o conteúdo dentro de um Grupo de Recursos.  
- Criar uma **Virtual Network (VNet)** para interconectar recursos.
---
## 1. Mapa de Regiões do Azure
O Azure possui diversos datacenters espalhados pelo mundo. No [datacenters.microsoft.com.br](https://datacenters.microsoft.com.br) é possível visualizar todas as **regiões disponíveis** e planejar a arquitetura considerando proximidade e latência.  
---
## 2. Criação de Grupo de Recursos
Um **Grupo de Recursos** é um contêiner lógico que organiza recursos relacionados do Azure.  
Passos realizados no lab:
1. Acessar o portal do Azure.  
2. Navegar até **Grupos de Recursos**.  
3. Clicar em **Adicionar** e preencher:
  - Nome do grupo de recursos  
  - Região de destino  
4. Criar o grupo.
---
## 3. Explorando um Grupo de Recursos
Dentro de um grupo de recursos criado, podemos visualizar todos os recursos relacionados, como:
- Máquinas Virtuais (VMs)  
- Bancos de Dados SQL  
- Virtual Networks (VNet)  
- Storage Accounts  
Isso permite **organizar e gerenciar recursos de forma centralizada**.
---
## 4. Criação de uma Virtual Network (VNet)
Uma **VNet** é a rede virtual do Azure que conecta recursos de forma segura.  
Passos realizados:
1. Acessar **Virtual Networks** no portal do Azure.  
2. Clicar em **Adicionar**.  
3. Preencher:
  - Nome da VNet  
  - Grupo de Recursos  
  - Região  
  - Faixa de endereços IP (CIDR)  
4. Criar a VNet e conectar recursos a ela.
---
## Observações Finais
Este lab é a base para **entender como os recursos do Azure são organizados e interconectados**, preparando para atividades mais avançadas de arquitetura e implantação de soluções na nuvem.
