VSCode の Vim についてのノート

### NOTE
- 複数行をコピー|カットペースト
    - 3dd => p
    - 3yy => p
- 行削除
    - dd でやるしかない（ので、システムクリップボードはリンクさせない）
- カーソルから後ろを削除
    - D, C => yankしてるから注意
    - cocoa キーバインド(ctr + e)は封印する？
- InsertMode中にcocoaキーバインドを生かす
    - ctrl + o での操作に慣れよう
- InsertModeでカーソル移動？
    - ctrl + o でNormalModeに一旦入るので操作
- Multi Cursor?
    - 普通に使えるっぽい？
- Normal mode で行を選択してコピーはどうする？
    - Visualモードの仕事かも
        - `V` 一行選択
        - `v` これで選択できる
- 一単語削除？
    - Normal `b` > `ciw` もっと便利にできないかなこれ
