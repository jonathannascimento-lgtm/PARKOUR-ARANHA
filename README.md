# 🕸️ Parkour Aranha 3D — Cyberpunk Platformer



![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.dot-js)

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.0-blue?style=for-the-badge&logo=tailwind-css)

![HTML5](https://img.shields.io/badge/HTML5-3D_Game-orange?style=for-the-badge&logo=html5)

![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)



**Parkour Aranha** é um jogo 3D dinâmico de plataforma e parkour cibernético desenvolvido em **Three.js** e **HTML5/JavaScript**. Enfrente 100 níveis progressivos em uma cidadela futurista flutuante, dominando saltos acrobáticos, corrida em paredes (*Wall-Run*) e mecânicas de disparo de teia (*Web-Swing*).



---



## 🎮 Funcionalidades Principais



- 🏃 **Movimentação 360° e Física Precisa:** Sistema de colisão otimizado com resposta instantânea aos comandos.

- 🤸 **Pulos Acrobáticos:** Saltos duplos com rotação acrobática no ar e ajuste de tempo das animações.

- 🕸️ **Mecânica de Teia (Web-Swing):** Trave sua teia nas superfícies e balance entre plataformas distantes.

- 🌌 **Gráficos 4K Cyberpunk:** Tone mapping cinematográfico (ACESFilmic), sombras suaves (*PCFSoftShadowMap*) e iluminação PBR.

- 📊 **100 Níveis & 3 Dificuldades:** Escolha entre Fácil, Médio e Difícil com geração procedural equilibrada.

- 🗺️ **Radar 360° & HUD Futurista:** Minimapa em tempo real para localizar gemas coletáveis e portais de saída.



---



## 🕹️ Controles



| Ação | Teclado / Mouse | Telas Sensíveis ao Toque |

| :--- | :--- | :--- |

| **Movimentar** | <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> | Joystick Virtual |

| **Olhar / Câmera 360°** | Movimento do Mouse (*Pointer Lock*) | Arrasto na Tela |

| **Pular / Salto Duplo** | <kbd>ESPAÇO</kbd> | Botão **JUMP** |

| **Disparar Teia** | <kbd>E</kbd> | Botão **WEB** |

| **Correr (Sprint)** | <kbd>SHIFT</kbd> | Botão **SPRINT** |



---



## 🚀 Como Executar o Projeto



Como o jogo foi construído em um único arquivo Web autônomo, não é necessário instalar dependências complexas (Node.js ou compiladores).



### Opção 1: Execução Direta



1. Baixe ou clone o repositório:

   ```bash

   git clone https://github.com/seu-usuario/parkour-aranha-3d.git

   ```

2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Brave, Safari).



### Opção 2: Servidor Local (Recomendado)



Para evitar restrições de CORS ao carregar os modelos 3D externos `.glb`:



```bash

# Utilizando Python 3

python -m http.server 8000



# Ou usando a extensão Live Server do VS Code

```

Acesse `http://localhost:8000` no seu navegador.



---



## 🛠️ Tecnologias Utilizadas



- **Renderizador 3D:** [Three.js](https://threejs.org/) (r128)

- **Carregador 3D:** GLTFLoader (`Soldier.glb`)

- **Estilização de UI:** [Tailwind CSS](https://tailwindcss.com/)

- **Sintetizador de Áudio:** Web Audio API (sem dependência de arquivos externos `.mp3`)

- **Ícones:** FontAwesome 6



---



## 📜 Licença



Este projeto é de código aberto sob a licença [MIT](LICENSE). Sinta-se livre para modificar, aprimorar e distribuir!
