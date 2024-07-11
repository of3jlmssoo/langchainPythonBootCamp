- コースのcontext compressionでは返されるドキュメントがゼロ
- langchainのマニュアルだと1ドキュメント返される
- ただし、langchainのマニュアル例だと追加の部分ではthreshholdの調整が必要

違いは、
- 元のテキストドキュメント
- コースはChroma、マニュアルはFAISS
なので、マニュアルの方をChromaにしてみる。

コースの方でテキストのスプリット、Chromaの作成からやり直すと１文書返されたのでデータをロードしたChromaの方に問題があったよう。