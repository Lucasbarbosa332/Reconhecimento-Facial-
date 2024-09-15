# Reconhecimento-Facial-

 # Facial 📷 

#  Windows & Linux 'beta':

Este é um programa em Python que utiliza a biblioteca de reconhecimento facial "face recognition". Ele permite adicionar fotos para que sejam detectadas pela câmera, excluir registros de pessoas e ativar o modo scanner, que apresenta o nome da pessoa ao entrar em frente à câmera. O programa pode ser utilizado para fins de segurança ou controle de acesso, caso seja adaptado corretamente.

# como Baixar ⬇️
Para esse código, você precisa baixar algumas coisas obrigatórias que as bibliotecas pedem:
📢 "Para o Linux, você deve baixar todas as dependências que serão mostradas abaixo, exceto a instrução do "Visual Studio". E lembre-se de que o método de instalação no Linux de cada etapa pode ser diferente da maneira feita no Windows. Qualquer dúvida, consulte o ChatGPT, e se não conseguir, entre em contato."

Vá à loja da Microsoft e baixe a versão mais recente do Python disponível. Caso queira usar a mesma versão utilizada neste código, basta acessar este link: "Py-3.11".

Segundo passo, baixe esse programa: "Visual Studio". Ao executá-lo, ele abrirá uma página de download. Nessa página, selecione a opção "Desenvolvimento para desktop com C++", que geralmente é a primeira opção, e clique em instalar.

Terceiro passo, você precisa baixar este programa: "CMake". Durante a instalação, é importante marcar a opção "Add CMake to the system PATH for all users" para evitar problemas. Após isso, você pode continuar o download do programa. Aviso: assim que o programa for baixado, é importante abri-lo pelo menos uma vez e, em seguida, você pode fechá-lo. Baixe o arquivo correspondente ao seu sistema operacional e certifique-se de instalar a versão do programa "Installer". Por exemplo, se você estiver usando o Windows, baixe o instalador para Windows x64.

Após fazer os últimos passos, recomendo reiniciar o PC. Para fazer essa etapa, abra seu CMD e execute o seguinte comando: pip install dlib && pip install face_recognition && pip install numpy && pip install opencv-python

Após seguir todas essas etapas, você pode abrir o arquivo do programa "Face Safety.py".

"Caso ocorra algum erro, pode ser um problema isolado relacionado ao seu sistema atual. Em caso de dúvidas, entre em contato pelo 'ctt no perfil'."

<img src="https://github.com/Lucasbarbosa332/Reconhecimento-Facial-/blob/main/Indentificador%20facial/facial/Fotos/4.5-ADMs.jpg?raw=true" width="70%" alt="Clothing GIF">

# Função KEY 🗝️

Pode ser personalizado...
Essa parte é apenas para aqueles que irão usar o código para gerenciar algo, como portas eletrônicas, sistemas de monitoramento, entre outros. Também haverá suporte para o Raspberry Pi. Nestas duas abas, você pode adicionar uma pessoa como administradora. Sendo assim, no final do código haverá um "Def Key". Quando uma pessoa entrar na frente da câmera e o nome dela estiver na lista de administradores, ela irá chamar essa função e executará o que estiver dentro dela "em loop". Caso contrário, se uma pessoa sem poderes administrativos ou alguém que não esteja cadastrado ficar na frente da câmera, ela não será chamada. Dessa forma, quem for utilizar este código pode realizar uma ação, como destrancar ou trancar uma porta, por exemplo, por meio desta variável. Lembrando que dentro dessa função ela pode ser totalmente personalizada caso você tenha conhecimento do que esteja fazendo.
