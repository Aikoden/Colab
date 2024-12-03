Many public datasets such as UCI repositories  
Exercise 演習問題

1

Download the following datasets from the UCI repositories:
次のデータセットを UCI レポジトリからダウンロードする.

Australian
Bank
Car (Car Evaluation Database)
CMC (Contraceptive Method Choice)
Echo (Echocardiogram Data)
German (German Credit Data)
Hepatitis (Hepatitis Domain)
Ilpd (Indian Liver Patient Dataset)
Seeds
Spect (SPECT Heart)
Tae (Teaching Assistant Evaluation)
Waveform2 (Teaching Assistant Evaluation, Version 2)
Wholesale (Wholesale customers)
For each dataset, divide data in each category into two subsets with ratio of 70% to 30%. The two datasets are used for training and testing, respectively.
データセットそれぞれに対して, クラスごとに 7:3 で訓練用データと評価用データに分けよ.
2クラス分類でないと, 先に進めないので, 最も大きいクラスを +1, それ以外を -1 にした2クラス分類に変換しましょう.




6

Try both L2-normalization and L1-normalization for data normalization. The regularization parameter λ\lambdaλ should be determined by cross-validation within a training dataset based on PRBEP.
学習法には, 各例題に L2正規化, L1正規化それぞれを考える. それぞれに対して, 正則化パラメータ λ\lambdaλ の値を訓練用データ内で交差確認を用いて, PRBEP をもとに推定せよ.


7

Compute PRBEP with the regularization parameter λ\lambdaλ using the testing dataset for each dataset and each normalization method.
推定した λ\lambdaλ を使って評価用データの PRBEP を計算せよ.


8

Repeat the steps 5-7 ten times, to get 10 PRBEP and to get the table of P-values based on the one sample t-test.
ステップ 5-7 を10回繰り返すことで, それぞれの方法で10個の PRBEP を算出し, one sample t-test で P 値の表を算出せよ.





9

Make a table of the mean and the standard deviation of PRBEP such as acctab1-kato.2002110816.pdf. For each dataset, the maximal PRBEP should be bold-faced, and the PRBEP with no significant difference from the maximal PRBEP should be underlined. See 2019/acctab1.
PRBEP の平均と標準偏差を acctab1-kato.2002110816.pdf のような表にする. ただし, 各データセットで最大の PRBEP を太字で, 最大の PRBEP と有意差がないものに下線を引く. やり方は 2019/acctab1 を参照.
