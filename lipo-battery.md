# リチウムイオンポリマー (LiPO) バッテリーパック の検討

リチウムイオンポリマー (LiPO) バッテリーパック を輸入・販売するために必要な事項について検討します。

## バッテリーパックの概要

### 仕様 (2016-05-10現在)

* 型番 HCP357390
* 14.8V, 2900mAh, 42.92Wh
* サイズ (推定, 最大で) 35 x 73 x 90 (mm)

サイズの推定は、バッテリー製造元の命名規則に従った。

## 検討事項

二次電池の流通においては下記の問題が関わる。

* 輸入
* 販売
* 輸送（運輸安全に関する事項）
* 環境 (廃棄、リサイクル、表示)

### 輸送（運輸安全）

航空機や船舶を使って輸送する場合に、制限が生じる場合がある。

* 輸入・販売するときに、航空機で運べるか？
* 輸入・販売するときに、船舶で運べるか？

MSDS (material safety datasheet) をバッテリーの製造元から取り寄せて確認。
通常は、化学薬品の安全性のみについて言及しているが、
ちゃんとしているメーカーのデータシートには、輸送モードごとにＥＵ指令やＩＣＡＯの規則に適合しているか記述がある。

HCP357390 については、すくなくとも船舶と航空機での輸送については、問題ない。

ただし、バッテリーパック単体を（部品として）輸送する時には、外箱に注意書きが必要。記載例は、MSDS参照。


### 輸入

このバッテリーパックについては、輸入や貯蔵、運搬に関して事前の許可や届出は不要。

MSDSによれば、化管法 (PRTR) の規制対象となる物質が一定数量以上含まれていない。
また、密封される状態で使用されるバッテリーなので、同法の規制対象外。


### 販売（電気安全）

電安法のPSEマークの表示が必要なLiPoバッテリーは、400Wh/L 以上。

このバッテリーパックは、 42.92Wh で容積約 0.23L なので、おおよそ 187Wh/L の体積・エネルギー密度。
（ほんとうかなあ？でも、ＬｉＰｏは、セルあたりで300Wh/L 以上ということは通常の用途だとないので、おそらく問題ないか。）


### 環境


資源有効利用促進法の義務について検討。

電池を作るメーカーと、電池を組み込みメーカーのどちらに該当するか？

* 二次電池の輸入・製造者に課せられる義務（電池メーカー）
* 二次電池を使用した製品の輸入・製造者に課せられる義務（電池で動く製品のメーカー＝機器メーカー）

バッテリーパック単体を輸入すると、電池メーカーとみなされる。
バッテリーパックを商品の構成部分（パーツ）として組みこんだ商品を輸入すると、機器メーカーとみなされる。

#### 廃バッテリーの回収、再利用義務など

指定再利用促進製品（第一種指定製品）に該当するか？

再資源化に必要な表示と再資源化の義務、再資源化を容易にする配慮を設計にとりこむなど。

* 機器メーカーやバッテリーメーカーなどにおいては、商品の出荷数量と種類により、義務となる。

今回販売する機器構成、出荷台数では対象外。

#### 分別回収の表示

* 製品のパーツ扱い(たとえばＰＣの内臓バッテリー)で小規模な数量だと、指定表示製品の対象外。

#### 指定再資源化製品	の表示義務

ＬｉＰｏを使用する機器は、小型二次電池使用機器として、ＬｉＰｏバッテリーを使っていることを、次の場所に表示する。

* 小形二次電池使用機器
* 小形二次電池使用機器の取扱説明書
* 小形二次電池使用機器に付属するその他の物品

表示事項(平成13年経済産業省令第93号)

* 小形二次電池使用機器である旨(省令２条)
* 小形二次電池使用機器の構造及び小形二次電池の取り外し方法（同６条）
* 再生資源の利用の促進に資する情報（同条）

Table: 小形二次電池使用機器の表示対象及び表示内容

表示対象　 |小形二次電池使用<BR>機器である旨     |小形二次電池使用機器の構造及び<BR>小形二次電池の取り外し方法    |再生資源の利用の<BR>促進に資する情報|
----------|-----------------|-------------------------------|----------------|
機器本体                      |◎|◎|◎|
取扱説明書                    |×|◎|△|
その他の付属物品（包装物など）|△|◎|△|

◎：必須、 △：推奨、 ×：不要

# 対応

- ベースハウスにLi-ionマークのステッカーを貼付
- 取扱説明書に指定再資源化製品の表示、回収方法の案内、二次電池パックの構造と取り外し方法の説明など

![Base house](./base-house-lipo-sticker.jpg)
 
