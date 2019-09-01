READ ME

Amplificadores s�o dispositicos eletr�nicos utilizados em diversos equipamentos que tem por objetivo aumentar o valor da amplitude do sinal da entrada (podendo ser tamb�m ru�do) e consequentemente aumentar tamb�m a pot�ncia.

Al�m de amplificar sinais ou ru�dos, os amplificadores reais tamb�m possuem um ru�do pr�prio que � adicionado ao sinal, sendo assim, vamos definir  SNRi como a rela��o sinal ru�do na entrada do amplificador e SNRo na sa�da do amplificador, onde a diferen�a b�sica entre as duas grandezas � a rela��o da sa�da leva em conta o ru�do adicionado pelo amplificador. Tamb�m podemos definir Figura de Ru�do como SNRi/SNRo.

Estes par�metros s�o importantes no c�lculo da figura de ru�do de diversos sitemas com amplificadores e outros componentes cascateados

Outros par�metros importantes a se considerar na escolha de amplificadores s�o OP1dB e OIP3

*OP1dB

O ganho dos amplificadores cresce de maneira linear at� o ponto de satura��o, onde independente do aumento do sinal de entrada, o sinal de sa�da n�o cresce mais. Assim, se fizermos uma proje��o da reta de ganho do amplificador e marcamos o ponto em que ela se distancia 1dB da regi�o de satura��o, podemos encontrar o OP1dB, como pode ser visto na imagem abaixo.

*OIP3

Os harm�nicos dos sinais tamab�m s�o amplificados, por�m, a medida que a ordem dos harm�nicos v�o crescendo, eles v�o tendo menos influ�ncia no sinal.

Sendo assim, faz-se uma an�lise do 3� harm�nico. Se pegarmos a proje��o reta de ganho do sinal e encontrarmos a interse��o da proje��o da reta de ganho do terceiro harm�nico, encontraremos OIP3. Este ponto � uma extrapola��o das duas retas e nunca vai ser alcan�ado por um dispositivo, por�m, um sinal de entrada no amplificador deve ser estar longe do OIP3.

O OIP3 pode ser visto na figura abaixo

(FIGURA)

Sendo assim, alguns par�metros importantes para a escolha de um amplificador s�o:

.Faixa de Opera��o
.Ganho
.Figura de Ru�do
.OIP3
.OP1dB

� importante pontuar que na escolha de um amplicador, deve se escolher o componente mais ideal poss�vel, ou seja, grande faixa de opera��o, grande ganho, pequena faixa de ru�do e valores altos de OIP3 e OP1dB.

Low Noise Amplifier - LNA

Este � um tipo especial de amplifi que adiciona apenas um pequeno ru�do ao sistema.

Gain Block

Este � um tipo de amplificador que est� pronto para colocar na placa, j� est� todo polarizado e n�o precisa que circuito externo seja adicionado para que funcione.

TQP3M9019 - High Linearity LNA Gain Block

Este amplificador possui as seguintes especifica��es:

Faixa de Opera��o: 20-4000MHz
Ganho: 22dB a 1900MHz
Figura de Ru�do: 1.3dB
O1P3: 39.5dBm

Outros par�metros importantes podem ser visto nos gr�ficos abaixo:

(FIGURA)