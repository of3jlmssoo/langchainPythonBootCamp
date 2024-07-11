- コースのcontext compressionでは返されるドキュメントがゼロ。ただし、データはセーブされたものをロードしたもの
- langchainのマニュアルだと1ドキュメント返される(01-09-context-comp-lchain.ipynb)。ただし、langchainのマニュアル例だと追加の部分ではthreshholdの調整が必要

コースの方でテキストロード、スプリット、Chroma DB作成で試したところ、それなりの文書が返された。
