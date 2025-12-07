# 🔫 VR 360 Shooter

Um jogo de Realidade Virtual (VR) simples e imersivo rodando diretamente no navegador, construído com **A-Frame**.

🔗 **[Jogue Agora (Clique Aqui)](https://kayvasconcelos.github.io/Ponderada2/)**

## 🎮 Sobre o Projeto
Este é um jogo de tiro estilo "360 graus". O objetivo é eliminar as esferas inimigas que aparecem aleatoriamente ao redor do jogador em um ambiente virtual estilo "Tron".

O projeto utiliza a tecnologia **WebVR**, permitindo que funcione em celulares (usando o giroscópio) e computadores sem a necessidade de instalar aplicativos.

## 🕹️ Como Jogar

### No Celular (Recomendado)
1. Acesse o link do projeto.
2. Fique em pé e **gire seu corpo fisicamente** para olhar ao redor (360º).
3. Encontre as esferas vermelhas flutuando.
4. **Mire:** Coloque o ponto vermelho central sobre o inimigo.
5. **Atire:** Mantenha a mira fixa por alguns milissegundos (o cursor irá diminuir) para disparar automaticamente.

### No Computador
1. Clique e arraste o mouse na tela para girar a câmera.
2. Coloque a mira sobre os inimigos para atirar.

## 🛠️ Tecnologias Utilizadas
* **HTML5 & JavaScript**: Estrutura e lógica do jogo.
* **[A-Frame](https://aframe.io/)**: Framework web para realidade virtual.
* **aframe-environment-component**: Para geração procedural do cenário.

## 📂 Estrutura do Código
O jogo roda inteiramente em um único arquivo `index.html`, contendo:
* Cena A-Frame (`<a-scene>`).
* Sistema de Câmera e Cursor (`fuse-based`).
* Lógica em JavaScript para gerar inimigos aleatórios, detectar colisões e contar pontos.
