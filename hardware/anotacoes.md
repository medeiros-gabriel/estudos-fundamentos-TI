# Hardware — Anotações

Resumo do curso de Hardware (Curso em Vídeo, Gustavo Guanabara), do início à montagem final.

---

## Introdução

**O que é Hardware?**
É a parte física do computador — tudo que dá pra tocar. Entender os componentes e sua função é a base pra saber montar, manter e resolver problemas de uma máquina.

**Requisitos de um PC**
Antes de montar qualquer máquina, é preciso definir pra que ela vai servir. Isso muda completamente os componentes escolhidos — um PC pra uso comum não precisa da mesma configuração de um PC gamer, por exemplo. Definir a necessidade de quem vai usar é o primeiro passo.

**Periféricos básicos**
Mouse, teclado, HD, monitor (com taxa de atualização em Hertz — ex: 75 Hz), gabinete e memória RAM (medida em GB) são os elementos básicos que compõem um PC.

---

## Processador (CPU)

A **Unidade Central de Processamento** é o cérebro do computador. Ela é responsável por processar as instruções e é o principal componente na hora de montar uma máquina — a compra de todos os outros componentes gira em torno dela.

---

## Fonte de Alimentação

É o dispositivo que transforma a energia elétrica que vem da tomada em uma voltagem contínua e estável, própria para alimentar os componentes eletrônicos do PC.

---

## Placa-mãe

**Regra importante:** sempre compre o processador primeiro, e só depois a placa-mãe — porque cada placa-mãe tem modelos específicos de socket para tipos específicos de processador.

**Componentes da placa-mãe:**

| Componente | Função |
|---|---|
| **Socket (soquete do processador)** | Onde o processador (CPU) é encaixado. Cada geração de processador exige um tipo específico de socket |
| **Slots de Memória (RAM)** | Fendas onde se encaixam os pentes de memória RAM |
| **Slot PCIe (PCI Express)** | Geralmente uma fenda longa, azul ou de cor destacada, usada para instalar a placa de vídeo (GPU) |
| **Slots PCI** | Usados para conectar/instalar placas de expansão |
| **Chipset** | Chips que controlam a comunicação entre os componentes da placa |
| **Conectores SATA / M.2** | Ligam HDs, SSDs e drives ópticos |
| **Conector de Alimentação ATX** | Recebe a energia vinda da fonte principal |
| **Painel Traseiro (I/O)** | Portas externas, como USB, HDMI e áudio |
| **Chip da BIOS/UEFI** | Armazena o software básico de inicialização do computador |
| **Bateria CMOS** | Mantém data, hora e configurações salvas mesmo com o PC desligado |
| **VRM (Módulo Regulador de Tensão)** | Controla a voltagem que vai para o processador |

**Diagrama ilustrativo** (baseado no modelo ASUS P5AD2-E): a placa-mãe reúne, lado a lado, os slots PCI Express e PCI, o slot AGP, as portas I/O (USB, HDMI, áudio), os conectores SATA, o socket da CPU, os capacitores, a bateria e os slots de memória RAM — todos interligados para permitir a comunicação entre os componentes.

---

## Memória RAM

É a **Memória Principal** do computador. Quanto mais compatível e rápida ela for, mais rápida a máquina vai processar tarefas no dia a dia.

---

## HD e SSD

Dois tipos de armazenamento:

- **HD** — mais barato, porém mais lento por ter discos rígidos que giram fisicamente para ler e escrever dados.
- **SSD** — mais rápido e eficiente, sem partes móveis, porém mais caro.

Vale considerar o custo-benefício entre os dois na hora de montar um PC — muita gente combina os dois: um SSD pequeno e rápido para o sistema operacional, e um HD maior para armazenamento.

---

## Periféricos

- **Monitor**: resolução Full HD é 1920x1080 (proporção 16:9); resolução Quad HD é 2560x1440 (padrão IPS).
- **Cabos de vídeo**:
  - **VGA** — antigo, transmite apenas vídeo (analógico).
  - **DVI** — melhor qualidade e resolução, um cabo digital.
  - **HDMI** — transmite áudio e vídeo ao mesmo tempo, é o padrão mais completo hoje.

---

## Softwares

O **Sistema Operacional** é o que faz a ponte entre o hardware e o usuário — sem ele, o computador não tem interface para funcionar. Existem sistemas licenciados (como Windows) e sistemas livres (como Linux).

---

## Gabinete

O gabinete precisa ter um bom fluxo de ar (ventilação) para evitar que os componentes esquentem demais. Também deve ter espaço suficiente para acomodar todos os componentes com organização — inclusive os cabos, que devem ficar bem passados para não atrapalhar a ventilação.

---

## Montagem do Computador (passo a passo)

**Parte 1 — Componentes e montagem inicial**

Peças necessárias: processador, fonte de alimentação, placa-mãe, SSD, HD, placa de vídeo, water cooler.

Passos:
1. Colocar a placa-mãe em um ambiente sem energia elétrica (por segurança)
2. Encaixar o processador no socket
3. Colocar o cooler em cima do processador (aplicando pasta térmica entre eles, se o cooler não vier com ela já aplicada)
4. Encaixar a memória RAM na lateral da placa-mãe

**Parte 2 — Fixação no gabinete**

1. Com a placa-mãe já montada com processador e RAM, encaixar no gabinete e fixar nos parafusos
2. Colocar o HD ou SSD no espaço reservado para eles

**Ligando a alimentação**

Depois dos passos acima, encaixar a fonte de alimentação no lugar certo e conectar todos os cabos — na placa-mãe, HD, SSD, etc.

---

## Instalação do Sistema Operacional

**Preparando o Windows 10**
Buscar o site oficial da Microsoft, escolher a versão do Windows desejada e preparar um pendrive bootável com ela.

**Instalando o Windows 10**
Colocar o pendrive no PC novo, seguir as configurações básicas exibidas na tela e esperar a instalação ser concluída.

**Preparando o Linux**
Buscar o site oficial do Linux (Ubuntu) e repetir o mesmo processo do Windows: gravar o Linux no pendrive e reiniciar o PC para instalar.

**Instalando o Linux**
Depois de separar espaço no HD ou SSD, configurar o Linux/Ubuntu. Isso permite ter **dois sistemas operacionais na mesma máquina** (dual boot).

**Testando a performance do PC**
Testar o funcionamento das IDEs, observando a resposta do PC — se roda com lentidão ou não.

---

## Manutenção do PC

**Limpando o PC**
1ª etapa: limpar a lateral interna do PC, retirando a poeira com pincel ou pano.
2ª etapa: retirar os componentes com cuidado, limpar a placa-mãe, RAM e demais peças com cuidado.

**Desmontando e trocando pasta térmica**
Desmontar as peças, trocar a pasta térmica do processador para garantir que ele continue funcionando bem (a pasta térmica perde eficiência com o tempo).

**Testando a performance do PC (revisão final)**
Guanabara mostra o PC organizado e testado, garantindo que os componentes funcionem bem juntos após a manutenção.

---

## Encerramento

Curso de Hardware finalizado! Passei por todo o ciclo: entender os componentes individualmente, aprender a montar um PC do zero, instalar sistemas operacionais (incluindo dual boot Windows + Linux) e fazer manutenção preventiva (limpeza e troca de pasta térmica).

---

## Feito por
Gabriel Medeiros, 2026.

## Fontes
- Curso de Hardware — Gustavo Guanabara (Curso em Vídeo)
