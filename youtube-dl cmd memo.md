## Download Options

`-r, --rate-limit LIMIT`
  -> ダウンロード速度を制限する。  
`--buffer-size SIZE`
  -> ダウンロードバッファを指定する。  
`--no-resize-buffer`
  -> ダウンロードバッファを自動調整しない。  
`--http-chunk-size SIZE`
  -> チャンクのサイズを指定する。

## Filesystem Options

`-a, -batch-file FILE`
  -> 動画URLを記述したファイルを指定すると，まとめてダウンロードする。  
`--id`
  -> ファイル名を動画IDのみにする。  
`--restrict-filenames`
  -> ファイル名をASCIIコードに制限する。  
`--no-cache-dir`
  -> キャッシュファイルを作成しない。  
`--rm-cache-dir`
  -> youtube-dlの作成したキャッシュファイルを全て削除する。

## Verbosity / Simulation Options

`-s, --simulate`
  -> 実行をシミュレートする。  
  
`-g, --get-url`  
`-e, --get-title`  
`--get-id`  
`--get-thumbnail`  
`--get-description`  
`--get-duration`  
`--get-filename`  
`--get-format`
  -> 指定のものを表示する。

## Video Format Options

`-f, --format FORMAT`
  -> Video Format Codeを指定する。  
`-F, --list-formats`
  -> 利用可能な全てのフォーマットを表示する。  
`--merge-output-format FORMAT`
  -> 結合が必要な場合にコンテナフォーマットを指定する。
  
## Post-processing Options

`-x, --extract-audio`
  -> 動画を音声のみに変換する。  
`--audio-format FORMAT`
  -> 音声フォーマットを指定する。best, aac, vorbis, mp3, m4a, opus, wavのいずれか。  
`--audio-quality QUALITY`
  -> 音声変換時のクオリティを指定する。
