---
theme: seriph
background: /images/background.jpg
class: text-center
highlighter: shiki
colorSchema: 'dark'
---

# 推しのコミュニティを紹介させて

<style>
h1 {
  font-size: 3rem!important;
}
</style>

<!--
今日は布教活動の一環として推しのslackコミュニティを紹介します。
よろしくお願いします
-->

---

# 自己紹介

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

<!-- 
はじめに自己紹介から
名前はいちのせよしひろでカラビナネームはみかんです。
担当領域はバックエンドとスマホアプリ開発をしています。
今は長崎の実家からリモートしてます
-->

---

# vim-jp

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

<!--
vimの紹介

早速本題に入りますが、今日紹介したいコニュニティはvim-jpです。
vimというのは非常に癖のある物書きのためのツールです。
癖がある反面、使いこなせるようになるとテキスト編集を非常に少ないキー入力で実現できます。

例としてこちらにJavaScriptのコードを用意しました

function say_hello(person,{name: 'kazuya', sex: 'male'},company){

  console.log(`Hello ${person.name}`);

}

(実践)

癖が強すぎるので嫌煙する人は多いと思いますが、サーバにアクセスする機会が多い人は覚えておいて損は無いと思います。
なぜならサーバにGUIは無いですから全てターミナル内で済ませる必要があります(猛者はremote sshを使ってVSCodeするかも知れませんけどね)。
サーバにはほとんど必ずと言っていいほどvimが用意されているので直接テキスト編集する際はvimを触らざるを得ないこともあるでしょう(どうしても嫌ならnanoを使ってください)

vim-jpの紹介

僕はというとvimのキーバインドに完全に感染してしまいvimと同じような操作感でないと手が受け付けなくなり、VSCodeでvimを再現するプラグインを入れるほどにvimを使っています。
今日紹介するのはそんなvimmerが集まるvim-jpというslackコミュニティです。
ここには初心者からVimコントリビューターまで様々なvim関係者が1670人(5/21時点,現在は1800人を超えています)集まっています。
vim-jpのslackで何ができるのかそしてvim-jpの素晴らしいところを紹介させてください
-->

---
layout: image-right
image: /images/community.jpg
---

# 居住空間

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

<!--
まずこのslackでは何ができるのか。
何でもできます。
vim系の話をするチャンネルが多いですが、ハードウェア(自作キーボードなどの作る系)やOSの話だったり、はては職業斡旋までしてますw
僕がよく見てるのは雑談チャンネル、CLIチャンネル、NeoVim, Gadgetというなの散財チャンネル,そしてmanga-animeです。
あまりにも充実していて、活発に会話がおこなわれているのでここに住めます。
朝開いてみてなんとなく会話を追っていると、いつの間にか夕方になってるなんてこともザラにあります
-->

---

# 安心して質問ができる

<div>
  <div class="w-200 h-auto absolute left-30" v-click="">
    <img src="https://gyazo.com/d3fd56ee529787653871a5454711bac6/raw" alt="また俺なんかやっちゃいました?">
  </div>
  <div class="w-100 h-auto absolute right-50 top-30" v-click="">
    <img src="/images/matanannka.png" alt="また俺なんかやっちゃいました?">
  </div>
  <div class="w-100 h-auto absolute left-60 bottom-5" v-click="">
    <img src="https://gyazo.com/9905bbc167d4ee81c50109244b7d2425/raw" alt="完全なムーブ">
  </div>
</div>

<!--
vim-jpのいいところとして安心して質問できる環境であるところです。
本当に初歩的な質問は見たことないですが、
キーバインド変更などでハマった時やプラグインの使い方よくわからなくなったなどの質問が投稿されて
5分程度で回答とそれをもとに議論が始まります。
初心者お断りの雰囲気は全く無いので調べてもよくわからんとなったときは質問してます。
vim-jpに限らず様々なプログラミング言語系コミュニティ(rust-jpなど)やツールのコミュニティ(emacs-jp)が存在するので
学習中の技術でググり力が無いと思った時は有識者のお話が聞けて便利ですし、
同じ趣味のオタクが集まっているので普通に会話してるだけでも楽しいので、自分の溺愛する技術がある方はその日本人コミュニティに入ってみてはいかがでしょうか。
-->

---

# まとめ

<div class="flex">
<div class="w-2/5">

- vimはいいぞ
- vim-jpはいいぞ
- コミュニティに参加しよう
  - __rust-jp__
  - ~~mohikan~~
  - nodered(Node Red)
  - pythonjp(discord)
  - scala-jp
  - firebase japan user group(FJUG)
  - Engineering Manager Meetup
  - Product Manages Japan(PMJP)

</div>
<div class="w-3/5 flex flex-col justify-center">
  <div>
    さまざまなコミュニティを見て、これだけは言える
    <div class="text-3xl text-blue-400 my-5">
      「vim-jpが一番<span class="text-purple-800">カオス</span>で一番楽しい」
    </div>
    エンジニアの楽園の名は伊達ではない
    </div>
  </div>
</div>

<!--
軽くまとめると
- vimはいいぞ
- vim-jpはいいぞ
- コミュニティに参加しよう

下に軽くググって見つけた日本人コミュニティを載せています
この中で所属しているのはRust-jpとmohikanというワークスペースですが、mohikanはおすすめしません見にくいので。
各コミュニティにいろんな特色がありますが、これだけは言えることはVim-jpが一番カオスで一番楽しい
Vim-jpをエンジニアの楽園と称したブログがあるんですが、まさにその名は伊達ではありません
-->

---

# ご清聴ありがとうございました

<div class="flex justify-center items-center h-110">
  <div class="flex flex-col">
    <img class="h-70 mr-20" src="/images/slidev-logo.png">
    <div class="text-xl text-gray-500">
      powered by Slidev(https://sli.dev)
    </div>
  </div>
  <div class="flex flex-col">
    <div class="w-full flex justify-center items-center mt-5">
      <div>
      <img class="w-70 py-1" src="/images/slidev-issue.png">
      <img class="w-70 py-1" src="/images/slidev-0.13.11.png">
      </div>
    </div>
  </div>
  <br/>
</div>

<!--
ご清聴ありがとうございました。
最後にこのスライドは最近話題になっていたSlidevというツールで書きました。
使っていてKaTeXのおかしな挙動を見つけたので人生初のOSSへのissue投稿してみました。markdown + vue3 + windicssで割とリッチなスライドが書けそうなのでおすすめです。
ではこれで終わりにします。
-->
