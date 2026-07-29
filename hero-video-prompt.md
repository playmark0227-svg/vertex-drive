# ヒーロー動画 生成指示書

バーテックスドライブ ブランドサイト「時間の美術館」ヒーローセクション用。
Veo 3 / Sora / Runway Gen-4 クラスのAI動画生成モデルを想定。

現在サイトに入っているのはcanvasで描いたCGプレースホルダーです。この動画が用意できたら
`index.html` のヒーロー内 `<canvas id="heroCanvas">` を削除し、その下にコメントアウトしてある
`<video class="hero-media">` のブロックを有効化してください。

---

## 1. 本命プロンプト(英語・そのまま貼り付け可)

```text
STYLE: photorealistic cinematic footage, large-format digital cinema camera, muted low-contrast archival film grade. Absolutely no on-screen text, no logos, no badges, no license plates, no people.

SCENE: The interior of a private automobile museum before opening hours. The space is near-total darkness in a deep warm charcoal (soft black, never crushed pure black — the feel of sumi ink #1C1B18). High above, from an unseen skylight, a single narrow blade of pale warm daylight — the color of aged plaster and gofun white (#F2EFE9) — falls diagonally into the room. This light shaft travels from left to right with almost imperceptible slowness, as if the sun's daily arc were compressed into a single quiet minute. Fine dust motes drift, catch light, and extinguish ONLY inside the shaft; the rest of the frame stays still and dark.

SUBJECT: A fictional 1960s-inspired neo-classic grand touring coupé — very long nose, low fastback roofline, hand-formed aluminum body, no chrome ornamentation, no grille detail visible. The car is an original design and must not resemble any existing production car. It rests in the dark, and as the light blade passes, it grazes the body: hairline-thin specular highlights appear along the roofline and the crest of the front fender, like two long calligraphic strokes of light. Never more than 20% of the car's form is readable; the full silhouette is never revealed. Once, a soft band of reflected light glides slowly along the fender highlight — the gesture of a polishing cloth — then fades over several seconds as the light moves on.

ATMOSPHERE: Still air, the faintest volumetric haze; in the deepest shadow areas a barely perceptible cool green-grey tint (verdigris, desaturated). No other color exists in the frame.

CAMERA: Locked-off static shot, no camera movement whatsoever. Low front three-quarter position, roughly knee height, 85mm equivalent lens, shallow but disciplined depth of field with focus on the fender crest. Composition: the car's dark mass occupies the lower third; the light blade enters upper left; generous negative space above.

MOTION & PACING: Everything moves at meditative, near-still speed — the shot should be mistakable for a photograph at first glance. No cuts. Designed as a seamless loop: the final frame's light position and haze density match the first frame. Silent film; no implied sound events.

MOOD: The hush of a museum at dawn. Restraint, patience, inheritance. Time itself as the material.
```

## 2. ネガティブプロンプト

```text
text, letters, typography, watermarks, logos, emblems, badges, hood ornament, license plate, any real car brand (Porsche, Jaguar, Ferrari, Mercedes, Aston Martin, Toyota), people, hands, drivers, reflections of people or windows, camera movement, pan, zoom, dolly, camera shake, cuts, fast motion, spinning wheels, driving, headlights on, taillights, neon, showroom lighting, multiple light sources, lens flare, bloom, glow, god rays too strong, HDR look, teal and orange, purple, violet, magenta, gold, golden light, glitter, sparkle, chrome shine, glossy showroom floor reflections, saturated colors, gradients as decoration, pure crushed black, blown-out highlights, smoke machine fog, rain, motion blur streaks, CGI plastic look, cartoon, illustration, oversharpening, music-video editing, dramatic reveal of the full car
```

## 3. 日本語版(クライアント確認・編集用)

**スタイル** — フォトリアルなシネマティック実写調。ラージフォーマット・デジタルシネマカメラの質感、彩度を抑えた低コントラストのアーカイブフィルム調グレーディング。画面内の文字・ロゴ・エンブレム・ナンバープレート・人物は一切なし。

**シーン** — 開館前の個人自動車美術館の内部。空間はほぼ完全な闇だが、深く温かみのある墨色(#1C1B18 の柔らかい黒。純黒に潰さない)。頭上の見えない天窓から、古い漆喰と胡粉(#F2EFE9)の色をした細長い一筋の淡い斜光が室内に落ちる。この光の帯は、太陽の一日の軌跡を静かな一分間に圧縮したかのように、ほとんど気づかない速さで左から右へ移動する。微細な塵の粒子が光の帯の中でだけ浮遊し、きらめき、消える。帯の外は静止した闇のまま。

**被写体** — 1960年代に着想を得た架空のネオクラシック・グランドツーリングクーペ。極端に長いノーズ、低いファストバックのルーフライン、手叩きのアルミボディ。クロームの装飾やグリルのディテールは見せない。実在のいかなる市販車にも似せないオリジナルデザインであること。車は闇の中に静かに置かれ、光の帯が通過する際にボディをかすめる。ルーフラインとフロントフェンダーの稜線に沿って、髪の毛ほどの細さのスペキュラーハイライトが、二本の長い書のような光の線として浮かび上がる。車の形が読み取れるのは常に全体の20%以下。全体像は最後まで見せない。一度だけ、柔らかな反射光の帯がフェンダーのハイライト上をゆっくりと滑る(磨き布の所作のように)。そして光が去ると数秒かけて消える。

**空気感** — 静止した空気、ごく薄いボリュームのある靄。最も深い影の部分にだけ、かろうじて知覚できる冷たい緑灰色(彩度を落とした緑青)の色味。それ以外の色は画面に存在しない。

**カメラ** — 完全固定。カメラの動きは一切なし。低いフロント3/4位置、膝の高さ程度、85mm相当のレンズ。浅いが抑制の効いた被写界深度で、フォーカスはフェンダーの稜線に。構図は、車の暗い質量が画面下1/3、光の帯は左上から進入、上部に豊かな余白。

**動きとペース** — すべての動きは瞑想的な、ほぼ静止に近い速度で。一見して写真と見紛う程度であること。カット割りなし。シームレスループ前提で、最終フレームの光の位置と靄の濃度は最初のフレームと一致させる。無音。

**ムード** — 夜明けの美術館の静けさ。抑制、忍耐、継承。時間そのものが素材である。

---

## 4. カメラとライティングの補足

**カメラ**

- 完全固定(locked-off)を最優先で指定する。放っておくとモデルはドリーやパンを足すので `static shot, no camera movement, tripod` を必ず明示。動きは光だけに担わせるのがこの演出の核。
- ポジションはフロント3/4、膝の高さ。ロングノーズの稜線が一本の水平に近い線として読める角度にする。車を彫刻の展示として見せ、走行感を消す。
- レンズは85mm相当の中望遠。パースを圧縮して静物的に。広角はショールーム感が出るので避ける。
- 構図は車体の闇が下1/3、上2/3は余白。Webヒーローでは中央下にタグラインが載るので、光の見せ場は画面中帯から上に置く。

**ライティング**

- 単一光源主義。天窓からの斜光1本のみで、フィルライトも環境光も置かない。露出は基準から約2段アンダー。
- 光色はウォームな昼光(4300K前後)。胡粉 #F2EFE9 の「白すぎない白」。シャドウは #1C1B18 の暖かい墨色で、青黒く沈めない。
- ヘイズは光の帯が成立する最小限に留める。ビームがくっきり出る「ゴッドレイ」まで行くとAI動画の定番の派手さになるので `faint volumetric haze, subtle` と抑える。
- アルミボディのハイライトは細く硬く少なく。面で光らせず稜線のみ。`hairline specular highlight` を繰り返し指定し、ギラつく映り込みとレンズフレアはネガティブプロンプトで殺す。
- 緑青は最深部シャドウの霧にごく僅かに乗せるだけ。グレーディング段階でシャドウのティントとして扱う。

**グレーディング** — 低コントラスト・低彩度のフィルムルック。ハイライトはロールオフさせ白飛びさせない。ブルーム、グロー、HDR感、ティール&オレンジは禁止。微細なフィルムグレインは可(暗部のバンディング隠しにも効く)。

## 5. 尺・書き出し・実装

- **尺** — 生成は8〜10秒。Web側で0.5倍速再生またはフレーム補間して16〜20秒相当に引き延ばすと「一見静止画」の体感速度になり、生成モデルの微妙な動きの粗も隠せる。
- **アスペクト** — 16:9で生成し、CSSの `object-fit: cover` でフルブリード表示。重要なハイライト(ルーフとフェンダーの光の線)は中央60%の帯に収まる構図にする。モバイル縦持ちでは左右が大きく切れるため。可能なら21:9も書き出してデスクトップで使う。
- **ループ** — 最終フレームと開始フレームの光位置を一致させる指定をまず試す。破綻する場合は末尾1.2〜1.5秒のクロスディゾルブで接合。最終手段はピンポン再生(順→逆)。この映像は動きが光の移動だけなので、逆再生してもほぼ気づかれない。
- **配信** — H.264 MP4 と WebM(VP9/AV1)の二本立て、1080pで実効3〜5Mbps程度。暗部主体なので低ビットレートでも保つが、バンディング対策にグレインは必須。`autoplay muted loop playsinline` と `poster` を付ける。`prefers-reduced-motion` 時は video を外して poster 静止画に差し替える(現在のCGプレースホルダーと同じ挙動)。
- **ファイル配置** — `assets/hero.mp4` / `assets/hero.webm` / `assets/hero-poster.webp`

## 6. 生成運用のコツ

まず同じプロンプトで静止画を生成してルックを固め、ベストフレームを image-to-video の始点にすると、車のデザインの一貫性と「実在車に似ない」管理がしやすくなります。光の移動速度は生成後にスロー再生で調整する前提なので、生成時は「ゆっくり動く」程度で妥協して構いません。完全静止に寄せすぎると生成が破綻しやすくなります。

## 7. 代替案(本命が上手く出ない場合)

**案B:フェンダー・マクロ(手の間近さ)**

```text
Photorealistic macro cinematography, static locked-off camera, 100mm macro lens. Extreme close-up of the front fender crest of a fictional 1960s-style hand-formed aluminum coupé, in near darkness (warm soft black, #1C1B18 feel). A narrow band of pale warm skylight (#F2EFE9 feel) travels across the curved metal with extreme slowness, left to right, revealing the faint hammer-finished texture of the aluminum and a single hairline specular line along the crest. Fine dust motes drift only within the light. Faintest volumetric haze; deepest shadows carry a barely visible desaturated green-grey tint. No logos, no text, no badges, no reflections of people or environment, no full car visible. Muted low-contrast film grade, no bloom, no lens flare. Meditative near-still pacing, seamless loop, silent.
```

**案C:天窓と塵(車は気配のみ)**

```text
Photorealistic cinematic footage, static locked-off wide shot, 50mm lens, of a dark museum hall before opening. A single tall blade of pale warm daylight (#F2EFE9 feel) descends diagonally from an unseen skylight into warm charcoal darkness (#1C1B18 feel, never pure black). Fine dust motes float, glimmer and fade only inside the shaft. In the far background, barely perceptible, the long low silhouette of a covered or shadowed vintage-style coupé — an original fictional design — is suggested by a single faint highlight on its roofline; the car reads as presence, not object, under 10% visible. Extremely slow drift of the light shaft across the floor, compressed sunlight. Faint haze, desaturated verdigris tint only in the deepest shadow. No text, no logos, no people, no camera movement, no cuts. Muted low-contrast archival film grade, silent, seamless loop.
```

**案D:磨き布の光(唯一の緩やかな移動)**

```text
Photorealistic cinematic footage, 85mm lens, near-darkness museum interior (warm soft black #1C1B18 feel). Ultra-slow lateral dolly, moving only a few centimeters over the entire shot, gliding along the flank of a fictional long-nose 1960s-style aluminum grand touring coupé of original design. A soft band of pale warm light (#F2EFE9 feel) travels along the roofline highlight at the same slow speed as the camera, like a polishing cloth drawn along the metal by an unseen hand — only a hairline specular line and the faint curve of the fender ever visible, the car never revealed. Fine dust in the light band, faint haze, trace of desaturated green-grey in shadow. No logos, no text, no people, no reflections of surroundings. Muted low-contrast film grade, no flare, no bloom. Meditative pacing, silent, composed to loop seamlessly.
```
