# 💻 Prática: Criando e Configurando uma Máquina Virtual na Microsoft Azure

Este repositório tem como objetivo registrar o processo de criação, configuração e uso de **Máquinas Virtuais (VMs)** na plataforma Microsoft Azure. O conteúdo serve como material de apoio para estudos, revisões e futuras implementações.

---

## 🌐 Benefícios da Computação em Nuvem

* Escalabilidade: aumente ou reduza recursos sob demanda.
* Redução de custos: pagamento conforme o uso.
* Alta disponibilidade e recuperação de desastres.
* Acesso global: recursos disponíveis em qualquer lugar.
* Atualizações e manutenção automáticas.
* Segurança avançada com padrões da indústria.

---

## 🎯 Objetivo do Desafio

* Entender o que é uma Máquina Virtual e como ela funciona na nuvem.
* Praticar a criação e configuração de uma VM no **Azure Portal**.
* Armazenar **resumos, comandos, boas práticas e dicas úteis** sobre o uso de VMs.
* Criar um repositório documentado que ajude outros desenvolvedores e estudantes a iniciarem no tema.

---

## 🧠 O que foi Aprendido

### 🔹 1. Conceitos de Máquina Virtual

* Máquina virtual é um ambiente virtualizado que simula um computador físico.
* Utilizada para testes, hospedagem de aplicações, bancos de dados, entre outros.
* Permite escolher **sistemas operacionais**, **recursos de hardware**, **região** e mais.

### 🔹 2. Criando uma VM no Azure

1. Acesse o [Portal da Azure](https://portal.azure.com/).
2. No menu lateral, clique em **"Máquinas Virtuais"**.
3. Clique em **"Criar" > "Máquina Virtual"**.
4. Preencha os dados:

   * **Grupo de Recursos**
   * **Nome da VM**
   * **Região** (ex: Brazil South)
   * **Imagem do SO** (ex: Ubuntu, Windows Server)
   * **Tamanho da VM**
   * **Usuário e senha/SSH**
5. Configurar opções de rede e disco.
6. Revisar e criar.

### 🔹 3. Acessando a VM

* **Linux**:

  * Usar SSH: `ssh usuario@ip-publico`
  * Verificar se a porta 22 está aberta nas configurações da rede.

* **Windows**:

  * Acesso via **Área de Trabalho Remota (RDP)**.
  * Certifique-se de que a porta 3389 está liberada.

---

## ⚙️ Ferramentas e Materiais Utilizados

| Ferramenta          | Finalidade                             |
| ------------------- | -------------------------------------- |
| Microsoft Azure     | Plataforma de nuvem                    |
| Azure Portal        | Interface para gerenciar recursos      |
| SSH / RDP           | Conexão com a máquina virtual          |
| Ubuntu / Windows    | Sistemas operacionais utilizados na VM |
| VS Code + Extensões | Acesso e manipulação remota (opcional) |

---

## 📌 Dicas e Boas Práticas

* Utilize **nomes claros** para suas VMs e recursos.
* Sempre defina **tags** para facilitar a organização e cobrança.
* Configure **alertas de custo** e use o **Azure for Students** para evitar cobranças.
* Lembre-se de **parar ou excluir** a VM se não estiver usando.
* Crie **snapshots ou imagens** para backup de máquinas importantes.

---

## ✅ Conclusão

Este exercício foi fundamental para consolidar os conhecimentos sobre infraestrutura na nuvem utilizando a Azure. A criação de uma máquina virtual permitiu:

* Compreender o processo de provisionamento de recursos.
* Aprender a se conectar, configurar e monitorar uma VM.
* Refletir sobre boas práticas e economia de recursos em ambiente cloud.

---

## 🔗 Links Úteis

* [Documentação de Máquinas Virtuais na Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)
* [Azure for Students - Ativação Gratuita](https://azure.microsoft.com/pt-br/free/students/)
* [Portal da Azure](https://portal.azure.com/)
* [DIO - Curso na Plataforma](https://www.dio.me/)
