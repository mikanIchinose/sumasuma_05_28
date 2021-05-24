---
theme: seriph
background: /images/background.jpg
class: text-center
highlighter: shiki
colorSchema: 'dark'
---

# 推しのコミュニティを紹介させて

<!--
今日は布教活動の一環として推しのslackコミュニティを紹介します
よろしくお願いします
-->

<style>
h1 {
  font-size: 3rem!important;
}
</style>

---

# 自己紹介
<!-- 
はじめに自己紹介から
本名:いちのせよしひろ、カラビナネーム:みかん です
担当領域はバックエンドとスマホアプリ開発(嘘)をしています
今は長崎の実家からリモートしてます
今日は僕の今一番推してるコミュニティを紹介させてください
-->

<div grid="~ cols-2 gap4">

<MyImages />

<div>

## name

いちのせ よしひろ<br/>
mikan

## tech

バックエンド(PHP)<br/>
スマホアプリ開発(嘘ホントはテスター)

## home

長崎の実家

</div>

</div>


---

# vim-jp
<!--
vimの紹介

それはvim-jpというvimの日本人コミュニティです。
vimとは非常に癖のある物書きのためのツールです
癖がある反面、使いこなせるようになるとテキスト編集を非常に少ないキー入力で実現できます。
例としてこちらにJavaScriptのコードを用意しました
function say_hello(person,{name: 'kazuya', sex: 'male'},company){
  console.log(`Hello ${person.name}`);
}
例えばconsole.logメソッドの引数のpersonはやっぱりcountry_nameにしたいなと思っておもむろにnの後ろにカーソルを持ってきて6回バックスペースを叩くと思います。vimであれば括弧の付近にカーソルを持ってきてノーマルモードでci(で完了です。コマンドの意味は括弧内を消してインサートモードに入るです。引数が1つだけの場合はバックスペース連打でも問題ありませんが、引数が増えて見やすくするために改行なんかされ始めた日には小指がつってしまいます。でもどんなときでもvimならci(で終了です。ね便利でしょ?
とはいえ癖が強すぎるので嫌煙する人は多いと思いますが、サーバにアクセスする機会が多い人は覚えておいて損は無いと思います。
なぜならサーバにGUIは無いですから全てターミナル内で済ませる必要があります(猛者はremote sshを使ってVSCodeするかも知れませんけどね)。
サーバにはほとんど必ずと言っていいほどvimが用意されているので直接テキスト編集する際はvimを触らざるを得ないこともあるでしょう(どうしても嫌ならnanoを使ってください)

vim-jpの紹介

僕はというとvimのキーバインドに完全に感染してしまいvimと同じような操作感でないと手が受け付けなくなり、VSCodeでvimを再現するプラグインを入れるほどにvimを使っています。
今日紹介するのはそんなvimmerが集まるvim-jpというslackコミュニティです。
ここには初心者からVimコントリビューターまで様々なvim関係者が1670人(5/21時点)集まっています。
vim-jpのslackで何ができるのかそしてvim-jpの素晴らしいところを紹介させてください
-->

<div class="flex">
<div class="w-1/2">

## vim

<VimLogos />

<div class="pr-10">

エディタ
<br/>
ノーマルモード、インサートモード、Exモード、プラグイン、...

</div>

</div>

<div class="w-1/2">

## vim-jp

初心者~コントリビューターまで1670人(5/21時点)ものVimに魅せられたオタクが集まる巨大コミュニティ

### Scackでの雑談が活発に行われています

\#ramdom, 
\#neovim,
\#lang\_rust,
\#os\_linux,
\#picked\_tips,
\#tech\_git,
\#hobby\_gadget
(ごく一部のチャンネルです)
全体で115チャンネル

</div>
</div>

<style>
h3 {
  margin-top: 1rem;
  font-size: 19px;
  opacity: 0.9!important;
}
</style>

---
layout: image-right
image: /images/community.jpg
---

# 居住空間

<!--
まずこのslackでは何ができるのか
何でもできます
vim系の話をするチャンネルが多いですが、ハードウェアやOSの話だったり、はては職業斡旋までしてますw
僕がよく見てるのは雑談チャンネル、CLIチャンネル、nvim,nvim-plugins, manga-animeです。
あまりにも充実してて活発に会話しているのでここに住めます。
-->

- 主にVimに関連するチャンネル
  - プラグイン
  - 使い方
  - キーバインド
  - バグ報告
- ハードウェア
- OS(Linux, Mac)
- __職業斡旋__
<br/>
<br/>

```
朝「さあ、Slackでも見てみるか」


夕方「...おや、一日が終わった」
```

<style>
.slidev-code {
  padding:1.5rem 1rem!important;
}
code {
  font-size: 16px;
}
</style>

---

# 安心して質問ができる
<!--
vim-jpのいいところとして安心して質問できる環境であるところです。
本当に初歩的な質問は見たことないですが、キーバインド変更などでハマった時やプラグインの使い方よくわからなくなったなどの質問は投稿されて5分程度で回答と議論が始まります。初心者お断りの雰囲気は全く無いので調べてもよくわからんとなったときは質問してます。
vim-jpに限らず様々なプログラミング言語系コミュニティ(rust-jpなど)やツールのコミュニティ(emacs-jp)が存在するので学習中でググり力が無いときは有識者のお話が聞けて便利ですし、同じ趣味のオタクが集まっているので普通に会話してるだけでも楽しいので自分の溺愛する技術がある方はその日本人コミュに入ってみてはいかがでしょうか。
-->

<div>
  <div class="w-100 h-auto absolute right-50" v-click="">
    <img src="/images/matanannka.png" alt="また俺なんかやっちゃいました?">
  </div>
  <div class="w-100 h-auto absolute left-30" v-click="">
    <img src="https://gyazo.com/d3fd56ee529787653871a5454711bac6/raw" alt="また俺なんかやっちゃいました?">
  </div>
  <div class="w-100 h-auto absolute right-20 top-30" v-click="">
    <img src="https://gyazo.com/fcbd7821600f24a8525acd2faabc698b/raw" alt="VimっていうTUIがあるんですけど...">
  </div>
  <div class="w-100 h-auto absolute left-60 bottom-5" v-click="">
    <img src="https://gyazo.com/9905bbc167d4ee81c50109244b7d2425/raw" alt="完全なムーブ">
  </div>
</div>


---

# まとめ
<!--
軽くまとめると
- vimはいいぞ
- vim-jpはいいぞ
- コミュニティに参加しよう
-->

<div class="flex">
<div class="w-1/2">

- vimはいいぞ
- vim-jpはいいぞ
- コミュニティに参加しよう
  - __rust-jp__
  - ~~mohikan~~
  - react japan
  - nodered(Node Red)
  - pythonjp
  - scala-jp
  - Engineering Manager Meetup
  - Product Manages Japan(PMJP)

</div>
<div class="w-1/2">

<div>

*slack list ja* にいっぱい載ってた
http://bokuweb.github.io/slack-list-ja/

</div>
<img src="/images/qrcode_bokuweb.github.io.png" width="200"/>

</div>
</div>

---

# おしまい
<!--
ご清聴ありがとうございました。最後にこのスライドは最近話題になっていたSlidevというツールで書きました。
使っていてKaTeXのおかしな挙動を見つけたので人生初のOSSへのissue投稿してみました。markdown + vue3 + windicssで割とリッチなスライドが書けそうなのでおすすめして終わりにしたいと思います。次回はパソチラでお会いしましょう。ということで終わります。
-->
<!-- powered by slidev -->


<div class="h-140 flex flex-col justify-center items-center">
  <div class="text-center text-5xl">
    ご清聴ありがとうございました
  </div>
  <br/>
  <div class="w-full flex justify-center items-center mt-5">
    powered by Slidev(https://sli.dev)<br/>
    <img class="h-20" src="/images/slidev-logo.png">
    <div>
    <img class="w-80" src="/images/slidev-issue.png">
    <div class="text-gray-500 text-xs mt-2">初めてOSSにイシューを出してみました</div>
    </div>
  </div>
</div>
