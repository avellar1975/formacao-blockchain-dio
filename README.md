**Projeto Blockchain**

1. Criar uma pasta para o projeto.
2. Dentro da pasta criada, iniciar o projeto do node através do comando ```npm init -y```
3. Instalar as bibliotecas:
   * bip39
   * bip32@2.0.6
   * bitcoinjs-lib
> comando ```npm install bip39 bip32@2.0.6 bitcoinjs-lib --save```
4. Criar a pasta src
5. Criar o arquivo createWallet.js dentro da pasta src
6. Executar o comando ```node ./createWallet.js```
7. Fazer o download e instalar o software electrum no site electrum.org
8. Executar o Electrum ```python Electrum-4.4.5/run_electrum``` 
<pre>
Exemplo de palavras geradas:
 
puppy fiber century bamboo milk uncover grape guard iron broken maze consider
</pre>

8. Gerar um novo endereço através do comando ```node ./createWallet.js```
9. Realizar transferência de bitcoins entre as carteiras e visualizar no explorer.

* Explorer testnet: https://blockstream.info/testnet/
* Faucet: https://testnet-faucet.com/btc-testnet/
