# RSAttack

O RSA é um dos algoritmos de criptografia assimétrica mais utilizados atualmente. Ele é baseado na dificuldade de fatorar números inteiros grandese utiliza duas chaves, uma pública (N,e) e uma privada (p,q,d). A chave pública é utilizada para criptografar a mensagem e a chave privada é utilizada para descriptografar a mensagem.

Entretanto, o RSA é vulnerável a alguns ataques que exploram algumas vulnerabilidades do algoritmo e escolhas de chaves. Aqui, vamos explorar alguns dos mais conhecidos ataques ao RSA.

- Força Bruta: O ataque de força bruta consiste em testar todas as possíveis chaves privadas até encontrar a correta. Esse ataque é inviável para chaves grandes, pois o tempo necessário para testar todas as chaves é muito grande.
- Fatoração de Fermat: O ataque de fatoração de Fermat consiste em fatorar o módulo N em dois primos p e q. Esse ataque é mais eficiente que o ataque de força bruta, mas ainda é inviável para $N$ muito grande.
- Expoente e pequeno: O ataque de expoente e pequeno consiste em descriptografar a mensagem utilizando um expoente pequeno. Esse ataque é eficiente quando o expoente é muito pequeno.
- Ataque de Pollard p-1: O ataque de Pollard p-1 consiste em fatorar o módulo N utilizando o método de Pollard p-1. Esse ataque é eficiente quando p-1 é suave, ou seja, possui muitos fatores primos pequenos.
- Ataque de Wiener: O ataque de Wiener consiste em fatorar o módulo N utilizando a fração contínua do expoente de descriptografia d. Esse ataque é eficiente quando o expoente d é pequeno em relação a N.