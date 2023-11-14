# SuperMario Docker na Nuvem
Criando um container que roda uma imagem do Super Mario, hospedado na nuvem, e acessando via browser

<br>

# Passo 1 - Start

Acesse o site Play With Docker, aperte em Start e inicie uma maquina

<img  alt="Windows" src="https://raw.githubusercontent.com/ksilva-kwn/SuperMario_Docker_Nuvem/main/supermario-images-print/Captura%20de%20tela%202023-11-13%20212250.png">

<br>

# Passo 2 - Adicione uma instância de máquina

Clique em Add New Instance na parte esquerda, e em seguida irá aparecer o terminar em sua tela, nesta máquina ja estará rodando o docker, então é so inserir os códigos e rodar o container.

<img  alt="Windows" src="https://raw.githubusercontent.com/ksilva-kwn/SuperMario_Docker_Nuvem/main/supermario-images-print/Captura%20de%20tela%202023-11-13%20212914.png">

<br>

# Passo 3 - Execute o código

Em seguida execute o seguinte comando no terminal

```

docker container run -it -p 8080:8080 pengbai/docker-supermario

```

Logo o download da imagem irá iniciar e rodar o container. Depois que o download ser completado, clique neste botão e acesse o container pelo navegador.

<img src="https://raw.githubusercontent.com/ksilva-kwn/SuperMario_Docker_Nuvem/main/supermario-images-print/Captura%20de%20tela%202023-11-13%20213920.png">
<br>

Após isso o jogo logo irá começar e é so se divertir, o site do docker Playground lhe dará 4 horas para poder usar o site, então da pra fazer vários testes e estudos de graça.

##

 <div align="center" valign="top">

### Video do jogo rodando
<img src="https://github.com/ksilva-kwn/SuperMario_Docker_Nuvem/blob/main/supermario-images-print/video-mario.gif" width="800" height="400"><br>
 <i>A magical universe can be born from small ideas! ⭐️</i> <br> <br>
</div>
