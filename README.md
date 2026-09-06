# 🚁 Drone Simulator

Um simulador de voo de drone desenvolvido para navegador utilizando **Three.js**.

O projeto foi criado inicialmente como uma ferramenta de treinamento para pilotagem de drones, permitindo praticar controles e movimentação utilizando um controle físico, como o DualShock 4.

O simulador busca reproduzir uma experiência de voo em primeira pessoa (FPV), inspirada nos controles e comportamentos de drones da linha DJI.

---

## 🎮 Funcionalidades

- 🚁 Simulação de voo em primeira pessoa
- 🎮 Suporte a controles físicos (Gamepad API)
- 🕹️ Compatibilidade com controles PlayStation e Xbox
- ⚙️ Sistema de calibração automática do controle
- 🎥 Câmera em primeira pessoa
- 📷 Controle independente do gimbal
- 🛩️ Modos de voo:
  - CINE
  - NORMAL
  - SPORT
- 🏙️ Ambiente urbano para exploração livre
- 🧱 Sistema de colisões
- 🌳 Elementos urbanos e áreas abertas
- 🔊 Sistema de áudio dinâmico
- 📊 HUD com informações de voo e leitura dos controles

---

# 🕹️ Controles

A configuração foi inspirada nos controles utilizados em drones DJI.

### Analógico esquerdo

| Movimento | Função |
|---|---|
| ↑ | Subir |
| ↓ | Descer |
| ← / → | Girar o drone (Yaw) |

### Analógico direito

| Movimento | Função |
|---|---|
| ↑ | Voar para frente |
| ↓ | Voar para trás |
| ← / → | Movimento lateral |

### Botões

| Botão | Função |
|---|---|
| L1 | Modo de voo anterior |
| R1 | Próximo modo de voo |
| L2 | Mover gimbal para baixo |
| R2 | Mover gimbal para cima |

---

# ✈️ Modos de voo

O simulador possui três modos de voo inspirados nos drones DJI.

### 🎬 CINE

Modo mais lento e suave.

Ideal para:

- movimentos cinematográficos;
- treinamento de precisão;
- voos próximos a estruturas.

---

### ⚪ NORMAL

Modo equilibrado entre velocidade e controle.

Ideal para:

- voo livre;
- treinamento geral;
- exploração do mapa.

---

### 🚀 SPORT

Modo com maior velocidade e resposta dos controles.

Ideal para:

- deslocamentos rápidos;
- treinamento de reflexos;
- exploração em alta velocidade.

---

# 🗺️ Mapa

O simulador possui um ambiente urbano criado para permitir exploração livre.

O mapa conta com diferentes áreas e pontos de referência, incluindo:

- centro urbano;
- bairros residenciais;
- prédios;
- casas;
- praça;
- igreja;
- áreas verdes;
- ruas e avenidas;
- estruturas urbanas;
- pontos altos para voo.

O objetivo do ambiente é proporcionar referências visuais e obstáculos para tornar a experiência de voo mais próxima de um ambiente real.

---

# 🔊 Sistema de Áudio

O som do drone responde à dinâmica do voo, incluindo:

- velocidade horizontal;
- velocidade vertical;
- intensidade do movimento;
- modo de voo.

> O movimento do gimbal não interfere no áudio do drone.

---

# 🧰 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Three.js
- Web Audio API
- Gamepad API

---

# 🚀 Como executar

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/drone-simulator.git
