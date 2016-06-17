# Infrastructure


# Storage

RAID 0 striping(しましまのストライプ)
データをディスク分に分け同時に書き込む。
データの冗長化は行われていないため、一台のディスクが損傷するとすべてのデータにアクセス不能になる。

RAID 1 mirroring
同一のデータを複数のディスクに書き込み、
片方で障害が発生しても処理を継続できるように冗長化した構成

RAID 5
RAID0と同じ原理で分散してディスクに書き込むと同時に、
データ損傷時にリカバリするためのパリティを計算し、ディスクに書き込む。

RAID 10
RAID 0 + RAID 1

#　ITIL　Infomation Technology Infrastructure Library
システム運用・管理を体系的にガイドラインとしてまとめ、書籍にしたもの
紹介されている事例にたいするグッドプラクティス、ベストプラクティスを紹介する。



IaaS イァース
 infrastracture as a service
 クラウド上でハードウェア・ストレージの設置を行うことができる。
 AWS

PaaS パース
 platform as a service
　アプリケーションを実行する環境、もしくはＯＳのような環境を利用できる。
 sakura web service ?

SaaS サース
 software as a service
google mail などクラウド上のアプリケーションを利用することができる




