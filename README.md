# 📘 Portfólio Reflexivo: Redes de Computadores

> **Aluno:** Marcus Pires de Castro  
> **Curso:** Engenharia de Software | UniCatólica  
> **Disciplina:** Redes de Computadores  
> **Professora:** Stéphany Moraes Martins  
> **Semestre:** 2025/2

---

## 👋 Sobre Mim e Minha Trajetória

Olá! Sou estudante de Engenharia de Software e, profissionalmente, atuo com **Apoio na Informática no CEM Tiradentes**. [cite_start]Minha rotina envolve a instalação e manutenção de equipamentos, além de suporte técnico em sistemas e redes[cite: 1404, 1409, 1411].

[cite_start]Antes disso, fui estagiário no **DETRAN TO**, onde desenvolvi agilidade no atendimento e análise de processos administrativos[cite: 1414, 1415, 1416]. Essa bagagem prática me permite olhar para a teoria de Redes de Computadores não apenas como conceitos abstratos, mas como ferramentas reais para resolver problemas de conectividade e infraestrutura no meu dia a dia.

[cite_start]Minhas principais competências incluem proatividade para resolver problemas e facilidade com recursos de informática[cite: 1424, 1425], habilidades que foram fundamentais durante esta disciplina.

---

## 🚀 Jornada de Aprendizagem

Este portfólio é um diário de bordo das competências técnicas desenvolvidas ao longo do semestre, conectando a teoria da sala de aula com minha prática profissional.

### 1. 📡 Fundamentos e Classificação de Redes
*Conceitos iniciais e Topologias*

[cite_start]Aprendi que uma rede é um sistema de comunicação de dados com dispositivos independentes compartilhando recursos[cite: 673]. Um dos pontos altos foi entender a classificação geográfica e como ela se aplica ao meu trabalho:

* **LAN (Local Area Network):** A rede interna do CEM Tiradentes onde atuo.
* **WAN (Wide Area Network):** A conexão que nos liga à internet global e a outros órgãos.

[cite_start]Também estudei as topologias (**Estrela, Barramento, Anel**) e os modos de transmissão (**Unicast, Multicast e Broadcast**)[cite: 713, 843].

> **💡 Reflexão Prática:** Antes, eu apenas conectava cabos. Agora, entendo que ao usar um Switch em topologia Estrela, evito colisões de dados que eram comuns em topologias de Barramento ou com o uso de Hubs.

### 2. 🏗️ Arquitetura e Protocolos (OSI vs TCP/IP)
*A linguagem da Internet*

Aprofundamos nos modelos que padronizam a comunicação mundial. [cite_start]Estudei a diferença entre o modelo teórico (OSI de 7 camadas) e o modelo prático (TCP/IP de 4/5 camadas)[cite: 56, 88].

| Camada | Protocolos Estudados | Minha Aplicação Prática |
| :--- | :--- | :--- |
| **Aplicação** | HTTP, DNS, FTP, SSH | Uso diário para acesso web e transferência de arquivos. |
| **Transporte** | TCP, UDP | [cite_start]Entender que o TCP garante a entrega (confiabilidade) e o UDP foca em velocidade (streaming)[cite: 124, 136]. |
| **Rede** | IP, ICMP | [cite_start]Uso o ICMP (`ping`) rotineiramente para testar se um host está ativo[cite: 140, 1665]. |
| **Enlace/Física** | Ethernet, 802.11 (Wi-Fi) | Manutenção física de cabos e configuração de pontos de acesso Wi-Fi. |

### 3. 🛠️ Laboratório Virtual: Cisco Packet Tracer
*Simulação de Cenários Reais*

[cite_start]Como não precisamos apenas de hardware físico, utilizei o simulador Packet Tracer para criar e validar cenários de rede[cite: 567]. Abaixo, descrevo dois cenários que configurei e testei:

#### Cenário A: Interconexão Básica e Domínio de Colisão
* **Objetivo:** Comparar o uso de um Hub versus um Switch.
* **Configuração:** Conectei diversos PCs a um Hub e outros a um Switch.
* **Resultado:** No Hub, percebi que os dados eram enviados para *todas* as portas (Broadcast), gerando colisões e insegurança. No Switch, a comunicação foi direta (Unicast) entre origem e destino.
* **Conclusão:** O Switch é muito mais eficiente para a rede do escritório onde trabalho.

#### Cenário B: Rede Wireless
* **Objetivo:** Configurar um roteador sem fio (WRT300N) e conectar laptops e smartphones.
* **Configuração:** Defini o SSID e a segurança.
* [cite_start]**Aprendizado:** Entendi como dispositivos móveis se autenticam e recebem IPs dinamicamente via DHCP na rede sem fio[cite: 1526].

### 4. 🚦 Roteamento e Sub-redes
*O caminho das pedras (ou dos pacotes)*

Estudamos como os roteadores escolhem o melhor caminho para os dados.

* **Roteamento Estático:** Aprendi a configurar rotas manualmente. [cite_start]É seguro, mas trabalhoso para grandes redes[cite: 1603].
* [cite_start]**Roteamento Dinâmico:** Protocolos como **RIP** e **OSPF** que atualizam as rotas automaticamente quando há falhas ou mudanças na topologia[cite: 1631].
* [cite_start]**Cálculo de IP:** Enfrentei o desafio de calcular sub-redes (ex: entender que uma máscara `255.255.255.224` permite apenas 30 hosts válidos)[cite: 1461]. Isso é crucial para planejar o endereçamento de novos setores no trabalho.

### 5. 🔒 Segurança da Informação
*Protegendo o Ativo mais valioso*

[cite_start]Finalizamos com a família de normas **ISO 27000** e os pilares da segurança[cite: 272].

* [cite_start]**Confidencialidade:** Garantir que apenas pessoas autorizadas (como no sistema do DETRAN) acessem os dados[cite: 420].
* [cite_start]**Integridade:** Garantir que os dados não foram alterados indevidamente[cite: 414].
* [cite_start]**Disponibilidade:** Manter o sistema no ar (backup e redundância)[cite: 426].

> **💡 Reflexão Prática:** A segurança não é só software (antivírus). [cite_start]Aprendi que a "Segurança Física" (controle de acesso, catracas, prevenção contra incêndio) é a primeira barreira de defesa, algo que vivencio nas instalações do CEM Tiradentes[cite: 542].

---

## 📝 Comandos Essenciais

[cite_start]Durante a disciplina, compilei uma lista de comandos de terminal que agora fazem parte do meu "cinto de utilidades" profissional[cite: 1658, 1670, 1682]:

* `ipconfig` / `ifconfig`: Para verificar o endereçamento IP atual da máquina.
* `ping [ip]`: Para testar a conectividade e medir a latência (tempo de resposta).
* `tracert` / `traceroute`: Para ver a rota (saltos) que o pacote faz até o destino.
* `arp -a`: Para ver a tabela que mapeia endereços IP em endereços físicos (MAC).

---

## 🎯 Considerações Finais

Esta disciplina foi um divisor de águas. Ela validou tecnicamente muitas atividades que eu já realizava intuitivamente e me apresentou a uma camada de engenharia e planejamento que eu desconhecia.

**Próximos Passos:**
[cite_start]Pretendo continuar estudando sobre **Segurança de Redes** e **Cloud Computing**, pois vejo que o futuro da infraestrutura é híbrido e exige profissionais adaptáveis, característica que prezo em minha carreira[cite: 1429].

---

### 📚 Referências Bibliográficas Utilizadas

* [cite_start]*Materiais de Aula:* Slides e PDFs da Professora Stéphany Martins (Conceitos Básicos, Modelo OSI/TCPIP, Packet Tracer, Roteamento, Segurança)[cite: 3, 255].
* [cite_start]*Kurose, J. F., & Ross, K. W.*: Redes de Computadores e a Internet[cite: 190].
* [cite_start]*ISO/IEC 27000 Family*: Information security management[cite: 272].
* [cite_start]*Tanenbaum, A. S.*: Organização Estruturada de Computadores[cite: 1136].

---
*Este portfólio foi desenvolvido como requisito parcial de avaliação da disciplina de Redes de Computadores.*
