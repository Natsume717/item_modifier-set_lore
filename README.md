# item_modifier-set_lore
item_modifierの1項目であるset_loreに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】set_loreで説明文を追加・上書きする【item_modifier】](https://natsumake.com/set_lore/)』を参考にしてください。

<h3>概要</h3>
アイテムに対して、説明文を付与させることが可能です。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、説明文が付け加えられたダイヤモンドをドロップします。

また、手元のアイテムに対して、以下のコマンドを実行することで説明文を付与することが可能です。

```copy
/item modify entity @s weapon.mainhand sample:set_lore
```

以下のコマンドの場合には、名前と説明文を付与することが可能です。

```copy
/item modify entity @s weapon.mainhand sample:set_lore_advanced
```
