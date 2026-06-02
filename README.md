# DesignSpark PCB オリジナルライブラリ

DesignSpark PCB 用のオリジナルコンポーネントライブラリです。

**対応バージョン:** DesignSpark PCB v13.0.2

## ファイル構成

| ファイル | 説明 |
|---|---|
| `Original.cml` / `Original.cmx` | コンポーネントライブラリ（回路シンボルとPCBフットプリントの対応付け） |
| `Original.ssl` / `Original.ssx` | 回路図シンボルライブラリ |
| `original.psl` / `original.psx` | PCBフットプリントライブラリ |
| `metric_2layer_mechanical.ptf` | 2層基板メカニカルレイヤー設定 |

## 登録コンポーネント一覧

### マイコン・モジュール

| コンポーネント | 説明 |
|---|---|
| `mbed LPC1768` | mbed マイコンボード |
| `GR-KURUMI` | Renesas GR-KURUMI ボード |
| `GR-SAKURA` | Renesas GR-SAKURA ボード |
| `PIC24FJ64GB002` | Microchip PIC マイコン (DIP28) |
| `RL78G13_48` | Renesas RL78/G13 マイコン (48ピン) |
| `R5N563N` | Renesas RX63N マイコン (QFP100) |
| `WRBB` | Wakayama.rb ボード |

### 無線・通信モジュール

| コンポーネント | 説明 |
|---|---|
| `RN42` | Bluetooth モジュール (Roving Networks) |
| `XBEE Adapter` | XBee アダプタ |
| `3G Shield` | 3G 通信シールド |
| `GPS LS20031` | GPS モジュール |
| `OpenLog` | シリアルロガーモジュール |

### センサー

| コンポーネント | 説明 |
|---|---|
| `MPU9150` | 9軸 IMU（加速度・ジャイロ・磁気） |
| `IMU6Degrees` | 6軸 IMU |
| `L3GD20` | 3軸ジャイロスコープ |
| `LPS331AP` | 気圧センサ |
| `ADT7420` | 温度センサ |
| `KXSD9-2050` | 3軸加速度センサ |
| `NJL7502` / `NJL7502L` | 照度センサ |
| `S11059_02DT` | カラーセンサ |
| `S9706` | フォトダイオードアレイ |
| `JpegCamera` | JPEG カメラモジュール |

### アナログ IC

| コンポーネント | 説明 |
|---|---|
| `AD8237` | 計装アンプ (MSOP8) |
| `AD8553` | 計装アンプ (MSOP10) |
| `REF43` | 電圧リファレンス (SOIC-8) |
| `NJM2845DL1-18` / `-33` | LDO レギュレータ (+1.8V / +3.3V) |
| `MAX1555` | リチウムイオン電池充電IC (SOT23-5) |
| `BCR5AM` | LED ドライバ |

### パワー系

| コンポーネント | 説明 |
|---|---|
| `TA7291P` | モータードライバ IC |
| `FDS5680` | N チャンネル MOSFET |
| `EMH7601` | MOSFET |
| `PRTR5V0U4D` | ESD プロテクション (SOT457) |
| `RB751S-40` | ショットキーダイオード (1608) |
| `6D0F` | ダイオードアレイ |
| `CR2450` | コイン電池ホルダー |

### コネクタ

| コンポーネント | 説明 |
|---|---|
| `UX60A-MB-5ST` | Mini-USB Type-B コネクタ |
| `ZX62R-B-5P_microUSB` | Micro-USB Type-B コネクタ |
| `microSD_DM3AT-SF-PEJM5` | microSD カードスロット |
| `XF2M10151A` | FFC/FPC コネクタ |
| `JTAG-E1` | JTAG コネクタ (14ピン) |
| `CON6` / `CONN8` / `CONN12` 等 | 各種ピンヘッダ |
| `CN2L14` | 2列14ピン コネクタ |

### 受動部品・その他

| コンポーネント | 説明 |
|---|---|
| `R1608` | 抵抗 (1608/0603) |
| `C1608` / `C2012` | コンデンサ (1608/2012) |
| `CT-47uF` / `CT-47uF-little` | タンタルコンデンサ (47μF) |
| `L-CD54` | インダクタ |
| `FB` | フェライトビーズ (1005) |
| `R4Net` | 抵抗ネットワーク (4素子) |
| `CX8045` | クリスタル発振子 |
| `MC-146` | クリスタル 32.768kHz |
| `LCD I2C SB1602B` | I2C 接続 LCD モジュール |
| `SW_SKRPACE010` | タクトスイッチ |
| `SW_DIP8SM` | DIP スイッチ (8回路 SMD) |
| `MHS121` / `MHS122-1` | スライドスイッチ |
| `PiezoBuzzer` | 圧電ブザー |
| `NEJI-M3` | M3 ネジ穴 |
| `TEST Pattern` | テストパッド |

## 使い方

1. DesignSpark PCB をインストールする
2. 各ライブラリファイルをDesignSpark PCBのライブラリフォルダにコピーする
   - Windowsの場合の標準パス: `C:\Users\<ユーザー名>\Documents\DesignSpark\Library\User\`
3. DesignSpark PCB を起動し、ライブラリとして登録する

## ライセンス

[LICENSE](LICENSE) を参照してください。
