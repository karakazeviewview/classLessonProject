# 仲間キャラクター作成
## 名前と職業を入力すると、職業に応じたステータスの<br>仲間キャラクターを生成してくれるプログラムを作ってみましょう。
### 実行例1  
仲間の名前を入力してください>キーファ [Enter]  
職業を入力してください([戦士][魔法使い][遊び人]のいずれか)>戦士 [Enter]  

キーファ(戦士)が仲間になりました。  
HP:20 力:15 守り:15 魔力:5 素早さ:10 運:0  

### 実行例2  
仲間の名前を入力してください>マリベル [Enter]  
職業を入力してください([戦士][魔法使い][遊び人]のいずれか)>魔法使い [Enter]  

マリベル(魔法使い)が仲間になりました。  
HP:15 力:0 守り:5 魔力:30 素早さ:10 運:5

## 上記のプログラムにメソッドを追加して、仲間になるキャラクターに<br>ステータスアップのボーナスを与えられるようにしてみましょう。
### 実行例1  
仲間の名前を入力してください>ホンダラ [Enter]  
職業を入力してください([戦士][魔法使い][遊び人]のいずれか)>遊び人 [Enter]  

ホンダラ(遊び人)の初期ステータス  
HP:15 力:10 守り:0 魔力:5 素早さ:15 運:20  

3回まで好きなステータスを強化できます  
(HPは1,力は2,守りは3,魔力は4,素早さは5,運は6で入力)  

どのステータスを強化しますか?[残り3回]>1 [Enter]  
HPが2上がった!

どのステータスを強化しますか?[残り2回]>2 [Enter]  
力が1上がった!

どのステータスを強化しますか?[残り1回]>5 [Enter]  
素早さが2上がった!

ホンダラ(遊び人)が仲間になりました。  
HP:17 力:11 守り:0 魔力:5 素早さ:17 運:20  

### ※ステータスの上昇値は1~3のランダムで作ってみました。

# Teachre's EYE

パラメータ生成の部分で具体的な指示があるとよいですね。


