# AI-CUP2025

## 1. 專案在做什麼
使用 Ultralytics YOLO 訓練心臟瓣膜（aortic valve）單類別物件偵測模型，並在測試/評估集輸出預測與錯誤分析結果。

#123

## 2. 執行環境（跑得起來需要什麼）
 Ultralytics: 8.3.228
- Python: 3.10.19
- PyTorch: 2.5.1+cu121
- CUDA: 12.1
- GPU: NVIDIA GeForce RTX 2080 Ti (11GB)

> 註：以上為本次作者訓練/驗證時的實際環境版本。若在其他電腦或 Colab 執行，版本可能不同，但 notebook 流程相同。

安裝套件（第一次跑才需要）：
```bash
pip install ultralytics torch torchvision torchaudio pandas numpy matplotlib pillow
