# Pong

Este projeto implementa uma versão do clássico jogo Pong utilizando Python e a biblioteca Pygame, incorporando uma rede Perceptron para criar um bot jogador inteligente. 

O objetivo principal é explorar as capacidades de uma rede Perceptron para criar um adversário desafiador.

[Vídeo apresentado: ](https://www.youtube.com/watch?v=nGC0mN8vBis) 

Após a apresentação na disciplina, em dupla, implementamos a versão 5, em que o bot (player 2) joga com o jogador humano ( player 1)

[Nosso artigo : ](artigo.pdf) 



## Como replicar

No ambiente Linux:

```console
git clone https://github.com/orlandosaraivajr/Pong.git
cd Pong/
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
python pong_v5.py 2> /dev/null


```

No ambiente Windows:

```console
git clone https://github.com/orlandosaraivajr/Pong.git
cd Pong/
virtualenv venv
cd venv
cd scripts
activate.bat
cd ..
cd ..
pip install -r requirements.txt
python pong_v5.py

```

