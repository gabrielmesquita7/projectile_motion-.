<h1 align="center">Projectile Motion</h1>
<p style align="center">
  <a href="#formulas">Formulas</a> -
  <a href="#bibliotecas">Bibliotecas</a> -
  <a href="#executar">Executar</a> 
</p>

# Formulas
Para o caso do lançamento oblíquo, a velocidade considerada na vertical será a componente Vy, sendo assim, podemos escrever:

img do site

O tempo destacado acima refere-se à subida do objeto, logo, o tempo total do movimento será o dobro.

img

A equação final para a determinação do alcance horizontal em um lançamento oblíquo é:

img

O alcance será o máximo possível quando o ângulo de lançamento for igual a 45°. Como o ângulo é multiplicado por dois na equação do alcance, o seno calculado será o de 90°, que corresponde ao máximo valor de seno possível, assim o alcance será o máximo possível.

A imagem abaixo indica as possíveis trajetórias para lançamentos oblíquos executados sobre ângulos diversos. Observe que o maior alcance ocorre quando o ângulo de lançamento é igual a 45º.

img do site

A equação abaixo determina a altura máxima atingida por um objeto que executa movimento oblíquo.

img




# Bibliotecas 
+ Foi utilizado a biblioteca **tkinter** para a criação de toda a interface gráfica.
+ Foi utilizado a bibliteca **numpy** para a resolução dos cálculos.
+ Foi utilizado a biblioteca **matplotlib** para plotar o grafico e gerar a animação.
# Executar
|   Comando   |    Função  |    
| -----------------------|-----------------------|
|    *sudo apt install python3-pip*     |     instala o pip para facilitar na hora de instalar as bibliotecas  |   
|     *pip install tk*     |   instala a biblioteca tkinter    |      
|     *pip install numpy*     |    instala a biblioteca numpy    |      
|*pip install matplotlib* | instala a biblioteca matplotlib
| *python3 main.py*| executa o programa