**1 - Qual técnica de regressão linear você usaria se tivesse um conjunto de treinamento com milhares de features? Explique por quais razões você utilizaria esta técnica.**

R: Com milhares de features usaria o gradiente descendente estocástico ou o gradiente descendente mini-batch. Poderia também usar o batch por gradiente descendente, onde o único impecilho seria a memória. No entanto, com milhares de features o uso da equação normal é inviável pois esta tem uma complexidade computacional que varia de O(n^2.4) a O(n^3), o que significa que sempre que o nº de features dobra, o tempo de cálculo aumenta de 5.3 a 8 vezes).

**2. Suponha que as features (i.e., atributos) do seu conjunto de treinamento tenham escalas muito diferentes. Qual técnica de regressão linear pode sofrer com isso e como? O que pode ser feito para mitigar este problema?**

R: Com features de conjuntos de treinamento com escalas muito diferentes os algoritmos que usam o erro quadrático médio como métrica de erro (caso dos algoritmos de gradiente descendente), assumirão que as features com escala maior têm muito mais importância. Consequentemente, poderão levar muito mais tempo para convergir. Para solucionar esse problema devemos escalonar o conjunto de treinamento antes de treinar o modelo.

**3. Suponha que você use o gradiente descendente em batelada e plote o erro de cada época. Se você perceber que o erro aumenta constantemente, o que provavelmente está acontecendo? Como você pode consertar isso?**

R: Se usamos o gradiente descendente em batelada e plotando o erro a cada época o erro aumenta constantemente, é provável que a taxa de aprendizado esteja demasiado alta (isso aplica-se tanto no período de treinamento como no de testes). Podemos resolver isso diminuindo a taxa de aprendizado.

**4. Entre os algoritmos baseados no gradiente descendente (GD) que discutimos (batch, estocástico e mini-batch), qual deles chega mais rapidamente à vizinhança da solução ótima? Qual deles realmente converge? O que você pode fazer para que os outros também convirjam?**

R:Entre os algoritmos baseados no gradiente descendente, o que chega mais rapidamente à vizinhança da solução óptima é o gradiente descendente estocástico, o que converge sempre é o batch em gradiente descendente (assumindo que um passo de aprendizagem bom seja usado). Para que os outros também convirjam podemos usar esquemas de variação do passo de aprendizagem