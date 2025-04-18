# CRIANDO UMA MÁQUINA VIRTUAL - DESAFIO DIO

Olá, tudo bem? Espero que sim. Gostaria de me apresentar. Meu nome é Carlos Eduardo, eu tenho 19 anos de idade e sou estudante universitário da faculdade impacta de tecnologia estou cursando sistemas de informação, eu não tenho experiência nenhuma no mercado de trabalho, pois até o momento, não tive muitas oportunidades de mostrar minhas habilidades e meus conhecimentos, por isso, estou fazendo os cursos lá na DIO, para tentar somar certificações, ganhar mais conhecimento e se possível uma oportunidade de estagiar, e espero que eu tenha feito o desafio certo, e também, espero que gostem dos meus esforços. Muito Obrigado!!! ☺️☺️☺️

_______________________________________________________________________________________________________________________________________________________________________________

### Criação de uma Máquina Virtual para o Desafio de Código do curso de XP Inc. - Cloud com Inteligência Artificial da DIO:
Existe 5 sessões respectivamente para configurar antes de se criar uma máquina virtual, dentre elas:

-Básico

-Gerenciamento

-Monitoramento

-Avançado

-Revisar + Criar

_______________________________________________________________________________________________________________________________________________________________________________
## BÁSICO 

1-PASSO: Fazer o Login com seu email e senha no Microsoft Azure.

2-PASSO: Clicar na opção Máquinas Virtuais que está localizada na barra lateral à esquerda, e escolher em qual tipo de S.O (Sistema Operacional) você desejar.

3-PASSO: Após clicar em Máquina Virtual, aparecerá diversas opções de configurações antes de você criar a VM, começaremos primeiro a configurar a aba "básico".

4-PASSO: Certo, aqui nós iremos configurar primeiro os detalhes da instância, na parte de assinatura eu prefiri não mexer, até porque eu to com a versão gratuita, o que limita algumas das minhas ações, a primeira configuração que precisamos fazer é criar um nome para sua VM, seja criativo.

5-PASSO: Logo após precisamos colocar uma região, você consegue escolher a região que quiser dentre as opções que o Azure lhe dá, eu optei por "(South America) Brazil South".

6-PASSO: Temos as opções de disponibilidade, vão aparecer 3 escolhas de disponibilidades, eu optei pela última "Conjunto de disponibilidade", por justamente ele distribuir nossas VMs automaticamente entre vários domínios de falha.

7-PASSO: Okay, eu sei, aqui já é mais um pouco complicado, logo abaixo em conjunto de disponibilidade, precisaremos criar um conjunto, ou seja, você irá clicar na opção de "criar novo" que se encontra bem abaixo do espaço em branco, quando apertado irá abrir uma barra lateral à direita, lá precisamos colocar um nome e configurar os dominios com falha e dominios com atualização, sinceramente por eu ser novo nesse assunto, eu só criei um nome, e deixei com as configurações padrões.

8-PASSO: Seguindo, temos a opção de segurança, eu optei escolhendo a segunda alternativa "Computadores virtuais de inicialização confiável", por ser mais seguro do que a opção "Padrão".

9-PASSO: Em imagem, aparecerá diversas opções para escolher, eu decidi deixar no padrão que apareceu pra mim, porém, existe diversas opções, caso queira alguma diferente e só apertar em "Ver todas as imagens", pois além de mostrar todas as possíveis imagens, ainda terá a descrição de cada uma delas, caso queira escolher alguma diferente do padrão.

10-PASSO: Na parte de arquitetura de VM, optei por deixar em padrão.

11-PASSO: Agora em tamanho, bom, como eu havia dito eu uso a versão gratuita então optei pelo tamanho mais simples para não consumir muito dos meus créditos, porém, eu recomendo que antes de tudo veja quanto de crédito tenha, ou caso você tenha a versão paga do Microsoft Azure, melhor ainda.

12-PASSO: Calma companheiro(a), estamos quase terminando, SÓ A PARTE BÁSICA AINDA 😔, brincadeiras à parte, seguindo temos que colocar nosso nome de usuário/host da VM e criar uma senha.

13-PASSO: Finalizando, temos que decidir se queremos as portas de entradas públicas ou não, eu optei pelas portas públicas e selecionei em específico a porta "HTTPS(443)", que pra quem não sabe muito, o HTTPS (Protocolo de Transferência de Hipertexto Seguro) é a versão segura do HTTP, utilizado para enviar dados entre um navegador e um site. Ele é criptografado para aumentar a segurança da transferência de dados, protegendo informações confidenciais. O HTTPS é amplamente utilizado na internet para garantir a segurança na troca de dados entre o navegador do usuário e o servidor web, e assim, encerramos a sessão básica.
_______________________________________________________________________________________________________________________________________________________________________________
## GERENCIAMENTO
1-PASSO: 
