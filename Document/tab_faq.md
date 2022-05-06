---
title: よくある質問
layout:  null
tab: true
order: 3
tags: OCCM
---











![OWASP Incubator Project](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OWASP-Incubator_Project-blue.svg)
![Release](https://owasp.org/www-project-cyber-controls-matrix/assets/images/release-tbd-blue.svg)
[![License](https://owasp.org/www-project-cyber-controls-matrix/assets/images/license-CC--BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

***


***
![OCCM Logo Banner](https://owasp.org/www-project-cyber-controls-matrix/assets/images/OCCM-logo-1000x348-wht.png)

***
## よくある質問 (FAQ)

* **私はどのようにしてプロジェクトを支援できますか？**

  - ご質問ありがとうございます。まずは [OCCM メーリングリストに参加](https://eepurl.com/g3kJBP) して、そのページにあるいずれかの質問に答えることから始めてください。
  - いずれはコンテンツ投稿の手順やフォームを一緒に用意する予定ですが、今は最初のリリースを出すことだけを優先しています。
<p></p>

* **OCCM の最初のリリースはいつ行われ、何が含まれるでしょうか？**

  - 公式には未定ですが、9月までに予定しています。
  - ロードマップタブでターゲットコンテンツの改訂リストをご覧ください。
  - また、[OCCM メーリングリストに参加](https://eepurl.com/g3kJBP) すると、OCCM 固有のニュースやリリースをお知らせします。
  - OCCM プロジェクトは2020年5月11日に発足しました。コア機能は運用可能です (自動マッピングのスキーマとコード) 。最初のサイバー分類体系を作成し、最初のコントロールセット全体で数百のコントロールを正規化するには時間がかかります。
<p></p>

* **OCCM は \[あるコントロールセット] と \[ある別のコントロールセット] との間のコントロールをマッピングするでしょうか？**

  - はい、OCCM に両方のコントロールセットがあれば。
  - OCCM はすべてのコントロールセットを別のすべてのコントロールセットに自動的にマッピングします。
  - これが各コントロールを OCCM サイバー分類体系に正規化する威力です。
  - 今後予定されているコントロールセットの改訂リストはロードマップタブをご覧ください。
<p></p>

* **OCCM はコントロールの選択、文書化、その他プログラムの他の側面を自動化するでしょうか？**

  - いいえ。OCCM はコードと豊富なデータによって推進されるドキュメンテーションプロジェクトです。複数の標準規格、コントロールセット、フレームワークにわたるサイバーコントロールの実装と準拠を支援するために価値のある情報を提供することにのみ注力しています。
  - しかし、私たちはあらゆる種類のソフトウェアが OCCM を利活用することを望んでいます。OCCM とそのコンテンツはサイバー業界への贈り物であり、商用、非商用、政府による使用について自由にライセンスされています。唯一の条件は帰属表示を必要とすることです。
<p></p>

* **OCCM は人工知能 (AI)、機械学習 (ML)、自然言語処理 (NLP) を使用したソリューションとどのように違うのでしょうか？**

  - OCCM は AI/ML/NLP ソリューションと補完関係にあります。それぞれを使用して、もう一方を検証して改善することができます。
  - 現時点で、私たちは一般に公開されている AI/ML/NLP コントロールマッピングを知りません。学術論文、統計解析、商用ソフトウェアの機能しか見たことがありません。実際のマッピングを提供している AI/ML/NLP ソースをご存じの方は [(電子メール)](mailto://occm@cybercontrolsmatrix.com?subject=OCCM AI/ML/NLP Mapping) をお願いします。
  - OCCM コンテンツはサイバーエキスパートの分析によるものですが、AI/ML/NLP は数学的モデルに基づいています。どちらの手法も精度、バイアス、コントロール関係性の欠落 (偽陰性)、あるべきではないコントロールのマッピング (偽陽性) にばらつきがあります。
  - AI/ML/NLP アプローチは大量のデータからパターンを発見することを得意とします。
  - OCCM アプローチは少量のデータに人間の直感、サイバーの専門知識、コンテキストを適用し、正規化 (カテゴライズ) の威力を利用して大量のデータに適用することを得意としています。
<p></p>

* **OCCM は Secure Controls Framework (SCF) とどのように違うのでしょうか？**

  - OCCM のアプローチは他のコントロールセット内の関連するコントロールの情報を活用しながら、対象となるコントロールセットを実装し文書化するものです。
  - SCF のアプローチは他のコントロールセットに準拠するためのベースラインとして SCF コントロール (メタフレームワーク) を実装し文書化するものです。言い換えると、SCF は他のコントロールセットを十分にカバーする普遍的なコントロールセットを提供しようとするものです。もちろん、SCF はこれらのコントロールセットにおけるすべての具体的な要件やガイダンスを捉えることができないので、SCF コントロールから対象となるコントロールへのマッピングが必要となり提供されています。
  - OCCM を使うにせよ、SCF のようなメタフレームワークを使うにせよ、コントロールセットで直接作業することが、現在のところ、監査と認証のための要件すべてを完全に満たすことを保証する唯一の方法となっています。
  - OCCM では特定のコントロールが各詳細レベル (高、中、低) にマッピングされた理由について OCCM サイバー分類体系を介して透明性を提供しますが、SCF マッピングの理由は SCF コントロールとそのコントロールに対して SCF が提供したマッピングの内容を分析することによってのみ推測できます。
  - OCCM はあるコントロールセットから他のすべてに直接マッピングします (つまり NIST->ISO) 。SCF は SCF コントロールのみがマッピングされる場合 (つまり SCF->ISO) を除き、コントロールセット間を間接的にマッピングします (つまり NIST->SCF->ISO)。
  - SCF ライセンスの「改変禁止」条件は、ライセンスの例外が認められない限り SCF コントロールを改変して配布することができないため、製品や研究での使用に支障をきたす可能性があります。OCCM ライセンスにはそのような支障はありません。どちらのライセンスも帰属表示を要求しています。
  - SCF は優れたプロジェクトであり、業界に貢献していますが、OCCM とは内容や使い方が大きく異なります。

<table align="center" style="font-size:70%;max-width:100%">
<thead>
  <tr>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center"></th>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center">OCCM</th>
    <th style="white-space:nowrap;padding:10px;vertical-align:top;text-align:center">SCF</th>
  </tr>
</thead>
<tbody>
  <tr><td style="text-align:right"><b>デザイン</b></td><td>シンプルなマトリクス</td><td>メタフレームワーク</td></tr>
  <tr><td style="text-align:right"><b>個別のコントロールセット</b></td><td>いいえ</td><td>はい。SCF コントロールが必要です</td></tr>
  <tr><td style="text-align:right"><b>アプローチ</b></td><td>コントロールセット A + コントロールセット B など</td><td>SCF コントロール + コントロールセット A + コントロールセット B など</td></tr>
  <tr><td style="text-align:right"><b>マッピング能力</b></td><td>直接 (つまり NIST->ISO)</td><td>間接 (つまり NIST->SCF->ISO)</td></tr>
  <tr><td style="text-align:right"><b>マッピング詳細</b></td><td>3 詳細レベル (高、中、低)</td><td>1 詳細レベル</td></tr>
  <tr><td style="text-align:right"><b>マッピング理由</b></td><td>OCCM サイバー分類体系で特定</td><td>特定なし</td></tr>
  <tr><td style="text-align:right"><b>成熟度モデル</b></td><td>特定なし [コントロール依存]</td><td>SCF コントロール [メタフレームワーク依存]</td></tr>
  <tr><td style="text-align:right"><b>ライセンス</b></td><td>フリー。 CC-BY 4.0</td><td>フリー。 CC-BY-ND 4.0 (改変禁止)</td></tr>
  <tr><td style="text-align:right"><b>親組織</b></td><td>OWASP Foundation, Inc. [501(c)(3) 非営利団体]</td><td>Secure Controls Framework Council, LLC</td></tr>
</tbody>
</table>
<p></p>

* **なぜ OWASP Cyber Controls Matrix (OCCM) という名前なのでしょうか？**

  - "OWASP" はこのプロジェクトを主催し支援している OWASP 財団によるものです。
  - "Cyber" は IT とサイバーセキュリティの両方を表すからです。一般的なバズワードではありますが、「サイバー」はその両方を表す唯一の言葉なのです。
  - "Controls" はコントロールセットやフレームワーク内の個々の測定可能な項目だからです。
  - "Matrix" は OCCM がすべてのコントロールと他のすべてのコントロールとのマッピング表を生成するからです。その表にたどり着くには特定のプロセスが必要ですが、OCCM が生成するものを (さらに別の) フレームワークやメソドロジーと呼ぶことで注意をそらすことがないようにしました。
  - CSA Cloud Controls Matrix (CSA CCM) に謝罪します。私たちは頭文字に "CCM" を使用しないようにしました。本当にそうしました。上記の理由はあまりにも説得力がありました。なにはともあれ、私たちは "OCCM" です。
<p></p>

### 質問に対する回答がこのサイトや他の場所にない場合は？
**[ここをクリックして電子メールでお問い合わせください。](mailto:occm@cybercontrolsmatrix.com?subject=OCCM Website FAQ)**

<br>
