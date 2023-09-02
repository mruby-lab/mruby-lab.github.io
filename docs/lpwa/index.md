# LPWA

LPWA（Low Power Wide Area）は、IoT（Internet of Things）デバイスやセンサーが低電力で長距離通信を行うための通信技術です。研究室では、LPWA通信技術の一つであるLoRa方式を使って、低コストで強靭なLPWA通信網を実現するための研究開発を行っています。

## 研究の特徴

Private LoRa方式を採用し、独自のプロトコル、経路制御アルゴリズムを研究しています。以下のような特徴を持っています。

- 閉じたネットワーク<br>
外部のネットワーク（インターネット）に接続しない、閉じたネットワークで構成されます。通信キャリアにも依存しないので、場所を選ばずネットワークを構築できます。
- マルチホップ通信<br>
マルチホップ通信により、LPWA通信の到達距離（おおむね数km）の制限を受けず、広域LPWAネットワークを実現します。中継器を柔軟に設置できます。
- セキュリティ<br>
論理的なネットワークを構築するためのセキュリティ機能を持っています。同じ論理ネットワークに属するデバイス同士が通信でき、それ以外の通信を遮断します。<br>**データの暗号化は行っていません。一方で、第三者が不正なデータを送ることはできない仕組みを設けています（なりすまし、データの改ざんができない）**。

## 関連論文

- **Tanaka, K.**, Maeda, H., Yamashita, K., Liu, Y., Hazarika, H.<br>
[Implementation and Proof Experiment of Communication Network for Disaster Prevention Using LPWA](https://doi.org/10.1007/978-3-031-10545-6_4)<br>
Computational Science and Its Applications – ICCSA 2022 Workshops. ICCSA 2022. Lecture Notes in Computer Science, vol 13379. Springer, Cham. https://doi.org/10.1007/978-3-031-10545-6_4
