#CSS設計について

FLOCSSの構成案をベースとする  
https://github.com/hiloki/flocss  


###class、id命名の例外
Styleを持たないJavaScriptのみで使用するclass名、id名はキャメルケースで記述。FLOCSSとは切り離して考える。


###単語の省略について

以下の単語については省略  
- annotation → annot  
- banner → bnr  
- button → btn  
- content → cont  
- description → desc  
- navigation → nav  
- section → sec  
- Template → temp  



##Utility

ユーティリティの命名はEmmetのチートシートを参考にすること。  
例えば、font-weight: bold;を書けたければ、プレフィックス以降は「:」を省略したfwbをつけ.u-fwbとする。  
!importantをつける。

