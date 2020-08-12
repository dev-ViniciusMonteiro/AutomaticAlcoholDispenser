# AutomaticAlcoholDispenser
 Automatic alcohol dispenser design with Arduino.

O sensor de temperatura junto ao suporte são opcionais, sendo assim você pode escolher seu produto de acordo com seu ambiente, para banheiro recomendamos a versão sem o suporte(fixada na parede), para ambientes externos recomendamos a versão com suporte sem sensor de temperatura.

A luz UVC faz com que as bactérias que se possam se acumular no produto sejam eliminadas, podendo assim ter uma melhor segurança ao utilizar o equipamento

O sensor de distancia faz com que conforme o usuário aproxime a mão perto da saída do álcool mais ira sair, sendo assim a própria pessoa pode regular a saída do mesmo evitando a perca desnecessária do produto.

Código pensado para calcular a distancia do sensor até a mão, sendo assim caso a pessoa aproxime mais a mão seria como se ela apertasse mais o recipiente que sai o álcool. Embutido uma função que ao aproximar a mão do sensor  mesmo antes de acioná-lo ira desligar a luz UVC na qual não pode ser olhada direta e embutido ao sensor de temperatura cada vez que capitar uma temperatura acima a 40 graus ira acinar um led sinalizador(existe uma margem de erro no sensor e devido a isso a temperatura que o aciona tem que ser maior que o normal).
