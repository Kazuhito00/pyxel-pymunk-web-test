# pyxel-pymunk-web-test
Qiita Pyxel アドベントカレンダー(2024年12月24日)の投稿「[「Pyxel × Pymunkで物理シミュレーションを始めよう！」を Webで動かしたい🌎](https://qiita.com/Kazuhito/private/cf7f2e0f42f47e611f3e)」で使用したソースコードです。

![mqgaj-qat4l](https://github.com/user-attachments/assets/ca75e82c-bd23-42cd-8c19-819703f411ad)

# Requirements 
```
pyxel==2.2.7
pymunk==6.10.0
```

# 1．ローカルPC
実行コマンドは以下の通り。
```python
python shot_bullet.py
```

# 2．Web
Web版のデモは以下のURLで公開しています。<br>
https://kazuhito00.github.io/pyxel-pymunk-web-test/

実行コマンドは以下の通り(ローカルで試す場合)
```python
pyxel package ./ shot_bullet.py
python -m http.server 8000
```

# Authors
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
pyxel-pymunk-web-test is under [MIT License](LICENSE).
