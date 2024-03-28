# kg_Macro-for-zbrush
焦げ餅(@Koge_Mochimochi)の作成したプラグインっぽいマクロセットです。
V1.0ではZbrushのサブツールのDelete時のフォルダを消し飛ばすことを防ぐ「S-Delete」、板ポリゴンとして画像を読み込む「Quick-image」などを公開します。

#### インストール要件
Windowsのみ対応です。Mac版で動かす場合はtxt版の内容(RoutineDefのどこか)のフォルダパスを書き換えてあげる必要があります。

#### インストール手順
Kg_Custom_Macro_Data フォルダ　と、Kg_Custom_Macro V1.0.zscの二つを、Zbrushのフォルダ内Zstartup/Zplugs64の中に入れて、Zbrushを再起動してください。

## ボタン紹介(V1.0)
![Kg_Custom_Macro_V1 0](https://github.com/P0clnApa/kg_Macro-for-zbrush/assets/17403397/83da87c9-7611-4f88-8c45-c810ed720133)

#### S-Duplicate
![S-Duplicate-Capture-HR](https://github.com/P0clnApa/kg_Macro-for-zbrush/assets/17403397/22664a0c-7e1d-496a-9914-cdb80526e0e6)

  現在のサブツールが閉じたフォルダ内にある場合、フォルダを強制的に開いてからDuplicateをするボタンです。

#### S-Delete
現在のサブツールが閉じたフォルダ内にある場合、フォルダを強制的に開いてからDeleteを押すボタンです。 眠いときに特に事故りがちなので作成。
内部処理的に「Deleteボタンをクリックする」動作なので、確認ダイアログは通常通り出ます。

#### S-Focus
サブツールリストから現在のサブツールを見失った際、リスト上に表示し直してくれるボタンです。
フォルダが閉じてる場合、開きます。

#### Quick-image
プレーンポリゴンに画像を取り込みます。比率は画像と同じままで取り込まれますが、短辺が 1unitになるようにしています。

## 改造について

Kg_Custom_Macro V1.0.txtがソースファイルです。ライセンスの範囲内で自由に改造などしてしまってください。

### チェンジログ
V1.0 リリース

## ライセンスと免責事項

このデータはCC-BY-SAにて配布されています。
このデータを利用、改造等した際に発生した不具合については、開発者は責任を負いません。
