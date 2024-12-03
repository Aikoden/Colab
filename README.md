# 学校課題の練習プロジェクト

## 概要  
このプロジェクトは、機械学習および深層学習に関連する複数の Jupyter Notebook を含む、学校課題の練習用プロジェクトです。サポートベクターマシン（SVM）、k 近傍法（KNN）、行列積の検証、画像セグメンテーション、PyTorch の基礎演習、UCI データセットを使用した演習など、多岐にわたる内容を網羅しています。データの前処理からモデルの訓練、結果の可視化までを学ぶことができます。

## 使用技術  
- **プログラミング言語**：Python 3.x  
- **Jupyter Notebook**（主に Google Colab で作成）  
- **機械学習ライブラリ**：  
  - Scikit-learn：SVM、KNN モデルの実装  
  - NumPy、Pandas：データ処理と行列計算  
  - Matplotlib、Seaborn：データの可視化  
- **深層学習フレームワーク**：PyTorch

## 必要条件  
これらのノートブックを実行するには、以下の環境が必要です。  
1. **Google Colab**（推奨）：  
   - 追加の環境構築は不要で、ブラウザ上でノートブックを開くだけで使用可能です。  
2. **ローカル環境**（オプション）：  
   ローカル環境で実行する場合、以下の依存関係をインストールする必要があります。  
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn torch
   
Matrix_multiplication_verification.ipynb：行列積の検証。
SVM.ipynb：サポートベクターマシン（SVM）の分類例。
knn_exercises.ipynb：KNN アルゴリズムの練習。
Segmentation.ipynb：画像セグメンテーションの例。
pytorch01.ipynb、pytorch02.ipynb：PyTorch の基礎練習。
制約付最適化d01.ipynb：制約付き最適化問題の練習。
