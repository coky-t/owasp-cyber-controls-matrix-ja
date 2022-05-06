---
title: 特徴
layout:  null
tab: true
order: 2
tags: OCCM
---











![OWASP Incubator Project](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OWASP-Incubator_Project-blue.svg)
![Release](https://owasp.org/www-project-cyber-controls-matrix/assets/images/release-tbd-blue.svg)
[![License](https://owasp.org/www-project-cyber-controls-matrix/assets/images/license-CC--BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

***


***
![OCCM Logo Banner](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OCCM-logo-1000x348-wht.png)

***
## 主な特徴

* **一対多のコントロールマッピング**

  (多対多と比較して)
  - 各コントロールは他のコントロールに対して個別に評価されるため、直接関連するコントロールのみに必要な分析が大幅に削減されます。
  - 一対多のマッピングは非常に直接的な結果をもたらします。
  
    "A1 --> B1, B2"
  - 多対多のマッピングは間接的でグループ化された結果となります。
  
    "A1, A2, A3, A4, A5 --> B1, B2, B3, B4, B5"
<p></p>

* **三つの異なる詳細レベルでのマッピング**

  (単一レベルと比較して)
  - 汎用レベル、具体レベル、詳細レベルで関連するコントロールの分析が可能です。
  - 曖昧すぎる、または具体的すぎるマッピングアプローチによりコントロールが見落とされることがないようにします。
<p></p>

* **サブコントロール、コントロール拡張、監査チェックのマッピング**

  (トップレベルコントロールのみを含むものと比較して)
  - トップレベルコントロールだけでなくサブコントロールとコントロール拡張に直接マッピングすることで関連性と詳細性が大幅に向上します。
  - サブコントロールやコントロール拡張が必要になることはよくありますが、公式や他のソースのマッピングには一般的に含まれていません。
<p></p>

* **コントロールセット全体のコントロールの正規化**

  (コントロールの関係性とマッピングのための参照点がないものと比較して)
  - 正規化された分類体系でのマッチングはコントロールが互いにマッピングされる理由を明らかにします。
  - コントロールのマッピングはもはや神秘的なブラックボックスではありません。
<p></p>

* **同じコントロールセット内での他のコントロールとの関係性**

  (コントロールが互いにどのように関係するかわからないものと比較して)
  - コントロールセットでどのように構成されているかに関係なく、コントロール間の関係性を見ることができます。
<p></p>

* **公式および他のソースからのマッピングを含む**

  (他のマッピングは他の場所を探す必要があるものと比較して)
  - 公式および他のマッピングをワンストップショップとして参照できます。
  - 公式および他のソースのマッピングから検証することで、正規化の見落としがないことを確認できます。
  - 公式および他のソースのマッピングは異なるアプローチだが有効である。
  - 命題:
  
    "やり方は一つではない (There's More Than One Way To Do It)"  \[Perl のモットー]
  - 裏命題:
  
    "それをおこなう明白な方法が一つ (できれば一つだけ) あるようにする (There should be one — and preferably only one — obvious way to do it.)"  \[Python の禅 (Zen of Python)]
<p></p>

<br>
