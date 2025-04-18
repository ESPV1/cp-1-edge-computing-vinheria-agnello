<h1 align="center"> Vinheria Agnello 🍷 -- Monitoramento de Luminosidade 💡</h1>
A Vinheria Agnello é uma empresa familiar, dirigida pelo proprietário Giulio e sua filha Bianca, que atua há mais de 15 anos com apenas uma loja física, que emprega mais 6 funcionários, entre a administração, estoques e vendas.  


## 🔴 Problema
Uma das particularidades relevantes dos vinhos é o risco de sua degradação, ou ao menos alteração de suas características de coloração, aromas e sabor, caso sejam mal armazenados, ***expostos por muito tempo à luz natural, temperaturas altas, ou mesmo quando expostos a vibrações ou movimentações constantes***.  Conhecedora desses riscos, a Vinheria Agnello adota cuidados especiais na armazenagem de seus vinhos, em especial com os vinhos de maior valor e vinhos raros, buscando assim garantir a seus clientes mais exigentes a qualidade original de cada garrafa, como recebida de seus fornecedores ou mesmo das vinícolas de origem.

## 💡 Solução
Nesta primeira etapa da solução, será desenvolvido um sistema que possa captar a luminosidade do ambiente para criar condições adequadas de armazenamento. Para que isto possa ser informado aos responsáveis pelo estoque, teremos um indicador de LED que informará qual a condição de luminosidade ambiente que o produto se encontra. Além dos LEDs para auxiliar no diagnóstico, teremos também uma buzina que irá informar no caso de a luminosidade do ambiente estar completamente fora das condições ideais.

## 🛠️ Detalhes Tecnicos
Para poder captar e tratar dados sobre a luminosidade, iremos utilizar um componente chamado LDR (Light Dependent Resistor), cujo princípio de funcionamento é alterar a condutividade quando há presença ou ausência de luz. Isto, junto a resistores, pode ser aplicado para criar condições específicas. O funcionamento técnico do LDR pode ser analisado da seguinte forma: mais luminosidade gera menos resistência e maior a corrente, por outro lado, quanto menos luminosidade, maior a resistência e menor a corrente.

O diagnóstico será feito da seguinte forma: 
- 🟢 LED Verde -> Em caso de a luminosidade ambiente seja adequada para o produto.
- 🟡 LED Amarelo -> Em caso de luminosidade não adequada, gerando um som de buzina por 3 segundos e continua em caso de ainda estar nessa condição de alerta.
- 🔴 LED Vermelho -> Indica caso exista algum problema.

## 🧭 Material
- 01 Arduino UNO = Para controlar o sistema
- 01 Breadboard = para montagem do circuito
- Cabos Jumper = Para realizar as conexões na breadboard
- 04 Resistores = 3 para os LED e 01 para o LDR
- 01 LED Verde 🟢 = Para indicar que está tudo OK
- 01 LED Amarelo 🟡 = Para indicar ALERTA
- 01 LED Vermelho 🔴 = Para indicar PROBLEMA
- 01 Buzzer 🔈 = Tem que ser ativado quando LED amarelo (ALERTA) estiver aceso
- 01 LDR = Sensor para medir a luminosidade do ambiente

## 🔗Como acessar o projeto
Para acessar o diagrama do projeto [clique aqui](https://www.tinkercad.com/things/gb3a7xdKSyy/editel?returnTo=%2Fdashboard&sharecode=m3Z69XnJ7JPIrK6wyWeotM_hYOcPNgquUM6DGji93v0)

## 🧰 Tecnologias utilizadas
- Software de Repósitorio Remoto: GitHub
- Software Simulador de Circuito: TinkerCard
- Linguagem de Programação: C

## 🧑‍💻 Equipe
<table>
  <tr><th><span>Integrantes</span></th><th><span>Tarefas</span></th></tr>
  <tr>
    <td align = "center">
      <img src="https://avatars.githubusercontent.com/u/73716198?v=4" width="100px" alt= "Adrian de Souza Profile Image" /><p><a href = "https://github.com/AdrianSouz">Adrian de Souza</a></p><span><b>RM:562959</b></span>
    </td>
    <td>
      <ul>
        <li>Código do LDR</li>
        <li>Revisão e otimização do código</li>
      </ul>
    </td>
  </tr>
    <tr>
    <td align = "center">
      <img src="https://avatars.githubusercontent.com/u/202196268?v=4" width="100px" alt= "Camila Martins Profile Image"/><p><a href = "https://github.com/dev-camila">Camila Martins</a></p><span><b>RM:561492</b></span>
    </td>
    <td>
      <ul>
        <li>Separar os materiais necessarios e código de declaração</li>
        <li>Código dos Leds</li>
      </ul>
    </td>
  </tr>
    <tr>
    <td align = "center">
      <img src="https://avatars.githubusercontent.com/u/80047823?v=4" width="100px" alt= "Gabriel Amara Profile Image"/><p><a href = "https://github.com/gabrielamara98">Gabriel Amara</a></p><span><b>RM:561403</b></span>
    </td>
    <td>
      <ul>
        <li>Gestão do README e repositório</li>
        <li>Pitch</li>
        <li>Código da Buzina</li>
      </ul>
    </td>
  </tr>
    <tr>
    <td align = "center">
      <img src="https://avatars.githubusercontent.com/u/35637366?v=4" width="100px" alt= "Luara(Lise) Profile Image"/><p><a href = "https://github.com/luararamos">Luara Ramos</a></p><span><b>RM:565573</b></span>
    </td>
    <td>
      <ul>
        <li>Código dos Leds</li>
        <li>Código da Buzina</li>
      </ul>
    </td>
  </tr>
    <tr>
    <td align = "center">
      <img src="https://avatars.githubusercontent.com/u/101485201?v=4" width="100px" alt= "Pedro Lucas Profile Image"/><p><a href = "https://github.com/pedroviscz">Pedro Lucas Almeida</a></p><span><b>RM:566256</b></span>
    </td>
    <td>
      <ul>
        <li>Montar a protoboard e Arduino</li>
        <li>Código do LDR</li>
      </ul>
    </td>
  </tr>
</table>

## 📓 Notas:
Projeto: Case-Vinheria Agnello

Repositório que servirá como 1º Checkpoint da disciplina de Edge Computing da FIAP

Professor avaliador: Lucas Demetrius Augusto
