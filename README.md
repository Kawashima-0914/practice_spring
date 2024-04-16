このリポジトリは、行きたい温泉地を開拓するためのwebページを作成、表示するためのものです。
ただ温泉を調べるのではなく、あなたが行ったことのある温泉地の中でそれに近い温泉を探したいと思ったときに、使えるようなサイトを考えました。
不出来なとこあると思いますが、次の行きたい温泉地を探すツールとして使って貰えれば良いと思い、制作しました。//
温泉地の泉質を第1に考え、それに加え、温泉地の風景、歴史などの概要を元に類似度を出し、似ている温泉地を割り出しました。
概要などの類似度を計算する際は、概要を単語に切り分け、chiveを用いました。
デプロイはしていませんが、実際に動かしてみたい方がいましたら、私がリアルタイムで動かす必要がありますが、ngrokで動かすので、ご連絡ください。
→kawork0914@gmail.com
より詳しく見たい方は、私のリポジトリvideoにspring.mp4として乗せているのでお手数ですが、ご覧ください。
→https://github.com/Kawashima-0914/video

https://github.com/Kawashima-0914/practice_spring/assets/149990150/b97d398f-7c34-4518-8997-0572337407c8





webページの概要としては、1.温泉の4つランキング(総合、泉質、雰囲気、食べ物)、2.日本地図から温泉を探す、3.温泉の泉質について、4.私の情報のページ
![スクリーンショット (97)](https://github.com/Kawashima-0914/practice_spring/assets/149990150/73a5f5f8-e9d0-4d41-bfd8-e5009647bd99)
上のページが最初のページであり、上記の1~4にアクセスすることができます。
また、それぞれのページに配置してある左上の温泉マークからいつでもこの最初のページにもどることができます。
![スクリーンショット (95)](https://github.com/Kawashima-0914/practice_spring/assets/149990150/bb99e1fd-4cca-41b4-84bc-e4b5e422fd5b)
最初のページの検索欄で、それぞれの温泉地のページへアクセスすることができます。(漢字、ローマ字、カタカナ入力できます)
それぞれの温泉地のページには、その温泉地に似ている温泉を表示するようになっています。

参考サイトとして以下を使用させていただいています。
ゆこゆこ、https://www.yukoyuko.net/onsen/search
観光経済新聞、https://www.kankokeizai.com/100sen_36/

観光経済新聞様では、表のみを使用しています。





