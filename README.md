# OF_doublePendulum
OpenFOAMのrigidBodyMotionによる二重振り子のケースです。
pimpleFoamを使用していますが、流体ソルバーは動かない設定にしてあるので、rigidBodyMotionの機能だけで動作しています。

2つのおもりの外側にメッシュを作成して、オーバーセットメッシュの設定を行い、境界条件などを正しく設定すれば、流体抵抗を考慮した計算もできると思います。

## 実行方法
OpenFOAM v2212で動作確認をしています。
`doublePendulum/Allrun`を実行してください。

## 可視化サンプル

![doublePendulum](https://github.com/user-attachments/assets/17c0bf36-e9d2-4223-ba17-175467ba165d)
