# 学校のchromebook100%workingブロック解除メソッド(全バージョン対応)

## 注意事項
> 全てのChromebookで動作する保証はありません。


> 使用する場合は全て自己責任です、私は責任を負いません。


> この方法はUSBメモリ.SDカードがポリシーで禁止されている端末では使用不可能です。


> この方法はChromebookを初期化するのでデータをGoogleドライブなどでバックアップしてください。

## 必要なもの
> USBメモリまたはSDカード(8GB以上)


> Chromebook リカバリ ユーティリティ

## ChromeOSのリカバリイメージファイルの作成
1.[ChromeOS Version113](https://dl.google.com/dl/edgedl/chromeos/recovery/chromeos_15393.58.0_octopus_recovery_stable-channel_mp-v32.bin.zip)をダウンロード



2.ダウンロードしたzipファイルを解凍。



3.[Chromebook リカバリ ユーティリティ](https://chromewebstore.google.com/detail/chromebook-%E3%83%AA%E3%82%AB%E3%83%90%E3%83%AA-%E3%83%A6%E3%83%BC%E3%83%86%E3%82%A3%E3%83%AA%E3%83%86%E3%82%A3/pocpnlppkickgojjlmhdmidojbmbodfm?hl=ja)にアクセスし拡張機能を追加。



4.拡張機能を開く。



5.右上の歯車のマークをクリック。



6.ローカルイメージを使用をクリック。



7.解凍したzipファイルの中にあるbinファイルを選択。



8.使用するメディアを選択し続行。



9.今すぐ作成をクリック



10.ブラウザーからユーザーアカウント制御が出てくるのではいを選択。



11.リカバリイメージが作成されたらファイルの作成は完了です。

## Wifiのパスワード取得



**__ここからは全てChromebookで行ってください。__**



1.[Policy Password tool](https://luphoria.com/netlog-policy-password-tool)にアクセス。



2.`chrome://net-export`にアクセス。



3.Include raw bytesを選択。



4.Start Logging to Diskをクリック。



5.`chrome://policy`にアクセス。



6.ポリシーを再読み込みをクリック。



7.`chrome://net-export`に戻り、



8,Stop loggingをクリック。



9.[Policy Password tool](https://luphoria.com/netlog-policy-password-tool)に戻りjsonファイルをアップロード。



10.表示されたSSIDとSecurityをメモし完了です。




## Chromeのバージョンダウン



1.Chromebookをシャットダウン。



2.作成したUSBまたはSDカードをChromebookに挿入。



3.電源ボタン、escキー、リロードキーを同時に長押し。



4.しばらくすると自動でリカバリを認識してくれます。



5.勝手にインストールが進むと思うので終わるまで待ちます。



6.インストールが完了したらUSBまたはSDカードを抜いてください、自動で再起動されます。



7.一度Chromebookを再起動



8.言語を選択後Wifiの接続が要求されると思うのでメモしたSSIDとパスワードを入力。



9.自動で企業の登録がされるので少し待ちます。



10.その後自動でデスクトップに移動します。



11.`chrome://version`にアクセスしバージョンを確認してください、バージョンが上がっていなければ終了です。




## 拡張機能のIDを取得と拡張機能の無効化。



1.`chrome://extensions`にアクセス。



2.デベロッパーモードをオンにします。(できない場合はID一覧が一番下にあるのでそれを見てください。)



3.フィルターのIDをコピーします。



4.`chrome-extension://gndmhdcefbhlchkhipcnnbkcmicncehk/manifest.json`にアクセス。



5.右クリックで検証を開きます。



6.デベロッパーツールでconsoleを開きます。



7.`http://chrome.management.setEnabled('拡張機能のID', false) `をペーストします。



8.ブロックされてるサイトを開いてアクセスできることが確認できたら完了です。



## Chromeの自動更新を停止。



**__このままだと自動でバージョンが上がってしまいバージョンダウンした意味がなくなってしまいます。__**



1.[chrome automatic update blocker](https://caub.glitch.me)にアクセス。



2.`chrome://network#state`にアクセス。



3.一番下までスクロールし、お気に入りのネットワークの下にある**+**をクリック。



4.文字が出てくるので中身を全てコピー。



5.[chrome automatic update blocker](https://caub.glitch.me)に戻り**read instruction!**にコピーした文字をペースト



6.**generate and download onc file**をクリック。



7.oncファイルがダウンロードされます。



8.`chrome://network#general`にアクセス。



9.一番下のONCファイルのインポートの下にある**ファイルを選択**をクリック。



10.先ほどダウンロードしたONCファイルを選択します。



11.選択した後再起動しバージョンが上がってないことを確認できたら終了です。




## 拡張機能ID一覧。
> i-FILTER@Cloud Agent `bkfmfndedcalgdgaklieojjfbbjpmijd`


> ロイロWebフィルター `pabjlbjcgldndnpjnokjakbdofjgnfia`


> Google Chrome™のウェブサイトをブロックする `jdbliieklfhihjpmhhekcoldpcemlafj`

このほかにもあったらDiscord [Discord](https://discord.gg/cDCkRDuGPF)まで。
