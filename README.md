
# Qiskit

[![License](https://img.shields.io/github/license/Qiskit/qiskit.svg?)](https://opensource.org/licenses/Apache-2.0) [![Build Status](https://img.shields.io/travis/com/Qiskit/qiskit/master.svg?)](https://travis-ci.com/Qiskit/qiskit) [![](https://img.shields.io/github/release/Qiskit/qiskit.svg)](https://github.com/Qiskit/qiskit/releases) [![Downloads](https://pepy.tech/badge/qiskit)](https://pypi.org/project/qiskit/)

**Qiskit** は、 noisy intermediate-scale quantum computers (NISQ) をパルス、回路、アルゴリズムのレベルで操作するオープン・ソース・フレームワークです。

Qiskitは、量子コンピューターを動かすための要素で構成されています。これは、Qiskitのすべての要素を一度にインストールするメタパッケージです。

## インストール
`qiskit`をインストールするには `pip`を使います。:

```bash
$ pip install qiskit
```

仮想環境の使い方や、Qiskitの個々の要素やコンポーネントのスタンドアロン・バージョンのソースからビルドするなどの詳細説明は、[install](docs/install.rst)を見てください。

## Qiskit 詳細
Qiskitは要素やコンポーネントで構成され、このメタパッケージでそれらすべての要素やコンポーネントをインストールすることを私達は目指していますが、
現在のところ、デフォルトのpipに含まれていない物がまだ少しあり、それらの個々のパッケージは以下の説明に沿ってインストールが必要です。
（次のupdateで修正される予定です。）

### Qiskit の要素

Qiskitの4つの要素は、Qiskitに力を与えるのに必要なパーツです。

| ビルド   | ステータス | バージョン | コントリビュート | 
| ---             | ---    | --- | --- | 
| [**Qiskit Terra**](https://qiskit.org/terra)   |  [![Build Status](https://img.shields.io/travis/Qiskit/qiskit-terra/master.svg?)](https://travis-ci.org/Qiskit/qiskit-terra)| [![](https://img.shields.io/github/release/Qiskit/qiskit-terra.svg?)](https://github.com/Qiskit/qiskit-terra/releases)  | [![](https://img.shields.io/github/forks/Qiskit/qiskit-terra.svg?)](https://github.com/Qiskit/qiskit-terra) |
| [**Qiskit Aer**](https://qiskit.org/aer)   |  [![Build Status](https://img.shields.io/travis/com/Qiskit/qiskit-aer/master.svg?)](https://travis-ci.com/Qiskit/qiskit-aer) | [![](https://img.shields.io/github/release/Qiskit/qiskit-aer.svg?)](https://github.com/Qiskit/qiskit-aer/releases) | [![](https://img.shields.io/github/forks/Qiskit/qiskit-aer.svg?)](https://github.com/Qiskit/qiskit-aer) |
| [**Qiskit Aqua**](https://qiskit.org/aqua)<sup>1</sup>  |  [![Build Status](https://img.shields.io/travis/Qiskit/qiskit-aqua/master.svg?)](https://travis-ci.org/Qiskit/qiskit-aqua) |  [![](https://img.shields.io/github/release/Qiskit/qiskit-aqua.svg?)](https://github.com/Qiskit/qiskit-aqua/releases) | [![](https://img.shields.io/github/forks/Qiskit/qiskit-aqua.svg?)](https://github.com/Qiskit/qiskit-aqua) |
| **Qiskit Ignis**<sup>2</sup>   |  --- |  ---| --- |

### Qiskit のコンポーネント

Qiskitのコンポーネントは、すべての機能のために必要なQiskitのより小さな自己完結型パーツです。

| ビルド   | ステータス | バージョン | コントリビュート | 
| ---             | ---    | --- | --- |
| **Qiskit Tutorial**  | --- |  [![](https://img.shields.io/github/release/Qiskit/qiskit-tutorial.svg?)](https://github.com/Qiskit/qiskit-tutorial/releases)   | [![](https://img.shields.io/github/forks/Qiskit/qiskit-tutorial.svg?)](https://github.com/Qiskit/qiskit-tutorial) |
| **Qiskit Chemistry**<sup>1</sup>  |  [![Build Status](https://img.shields.io/travis/com/Qiskit/qiskit-chemistry/master.svg?)](https://travis-ci.com/Qiskit/qiskit-chemistry) |  [![](https://img.shields.io/github/release/Qiskit/qiskit-chemistry.svg?)](https://github.com/Qiskit/qiskit-chemistry/releases)   | [![](https://img.shields.io/github/forks/Qiskit/qiskit-chemistry.svg?)](https://github.com/Qiskit/qiskit-chemistry) |
| **IBM Q Provider** |  [![Build Status](https://img.shields.io/travis/Qiskit/qiskit-ibmq-provider/master.svg?)](https://travis-ci.org/Qiskit/qiskit-ibmq-provider) |  [![](https://img.shields.io/github/release/Qiskit/qiskit-ibmq-provider.svg?)](https://github.com/Qiskit/qiskit-ibmq-provider/releases) | [![](https://img.shields.io/github/forks/Qiskit/qiskit-ibmq-provider.svg?)](https://github.com/Qiskit/qiskit-ibmq-provider) |


1: 現在、こちらは個別インストールが必要です：詳細はレポジトリーを参照してください。

2: 現在、リリースされていません（2019年前半にリリース予定）。

### 追加の拡張

Qiskitとその機能性の強化には、以下の拡張が使えます。

| ビルド   | ステータス | バージョン | コントリビュート |
| ---   | --- | --- | --- |
| **JKU Provider** |  --- |  --- | | [![](https://img.shields.io/github/forks/Qiskit/qiskit-jku-provider.svg?)](https://github.com/Qiskit/qiskit-jku-provider) |
| **QCGPU Provider** |  --- |  --- | | [![](https://img.shields.io/github/forks/Qiskit/qiskit-qcgpu-provider.svg?)](https://github.com/Qiskit/qiskit-qcgpu-provider) |
| **Project Q Provider** |  --- |  --- | | [![](https://img.shields.io/github/forks/Qiskit/qiskit-projectq-provider.svg?)](https://github.com/Qiskit/qiskit-projectq-provider) |
| **Sympy Provider** |  --- |  --- | | [![](https://img.shields.io/github/forks/Qiskit/qiskit-sympy-provider.svg?)](https://github.com/Qiskit/qiskit-sympy-provider) |

これらは作業中で、Qiskit 0.7で追加されます。

## コントリビューション・ガイドライン

あなたが、Qiskitに貢献したい場合、こちらをご覧ください：
[contribution guidelines](.github/CONTRIBUTING.rst)。
このプロジェクトは、Qiskit's [code of conduct](.github/CODE_OF_CONDUCT.md)　に従います。
参加する方は、この code of conduct を守ることを期待されています。

リクエストとバグの記録に[GitHub issues](https://github.com/Qiskit/qiskit/issues) を使います。
ディスカッションや簡単な質問には、[slack](https://qiskit.slack.com) を使ってください。
Slack community に参加するには、 [link](https://join.slack.com/t/qiskit/shared_invite/enQtNDc2NjUzMjE4Mzc0LTMwZmE0YTM4ZThiNGJmODkzN2Y2NTNlMDIwYWNjYzA2ZmM1YTRlZGQ3OGM0NjcwMjZkZGE0MTA4MGQ1ZTVmYzk)　へ。
フォーラムに適した質問は、Qiskitタグをつけて[Stack Overflow](https://stackoverflow.com/questions/tagged/qiskit)　へお願いします。


## 次のステップ

セットアップがすんだら、[Qiskit Tutorials](https://github.com/Qiskit/qiskit-tutorials) レポジトリーを御覧ください。

## 著者

Qiskit は、様々なレベルで[多くの](https://github.com/Qiskit/qiskit/graphs/contributors) が貢献してくれているプロジェクトです。


## ライセンス

[Apache License 2.0](LICENSE.txt)
