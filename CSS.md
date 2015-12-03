#CSS設計について

FLOCSSの構成案をベースとする  
https://github.com/hiloki/flocss  

###命名規則
BEMをベースとする

例えば

```css
.p-list__listItem_active {　　
　　
}　　
```

単語のつなぎ目は大文字で記述。  
-はプレフィックスのみで使用する。

####Utility

ユーティリティの命名はEmmetのチートシートを参考にすること。  
例えば、font-weight: bold;を書きたければ、プレフィックス以降は「:」を省略したfwbをつけ.u-fwbとする。  
!importantをつける。

###単語の省略について

以下の単語については省略  
- annotation → annot  
- banner → bnr  
- button → btn  
- content → cont  
- description → desc  
- information → info  
- introduction → intro  
- navigation → nav  
- position → pos  
- section → sec  
- template → temp  

###class、id命名の例外
styleを持たないJavaScriptのみで使用するclass名、id名はキャメルケースで記述。FLOCSSとは切り離して考える。


