# resumo-lab3
Este documento reúne os principais conceitos sobre armazenamento, redundância, pontos de extremidade, camadas de acesso, migrações e gerenciamento no Azure, conforme abordado no exame AZ-900.  

# 📘 Resumo – Microsoft Azure AZ-900  

## 🔄 Redundância e Serviços de Armazenamento  

O Azure garante **alta disponibilidade e durabilidade** dos dados por meio de modelos de redundância:  
- **LRS (Locally Redundant Storage)** → cópias dentro de um único datacenter.  
- **ZRS (Zone-Redundant Storage)** → cópias sincronizadas em diferentes zonas de uma mesma região.  
- **GRS (Geo-Redundant Storage)** → cópias assíncronas entre regiões distintas.  
- **RA-GRS (Read-Access Geo-Redundant Storage)** → cópias entre regiões com acesso somente leitura à réplica secundária.  

**Serviços de Armazenamento disponíveis:**  
- **Blob Storage** → dados não estruturados (imagens, vídeos, backups).  
- **File Storage (Azure Files)** → compartilhamentos SMB ou NFS.  
- **Disk Storage** → discos gerenciados para VMs (HDD, SSD, Ultra Disk).  
- **Queue Storage** → filas de mensagens assíncronas.  
- **Table Storage** → dados NoSQL chave-valor.  

---

## 🌐 Pontos de Extremidade Públicos e Camadas de Acesso  

- **Pontos de extremidade públicos (Endpoints):** permitem acesso externo aos recursos de armazenamento.  
- **Camadas de acesso (Access Tiers) do Blob Storage:**  
  - **Hot** → dados acessados frequentemente.  
  - **Cool** → dados acessados de forma esporádica.  
  - **Archive** → dados raramente acessados, armazenados offline.  

---

## 🚚 Migrações para o Azure  

O Azure disponibiliza serviços e ferramentas para facilitar a **migração de workloads e dados**:  
- **Azure Migrate** → avaliação e migração de VMs, bancos e aplicativos.  
- **Data Box** → transferência física para grandes volumes de dados.  
- **AzCopy** → linha de comando para cópia em escala.  
- **Storage Migration Service** → migração de servidores de arquivos para Azure Files.  

---

## 🗂️ Gerenciamento de Arquivos e Armazenamento  

Formas de gerenciar dados e recursos no Azure:  
- **Azure Storage Explorer** → ferramenta gráfica.  
- **Azure Portal** → interface centralizada via navegador.  
- **CLI e PowerShell** → automação e scripts.  
- **SDKs e APIs REST** → integração em aplicações.  
- **File Sync** → sincronização de servidores locais com Azure Files.  

---

✦ Esse resumo traz uma visão consolidada dos principais pontos do **AZ-900** sobre **armazenamento e gerenciamento no Microsoft Azure**.  
