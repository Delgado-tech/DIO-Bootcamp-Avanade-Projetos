<span id="header"/>

<a href="https://github.com/Delgado-tech/dio-bootcamp-avanade-projetos">◀ Voltar</a>

<div align="center">

# Introdução ao .NET
> Foi aprendido os conceitos base da utilização da ferramente .NET para produzir aplicações do tipo console, também foi mostrado toda a sua trajetória e história de criação  
> ⏳ Duração: 7h

</div>

<div align="center">
  <img name="borda-divisora-cima" src="https://user-images.githubusercontent.com/60985347/144115785-57af7916-729a-4dc8-aa8b-4ec1e51e8dd1.png" width="30%"/>
</div>


<span id="summary">

# Sumário
> - **<a href="#topic1">O que é .NET?</a>**
> - **<a href="#topic2">Trajetória de criação</a>**
> - **<a href="#topic3">Funcionamento das linguagens dentro do .NET</a>**
> - **<a href="#topic4">Comandos .NET via CMD</a>**
>
> - **<a href="#footer">Rodapé</a>**


<div align="center">
  <img name="borda-divisora-baixo" src="https://user-images.githubusercontent.com/60985347/144116278-04e3380a-d516-4017-916c-62301948b09b.png" width="30%"/>
</div>

<br>

<span id="topic1"/>

## O que é .NET?
> <a href="#summary">#retornar ao sumário</a>

> É um framework que permite a comunicação entre várias linguagens que tem uma infraestrutura comum, entre elas o Visual Bascic, C++, F# e C#.
> 
> Uma aplicação .NET é desenvolvida para e roda em uma das seguintes implementações do .NET:
> - .NET Core
> - .NET Framework
> - Mono
> - Universal Windows Plataform (UWP)
>
> ![image](https://user-images.githubusercontent.com/60985347/148050890-7d99c4f8-81a2-495c-a1a6-469c29ff2b88.png)
>
> Cada implementação inclui um ou mais .NET Runtimes (ambiente de execução):
> - **.NET Core** - CoreCLR e CoreRT
> - **.NET Framework** - CLR
> - **Mono** - Mono Runtime
> - **UWP** - .NET Native

<br>

<div align="center">
  <img name="borda-divisora-baixo" src="https://user-images.githubusercontent.com/60985347/144116278-04e3380a-d516-4017-916c-62301948b09b.png" width="30%"/>
</div>


<span id="topic2"/>

## Trajetória .NET
> <a href="#summary">#retornar ao sumário</a>

> ## Anos 70
> Microsoft desenvolve linguagem de programação básica chamada **Basic.** (Nome muito criativo aliás)
> 
> ## Anos 80
> Microsoft firma uma parceria com a IBM uma das maiores produtoras de computadores da época, que procurava alguém que fornecesse um sistema operacional para seus computadores.
>
> ## 1997
> Microsoft consolida as ferramentas de desevolvimento, as IDE's e runtimes com o Visual Studio 97, tendo as linguagens: 
> - **Visual Basic 5**
> - **Visual FoxPro 5**
> - **C++ 5**
> - **J++ (Java)**
>
> ## 1999
> - Scott Guthrie cria uma ferramenta web com Java, e a chama de ASP+ (que logo depois mudou para ASP Next e depois ASPX)
> - Jason Zander ajuda na criação de um common language runtime (CLR) para Visual Basic e C++
>
> É firmado ainda nessa época um acordo entre a Microsoft e a Sun Microsystems, para ela não utilizar ou modificar mais a linguagem Java.
>
> Devido a esse acordo, Anders Hejlsberg começa a trabalhar no desenvolvimento da linguagem C# (Acreditasse que essa linguagem jamais existiria se não fosse firmado esse acordo com a Sun Microsystems).
>
> ## 2000
> É lançado um novo ambiente de desnvolvimento .NET 1.0 - que inicialmente era chamado de Next Generation Windows Services (NGWS)
>
> ## 2001
> Miguel de Icaza começa a trabalhar no projeto Mono, que é uma reimplementação BlackBox (gerenciador de janelas livre) do .NET, que seria open source e multiplataforma.
>
> ## 2002
> É lançado o Visual Studio .NET com C# 1.0, tendo 22 linguagens dentro de apenas uma plataforma, contendo:
> - **C#.net**
> - **C++.net**
> - **VB.net**
> - **J#.net**
> - **etc.**
>
> ## 2003
> É lançado .NET 1.1 com o Visual Studio 2003, trabalhando em melhorias na CLR para lançar a CLR 2
> 
> ## 2005
> É lançado .NET 2.0 com C# 2.0 no Visual Studio 2005, nesse ano a Microsoft começa a atingir seu objetivo inicial, e a evoluir na web.
>
> ## 2007 - 2008
> É lançado .NET 3.5 com C# 3.0 no Visual Studio 2008, com Silverlight (uma tecnologia nova na época), WPF (Windows Presentation Foundation) que é uma estrutura para criação de aplicações para computador e WCF (Windoes Communication Foundation) que é uma estrutura para criação de aplicações web.
>
> É contratado uma equipe de peso com uma pegada open source que começa a atuar na criação do ASP.NET MVC (Model View Controller)
> Nessa época começa a se falar de Windows Azure.
>
> ## 2010
> É lançado .NET 4.0 com C# 4.0 no Visual Studio 2010, também com F# (Uma linguagem mais focada em orientação a objetos). Microsoft lança também comercialmente Windows Azure.
> Nesse ano Anders Hejlsberg (criador do C#) começa a trabalhar no Typescript.
>
> ## 2011
> Miguel de Icaza criador do Mono, inicia o projeto Xamarin, que basicamente desenvolvia aplicativos C# que rodassem em Android e iOS.
> 
> ## 2012
> É lançado .NET 4.0 com C# 5.0 no Visual Studio 2012, temos também o lançamento do Typescript.
>
> ## 2013
> É lançado .NET 4.51 no Visual Studio 2013, temos também o início de Roslyn, um novo compilador para C# e VB.net.
>
> ## 2014
> Microsoft deixa de ser uma empresa focada em sistemas operacionais e passa a focar em cloud, devido a entrada do novo CEO Satya Nadella.
> 
> É criado o .NET Foundation para gestão de projetos open source.
> 
> O Windows Azure passa a se chamar Microsoft Azure, já que ele se torna um marketplace que não é focado apenas em Windows.
>
> É introduzido o conceito do ASP.NET vNext, posteriormente chamado de ASP.NET Core. Que ainda trabalhava com o CLR padrão, mas com a adição do Core CLR, que era mais focado para cloud.
>
> ![image](https://user-images.githubusercontent.com/60985347/148056075-e21f1d1d-a01d-4fd4-8fb1-f36997f4415f.png)
>
> ## 2015
> É lançado .NET 4.6 com C# 6.0 no Visual Studio 2015, também é lançado o Visual Studio Code que é multiplataforma.
>
> ## 2016
> Microsoft adquire a Xamarin e adiciona o produto como parte de sua stack .NET e projetos open source. E também temos o lançamento do Visual Studio for Mac.
>
> Temos também o lançamento da plataforma .NET Core 1.0 que é uma plataforma totalmente nova, reescrita do zero, sendo open source e multiplataforma.
>
> ![image](https://user-images.githubusercontent.com/60985347/148056474-36026f6e-389b-42ef-b14b-4f81630a43b9.png)
>
> ## 2017
> É lançado .NET Framework 4.7 com C# 7.0 no Visual Studio 2017, também é lançado .NET Core 2.0 com C# 7.0 no Visual Studio 2017, Visual Studio Code e Visual Studio for Mac 2017
>
> ## 2019
> É lançado .NET Framawork 4.8 com C# 7.3 no Visual Studio 2019. Temos também o lançamento do .NET Core 3.0 com C# 8.0 no Visual Studio 2019, Visual Studio Code e Visual Studio for Mac 2019.
>
> ## 2020
> .NET Framework é concluído na versão 4.8 e deixa de ser evoluído - junto com o WCF e ASP.NET Webforms exclusivos dele. Temos também o lançamento do .NET 5 (que antes era chamado de .NET Core) que junta tudo o que há de melhor no .NET Framework, .NET Core e no Mono Project.
>

<br>

<div align="center">
  <img name="borda-divisora-baixo" src="https://user-images.githubusercontent.com/60985347/144116278-04e3380a-d516-4017-916c-62301948b09b.png" width="30%"/>
</div>


<span id="topic3"/>

## Funcionamento das linguagens dentro do .NET
> <a href="#summary">#retornar ao sumário</a>

> Cada linguagem contida dentro do .NET, possui um compilador próprio, que compila essa linguagem para uma linguagem intermediária (Common Intermediate Language ou CIL) que será compilado por um CRL que irá traduzir essa linguagem intermediária para binário, ou seja, uma linguagem que o computador entenda.
>
> ![image](https://user-images.githubusercontent.com/60985347/148058199-a5ae85b2-98d2-4fda-bb1a-30e10fd9a097.png)
>
> Quando o programa C# é executado, o assembly é carregado no CLR. 
> Em seguida o CLR executará a compilação just in time (JIT) para converter o código IL em instruções de máquinas ativas.
>
> O CLR também fornece outros serviços como:
> - Garbage Collector – Coleta partes do código que não estão sendo utilizados e remove eles da memória.
> - Exception Handler – Recebe e controla as exceções do nosso código. 
> - Resources Manager - Um gerenciador de recursos que fornece acesso conveniente aos recursos específicos da cultura no tempo de execução.



<br>
<br>
<br>
<br>

<span id="footer"/>
  
> <div align="center"><a href="#header">Voltar ao topo</a></div>

  
<div align="center">
  <img name="borda-divisora-baixo" src="https://user-images.githubusercontent.com/60985347/144116278-04e3380a-d516-4017-916c-62301948b09b.png" width="30%"/>
</div>
