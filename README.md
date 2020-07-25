# Pytorchを用いて航空機の撮像画像から建物セグメンテーションの作成方法のデモンストレーション．

Pytorchを用いて航空機の撮像画像から建物地図のセグメンテーションを作成しました．
詳細は以下の記事をご参考ください．

https://qiita.com/nigo1973/items/1d7495a963c23c97189c

手順
１．make_training_data_A.ipynbを実行し，学習および検証用データを準備する．
２．SMP_Unet_A.ipynbを実行し，１で準備した学習データを用いて建物セグメンテーションのモデルを構築する．
　　このモデルを，検証用データを用いて評価する．
