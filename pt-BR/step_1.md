O bloco `deslize`{:class="block3motion"} no Scratch pode ser usado para mover um ator pelo Palco.

Um ator pode `deslizar`{:class="block3motion"} para um ponto específico (coordenadas), uma `posição aleatória`{:class="block3motion"}, o `ponteiro do mouse`{:class="block3motion"}, ou para um outro ator.

Posicione seus atores em seus pontos de partida e selecione o ator que vai deslizar:

![O Palco com ambos os atores, gato e bolo, em sua posição inicial.](images/example-start.png)

Arraste um bloco `deslize por (1) segs. até x: y:`{:class="block3motion"} para a área de Código, mas não o encaixe em nenhum outro bloco por enquanto. Este bloco tem as coordenadas do ponto inicial e será usado depois para fazer o ator voltar:

```blocks3
glide (1) secs to x: (-150) y:(-80) // seus números serão diferentes
```

Arraste um bloco `deslize por (1) segs. até (posição aleatória v)`{:class="block3motion"} para a área de Código e o encaixe no ponto em que você deseja que seu ator se mova.

Clique na lista de opções e selecione o nome do ator para o qual você deseja que seu ator `deslize`{:class="block3motion"}:

![A lista de opções do bloco "deslize" mostrando outros atores na lista.](images/glide-menu.png)

```blocks3
glide (1) secs to (Cake v)
```

![O Palco mostrando que o ator "gato" deslizou até o ator "bolo".](images/example-end.png)

Por fim, arraste para o seu programa o bloco `deslize por (1) segs. para x: y:`{:class="block3motion"}, que já está na área de Código, para que `deslize`{:class="block3motion"} de volta ao início:

```blocks3
glide (1) secs to (Cake v)
glide (1) secs to x: (-150) y:(-80)
```
