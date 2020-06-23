# Gaussian Process Test
全てgoogle colabで動作することを確認しています．

## シンプルなGP
- [Pytorch実装](gp_torch.ipynb)
- [Cython実装](gp.ipynb)

## 多出力GP
- [Notebook](MultiOutputGP.ipynb)
- Mauricio A. Alvarez, Lorenzo Rosasco, Neil D. Lawrence, "Kernels for Vector-Valued Functions: a Review"　https://arxiv.org/pdf/1106.6251.pdf

## 補助点を使ったGP
- [numpy実装](sor_gp_np.ipynb)
- [pytorch実装](sor_gp.ipynb)：GPUを使ってもあまり高速化しなかった・・・
- Joaquin Quinonero-Candela, Carl Edward Rasmussen, "A Unifying View of Sparse Approximate Gaussian Process Regression," Journal of Machine Learning Research, pp. 1939–1959, 2005

## 補助変数法GPの変分ベイズ学習
- [Notebook](vbgp.ipynb)
- Titsias, Michalis. "Variational learning of inducing variables in sparse Gaussian processes." Artificial Intelligence and Statistics. 2009


## 補助変数法GPの変分ベイズ学習に基づく方策探索
- [Notebook](vbgp_policy_serch.ipynb)
- 状態（入力）x，アクション（出力）y，と報酬rから，変分ベイズを使ってGPの補助入力点とハイパーパラメータを学習します

## Gaussian Process Latent Variable Models
- [Notebook](gplvm.ipynb)
- Lawrence, Neil D. "Gaussian process latent variable models for visualisation of high dimensional data," Advances in neural information processing systems, 2004

## 畳み込みGP
- 単純な方法：[Notebook](conv_gp_torch.ipynb)
- 変分ベイズで畳み込みのパッチを学習する方法：[Notebook](conv_vbgp.ipynb)
- Mark van der Wilk, Carl Edward Rasmussen, James Hensman, "Convolutional Gaussian Processes", NIPS, 2017
