### **お茶の水女子大学 物理学実験：PET試料DSC測定の解析データ**

**概要**
本ドキュメントは、お茶の水女子大学の物理学実験で実施された、PET（ポリエチレンテレフタレート）試料のDSC（示差走査熱量測定）実験における解析データおよび手法をまとめたものです。

---

**使用データ**

[ベースライン補正済み生データ](https://github.com/kyoka1013/-DSC-/blob/main/2025-06-30%20PET%20DSC-60%EF%BD%9E%E8%A3%9C%E6%AD%A3.csv)
  * DSC測定で得られた、ベースライン補正後の生データです。

  * 
[Python用加工データ](https://github.com/kyoka1013/-DSC-/blob/main/PET2.csv)
  * 上記の生データを、Pythonで解析しやすい形式に加工したものです。

---

**解析手法**

[アブラミ式フィッティングJupyter Notebook](https://github.com/kyoka1013/-DSC-/blob/main/ana.ipynb)
  * アブラミ式を用いてデータをフィッティングするためのJupyter Notebookファイルです。

  * 
[フィッティング用データ](https://github.com/kyoka1013/-DSC-/blob/main/df_trimmed_output.csv)
  * フィッティングに実際に使用したデータです。
