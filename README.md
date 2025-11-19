# 📘 Portfólio Reflexivo: Redes de Computadores

> **Aluno:** Marcus Pires de Castro  
> **Curso:** Engenharia de Software | Católica do Tocantins  
> **Disciplina:** Redes de Computadores  
> **Professora:** Stéphany Moraes Martins  
> **Semestre:** 2025/2

---

## 👋 Sobre Mim e Minha Trajetória

Olá! Sou estudante de Engenharia de Software e, profissionalmente, atuo com **Apoio na Informática no CEM Tiradentes**. Minha rotina envolve a instalação e manutenção de equipamentos, além de suporte técnico em sistemas e redes.

Antes disso, fui estagiário no **DETRAN TO**, onde desenvolvi agilidade no atendimento e análise de processos administrativos. Essa bagagem prática me permite olhar para a teoria de Redes de Computadores não apenas como conceitos abstratos, mas como ferramentas reais para resolver problemas de conectividade e infraestrutura no meu dia a dia.

Minhas principais competências incluem proatividade para resolver problemas e facilidade com recursos de informática, habilidades que foram fundamentais durante esta disciplina.

---

## 🚀 Jornada de Aprendizagem

Este portfólio é um diário de bordo das competências técnicas desenvolvidas ao longo do semestre, conectando a teoria da sala de aula com minha prática profissional.

### 1. 📡 Fundamentos e Classificação de Redes
*Conceitos iniciais e Topologias*

Aprendi que uma rede é um sistema de comunicação de dados com dispositivos independentes compartilhando recursos. Um dos pontos altos foi entender a classificação geográfica e como ela se aplica ao meu trabalho:

* **LAN (Rede Local):** A rede interna do CEM Tiradentes onde atuo.
* **WAN (Rede de Longa Distância):** A conexão que nos liga à internet global e a outros órgãos.

Também estudei as topologias (**Estrela, Barramento, Anel**) e os modos de transmissão (**Unicast, Multicast e Broadcast**).

> **💡 Reflexão Prática:** Antes, eu apenas conectava cabos. Agora, entendo que ao usar um Switch em topologia Estrela, evito colisões de dados que eram comuns em topologias de Barramento ou com o uso de Hubs antigos.

### 2. 🏗️ Arquitetura e Protocolos (OSI vs TCP/IP)
*A linguagem da Internet*

Aprofundamos nos modelos que padronizam a comunicação mundial. Estudei a diferença entre o modelo teórico (OSI de 7 camadas) e o modelo prático (TCP/IP).

| Camada | Protocolos Estudados | Minha Aplicação Prática |
| :--- | :--- | :--- |
| **Aplicação** | HTTP, DNS, FTP, SSH | Uso diário para acesso web e transferência de arquivos. |
| **Transporte** | TCP, UDP | Entender que o TCP garante a entrega (confiabilidade) e o UDP foca em velocidade (streaming). |
| **Rede** | IP, ICMP | Uso o ICMP (ping) rotineiramente para testar se um host está ativo. |
| **Enlace/Física** | Ethernet, 802.11 (Wi-Fi) | Manutenção física de cabos e configuração de pontos de acesso. |

### 3. 🛠️ Laboratório Virtual: Cisco Packet Tracer
*Simulação de Cenários Reais*

Utilizei o simulador Packet Tracer para criar e validar cenários de rede sem riscos. Abaixo, descrevo dois cenários que configurei e testei:

#### Cenário A: Interconexão Básica e Domínio de Colisão
* **Objetivo:** Comparar o uso de um Hub versus um Switch.
* **Resultado:** No Hub, percebi que os dados eram enviados para *todas* as portas (Broadcast), gerando tráfego inútil. No Switch, a comunicação foi direta (Unicast) entre origem e destino.
* **Conclusão:** O Switch é essencial para a eficiência da rede corporativa.

#### Cenário B: Rede Wireless e Serviços
* **Objetivo:** Configurar um roteador sem fio e serviços de rede.
* **Configuração:** Implementei um servidor DHCP (para distribuir IPs automaticamente) e um servidor DNS (para traduzir nomes de sites em IPs).
* **Aprendizado:** Entendi como dispositivos móveis se autenticam na rede sem fio e recebem suas configurações sem intervenção manual.

### 4. 🚦 Roteamento e Endereçamento
*O caminho dos dados*

Estudamos como os roteadores escolhem o melhor caminho para os dados na Camada de Rede.

* **Roteamento Estático:** Configuração manual de rotas. É seguro, mas trabalhoso para manter.
* **Roteamento Dinâmico:** Uso de protocolos como **RIP** e **OSPF** que atualizam as rotas automaticamente.
* **Endereçamento IP:** Pratiquei o cálculo de sub-redes e máscaras, fundamental para segmentar redes e evitar desperdício de IPs.

### 5. 🔒 Segurança da Informação
*Protegendo o Ativo mais valioso*

Finalizamos com a família de normas **ISO 27000** e os pilares da segurança da informação.

* **Confidencialidade:** Garantir que apenas pessoas autorizadas acessem os dados.
* **Integridade:** Garantir que os dados não foram alterados indevidamente.
* **Disponibilidade:** Manter o sistema funcional e acessível.

> **💡 Reflexão Prática:** A segurança não é apenas digital. Aprendi que a segurança física e a conscientização dos usuários (contra engenharia social) são a primeira linha de defesa.

---

## 📝 Comandos Essenciais

Durante a disciplina, dominei comandos de terminal que agora fazem parte do meu dia a dia profissional:

* `ipconfig` / `ifconfig`: Verifica o endereçamento IP e MAC da máquina.
* `ping [ip]`: Testa a conectividade e latência.
* `tracert`: Mapeia a rota e os saltos que o pacote faz até o destino.
* `arp -a`: Exibe a tabela de conversão de IP para MAC.

---

## 🎯 Conclusão

Esta disciplina foi um divisor de águas. Ela validou tecnicamente muitas atividades que eu já realizava no suporte técnico e me apresentou a uma camada de engenharia e planejamento que eu desconhecia.

**Próximos Passos:**
Pretendo continuar estudando sobre **Segurança de Redes** e **Cloud Computing**, pois vejo que o futuro da infraestrutura exige profissionais adaptáveis, característica que prezo em minha carreira.

---

### 📚 Referências Bibliográficas

* *Materiais de Aula:* Slides e PDFs da Professora Stéphany Martins (Conceitos Básicos, Modelo OSI/TCPIP, Packet Tracer, Roteamento, Segurança).


---
*Este portfólio foi desenvolvido como requisito parcial de avaliação da disciplina de Redes de Computadores.*
