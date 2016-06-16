
WSUSサーバ
SCCMサーバ

の基本機能

利用目的と所有機能

Windows10

ジャンボパッチ４ＧＢ　年一回ある
バッチファイルの転送だけで、サーバがスローダウンするかも

１サーバーあたり何クライアント同時にさばける？性能面は？
→IISでセッション数を制限し、トラフィックに負荷のない設計を行うこと。

10Gbps

MTU 最大送信サイズ 1500byte
1GB







修正適用要求を受けないよう、ＷＳＵＳサーバ側に制御（スケジュール）する機能とかあるか調査ポイント

同期
Upstream WSUS

基本プル
自動適用もあるみたい

Microsoft Report Viewer レポート
.net framework 2.0






# SCCM

# マイクロソフト社の運用管理ソリューションSytem Center ファミリー

# 構成管理ソフト
SCCMのソフトウェア更新機能はWSUSを利用するが、
そのまま利用するわけではない。



の一部でWSUSの機能を使う

bitLocker
拡張機能

bitolocker

TPMを実装したコンピュータ（ハードウェア？）で利用することができる。
また、TPMを利用しなくとも、USBメモリなどリムーバブルデバイスに起動キーを保することで利用することができる。

企業への実装
Active Directoryインフラストラクチャーを使用して、回復キーをリモートに保管しておくことができます。（ＴＰＭが搭載されていること）

→
回復キーをリモートに保管しておくと？


ロックアウト
一定関数


BitLockerの回復パスワードをADで管理する

Active Directory
シングルサインオン

bitblockerとsccmの連携
sccmに対してactive directory のスキーマを拡張する必要がある。


ドメコン
acitive directory の単位


SCCMサーバーはBitLockerを使用する。
Windows10から？？導入されたデバイス等のディスク暗号化技術
SCCMとどんな」連携ができる

SCCM向けのActive Directoryの準備
Active Directoryスキーマの


# SCCM 
