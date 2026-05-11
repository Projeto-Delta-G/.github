# 📐 Bem-vindo(a) ao Projeto Delta G

O **Delta G** é uma iniciativa tecnológica que propõe a evolução do clássico equipamento do Plano Inclinado de Galileu para o ecossistema da Internet das Coisas (IoT). O nosso objetivo é modernizar a coleta e a visualização de dados em laboratórios de física, transformando o ensino da cinemática numa experiência interativa, precisa e digital.

### ⚙️ Como Funciona
O ecossistema é dividido em hardware automatizado e uma plataforma web de gestão:
- **Hardware (Kit Físico):** Construído com ESP-32, utiliza sensores infravermelhos para telemetria de tempo e distância, além de um atuador linear elétrico e giroscópio para controle preciso do ângulo.
- **Plataforma Web:** Sistema *mobile-first* onde professores gerenciam salas de aula e alunos (Guests) acessam as equipes via PIN para acompanhar os experimentos em tempo real.
- **Comunicação:** Telemetria de alta velocidade utilizando protocolo MQTT (Broker) e suporte a atualizações remotas via MQTT OTA.

### 🗂️ Estrutura de Repositórios
A arquitetura de software do Delta G está dividida nos seguintes módulos:

* 📦 **`IOT-DeltaG`** *(Em breve)*: Código C/C++ embarcado no ESP-32 para controle de sensores, atuadores e comunicação MQTT.
* 🌐 **`API-DeltaG`** *(Em breve)*: API REST e serviços de subscrição MQTT para gerenciamento de dados das salas e kits.
* 📱 **`WEB-DeltaG`** *(Em breve)*: Interface de usuário (UI) para o painel do professor e acesso via PIN para alunos.

---
*Projeto desenvolvido para modernizar e gamificar a prática laboratorial de mecânica clássica.*
