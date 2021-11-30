<div align="center">

# Git & GitHub
> Foi aprendido os conceitos base do funcionamento da ferramenta Git e do repositório remoto GitHub  
> ⏳ Duração: 7h

</div>

<div align="center">
  <img name="borda-divisora-cima" src="https://user-images.githubusercontent.com/60985347/144115785-57af7916-729a-4dc8-aa8b-4ec1e51e8dd1.png" width="30%"/>
</div>

<br>

## Conceitos
> ### Git
> É um software criado por Linus Torvalds (mesmo criador e desenvolvedor do sistema operacional Linux) e sua equipe de desenvolvedores, que baseia-se em um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, podendo ser utilizado para registrar o histórico de edições de qualquer tipo de arquivo.
>
> ### GitHub
> É um repositório remoto onde você pode armazenar seus repositórios, funcionando também como uma grande Rede Social para divulgar seus projetos, servindo como um portifólio para recrutadores verem.
>
> #
>
> ### GUI x CLI
> - **Graphic User Interface** - São programas que disponibilizam de uma interface gráfica permitindo você interagir com o software.
> - **Command Line Interface** - São programas que disponibilizam apenas de linhas de comando para você interagir com o software (ex: Terminal do Windows, Linus, MacOS, etc.).
>
> O Git possui os dois tipos de interfaces, sendo mais comum utilizado o tipo de interface **CLI**.
>
> #
>
> ### SHA1
> **Secure Hash Algorithm**, é um algoritimo de encripitação Hash, onde ele utilizará da encriptação hash para embaralhar de uma forma específica os dados presentes do objeto, com o intuito de proteger as informações contidas no arquivo criptografado.
> A encriptação irá gerar uma chave de 40 digítos única, que servirá como o identificador daquele arquivo.
> 
> ![image](https://user-images.githubusercontent.com/60985347/144118860-f4d8f448-a221-47c3-8664-1a8aa502a0ed.png)
>
> **GitBash** <br>
> `$ Openssl sha1 file.extension` - gerá uma chave criptografada do arquivo informado
>
> #
>
> ### Tipos de armazenamento do Git
> Existem 3 níveis de armazenamento no Git, sendo eles Blob, Tree e Commit
>
> - **Blob** -
> É uma função que contém metadados do Git, armazenando dentro dele o tipo do objeto, o tamanho dele, o conteúdo dele, etc., tento um **sha1** próprio como códificação. Ilustrando seria como a representação do conteúdo de um arquivo.
>
> - **Tree** -
> Armazena os metadados tanto de blobs como de outras trees, também possue seu **sha1** próprio que é alterado quando algum objeto dentro dela é mudado, seja um blob ou outra tree, ela armazena o sha1 dos blobs, de outras trees, incluindo o nome do arquivo/objeto referente à elas. Ilustrando seria como a representação das pastas e arquivos de um diretório.
>  
> - **Commit** -
> Ele é responsável por fazer a junção dos metadados, das trees, blobs, etc., contendo também a informação **parent** que remete ao último commit registrado, a informação **autor** remetendo á quem fez esse commit, possuí uma timestamp e também um próprio sha1 de identificador que é alterado caso qualquer tree ou blob dentro dele seja alterado.
> 
> ![image](https://user-images.githubusercontent.com/60985347/144123692-edf8b23a-6a3c-4c3d-b9c7-969d037dd40e.png)
>
> #
>
> ### Chave SSH (Secure Shell)
> É um protocolo que permite a conexão com servidores remotos, de forma criptografada e mais segura, usando um par de **chaves RSA**.
> > #
> > **Chave RSA (Rivest-Shamir-Adleman)** - É um dos primeiros sistemas de criptografia de chave pública e é amplamente utilizado para transmissão segura de dados. Neste sistema de criptografia, a chave de encriptação é pública e é diferente da chave de decriptação que é secreta (privada).
> > #
> Podemos criar uma chave SSH pelo GitBash pelo comando:
> 

<div align="center">
  <img name="borda-divisora-baixo" src="https://user-images.githubusercontent.com/60985347/144116278-04e3380a-d516-4017-916c-62301948b09b.png" width="30%"/>
</div>
