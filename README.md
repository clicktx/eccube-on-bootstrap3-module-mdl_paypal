# ペイパル ウェブペイメント プラス 決済モジュール(2.11系・2.12系・2.13系)
[ペイパル ウェブペイメント プラス 決済モジュール(2.11系・2.12系・2.13系)](http://www.ec-cube.net/products/detail.php?product_id=179) をEC-CUBE on BootStrap3に最適化したもの。

### PayPal支払い遷移後のキャンセルでカートロールバック
[issue #1 「PayPalで支払う」でPayPalに遷移後、ショップページに戻るとカートがクリアされてしまう](https://github.com/clicktx/eccube-on-bootstrap3-module-mdl_paypal/issues/1) に対応

実際には`/html/user_data/paypal_cancel.php` を修正する必要がある。
