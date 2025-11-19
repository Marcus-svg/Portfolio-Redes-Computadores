# Portfólio Reflexivo: Redes de Computadores 🌐

**Aluno:** Marcus Pires de Castro  
**Curso:** Engenharia de Software | UniCatólica  
**Disciplina:** Redes de Computadores  
**Professora:** Stéphany Moraes Martins  
**Semestre:** 2025/2

---

## 🚀 Apresentação e Perfil Profissional

Olá! Sou Marcus Pires, estudante de Engenharia de Software e profissional com atuação em suporte técnico e análise administrativa.

[cite_start]Minha trajetória profissional inclui experiências no **CEM Tiradentes**, onde fui responsável pela instalação, manutenção de equipamentos e suporte a sistemas e redes [cite: 1130, 1131][cite_start], e no **DETRAN TO**, onde desenvolvi capacidades analíticas e de organização[cite: 1136, 1138].

**Objetivo deste Portfólio:**
Este repositório serve como um diário de bordo reflexivo para a disciplina de Redes de Computadores. [cite_start]O objetivo é documentar não apenas a teoria absorvida sobre protocolos e arquiteturas, mas conectar esses conhecimentos com minha prática profissional de suporte técnico, demonstrando como a teoria fundamenta a resolução de problemas reais que enfrento no dia a dia[cite: 1389, 1400].

---

## 📚 Jornada de Aprendizagem

### 1. Introdução e Fundamentos de Redes
*Referência: Aula 06/08 e 13/08*

[cite_start]No início da disciplina, debatemos o conceito fundamental de redes como um sistema de comunicação de dados com dispositivos independentes em uma área geográfica limitada[cite: 20, 24].

**O que aprendi:**
* **Classificação Geográfica:** Entendi a distinção entre LAN, MAN, WAN e PAN. [cite_start]Isso foi crucial para categorizar a rede do meu local de trabalho (CEM Tiradentes) como uma LAN, mas que se conecta a WANs para acesso externo[cite: 180, 182, 187].
* **Topologias:** Estudamos as topologias física e lógica (Estrela, Barramento, Anel, Malha). [cite_start]A topologia em estrela é a mais comum que vejo na prática, com switches centrais conectando os PCs[cite: 191, 198].
* [cite_start]**Modos de Transmissão:** A diferença entre Unicast (um para um), Multicast (um para um grupo) e Broadcast (um para todos)[cite: 66, 90, 113].

> **Reflexão:** Antes, eu conectava cabos intuitivamente. Agora, compreendo que ao conectar um PC em um Switch, estou criando um ponto em uma topologia estrela que utiliza Unicast para direcionar dados eficientemente, evitando a colisão que ocorria nos antigos Hubs.

---

### 2. Modelos de Referência (OSI e TCP/IP)
*Referência: Aula 20/08*

Aprofundamos na arquitetura de camadas, essencial para a padronização da comunicação.

**Conceitos Chave:**
* [cite_start]**Modelo OSI (7 Camadas):** Física, Enlace, Rede, Transporte, Sessão, Apresentação, Aplicação[cite: 980].
* [cite_start]**Modelo TCP/IP (4/5 Camadas):** A "pilha" real da internet, focando em Aplicação, Transporte (TCP/UDP), Internet (IP) e Acesso à Rede[cite: 1011, 1012].
* [cite_start]**Encapsulamento:** O processo onde cada camada adiciona seu cabeçalho aos dados, descendo da aplicação até a física (bits)[cite: 1013].

**Atividade Prática Reflexiva (`ping` e `tracert`):**
[cite_start]Realizei testes práticos utilizando comandos de diagnóstico[cite: 528].
* `ping`: Utiliza o protocolo ICMP para testar conectividade. [cite_start]Percebi a importância do TTL (Time to Live) para evitar loops infinitos[cite: 540, 552].
* `tracert`: Mostra os saltos (hops) entre roteadores. [cite_start]Foi fascinante ver a rota física que meus dados fazem para sair de Palmas até um servidor internacional[cite: 575, 578].

> **Dificuldade:** Inicialmente, confundi as responsabilidades da Camada de Transporte (TCP vs UDP).
> [cite_start]**Solução:** A analogia dos slides ajudou muito: o TCP é como uma carta registrada (garante entrega), enquanto o UDP é como um envio simples (rápido, mas sem garantia)[cite: 1048, 1059, 1580].

---

### 3. Prática com Cisco Packet Tracer
*Referência: Aula 10/09*

[cite_start]Utilizamos o simulador Packet Tracer para criar ambientes de rede virtuais[cite: 434].

**Atividades Realizadas:**
1.  Conexão de PCs via Switch e Hub.
2.  [cite_start]Configuração de IPs estáticos e máscaras de sub-rede (ex: 192.168.100.X)[cite: 476, 506].
3.  [cite_start]Simulação de redes Wireless com roteadores domésticos[cite: 517].

![Insira aqui um print da sua topologia no Packet Tracer]

> [cite_start]**Reflexão Profissional:** No meu currículo, cito "facilidade com recursos de informática"[cite: 1147]. O Packet Tracer elevou isso, permitindo-me testar configurações de rede (DHCP, DNS) sem o risco de derrubar a rede real do meu estágio. [cite_start]Entendi visualmente o conceito de "Domínio de Colisão" ao comparar Hubs e Switches[cite: 1256].

---

### 4. Roteamento e Endereçamento IP
*Referência: Aula 01/10*

Estudamos como os dados viajam entre redes diferentes.

* [cite_start]**Roteamento Estático:** Configuração manual, segura para redes pequenas, mas trabalhosa[cite: 1325].
* **Roteamento Dinâmico:** Protocolos como RIP e OSPF que aprendem rotas automaticamente. [cite_start]Essencial para a redundância e escalabilidade da internet[cite: 1340, 1353].
* **Cálculo de Sub-redes:** Um dos pontos mais desafiadores. [cite_start]Entender como a máscara de rede (ex: /24 ou 255.255.255.0) define quantos hosts cabem na rede[cite: 1183].

---

### 5. Segurança da Informação
*Referência: Aula 12/11*

A segurança não é um produto, é um processo. [cite_start]Discutimos a família ISO 27000 e os pilares da segurança[cite: 637].

**Os Pilares (CID):**
* [cite_start]**Confidencialidade:** Garantir que só pessoas autorizadas acessem (ex: Criptografia)[cite: 784].
* [cite_start]**Integridade:** Garantir que a informação não foi alterada (ex: Hash)[cite: 778].
* [cite_start]**Disponibilidade:** Garantir que o sistema esteja acessível quando necessário (ex: Proteção contra DDoS, Backups)[cite: 790].

> [cite_start]**Conexão com o Projeto de Vida:** Como futuro Engenheiro de Software, a segurança deve ser parte do design do software ("Security by Design") e não algo adicionado no final[cite: 668]. Isso muda a forma como escreverei meus códigos daqui para frente.

---

## 💡 Conclusão e Projeto de Vida

A disciplina de Redes de Computadores foi fundamental para solidificar a base técnica necessária para minha carreira.

**Pontos Fortes do Aprendizado:**
* Capacidade de diagnosticar problemas de rede (físico vs lógico) no meu trabalho atual.
* Entendimento de como minhas aplicações (software) trafegam pela infraestrutura global.

**Desafios Superados:**
* A matemática binária do endereçamento IP foi complexa, mas resolvida através de exercícios repetitivos de fixação.

**Planejamento Futuro:**
Pretendo aprofundar meus estudos em **Cloud Computing** e **DevOps**. [cite_start]O conhecimento sobre roteamento, portas e protocolos (HTTP, SSH, FTP) adquirido aqui [cite: 1012] [cite_start]é pré-requisito obrigatório para configurar servidores na nuvem e pipelines de deploy, alinhando-se com minha habilidade de adaptação a novas funções citada em meu currículo[cite: 1151].

---

## 📖 Referências Bibliográficas

As referências abaixo foram utilizadas como base para o estudo e construção deste portfólio, conforme material disponibilizado pela Professora Stéphany Martins.

1.  [cite_start]**Kurose, J. F., & Ross, K. W.** *Redes de Computadores e a Internet*.[cite: 368, 1114, 1734].
2.  **Tanenbaum, A. S.** *Organização Estruturada de Computadores*. [cite_start]Prentice Hall[cite: 1476].
3.  **Material de Aula:** Slides "Conceitos Básicos", "Modelo OSI/TCPIP", "Packet Tracer", "Roteamento" e "Segurança" fornecidos no AVA.
4.  [cite_start]**ISO/IEC 27001:** Normas de Segurança da Informação[cite: 725].

---
*Este portfólio foi desenvolvido como requisito parcial de avaliação da disciplina de Redes de Computadores.*
