# Whisper
(Nome não definido)

## Ideia:
Desenvolver uma aplicação que ajude crianças com problemas na aquisição da fala a evoluirem e aumentarem o seu vocabulário.

A ideia inicial é desenvolver uma aplicação que é um deck de um baralho onde cada carta contem uma expressão (frase). 

Cada uma dessas expressões será uma frase onde cada palavra é representada por uma imagem e um som (voz). 

Sempre que uma carta é exibida, devemos apresentar nela as imagens que representam a frase e executar o áudio onde e o usuário (criança) poderá ouvir novamente e analisar se ele aprendeu ou não a frase. (Num futuro podemos pensar em gravar a criança falando a frase).

Caso a resposta seja negativa, a carta deverá ser exibida novamente num curto espaço de tempo. Quanto mais vezes a criança responde "não" a uma expressão, mais frequente será a sua exibição. 

Caso a resposta seja positiva, a carta deverá ser exibida novamente após tempo mais longo. Quanto mais vezes a criança responde "sim" para uma expressão, menos frequente será a sua exibição.


### Referências

#### Sistema de repetição espaçada
Sistemas de repetição espaçada é uma técnica de aprendizado baseado em evidências que é geralmente usada em conjunto com cards. Cards introduzidos mais recentemente, assim como os mais difíceis são exibidos mais frequentemente, enquanto antigos ou menos difíceis são exibidos com menos frequência de forma que explorem o efeito pscicológico do espaçamento. O uso de sistemas de repetição espaçada provatamente aumenta as taxas de aprendizado. 

Definição: https://en.wikipedia.org/wiki/Spaced_repetition
App exemplo: https://apps.ankiweb.net/

#### Pictograma
Um pictograma é um símbolo que representa um objeto ou conceito por meio de desenhos figurativos. Pictografia é a forma de escrita pela qual ideias e objetivos são transmitidos através de desenhos.

A Arasaac (Aragonese Center of Augmentative and Alternative Communication) possui uma API onde é possível obter esses desenhos

API: https://arasaac.org/developers/api

#### Voz
Parte do aprendizado da criaça vem dela seguir um modelo, copiar o que a outra pessoa fala. 

Pensei em usar alguma API de voz caso esteja disponível. Algo como a API de voz do Google Tradutor.
