Arabic/Cyrillic/Latin extended characters input panel = アラビア文字/キリル文字/ラテン拡張文字入力パネル
====
## Description 説明
A character input panel for cataloging multilingual resources in university/research libraries in Japan.
It uses simple javascript so that you can download and use in local environment, or build in your website or application.
The character set is designed for cataloging in NACSIS-CAT (based on ALA-LC Romanization Tables). However, "ʻ" (U + 02BB) used for transliteration of ع (‘ayn) in LC (USMARC) is replaced with "ʿ" (U + 02BC) in NACSIS-CAT.

大学・研究図書館での多言語目録作成のための文字入力パネルです。
簡易なjavascriptで作成していますので、ダウンロードしてローカル環境で使用したり、ウェブサイトやアプリケーションに組み込んで使えます。
クリップボードへのコピー機能などはありません。
NACSIS-CATへの登録（ALA-LC Romanization Tables準拠）を念頭においた文字セットになっています。LC(USMARC)でアインの翻字に用いられている" ʻ "(U+02BB)は、NACSIS-CATでは" ʿ "（U+02BC)になります。

## Demo　動作デモ
https://tokuhararian.github.io/inputpanels/

Previous version (Arabic and Latin extended) also available at TBIAS website.
http://tbias.jp

## Usage　ローカル環境での使い方（素人向け）
リポジトリから、

- arabicchar.html  
- cyrillic.html  
- index.html  
- latinextended.html  
- special_characters_input.js    

の５つをダウンロードして、同じディレクトリ（フォルダ）内に置いてください。

## Licence ライセンス
Copyright (c) 2020 Yasuhiro Tokuhara
Released under the MIT license
https://opensource.org/licenses/mit-license.php
