
Algokit を使用して Algorand でスマートコントラクトを作る。

  

# Algorandとは?

- ブロックチェーンプラットフォームと暗号通貨 (there are many other blockchain platforms, each with its own features, use cases, and characteristics)

- さまざまなアプリケーションを作成するための分散インフラストラクチャを提供します

- アプリケーションには金融システムや分散型アプリケーションが含まれます (dApps)

  

# What is a dApp?

- Stands for decentralized application

- Key principle of dApp: open and accessible to anyone who wants to create and use them.

  

# スマートコントラクトとは?

- ブロックチェーン上に格納され、所定の条件が満たされたときに実行されるプログラム

- 契約の実行を自動化するために使用されるため、すべての参加者は仲介業者の関与や時間のロスなく、即座に結果を確認できます。

Ex:

- Vending machine: put in some money, press a button, and it gives you coffee. A smart contract is similar, but it's digital program and lives on a computer.

  
  

# Algokitとは?

- Algorand ブロックチェーン用のスマート コントラクト開発ツール。

- Algokit を使用してスマート コントラクトを作成し、Algorand 上でスマート コントラクトと対話する

- オープンソース、Windows + MacOS をサポート

  

# Algokit を使用してスマートコントラクトを作成する方法?

- 要件(MacOS): PipX, Homebrew, Python 3.10以上, Docker, VSCode

  

## AlgoKitをインストールする

- `brew install algorandfoundation/tap/algokit`

- ターミナルを再起動します (Algokit が PATH で利用可能であることを確認するため)

- 確認する: algokit --version (結果は 1.6.0 になるはずです)

  

## LocalNetをスタート

- `algokit localnet start`

  

## スマートコントラクトを作成する

- `algokit init`

- 完了すると、VS Code が自動的に開き、初期化されたプロジェクトが表示されます。 The app used in the demo contain one smart contract (built using Beaker - smart contract development framework)

- (Explain helloworld.py and demo.py)

- [demo.py] を右クリックし、[Run Python File in Terminal] を選択して、HelloworldApp スマート コントラクトをデプロイします。

  

# Dappflow

- Algorand ネットワーク上のアカウント、トランザクション、アプリを視覚化できる Web ベースのユーザー インターフェイス

- スマート コントラクトをデプロイして呼び出す機能を提供します。

- 起動コマンド: `algokit explore`






(potential bug fix: No module 'pkg_resources' -> pip install --upgrade setuptools )