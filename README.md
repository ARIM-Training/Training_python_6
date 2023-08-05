# python 演習5
## 海洋性生分解性ポリマー編


**目　標**：　本講座の目標

## Polymer:NFA データセット
Polymer:NFA data setは、大阪大学・佐伯教授らの総説論文[1,2]で公開されている文献から収集した非フラーレンアクセプター（NFA）系有機太陽電池材料のデータセットです。ここには2011年～2021年にかけて発表された558報の論文から、有機太陽電池の研究に検討された有機半導体のHOMO/LUMO レベルやエネルギーギャップ（Eg） の報告値（実験値）のほか、1318の太陽電池素子の特性であるエネルギー変換効率（PCE)、短絡電流密度（Jsc)、曲線因子（FF）、開放端電圧（Voc）がまとめられています。

[1]の総説では、プログラムとしてRを用い、機械学習モデルにはRandom forest (RF) を適用した検討が述べられています。ポリマー/ドナーのフィンガープリントはECFP6およびMordred（2次元因子のみを使用）の二つのケースについて考察されています。

---
[1] Yuta Miyake and Akinori Saeki　"Machine Learning-Assisted Development of Organic Solar Cell Materials: Issues, Analyses, and Outlooks", J. Phys. Chem. Lett. 2021, 12, 51, 12391–12401 (2021) https://pubs.acs.org/doi/10.1021/acs.jpclett.1c03526

[2] Kakaraparthi Kranthiraja, Akinori Saeki  "Experiment-Oriented Machine Learning of Polymer:Non-Fullerene Organic Solar Cells". Adv. Funct. Mater. 2021, 31, 2011168. https://doi.org/10.1002/adfm.202011168

[3] 佐伯昭紀、"塗布型太陽電池材料のマテリアルズ・インフォマティクス"、化学と工業、Vol.76-6　 (2023) https://www.chemistry.or.jp/journal/ci23p374.pdf



<hr>

## 演習コード
Google Colabでステップ・バイ・ステップで動作を確認しながら進めます．下記のボタンを押して進んでください．

<div align="center">
  <a href="https://colab.research.google.com/github/ARIM-Training/Training_python_6/blob/main/有機太陽電池編.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
</div>

