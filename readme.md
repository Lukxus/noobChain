# NoobCoin

NoobCoin é uma criptomoeda simples desenvolvida em Java, projetada para demonstrar os princípios básicos da tecnologia blockchain.

## Resumo Técnico

**Funcionamento Técnico do NoobCoin:**

1. **Geração de Carteiras**:
    - As carteiras geram pares de chaves públicas e privadas usando criptografia de curva elíptica (ECC).
    - A chave pública atua como um endereço para receber pagamentos.
    - A chave privada é usada para assinar transações.

2. **Transações**:
    - Cada transação contém a chave pública do remetente e do destinatário, o valor transferido, inputs (referências a transações anteriores) e outputs (quantidade enviada a cada endereço).
    - As transações são assinadas com a chave privada do remetente e verificadas com a chave pública, garantindo a autenticidade e integridade.

3. **Blocos**:
    - Blocos contêm múltiplas transações e são encadeados usando hashes.
    - Cada bloco armazena o hash do bloco anterior, a raiz de Merkle das transações, um timestamp e um nonce.

4. **Mineração**:
    - A mineração envolve encontrar um nonce que, quando combinado com os dados do bloco, produz um hash que atende a um determinado nível de dificuldade.
    - O minerador que encontra o nonce correto adiciona o bloco à blockchain.

5. **Validação e Consenso**:
    - A blockchain valida novas transações e blocos verificando assinaturas e confirmando que os inputs não foram gastos anteriormente.
    - Todas as transações e blocos são armazenados em uma estrutura de dados imutável.

## Resumo Teórico

**Funcionamento Teórico do NoobCoin:**

1. **Carteiras e Chaves**:
    - As carteiras geram dois tipos de chaves: pública e privada.
    - A chave pública serve como endereço para receber noobcoins.
    - A chave privada é mantida secreta e usada para assinar transações, garantindo que apenas o dono da chave possa gastar os noobcoins.

2. **Transações**:
    - As transações movem noobcoins de uma carteira para outra.
    - Cada transação é assinada digitalmente pela chave privada do remetente, assegurando que foi autorizada pelo verdadeiro proprietário.
    - A rede verifica essas assinaturas utilizando a chave pública do remetente.

3. **Blocos e Blockchain**:
    - As transações são agrupadas em blocos.
    - Cada bloco contém um conjunto de transações, um hash do bloco anterior, e uma raiz de Merkle que representa todas as transações no bloco.
    - A blockchain é uma cadeia de blocos, onde cada bloco é ligado ao anterior, formando um registro imutável e transparente.

4. **Mineração**:
    - Mineração é o processo de adicionar novos blocos à blockchain.
    - Os mineradores competem para resolver um problema matemático complexo, e o primeiro a encontrar a solução adiciona o novo bloco à cadeia.
    - Este processo garante a segurança e a descentralização da rede.

5. **Segurança e Consenso**:
    - A segurança é mantida através da criptografia e da validação das transações.
    - O consenso é alcançado pela verificação de blocos por múltiplos nós na rede, garantindo que todos concordem com o estado da blockchain.

## Conclusão

Este projeto demonstra os conceitos fundamentais de criptomoedas e blockchain de maneira prática e acessível. Ao seguir este tutorial, você entenderá melhor como funcionam as transações, a geração de chaves, a mineração e a validação em um sistema de criptomoeda simples.


Fontes:
https://medium.com/programmers-blockchain/create-simple-blockchain-java-tutorial-from-scratch-6eeed3cb03fa
