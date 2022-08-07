# caesar_cipher
 Projeto Challenge do programa ONE (Oracle Next Education) - Codificador e decodificador de texto

# Cifra de César

## Prefácio
João frequentemente esquece suas senhas, pensando nisso decidiu anotá-las, mas lembrou que outras pessoas podem ter acesso, então pensou em criptografar antes de anotá-las, assim poderá guardá-las criptografadas e com segurança, sem que possam descobrir e quando precisar utilizá-las poderá descriptografar. 😎

## Introdução
A cifra de César é um dos primeiros tipos de criptografias conhecidos na história. É um tipo de cifra por substituição, em que uma letra no texto original é substituída por outra, seguindo um número fixo para essa subtituição.

O imperador Júlio César usou essa cifra para enviar ordens aos seus generais no campo de batalha. Essa é uma das técnicas mais simples e mais usadas para cifrar mensagens.

Por exemplo se usarmos o deslocamento de 3:

Alfabeto sem cifrar: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z

Alfabeto com cifra: D E F G H I J K L M N O P Q R S T U V W X Y Z A B C

## Scripts / Arquivos
* src/index.html: este é o ponto de entrada da aplicação. Este arquivo contem o markup (HTML) e o CSS e JavaScript necessário.

* src/cipher.js: este é o objeto (cipher) contem dois métodos:

* cipher.cifrar(string,offset): string a mensagem (texto) que queremos cifrar e offset é o número de posições que queremos mover para a direita no alfabeto.

* cipher.decifrar(string,offset): string é a mensagem (texto) que queremos decifrar e offset é o número de posições que queremos mover para a esquerda no alfabeto.
