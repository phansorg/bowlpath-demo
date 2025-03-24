# bowlpath-demo

python 3.13.2

## 仮想環境を作成

python -m venv venv

## 仮想環境を有効化

venv\Scripts\activate

## 仮想環境を無効化

deactivate

## pytorchのインストール

```shell
pip install torch torchvision torchaudio --index https://download.pytorch.org/whl/cu118
```

## 動作確認

```shell
python -c "import torch; print(torch.__version__, torch.cuda.is_available())"
```

## パッケージのインストール

- ultralytics
