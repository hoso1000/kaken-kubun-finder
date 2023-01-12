# kaken-kubun-finder
科研費応募区分ファインダー（仮）
応募しようとする科研費の課題名＋概要を入力すると、
KAKENデータベースに掲載されている＝すでに採択されている科研費課題から課題名・概要が似ている（文ベクトルのコサイン距離が近い）課題を探し出し、似ている課題がどの小区分で多く採択されているかチェックできます。

このツールを使用し、実際に科研費申請等に利用した場合の結果に対する責任は負いかねます。

 - 使用している言語モデル：https://huggingface.co/sonoisa/sentence-bert-base-ja-mean-tokens-v2
 - KAKENデータベース：https://kaken.nii.ac.jp/ja/index/

