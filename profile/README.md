<p align="center">
  <a href="https://toitoitoi-lab.github.io/"><img src="https://raw.githubusercontent.com/toitoitoi-lab/.github/main/profile/banner.png" alt="toi toi toi　アプリの置き場　AT（ICT）を使った学びの支援のために、つくってきた道具" width="100%"></a>
</p>

公立学校の教員が、個人の活動としてつくってきたアプリを置いています。
どのアプリも、**プレビュー → つくった理由 → 開く・コードを見る** の順に並べています。

[サイト](https://toitoitoi-lab.github.io/)　｜　[YouTube](https://www.youtube.com/@toitoitoi-lab)　｜　[note](https://note.com/malu_malu)　｜　[利用ルール](https://toitoitoi-lab.github.io/rules/)

---

## アプリ一覧

### 1. せんせいアシスト（教育相談編）

<a href="https://toitoitoi-lab.github.io/sensei-assist/"><img src="https://raw.githubusercontent.com/toitoitoi-lab/.github/main/profile/sensei-assist.png" alt="せんせいアシストの画面。左に自立活動の項目ごとのスライダー、右に6区分のレーダーチャートが並ぶ" width="100%"></a>

**つくった理由**
巡回相談で先生と話せる時間は、多くの場合15〜30分です。その短い時間で、子どもの全体像を先生と同じ画面で見ながら、「明日から試せること」をいっしょに考えたい。そのためにつくりました。

**できること**
- 自立活動の6区分27項目を、スライダーでざっくり置く
- レーダーチャートで、全体の偏りを見る
- AI（Gemini）に、一般的に考えられる傾向と、具体的な手立ての例を出してもらう
- 結果を Google ドキュメントや JSON に残す

**使うときの約束**　架空の事例（仮想データ）で、一般的な傾向を考えるための道具です。実在する児童生徒の個人情報は入力しないでください。

**動かし方**　画面（HTML）＋ Google Apps Script ＋ Gemini API。AIの機能は、自分の Google アカウントでのセットアップが必要です。

**[▶ アプリを開く](https://toitoitoi-lab.github.io/sensei-assist/)**　｜　**[コードを見る](https://github.com/toitoitoi-lab/sensei-assist)**　｜　**[セットアップの手順](https://github.com/toitoitoi-lab/sensei-assist#セットアップ15分ほど)**

---

### 2. techo（準備中）

**つくった理由**
役割がいくつもあり、それぞれが別々に動いている状態を、1つの構造として見渡すため。フランクリン・プランナーの「使命 → 大きな石 → 日々の優先順位」を土台にした、自分用の手帳アプリです。異動しても記録を失わないよう、個人の Google アカウントで動かします。

**動かし方**　Google Apps Script ＋ Google スプレッドシート ＋ Google カレンダー。
公開の準備をしています。

---

## 利用について

- **コード**は MIT ライセンスです。自由に使い、改変できます。
- **記事・教材や、アプリの考え方を研修などで紹介するとき**は、事前にご連絡ください。→ [利用ルール](https://toitoitoi-lab.github.io/rules/)
- このページやコードを、訪問者が書きかえることはできません。改良したいときは、自分のアカウントに複製（Fork）して使ってください。
