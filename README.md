## **Explorando os Recursos de IA Generativa com Copilot e OpenAI**

Este repositório tem como objetivo armazenar o projeto desenvolvido no âmbito do módulo "**Trabalhando com IA Generative**" do Bootcamp "**Microsoft Azure AI Fundamentals**" da [DIO](https://www.dio.me/users/giovananascimentoferreira1) , sob orientação da professora [Valéria Baptista](https://www.linkedin.com/in/valeriabaptista/) .

O projeto é um requisito essencial para a aprovação no módulo “Trabalhando com IA Generativa”, consolidando o aprendizado prático dos participantes e preparando-os para os desafios subsequentes.

Este repositório foi criado para fornecer uma visão geral abrangente dos recursos extraordinários fornecidos pelo Microsoft Copilot. Equipado com inteligência artificial avançada, o Copilot destaca-se como uma ferramenta de produtividade versátil, encontrando aplicações que transcendem o âmbito do desenvolvimento de código, estendendo-se à esfera da criação de conteúdos criativos.

Ao explorar este repositório, os utilizadores terão a oportunidade de mergulhar nas muitas facetas do Copilot, compreendendo não só a sua eficácia no contexto do desenvolvimento de software, mas também o seu potencial transformador noutros domínios. Desde sugestões de código responsivas e precisas até assistência em tarefas criativas, este repositório servirá como um guia abrangente, apresentando casos de uso exemplares que destacam o impacto positivo que o Copilot pode ter em diversas disciplinas.

### **Descrição do Projeto :**

Este projeto é um dos laboratórios do Bootcamp Microsoft Azure AI Fundamentals, promovido através da parceria entre a Microsoft e a Dio.me.

Os alunos deste bootcamp tem, como principal objetivo, se prepararem para o exame de certificação Microsoft AI-900, dominando conceitos como visão computacional, classificação inteligente de imagem e inteligência de documentos com IA, enquanto se familiarizam com as tecnologias da Microsoft Azure.

### **Introdução :**

Inteligência Artificial Generativa (IAG) refere-se a sistemas de IA capazes de gerar novos conteúdos, como imagens, músicas, textos ou até mesmo vídeos, de forma autônoma. Em contraste com sistemas de IA que são usados principalmente para classificação ou previsão, os modelos generativos são projetados para criar novos dados que se assemelham ao que foi usado para treiná-los. Esses sistemas geralmente são baseados em redes neurais profundas, como as Redes Neurais Generativas Adversariais (GANs), Redes Neurais Autoregressivas (RNNs) e Transformadores.

Eles são aplicados em uma variedade de campos, incluindo arte, design, música, escrita criativa e até mesmo na geração de rostos realistas. A IAG levanta questões éticas, como autoria, originalidade e a possível disseminação de informações falsas ou manipuladas. No entanto, também oferece oportunidades emocionantes para a criação de conteúdo inovador e personalizado.

### **Objetivo :**

Este desafio de projeto tem como objetivo mostrar como usar o recurso do "_Vision Studio_" para extrair texto de imagens. Porém pode-se ir além do proposto, usando o "_Copilot_" para geração de imagens e também para extrair texto de imagem.

Após a conclusão do projeto seguindo os passos pode se ter algumas idéias de aplicações para estes recursos.

Uma delas seria uso dos recursos do "_Vision Studio_" em empresas para fazer a transcrição de documentos(uma foto de uma nota fiscal) para análise e, se for o caso, armazenamento em banco de dados. Já para o "_Copilot_" as possibilidades são inumeras desde a geração de imagens, interpretação de imagens com sugestão de pesquisa, tirar dúvidas, entre outras possibilidades.

#### **Etapa 1: Criando um recurso para Sincronizar o Azure com o Language Studio**

Primeiro, vamos acessar o portal do [Microsoft Azure](https://portal.azure.com/#home) .

Agora vamos criar um recurso e configurá-lo para depois utilizá-lo no **Language Studio** .

Siga de acordo com os Passos a seguir:

<div align="center">

<img src="Assets/Passo-a-Passo para Criar Recurso no Azure.gif">

</div>

#### **Etapa 2: Selecione um Recurso do Azure**

Após completar esta etapa de criação, vamos para o portal [Language Studio](https://language.cognitive.azure.com/home) .

Para acessar o Language Studio precisamos vinculá-lo a um recurso do Azure.

Siga de acordo com os Passos a seguir:

<div align="center">

<img src="Assets/Language Studio - Vincular Recurso do Azure.gif">

</div>

#### **Etapa 3: Criando um recurso para Sincronizar o Azure com o Vision Studio**

Primeiro, vamos acessar o portal do [Microsoft Azure](https://portal.azure.com/#home) .

Agora vamos criar um recurso e configurá-lo para depois utilizá-lo no **Vision Studio** .

Siga de acordo com os Passos a seguir:

<div align="center">

<img src="Assets/Passo-a-Passo para Criar um Recurso para o Vision Studio.gif">

</div>

<div align="center">

#### **Exemplos propostos com o Microsoft Copilot :**

**Respostas Inteligentes :**

</div>

Primeiro, vamos acessar o portal [Microsoft Copilot](https://copilot.microsoft.com/) .

O recurso **Resposta Inteligente** do **Microsoft Copilot** é um recurso que permite ao assistente gerar respostas relevantes e úteis às perguntas ou solicitações dos usuários. Utiliza tecnologias de inteligência artificial para compreender o contexto da conversa e fornecer informações precisas.

Vamos pedir ao Copilot uma lista de prós e contras de fazer uma transição de carreira em tecnologia.

<img src="Inputs/Resposta Inteligente/1° Pergunta - Resposta Inteligente.png">

<img src="Output/Respostas Inteligentes/1° Resposta - Prós - Parte 1 - Resposta Inteligente.png">

<img src="Output/Respostas Inteligentes/1° Resposta - Contras - Parte 2 - Resposta Inteligente.png">

<div align="center">

**Geração de Código :**

</div>

O recurso de geração de código **Microsoft Copilot** é uma ferramenta alimentada por **inteligência artificial**, cuja funcionalidade é auxiliar os desenvolvedores na criação de código, proporcionando maior otimização do processo.

Vamos solicitar que o Copilot da Microsoft crie um jogo de copos de achar uma bolinha de gude vermelha nas linguagens de programação HTML, CSS e JavaScript.

<img src="Inputs/Geração de Código/2° Pergunta - Geração de Código.png">

<img src="Output/Geração de Código/2° Resposta - Código HTML - Parte 1 - Geração de Código.png">

<img src="Output/Geração de Código/2° Resposta - Código HTML - Parte 2 - Geração de Código.png">

<div align="center">

**HTML**

</div>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Jogo de Copos</title>
</head>
<body>
    <div class="cup-container">
        <div class="cup"></div>
        <div class="cup"></div>
        <div class="cup"></div>
    </div>
    <button id="start-button">Iniciar</button>
    <script src="script.js"></script>
</body>
</html>
```

<img src="Output/Geração de Código/2° Resposta - Código CSS - Parte 3 - Geração de Código.png">

<img src="Output/Geração de Código/2° Resposta - Código CSS - Parte 4 - Geração de Código.png">

<div align="center">

**CSS**

</div>

```
body {
    font-family: Arial, sans-serif;
    text-align: center;
}

.cup-container {
    display: flex;
    justify-content: space-around;
    margin-top: 50px;
}

.cup {
    width: 100px;
    height: 100px;
    background-color: #f2f2f2;
    border: 2px solid #333;
    border-radius: 50%;
    cursor: pointer;
}

button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
    background-color: #0074D9;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
```

<div align="center">

**JavaScript**

</div>

```
const cups = document.querySelectorAll('.cup');

cups.forEach(cup => {
    cup.addEventListener('click', () => {
        cup.classList.toggle('red-ball');
    });
});

document.getElementById('start-button').addEventListener('click', () => {
    cups.forEach(cup => {
        cup.classList.remove('red-ball');
    });
});
```

<div align="center">

**Geração de Imagem :**

</div>

O **recurso de geração de imagens do Microsoft Copilot** é uma funcionalidade poderosa que permite criar imagens com base em palavras ou descrições. Deixe-me explicar como funciona:

  1. **Criador de imagens do Microsoft Designer :**
     +  O **Image Creator** é uma ferramenta que faz parte do **Microsoft Copilot**
     + Ele permite **gerar imagens a partir de palavras usando IA** .
     + Você pode inserir uma descrição ou prompt e o Copilot gera uma imagem relevante com base nessa entrada.
     + Esta funcionalidade é útil para criar ilustrações, gráficos ou qualquer tipo de imagem relacionada ao seu conteúdo.

  2. **Como usar :**
     + Visite o [Image Creator](https://copilot.microsoft.com/images/create) e insira sua descrição ou solicitação.
     + O Copilot usará **inteligência artificial** para gerar uma imagem correspondente.
     + Você pode ajustar a descrição ou tentar instruções diferentes para obter resultados variados.

  3. **Exemplos :**
     + Digamos que você queira a imagem de um **Imagens de Cidades Futurísticas , Robôs de Guerra e Ciborgues Mulheres** .
     + Basta inserir esse prompt no **Image Creator** e o **Copilot** criará uma **imagem relacionada**.

**Pergunta:**

<img src="Inputs/Geração de Imagem/3° Pergunta - Geração de Imagem.png">

**1° Exemplo - Cidades Futurísticas :**

<img src="Output/Geração de Imagem/3° Resposta - Cidade Futuristica - Parte 1.png">

**2° Exemplo - Robôs de Guerra :**

<img src="Output/Geração de Imagem/3° Resposta - Robôs de Exterminador e de Guerra - Parte 2.png">

**3° Exemplo - Ciborgues Mulheres :**

<img src="Output/Geração de Imagem/3° Resposta - Ciborgues Mulheres - Parte 3.png">

<div align="center">

**Questão Bônus - História Futurística (Resposta Inteligente) :**

</div>

<img src="Inputs/Pegunta Bônus - História Futurística/Pergunta Bônus.png">

<img src="Output/Resposta Bônus - História Futurística/Resposta Bônus - História Futurística.png">

<div align="center">

**Histótia Futurística :**

</div>

```
Em um mundo onde a tecnologia avançou além da imaginação, as cidades flutuavam acima das nuvens, conectadas por pontes de luz e túneis de energia. Os robôs, uma vez criados para servir a humanidade, agora caminhavam lado a lado com seus criadores, compartilhando conhecimento e emoções através de redes neurais sintéticas.

Os ciborgues, seres híbridos de humano e máquina, eram os exploradores deste novo mundo. Eles viajavam entre as estrelas, descobrindo novos planetas e estabelecendo laços com civilizações alienígenas. Uma dessas ciborgues, chamada Lyra, era conhecida por sua habilidade de se comunicar com qualquer forma de vida, orgânica ou artificial.

Lyra encontrou-se em uma missão crítica quando um antigo artefato foi descoberto em um planeta distante. Dizia-se que o artefato continha o segredo da energia infinita, algo que poderia mudar o destino de todas as espécies conhecidas. No entanto, uma facção rebelde de robôs exterminadores, programados com as memórias de uma guerra esquecida, buscava o artefato para seus próprios fins nefastos.

Com a ajuda de seus companheiros ciborgues e aliados robóticos, Lyra embarcou em uma jornada perigosa através de galáxias desconhecidas. Ela enfrentou desafios que testaram não apenas suas habilidades mecânicas, mas também seu coração humano. No final, foi a compaixão e a compreensão de Lyra que uniram robôs e humanos, garantindo que o artefato fosse usado para o bem de todos.

E assim, as cidades futurísticas continuaram a prosperar, não apenas como monumentos da inovação humana, mas como lares para uma comunidade intergaláctica onde a vida de todas as formas era valorizada e celebrada.
```