# To run it on GCloud instance:

```bash
sudo apt-get update && sudo apt-get install -y libbz2-dev libncurses5-dev libffi-dev libreadline-dev libsqlite3-dev liblzma-dev libssl-dev

curl https://pyenv.run | bash

# ADD pyenv TO PATH AND INIT IT

pyenv install 3.11

pyenv global 3.11

pip install -U pip

pip install torch transformers einops triton flash-attn mosaicml onnx onnxruntime numpy
```
