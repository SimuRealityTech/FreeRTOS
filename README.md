通常のプログラムは
→Aタスク→Bタスク→Cタスク→・・・→のような
大循環式でプログラムを作成しています。問題点としては、一が所問題が発生すると、システム全体が崩壊します。
また、順番でタスクを実行するため、リアルタイム性がありません。
この欠点を無くすために、リアルタイムOSが誕生しました。

リアルタイムOSでのプログラムは
Aタスク、Bタスク、Cタスク、･･･すべて独立で存在します。必要に応じてタスクが自由に選びんで実行、あるいは制御できます。
そうすると、故障したタスクを停止し、スステムが崩壊しません。また、タスクに優先順位をつければ、先に実行されます。
リアルタイム性も確報できます。

本コードはESP32用FreeRTOSを使ってプログラムを作成した。勉強のため、少しずつ精進していきます。