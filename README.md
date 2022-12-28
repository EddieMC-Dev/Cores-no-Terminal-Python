# Cores-no-Terminal-Python
Aqui falaremos sobre como colocar cores nas informações que aparecem no terminal, 
proponho o uso do padrão ANSI de cores. Mas nas bibliografias vocês terão informações extras
mostrando outra forma de exibir cores através de biblioteca, o que não é o intuito desse repositório.
<hr>
<h2> Tabelas de cores: </h2>
<h3>CORES DE FONTE:</h3>
- 033[30m -> preto <br>
- 033[31m -> vermelho <br>
- 033[32m -> verde <br>
- 033[33m -> amarelo <br>
- 033[34m -> azul <br>
- 033[35m -> magenta <br>
- 033[36m -> cyan <br>
- 033[37m -> cinza claro <br>
- 033[90m -> cinza escuro <br>
- 033[91m -> vermelho claro <br>
- 033[92m -> verde claro <br>
- 033[93m -> amarelo claro <br>
- 033[94m -> azul claro <br>
- 033[95m -> magenta claro <br>
- 033[96m -> cyan claro <br>
- 033[97m -> branco <br>

<h3>CORES DE FUNDO: </h3>
- 033[40m  -> preto<br>
- 033[41m  -> vermelho<br>
- 033[42m  -> verde<br>
- 033[43m  -> amarelo<br>
- 033[44m  -> azul<br>
- 033[45m  -> magenta<br>
- 033[46m  -> cyan<br>
- 033[47m  -> cinza claro<br>
- 033[100m -> cinza escuro<br>
- 033[101m -> vermelho claro<br>
- 033[102m -> verde claro<br>
- 033[103m -> amarelo claro<br>
- 033[104m -> azul claro<br>
- 033[105m -> magenta claro<br>
- 033[106m -> cyan claro<br>
- 033[107m -> branco<br>

<hr>
<h2>Como usá-las?</h2>
<h3> Fonte: </h3>
>>> print("<a href="">\033[32m</a>Helloworld!")
<h4>Resultado:</h4>
<img src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste1.PNG"> 

<h3> Fundo: </h3>
>>> print("<a href="">\033[42m</a>Helloworld!")
<h4>Resultado:</h4>
<img src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste2.PNG">
<h3> Fonte + Fundo: </h3>
>>> print("<a href="">\033[31;42m</a>Helloworld!")
<h4>Resultado:</h4>
<img src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste3.PNG">
<h3> Como remover ambos: </h3>
>>> print("<a href="">\033[31;42m</a>Helloworld!<a href="">\033[m</a>")<br>
>>> print("Nice!")
<h4>Resultado:</h4>
<img src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste4.PNG">
<h3> Como remover separado: </h3>
Removendo a fonte:<br><br>
>>> print("<a href="">\033[31;42m</a>Helloworld!<a href="">\033[0;42m</a>")<br>
>>> print("GOOD!!!")<br><br>
<h4>Resultado:</h4>
<img src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste5.PNG">
Removendo o fundo: <br><br>
>>> print("<a href="">\033[31;42m</a>Helloworld!<a href="">\033[0;31m</a>")<br>
>>> print("Good!!!")<br>
<h4>Resultado:</h4>
<imc src="https://raw.githubusercontent.com/EddieMC-Dev/Cores-no-Terminal-Python/main/teste6.PNG">

<hr>
<h2> Para saber mais, acesse as bibliografias: </h2>
- Tabelas: https://raccoon.ninja/pt/dev-pt/tabela-de-cores-ansi-python/ <br>
- Tutorial de uso: https://www.youtube.com/watch?v=0hBIhkcA8O8 <br>
- Informações extras: https://www.geeksforgeeks.org/print-colors-python-terminal/
