# 漢字直接入力コミュニティサーベイ

|FIELD1   |OS                     |漢直スタイル  |漢直実現方法                                                                                               |
|---------|-----------------------|--------|-----------------------------------------------------------------------------------------------------|
|kozo2    |Windows                |T-Code  |https://meech.hatenadiary.org/entry/20101222/1293037939 と 漢索JS。ベストプラクティスは https://kanchoku.github.io/|
|nyaocat  |Linux                  |G-Code  |uim-tutcode + 自作のgcode設定ファイル                                                                         |
|nixeneko |Windows                |TUT-Code|漢直Win https://github.com/kanchoku/kw                                                                 |
|naota    |Linux                  |T-Code  |PC https://github.com/naota/fcitx-tcode Android 自作のT-Code IME                                        |
|yoyuse   |macOS                  |TT-Code |Emacs + 自作 elisp (未公開)。MacUIM + 自作の TT-code 設定ファイル                                                   |
|deton    |Windows, Linux, Android|TUT-Code|tcvime, tsf-tutcode, AndroidTUTCode                                                                  |
|na4zagin3|Linux                  |TUT-Code|Emacs + tc.el, uim-tutcode; 旧字用キーマップを https://github.com/na4zagin3/uhim-dict で生成                     |

# 漢字直接入力比較表

|FIELD1   |ひらがな入力方法               |カタカナ入力方法|漢字入力方法                                                                                               |規則性(連想性)      |入力実現方法                                                  |ウェブサイト                                       |
|---------|-----------------------|--------|-----------------------------------------------------------------------------------------------------|--------------|--------------------------------------------------------|---------------------------------------------|
|T-Code   |無連想2打鍵                 |無連想2打鍵 (ただし変換によって入力することが多い)|無連想2打鍵 (ただしひらがなからの変換で入力することはよくある)                                                                    |完全に無し         |https://github.com/kanchoku/tc#install%E6%96%B9%E6%B3%95|http://openlab.ring.gr.jp/tcode/intro.html   |
|         |                       |        |                                                                                                     |              |https://meech.hatenadiary.org/entry/20101222/1293037939 |                                             |
|         |                       |        |                                                                                                     |              |https://github.com/deton/tsf-tutcode                    |                                             |
|         |                       |        |                                                                                                     |              |https://github.com/naota/fcitx-tcode                    |                                             |
|TUT-Code |規則的2～4打鍵(原則清音2打, 濁音3打, 半濁音4打)|ひらがなと同一打鍵で、切り替えて入力|無連想2～3打鍵                                                                                             |かなのみ。漢字はなし    |https://github.com/kanchoku/kw                          |https://crew-lab.sfc.keio.ac.jp/projects/tut/|
|G-Code   |                       |        |                                                                                                     |              |                                                        |                                             |
|TT-Code  |T-Code準拠               |T-Code準拠|T-Code準拠の2打鍵 + 4打鍵拡張(頻度別に3分類し、各分類内はJISコード順)                                                          |拡張部分はJISコード順など|                                                        |                                             |
