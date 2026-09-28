<p align="center">
  <a href="https://toitoitoi-lab.github.io/"><img src="https://raw.githubusercontent.com/toitoitoi-lab/.github/main/profile/banner.png" alt="toi toi toi　アプリの置き場　AT（ICT）を使った学びの支援のために、つくってきた道具" width="100%"></a>
</p>

公立学校の教員が、個人の活動としてつくってきたアプリを置いています。
どのアプリも、**プレビュー → つくった理由 → 開く・コードを見る** の順に並べています。

[サイト](https://toitoitoi-lab.github.io/)　｜　[YouTube](https://www.youtube.com/@toitoitoi-lab)　｜　[note](https://note.com/malu_malu)　｜　[利用ルール](https://toitoitoi-lab.github.io/rules/)

---

## アプリ一覧

### 1. せんせいアシスト（仮想の児童生徒で支援を学ぶ）

<a href="https://toitoitoi-lab.github.io/sensei-assist/"><img src="https://raw.githubusercontent.com/toitoitoi-lab/.github/main/profile/sensei-assist.png" alt="せんせいアシストの画面。左に自立活動の項目ごとのスライダー、右に6区分のレーダーチャートが並ぶ" width="100%"></a>

**つくった理由**
「こういう特性の子には、どんな支援が考えられるだろう」。研修や校内の話し合いでよく出るこの問いを、短い時間で具体的に考えるための道具です。不特定の児童生徒を想定した仮想の児童生徒の特性を置き、典型的な支援の例を並べて見ることで、支援の引き出しを増やします。特定の児童生徒の相談には使わず、支援を学ぶことに目的をしぼっています（特定の子について入力すると、個人が分かる情報を入れることになるためです）。

**できること**
- 架空の児童生徒の特性を、自立活動の6区分27項目のスライダーで置く
- レーダーチャートで、特性の偏りを見る
- AI（Gemini）に、その特性で典型的に考えられる支援の例を出してもらう
- 結果を Google ドキュメントや JSON に残す

**大切な約束**　入れるのは架空の児童生徒の特性だけです。実際の児童生徒のデータは入力しないでください。

**動かし方**　画面（HTML）＋ Google Apps Script ＋ Gemini API。AIの機能は、自分の Google アカウントでのセットアップが必要です。

**[▶ アプリを開く](https://toitoitoi-lab.github.io/sensei-assist/)**　｜　**[コードを見る](https://github.com/toitoitoi-lab/sensei-assist)**　｜　**[セットアップの手順](https://github.com/toitoitoi-lab/sensei-assist#セットアップ)**

---

### 2. techo（手帳）

<a href="https://toitoitoi-lab.github.io/techo/"><img src="https://raw.githubusercontent.com/toitoitoi-lab/.github/main/profile/techo.png" alt="techo の画面。左は今日の予定と予定の登録、右は役割ごとの今週の大石と今月の見通し" width="100%"></a>

**つくった理由**
役割がいくつもあり、それぞれが別々に動いている状態を、1つの構造として見渡すため。フランクリン・プランナーの「使命 → 大きな石 → 日々の優先順位」を土台にした、自分用の手帳アプリです。異動しても記録を失わないよう、個人の Google アカウントで動かします。

**できること**
- Google カレンダーと学校の予定（限定公開 ICS）を、1つの「今日」にまとめて見る
- まとめて話した予定・タスク・目標を、AI が1件ずつに分けて優先度を付ける
- 役割ごとに「今週の大石」を決め、月と週の見通しを持つ
- 1日1ページの手書きメモ

**動かし方**　Google Apps Script ＋ スプレッドシート ＋ カレンダー ＋ Gemini API。自分の Google アカウントでのセットアップが必要です（デモは架空のデータで画面だけ試せます）。

**[▶ デモを開く](https://toitoitoi-lab.github.io/techo/)**　｜　**[コードを見る](https://github.com/toitoitoi-lab/techo)**　｜　**[セットアップの手順](https://github.com/toitoitoi-lab/techo#セットアップ20分ほど)**

---

## 利用について

- **コード**は MIT ライセンスです。自由に使い、改変できます。
- **記事・教材や、アプリの考え方を研修などで紹介するとき**は、事前にご連絡ください。→ [利用ルール](https://toitoitoi-lab.github.io/rules/)
- このページやコードを、訪問者が書きかえることはできません。改良したいときは、自分のアカウントに複製（Fork）して使ってください。
