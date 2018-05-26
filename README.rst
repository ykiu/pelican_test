Pelican tests
=============

Installing
----------

1. このリポジトリをクローン
2. コマンドライン上で、cd {{リポジトリのフォルダへのパス}}
    e.g. cd c:\\pelican_tests
3. コマンドライン上で、pip install -r requirements.txt

Generationg HTML files
----------------------

1. コマンドライン上で、cd {{リポジトリのフォルダへのパス}}\\site
    e.g. cd:\\pelican_tests\\site
2. コマンドライン上で、pelican content

Previewing the generated files
------------------------------

1. コマンドライン上で、cd {{リポジトリのフォルダへのパス}}\\site\\content
    e.g. cd:\\pelican_tests\\site\\content
2. コマンドライン上で、cd python -m pelican.server
3. ブラウザで http://localhost:8000/ にアクセス。

詳しくは
http://docs.getpelican.com/en/stable/quickstart.html
