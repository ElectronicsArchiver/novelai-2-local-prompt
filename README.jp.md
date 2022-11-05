# ja
## INSTALL
~~`nai2local.js`を`stable-diffusion-webui/javascript`に入れてください。~~  
推奨:  
`git clone https://github.com/animerl/novelai-2-local-prompt.git extensions/novelai-2-local-prompt`  
もしくは、WebUIの`Extensions`タブからインストール。
##
<img width="201" src="https://user-images.githubusercontent.com/113022648/197382468-65f4a96d-48af-4890-8fcf-0ec7c3b9ec3a.png">

`NAIConvert`をクリックすると、自動で括弧が処理され、quality tagが追加され、ネガティブプロンプトにNovelAIが利用しているものが自動で追加されます。
ワードに対して適用される倍数は、小数点以下4桁で丸めています。

```
(a),{b},[c]
↓NAIConvert
masterpiece, best quality,
\(a\),(b:1.05),(c:0.9524)
```
`History`をクリックすると、前に生成したプロンプトを新しいものから順に呼び出します。最大保存数はデフォルトで10です(`MaxHistory`)