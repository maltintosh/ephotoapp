# ePhotoapp
写真をAIにより管理するWebアプリケーション
アップロードした画像を機械学習により自動でタグ付し、写真管理をしやすくしたアルバムアプリケーションです。
WebフレームワークはDjangoを使っており、機械学習部分はGoogleのObjectDetectionAPIを用いています。
フロントエンドはBootstrap4やjQueryを用いています。
UIには力を入れており、写真をアップロードする過程の画面遷移を考えて制作しました。
また、写真をアップロードするだけでなく、その写真を使って間違え探しのできるゲーム機能をつけてあります。
aws EC2
wsgi gunicorn
server nginx
db postgresql
