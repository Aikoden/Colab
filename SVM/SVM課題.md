Exercises

1.1

Implement K-means described in k-means-clustering-Wikipedia.2002271236.pdf.
Use the one denoted by naive algorithm in the document.

Translation: k-means-clustering-Wikipedia.2002271236.pdf にある K平均法(naive algorithm)を実装せよ．




1.2

Plot 100 two-dimensional data points and plot by the following code:


 ntras = 100;
 thets = rand(1,ntras)*(2*pi); 
 radis = rand(1,ntras)*0.1+1.0; 
 X     = [cos(thets);sin(thets)]*diag(radis); 
 plot( X(1,:), X(2,:), 'ko' );
 csvwrite( 'k.X.csv', X' ); 



1.3

Set K=2 and record the value of Within-cluster sum of squares (WCSS). Plot WCSS against interation numbers. Verify that the curve is monotonically decreased.

Translation: K=2 とし，Within-cluster sum of squares (WCSS) の値を記録しろ．横軸反復数，縦軸 WCSS として，グラフを描け．ヒント（関数 plot）．単調減少していることを確かめよ．




1.4

Plot K-means with K=2,3,4. Use different colors for different clusters. Use of function print_eps_and_png is recommended to generate figures.

Translation: クラスタ数 2, 3, 4 の場合で K平均法を適用しろ．
クラスタリング結果をもとに色付けしてプロットせよ．




1.5

Create the following function. The function applies K-means five times with different initial solutions. The solutions are chosen randomly. Find the minimal one from the five WCSS, and return the assignment associated with the minimal WCSS.

Translation: 初期割当をランダムに選んで，５回 K 平均法を行い，最も J(U,V) が小さい結果を最終結果とするような関数を作れ．
