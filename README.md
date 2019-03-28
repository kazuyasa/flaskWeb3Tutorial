# flaskWeb3Tutorial
#Web3.pyサンプルコード
##使用方法
   1. Ganache等のテストネット上に、「Adoption.sol」をデプロイする（デプロイ方法については、今回は割愛）
   2. petdata.jsonに、ABIとコントラクトアドレスを設定する
   3. petshop.pyを起動する
      >>>「FLASK_APP=petshop.py flask run」
   4. APIを起動させてみる
      >>>「curl -H "Content-Type: application/json" --request POST -d'{"petId":"0"}' http://localhost:5000/blockchain/pet」
