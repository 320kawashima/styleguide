#CSS設計について

FLOCSSの構成案をベースとする  
https://github.com/hiloki/flocss  

###命名規則
mindBEMDingをベースとする  
※objectはプレフィックスをつける  


単語のつなぎ目の頭文字は大文字で記述。  
-はプレフィックスのみで使用する。  
__はblockとelementの区切り。  
--はmodifierの直前のみ
-はkeyとvalueのつなぎとして使用する。  

####JSで使用するclass名の命名規則
js-のプレフィックスをつける

####Utilityの規則

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