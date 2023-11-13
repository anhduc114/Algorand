
Algokit を使用して Algorand でスマートコントラクトを作る。

  

# Algorandとは?

- ブロックチェーンプラットフォームと暗号通貨

- さまざまなアプリケーションを作成するための分散インフラストラクチャを提供します

- アプリケーションには金融システムや分散型アプリケーションが含まれます (dApps)  


# スマートコントラクトとは?

- ブロックチェーン上に格納され、所定の条件が満たされたときに実行されるプログラム

- 契約の実行を自動化するために使用されるため、すべての参加者は仲介業者の関与や時間のロスなく、即座に結果を確認できます。
 

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

- 完了すると、VS Code が自動的に開き、初期化されたプロジェクトが表示されます。 

- [demo.py] を右クリックし、[Run Python File in Terminal] を選択して、HelloworldApp スマート コントラクトをデプロイします。

  

# Dappflow

- Algorand ネットワーク上のアカウント、トランザクション、アプリを視覚化できる Web ベースのユーザー インターフェイス

- スマート コントラクトをデプロイして呼び出す機能を提供します。

- 起動コマンド: `algokit explore`






