検査設定の確からしさを評価するツールです。
  
Result.ipynb  
input.csvからt-SNEとRandom Forest、XGBoostの結果を出力したもの
t-SNEの結果をoutput.csvとして出力　　

input.csv  
ImageId 画像ID  
PinNumber 各画像におけるピン番号  　
VisualResultType  0:良品、0以外: 不良品  
Result  VisualResultTypeから良品・不良品を0, 1 にラベルづけしたもの  
logic1 - logic10  各検査の計測値  

output.csv
x t-SNEの各点のx座標  
y t-SNEの各点のy座標  
それ以降の列はinput.csvに同じ  

