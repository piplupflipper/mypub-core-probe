# mypub-core-probe

使い捨ての検証用リポジトリ (2026-10-14 作成)。
piplupflipper/mypub を本体と記事のリポジトリに分けるとき、記事側のリポジトリに本体を git submodule として入れ、Cloudflare Workers Builds のビルドで取得できるかを確かめる。
本体の代わりに、jq を使う最小の生成スクリプト `bin/probe-build` と CSS 1 つを置く。
検証が終わったら消す。
