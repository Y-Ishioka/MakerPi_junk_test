◆概要

秋月のドット抜け御免マトリクスLEDモジュールを MAKER PI RP2040 で動作確認するプログラム

- 起動後に１６ｘ１６ドットの塗りつぶしパターンがモジュール右側から左側へ移動を繰り返す

- 以下に記すボタンを用意し、このボタンを押下することで表示パターンを以下の順で変更する

　- １６ｘ１６ドットの塗りつぶしパターン

　- 横線＋斜め線のパターン

　- １６ｘ１６ドットフォントの「赤」

マトリクスLEDモジュールは１セットでの使用を想定

動作確認は Cytron社の MAKER PI RP2040 を使用

https://akizukidenshi.com/catalog/g/g116939/

https://www.cytron.io/p-maker-pi-rp2040-simplifying-robotics-with-raspberry-pi-rp2040

◆参考資料

https://akizukidenshi.com/img/contents/kairo/%E3%83%87%E3%83%BC%E3%82%BF/%E8%A1%A8%E7%A4%BA%E8%A3%85%E7%BD%AE/LED%E9%9B%BB%E5%85%89%E6%8E%B2%E7%A4%BA.pdf

◆参考情報１

https://x.com/YI_Studio/status/1842111760213663799

https://x.com/YI_Studio/status/1893488568930025907


◆ピンアサイン

マトリクスLEDモジュールと接続するピンは以下の通り。

#define SIN1PIN         0

#define SIN2PIN         1

#define SIN3PIN         2

#define CLKPIN          3

#define LATPIN          4

また、表示内容の変更に使用するボタンのピンは以下の通り。

#define BTNPIN          20


◆免責

　著作者は，提供するプログラムを用いることで生じるいかなる損害に関して，一切の責任を負わないものとします．

　たとえ，著作者が損害の生じる可能性を知らされていた場合も同様に一切の責任を負わないものとします．
