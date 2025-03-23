<p align="center">
  <img src="https://github.com/user-attachments/assets/147d226e-982b-4483-a8ab-505c125927de" width="280">
</p>


<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=ryusei-inamori.DICOM_Anonymizer" />
  <img src="https://img.shields.io/github/stars/ryusei-inamori/DICOM_Anonymizer?style=social" />
</p>

<p align="center">
  <strong style="font-size:30px;">お問い合わせはこちら : inamori.ryusei.q4[atmark]dc.tohoku.ac.jp</strong>  <br>※ [atmark]を@に変えてください。
</p>

DICOM形式の医療画像を匿名化するツールを開発しました。医療機関に技術者がいない場合等に、匿名化処理を効率よく行えるツールになると思いますので、ぜひご活用ください。


# DICOM Anonymizer リリース

DICOM形式の医用画像を匿名化するツール「DICOM Anonymizer」をリリースします。MacとWindowsの両方のOSに対応しています。

## **対応 OS**
- macOS Sonoma
- Windows 10 / 11

↓ 以下よりダウンロードしてください:

| OS | ダウンロードリンク |
|----|-------------------|
| Mac | [DICOM_Anonymizer.zip](https://github.com/ryusei-inamori/DICOM_Anonymizer/releases/download/v1.0.0/DICOM_Anonymizer.zip) |
| Windows | [DICOM_Anonymizer.exe](https://github.com/ryusei-inamori/DICOM_Anonymizer/releases/download/v1.0.0/DICOM_Anonymizer.exe) |

## 機能について

<p align="center">
  <img src="https://github.com/user-attachments/assets/36fdd630-ff45-4ebb-a0b4-82ac38e78f7c" width="800">
</p>

ツールを起動すると、上図のようなUIが表示されます。
フォルダ内の全ての階層を維持したまま、全てのDICOM画像に対して匿名化を行うことが可能です。
また、結果を確認するためにメタデータを参照する機能も付いています。

元のDICOMデータを保持しておきたい場合（上書きしたくない）を想定して、コピー保存モードを搭載しています。
コピー保存モードで実行すると出力選択で選んだフォルダ内に匿名化後のデータがコピーされて保存されます。
上書きモードを使用すると、直接元データが書き換えられますのでご注意ください。
