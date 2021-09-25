# Deeper-Depth-Estimation

深度推定のexample リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── Boostmonoculardepth.ipynb
│   ├── Monocular_Depth_Estimation_Keras.ipynb
│   ├── monodepth2_depth_prediction_example.ipynb
│   └── octDPSNet_demo.ipynb
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Deeper-Depth-Estimation）

```
cd Desktop/Deeper-Depth-Estimation
```

- Dockerによる環境構築（フォルダをマウント：Desktop/Deeper-Depth-Estimation）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
