# StudyStableBaselines

このリポジトリは、強化学習ライブラリ [Stable Baselines3](https://github.com/DLR-RM/stable-baselines3) の学習・実験用プロジェクトです。

## 目的

- Stable Baselines の基本的な使い方を学ぶ
- 代表的なアルゴリズムの実装例を試す
- 独自の環境やカスタマイズ手法を検証する

## セットアップ

conda環境を使用して, Stable Baselinesの環境を立てる(事前にcondaをインストール済みのこと)
```bash
$ conda create -n stable_baselines python=3.10
$ conda activate stable_baselines
$ conda install -c conda-forge mesa-libgl
$ pip install numpy==2.1.1
$ pip3 install stable-baselines3[extra] 'gymnasium[other]' imitation pyglet
```

## 参考リンク

- [Stable Baselines3 ドキュメント](https://stable-baselines3.readthedocs.io/ja/master/)
- [OpenAI Gym](https://www.gymlibrary.dev/)