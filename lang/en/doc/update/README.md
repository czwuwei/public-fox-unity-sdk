## About update to latest version

旧バージョンのF.O.X SDKが導入されたアプリに対して、最新バージョンのF.O.X SDKを導入する際に必要な手順を説明します。

1. 以前のバージョンのファイルがプロジェクトに組み込まれていれば、それらを全て削除します
2. 最新バージョンのファイルをプロジェクトに追加します
3. 「Plugins/FoxPlugin」及び「Plugins/FoxAnalyticsSession」をMainCamera等にドラッグ＆ドロップに追加することで実装を行っていた場合は、古いバージョンのファイルを全て消した上で、再度新しいファイルをドラッグ＆ドロップで追加してください。
4. iOSの場合は、Unityのビルド後に立ち上がるXcode上でAppAdForce.plistを再作成してください。


v2.14からAndroidにおいて、広告IDに対応しています。
広告IDを取得する場合は、「[広告IDを利用するためのGoogle Play Services SDKの導入](/lang/en/doc/integration/android/google_play_services/README.md)」を確認してください。

また、v2.14からリエンゲージメント計測機能が追加されています。
リエンゲージメント計測を実施される場合は、iOSアプリの場合は、FoxReengagePlugin.m/hをプロジェクトに追加してください。Androidアプリの場合は、「リエンゲージメント計測の実装」を確認し、実装してください。

SDKのアップデート後は、必ず効果測定テストを実施し、計測及びアプリケーションの動作に問題ないことを確認してください。
また、リエンゲージメント計測を実施される場合は、リエンゲージメント計測用のテストを実施する必要があります。


---
[TOP](/lang/en/README.md)