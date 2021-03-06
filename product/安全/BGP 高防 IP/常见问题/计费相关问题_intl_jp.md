[//]: # (chinagitpath:XXXXX)

## Anti-DDoS Advancedサービスの弾性防護課金モードは同じですか？計算方法は？
同じです。当日の防護可能な攻撃トラフィックピーク値に対応する弾性防護ピーク値区間に基づいて課金します。課金の詳細については、[課金概要](https://cloud.tencent.com/document/product/1014/31100)を参照してください。
例えば、購入したAnti-DDoS Advancedインスタンス仕様は、20Gbps最低防護ピーク値 + 50Gbps弾性防護ピーク値の場合、当日、DDoS攻撃イベントが発生し、かつ最高攻撃トラフィックピーク値が45Gbpsであれば、45Gbpsが最低防護ピーク値範囲を外れて弾性防護をトリガし、そして、40Gbps ＜ 弾性ピーク値 ≤ 50Gbps課金区間に該当すると、当日に発生する弾性費用は、40Gbps ＜ 弾性ピーク値 ≤ 50Gbps課金区間において請求します。

## Anti-DDoS Advancedが防護するIPが大量のトラフィック攻撃を受けてブロックされた場合、その攻撃トラフィックは課金されますか？
Anti-DDoS Advancedサービスの弾性防護課金規則は、最低防護ピーク値超、弾性防護ピーク値以下の攻撃トラフィックに基づいて課金します。ブロックは、攻撃トラフィックが設定した弾性防護ピーク値を超えたことを意味しますので、弾性防護ピーク値を超えた攻撃トラフィック分は課金範囲外です。

## 弾性防護を購入する後、1ヶ月以内に攻撃を受けていない場合、料金がかかりますか？
この場合、最低防護の月額料金だけを支払います。追加費用が発生しません。

## 100Gbpsの最低防護を購入するとき、50Gbpsまで下げられますか？
いいえ。最低防護レベルはアップグレードできますが、ダウングレードできません。

## サービスが攻撃を受けているとき、弾性防護ピーク値のアップグレードができますか？
できます。Anti-DDoS Advancedサービス基本情報画面で弾性防護ピーク値を増加と下降の両方に調整できます。地域によって防護能力も異なります。弾性防護ピーク値の具体的な数値範囲については、[製品概要](https://cloud.tencent.com/document/product/1014/31091)を参照してください。
>!当日に発生する攻撃で課金が生じたが、変更後に翌日から最新の弾性防護ピーク値で課金します。

## 防護されるIPが1日中数回の攻撃を受けた場合、料金をその回数に分けて請求しますか？
Anti-DDoS Advancedサービスは、当日に防護した最高攻撃トラフィックピーク値に基づいて計算され、1回だけ課金されます。

## 2つのAnti-DDoS Advancedサービスセットを購入し、2つのAnti-DDoS Advancedサービスインスタンスが受けた攻撃のトラフィックがすべて最低防護を超えた場合、弾性防護料金の計算方法は？
弾性防護料金は、製品インスタンスを計算単位とします。2つのAnti-DDoS Advancedサービスインスタンスが最低防護を超えるとき、2つのAnti-DDoS Advancedインスタンスの弾性防護料金がそれぞれ請求されます。

