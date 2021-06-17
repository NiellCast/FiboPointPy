<h1>Script feito em PYTHON para calcular o indicador "Ponto de Pivot" utilizando Fibonacci no mercado de ações brasileiro.</h1>
  
  
  <h2>Informações ⚠️</h2>
  
  <li>Script feito inicialmente para DayTrade.
  <li>Use por sua conta e risco. Não me responsabilizo por possíveis perdas financeiras.
  <li>Este script não funciona para o mercado fracionário.
  <li>Necessário ter a linguagem Python instalada no dispositivo.
  <li>Necessário ter o pacote "Investpy" instalado.
  <li>Script inspirado no método "LeandroStormer" para o indicador Pivot Point.
  <li>Para escolher o timeframe em que o indicador vai ser calculado basta inserir "D" para o gráfico diário e "S" para o semanal.</li>
  
  <h2>Como Usar ▶️</h2>
  
<pre><code>pip install -r requirements.txt</code></pre>

<p>E então:</p>

<pre><code>python FPP.py</code></pre>

<p>Ou...</p>

<pre><code>from FiboPoint import FiboPoint

iniciar = FiboPoint('BBAS3', 'S')
print(iniciar.calculo())</code></pre>

<P>Será retornado um dicionário com os preços de suporte 1, 2 e 3. Resistência 1, 2 e 3 e Ponto de Pivot.</P>
