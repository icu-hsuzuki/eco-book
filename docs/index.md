--- 
title: "Book on Economics"
author: "Hiroshi Suzuki"
date: "2023-04-12"
site: bookdown::bookdown_site
booklanguage: JP
documentclass: bxjsbook #book
# classoption: xelatex, ja=standard
bibliography: [book.bib, packages.bib]
url: https://icu-hsuzuki.github.io/eco-book/
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is a minimal example of using the bookdown package to write a book.
  The HTML output format for this example is bookdown::bs4_book,
  set in the _output.yml file.
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
biblio-title: "参考文献"
---
# この本について

経済関係のデータサイエンスの内容を書いていくための練習用です。
ほぼ、同じ内容を、README にも、書いてありますから、この内容（`index.Rmd`）は、編集段階で消去して構いません。

RStudio の New Project から Book を選び、作成したファイルを、編集したものです。最初に書かれている内容は、本を作成する時に、有用な内容も含みますから、それは、最後の、bookdown に、まとめてあります。

自分で、bs4_book テンプレートを利用して、日本語で本を書く時には、リポジトリ [
bs4_book_template](https://github.com/icu-hsuzuki/bs4_book_template) を利用することも可能です。必要ファイルを整理し、`preamble.tex` に、数行書き加え、日本語で、PDF も作成できるようにしてあります。

## Git-GitHub-Pull Request を用いての共同編集

本を作成するには、いくつかのレベルがあります。

1. RStudio book project を作成して、編集
2. Git を利用して、履歴をとる
3. GitHub Repository に同期させて編集
4. 管理者のGitHub Repository （オリジナル・リポジトリ）からフォークしたリポジトリを編集して、Pull Request
5. 編集者何人かで、共同編集
6. 編集者何人かで共同編集し、その管理を行う

最後の二つは、管理者としての仕事を含みます。

これらを、段階的に、練習しているための、練習用 Book となっています。
