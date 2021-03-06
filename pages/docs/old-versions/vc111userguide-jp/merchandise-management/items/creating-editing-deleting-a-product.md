---
title: 製品の作成・編集・削除
description: 製品の作成・編集・削除
layout: docs
date: 2016-06-03T10:21:23.333Z
priority: 3
---
Commerce Manager の製品は、販売される実際の製品になります。各製品は、それぞれに特製を持っており、販売され、タイプグループに属することになります。

全ての製品は、プロダクトタイプに割り当てられています。プロダクトタイプは、製品の組み合わせでどのように表示するか・適用される税コード・属性・製品タイプで利用可能なSKUオプションを定義します。

## 製品の作成

新しい製品が含まれるカテゴリーに移動します。カテゴリー画面の左側に製品リストが表示されています。

![](../../../../../assets/images/docs/027-list-of-products.PNG)

製品を作成するには、 Add ボタンをクリックします。

![](../../../../../assets/images/docs/028-add-product.PNG)

製品を作成する為に アイテムの種類を選択します。

最初のステップは、製品の詳細を入力します。

1. **Item Name** - 製品の名前を入力
2. **Item Type** - ドロップダウンリストからタイプを選択
3. **Can be purchased** - チェックした場合、製品の購入可能
4. **Store visible** - チェックした場合、この製品がストアに表示
5. **Min. Quantity** - 顧客が購入可能最少数量を指定
6. **Max. Quantity** - 顧客が購入可能な最大数を指定
7. **Enable Date/Time** - ストアで利用可能日時を指定、シーズン商品として有効
8. **Disable Date/Time** - ストアで利用不可日時を指定、シーズン商品として有効

ステップ２としてレビュー情報を入力します。この情報は、必須ではないのでスキップすることができます。

ステップ３としてプロパティ値を入力します。ステップ４では、価格情報を入力し(ドロップダウンから価格リストを選択) "Finish" ボタンをクリックします。

新しい製品が、選択されたカテゴリーに表示されます。

## 製品の編集

製品を編集するには、カタログのカテゴリーから、ダブルクリックし、製品ウィンドウを表示し、必要な項目を変更します。

## 製品の削除

製品を削除するには、カテゴリーから製品を選択し、"Remove" ボタンをクリックします。製品を削除すると、その製品を含む全ての価格リストから価格が削除されます。

複数の製品を削除するには、Ctrl キーを利用し削除するアイテムを選択します。

## バリエーションサンプルと製品の作成

サンプル "Apple" ストアの製品 "apple ipod shuffle"があり、カラーとサイズオプションを選択することができます。

その製品を操作する方法を説明します。

製品の全てのバリエーションの "parent" になる製品を作成します。"Store visible" チェックボックスをチェックし、 "Can be purchased" チェックボックスのチェックを外します。それで、製品は、ストアで販売可能になりますが、直接購入できなくなります。

![](../../../../../assets/images/docs/1.png)

次に選択できるプロパティオプションの可能な製品のバリエーションを作成します。つまり、サンプル製品のカラーとサイズです。"Can be purchased" をチェックし、"Store visible"を未チェックしましたので、購入することはできましたが、"parent" 製品のオプションを選択し、直接表示することはできませんでした。

![](../../../../../assets/images/docs/3.png)

"parent" 製品に移動し、"Product Items" タブを選択します。そして、製品アイテムリストのバリエーションを作成します。製品名でそれらをグループ化します。サンプルでは、"Size" と "Color" プロパティを指定します。

![](../../../../../assets/images/docs/2.png)

バリエーションは、グループ化されたプロパティによってグループ化され、フロントエンドで利用可能になります。

![](../../../../../assets/images/docs/4.png)