# Google日本語入力用AZIK
azik.tsvをGoogle日本語入力のカスタムローマ字テーブルとしてインポートすると、AZIKを使えるようになります。	
	
[公式](http://hp.vector.co.jp/authors/VA002116/azik/azikinfo.htm)では、
> 通常のＦＥＰのローマ字変換テーブルでは、クヮ、グェ、ヴュなどの特殊な拗音も定義されていますが、これらは頻度が低いのでわざわざ覚えるよりも「ク」と「ヮ」のように分けて入力した方が覚えることも少なく結局速く打てます。	

とされていますが、このテーブルでは、特殊な拗音もAZIKとバッティングしないものについてはすべて定義しています。	

## azik-extend.tsvについて
azik-extend.tsvは、AZIKの独自拡張バージョンです。通常のAZIKと完全な互換性があります。  
拡張したのは以下の点です。
- 母音の右上(もしくは右)にあるキー使うことで「っ」を補完できます。
  - 例: ks -> かっ
  - 例: k9 -> きっ
  - 例: k8 -> くっ
  - 例: k4 -> けっ
  - 例: k0 -> こっ
- 「@」をきゃ行として使えます。
  - 例: @a -> きゃ
  - 例: @i -> きぃ
  - 例: @u -> きゅ
  - ...
