# MedalGame_SMASHSTADIUM

KONAMI様のスマッシュスタジアムのハードウェアを基にして、回路及びプログラムを作成し動作させたものです。

## 動作例

https://github.com/UnknownSP/MedalGame_SMASHSTADIUM/assets/39638661/8527d8a6-44d7-43fd-9662-79298d5f2db3

## 回路

赤枠で囲まれた部分が作成した回路及びハーネスになります。

![SMASTA_cirecuit](https://github.com/UnknownSP/MedalGame_SMASHSTADIUM/assets/39638661/5cb7c1a5-31e8-4239-8cae-0a62c52fe2df)

## 仕様

テープLEDやソレノイド、その他IOをSTMで一括管理しています。

テープLED(ws2812b)はタイマ機能を用いて動作させています。ws2812bのクロックタイミングと合わせるために内部クロック(APB1)を40MHzに落としています。
