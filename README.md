# explorer-use-singleGPU(<= 16GB VRAM)
## 概要
比較的安価な単一のNvidia製GPU(VRAM 8GB～16GB)のみを使用し、自然言語処理や音声認識、画像処理プログラムの動作検証を行うリポジトリです。  
20万円～30万円ほどのミドルクラス家庭用PCで何ができて何ができないのかをまとめることを目標にしています。

## 検証用PC構成
| パーツ | 仕様 |
|--------|------|
| CPU | Ryzen 7 5700X |
| RAM | DDR4 32GBx2 |
| GPU | RTX4060Ti 16GB |
| SSD | M.2 NVMe 2TB |
| HDD | SATA 2TB |
| OS | Ubuntu Server 22.04.4 LTS |

## ToDo
- [ ] BERT系モデルを使った画像検索
- [ ] GPT系モデルを使ったメール入力補助(メール版のGitHub Copilotのような)
- [ ] T5系モデルを使った要約タスク
- [ ] STT系モデルを使った音声認識とBERT系モデルを使った会議重要ポイント抽出
- [ ] CLIP、BLIP-2モデルを使った画像キャプショニング
- [ ] GPT系モデルを使った会話botをCPU推論
- [ ] GPT、BERT系モデルの事前学習
- [ ] [margekit](https://github.com/arcee-ai/mergekit)を使ったモデルマージ
- [ ] その他(GPT系7BモデルのGPU推論、LoRAでのSFT、...)

## Notes
- 私はプログラミングや機械学習について経験が浅いため、読みにくいコードや誤りを書いている可能性があります。その場合はご指摘いただけますと大変ありがたいです。
