## BattleModJ
Japanese version of Windower4 battlemod addon

BattleModを一部日本語化したものです。アビリティ名や魔法名などの各種アクション内容やメッセージが日本語で表示されます。

BattleModは主に戦闘メッセージを加工して見やすくしてくれるアドオンで、以下のような機能を持っています。
- 戦闘メッセージの短縮/単純化
- 複数ターゲットに対して同じ結果となったメッセージを纏めて1行にする
- 複数回通常攻撃（エンによる追加ダメージを含む）のメッセージを合算して1行にする
- メッセージのカラーリング
- 細かなメッセージ種類ごとのフィルタリング（パーティメンバの通常攻撃をログに出さず、WSはログに出すといったことも可能）

### 変更内容
BattleModでは加工後のメッセージが英語になってしまいますが、加工後の文字列を日本語にする あるいは アドオン内で加工せずにスルーさせるようにしてクライアントの持つメッセージをそのまま表示させる といった変更により日本語化を行っています。結果として添付画像のようなログになります。
なお、変更後の動作確認はデフォルト設定かつ一部のメッセージ種類に対してのみ行っています。

### 使用方法
Windower4フォルダ内に `addons/battlemodj/battlemodj.lua`(zipファイル内の他のファイルも同様) となるように配置し、`lua l battlemodj` でロードしてください。
設定内容などは元のBattleModのreadmeなどを参照してください。
