# ReedSW Unit

<img src="https://github.com/akita11/ReedSWUnit/blob/main/ReedSWUnit.jpg" width="320px">

磁石を近づけるとONになるリードスイッチのUnitです。ネオジム磁石のような強い磁石であれば5mm程度近づけるだけでONになります。ONになるとLEDが点灯します。UIFlowなどからは、M5Stackの[ボタンUnit](https://www.switch-science.com/products/4047)と同じように扱うことができます。

※OFF時にLEDがうっすらと点灯しますが、異常ではありません（LEDに流れている電流は20uA程度ですが高輝度LEDのためうっすらと点灯しているように見えます）

## ピン配置

Grove端子の1番から順に「SW（負論理）」「無接続」「VDD(5V/3.3V)」「GND」の順です。


## Author

Junichi Akita (akita@ifdl.jp, @akita11)
