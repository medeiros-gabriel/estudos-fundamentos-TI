# Redes de Computadores — Anotações

Resumo dos principais conceitos estudados no curso de Redes (Curso em Vídeo — Gustavo Guanabara).

---

## Tipos de Rede (quanto à hierarquia)

### Ponto a Ponto
Esse tipo de rede **não possui servidor**. Os computadores dos usuários se conectam entre si diretamente, compartilhando arquivos e recursos sem um intermediário central.

### Cliente-Servidor
Existe um **servidor central** responsável por gerenciar a rede e distribuir recursos para os clientes conectados. Esse modelo:
- Abrange uma área maior
- Suporta mais dispositivos
- É mais seguro que o modelo Ponto a Ponto

---

## Classificação por alcance

| Tipo | Alcance | Características |
|------|---------|------------------|
| **PAN** | Curto alcance | Não precisa de intermediário (ex: Bluetooth) |
| **LAN** | Área local | Um servidor para poucas máquinas, até ~100 metros |
| **CAN/MAN** | Metropolitana | Cobre cidades, alcance de até ~100 km |

---

## Cabos de Rede

### Cabo Coaxial
Padrão antigo, transmite a 10 Mb (Mega bits). *Obs: B = Byte, b = bit.*

### Cabo de Par Trançado
Os cabos são **trançados em pares** — são 8 fios de cobre divididos em 4 pares, trançados uns nos outros. Eles não ficam paralelos porque, se ficassem, um par interferiria no sinal do outro.

**Tipos:**
- **UTP** — cabo padrão usado em casas e escritórios. Mais barato, flexível e fácil de instalar.
- **STP** — possui uma folha de alumínio como proteção ao redor dos fios (blindagem contra interferência).

**Categorias (CATs):**
| Categoria | Velocidade | Uso comum |
|-----------|------------|-----------|
| CAT 5 | 100 Mbps | Padrão antigo |
| CAT 5e | 1 Gbps | Comum em residências |
| CAT 6 | 10 Gbps | — |
| CAT 6A / CAT 7 | — | Usados em data centers |

### Montagem de cabo UTP (padrões T568A e T568B)
Ao montar um cabo UTP CAT5e, existem dois padrões de pinagem (ordem das cores nos pinos 1-8), usados dependendo se o cabo é "reto" (mesma ponta nas duas pontas) ou "crossover" (uma ponta A, outra B — usado para conectar dispositivos iguais diretamente, como PC a PC).

---

## Cálculo de Sub-rede (exemplo prático)

Exemplo com máscara `255.255.255.192`:

**Passo 1 — Máscara:** identificar o último octeto da máscara (192)

**Passo 2 — Salto:** 256 − 192 = **64** (esse é o "salto" entre cada sub-rede)

**Passo 3, 4 e 5 — Rede / Broadcast / Host:** usando o salto de 64, cada sub-rede ocupa um bloco de 64 endereços:

| Rede | Host (utilizável) | Broadcast |
|------|--------------------|-----------|
| 192.168.1.0 | 192.168.1.1 até 192.168.1.62 | 192.168.1.63 |
| 192.168.1.64 | 192.168.1.65 até 192.168.1.126 | 192.168.1.127 |
| 192.168.1.128 | 192.168.1.129 até 192.168.1.190 | 192.168.1.191 |
| 192.168.1.192 | 192.168.1.193 até 192.168.1.254 | 192.168.1.255 |

**Regra prática:** o endereço de rede sempre soma o "salto" (resultado do Passo 1) para achar a próxima sub-rede. O broadcast é sempre o salto − 1, adicionado à tabela. Nesse exemplo, essa máscara resulta em **4 sub-redes**.

---

## Fontes
- Curso de Redes de Computadores — Gustavo Guanabara (Curso em Vídeo)
- Livro: *Trabalhando com Redes de Computadores — Conceito e Prática* (Camila Ceccatto da Silva Perez, Editora Viena, 2ª edição)
