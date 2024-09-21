# SlideshareDownloader

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `slideshare_downloader` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:slideshare_downloader, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/slideshare_downloader>.

---

## TODO
- [x] CI入れる
- [ ] CLIのベースインターフェース作る
  - [ ] URL指定(コマンドライン引数あればスキップ)
  - [ ] 出力先指定(defaultは今いるディレクトリに入れる？)
  - [ ] 出力方法(pdfなのか画像なのか)
- [ ] スライド落としてくる処理を書く

## できれば
- [ ] 画質操作(convertするか)
- [ ] 待ち画面のアニメーション
  - [ ] バー的なやつ
  - [ ] くるくる回るやつ
