# Changelog

## [0.3.0-alpha.1] - 2026-11-21

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Added

- 本人の三人称視点と他のプレイヤーの画面で、RX-78-2の全身の動きと装備の持ち替えを表示します。
- BOT練習場に、ハイパー・ハンマーで盾を崩してライフルで追撃できる標的を追加しました。練習場で構えたバニラ盾も、ハンマーの直撃で3秒間使えなくなります。

### Changed

- ビーム・ライフルが遠距離の標的にも命中するよう射程と距離減衰を修正し、ADSを保持したままリロードした直後の初弾に照準時の精度を適用しました。
- ハイパー・ハンマーが床に当たったときの火花と、スーパーナパームの炎・残火の演出を更新しました。

## [0.2.4-alpha.1] - 2026-11-16

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Added

- RX-78-2とビーム・ライフルを装備中にしゃがめるようになりました。専用キーは設定で変更できます。

### Fixed

- ハイパー・ハンマーの構え中に照準を振ると、投げる方向に反映されるようになりました。
- ハイパー・ハンマーの投擲直後に、飛翔モデルが一瞬画面を覆う問題を修正しました。
- BOT練習場でスーパーナパームを初めて使うときの引っかかりを軽減しました。

## [0.2.3-alpha.1] - 2026-11-16

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Fixed

- 壁の縁をかすめるビーム・ライフルの弾が、射線が通っているのに壁で止まる問題を修正。
- ハイパー・ハンマーの爆風で押し出された練習用ザクIIが、段差の縁に引っかかる問題を修正。

## [0.2.2-alpha.3] - 2026-11-15

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Added

- スーパーナパーム使用時に三人称へ切り替わり、全身の投擲・反動モーションと武器の持ち替えを表示。
- ハイパー・ハンマーを構えて投げる一人称モーションを追加。

### Changed

- 練習用ザクIIのハイパー・ハンマー被弾後の減速と着地を原作に近づけ、ライフルの命中部位に応じてダメージが変わるように変更。

### Fixed

- 空中でも盾を構え、正面からの攻撃を防げるように修正。

## [0.2.1-alpha.1] - 2026-11-15

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Changed

- ハイパー・ハンマーの爆風ダメージ、押し出し、遮蔽判定を改善。

### Fixed

- スーパーナパーム使用時のライフル残弾補充、リロード解除、ADS復帰を修正。
- 盾・ハイパー・ハンマー・スーパーナパームを続けて使ったときの発動条件と再使用待ちを修正。

## [0.2.0-alpha.1] - 2026-11-15

Minecraft 1.21.1／NeoForge 21.1.265／Java 21

### Added

- RX-78-2に一人称で構えられる盾を追加。正面からの攻撃を防ぎ、盾には耐久と再使用待ちがあります。
- ハイパー・ハンマーと、着弾後に範囲ダメージを与えるGマニューバ「スーパーナパーム」を追加。
- BOT練習場にブースト、スキル、Gマニューバ、ライフルの残弾を表示するHUDを追加。

## [0.1.0-alpha.1] - 2026-11-14

### Added

- Minecraft 1.21.1／NeoForge 21.1.265／Java 21向けの配布JARを追加。
- RX-78-2の操縦とBOT練習場をNeoForgeへ移植。
- ビーム・ライフルの射撃時の反動と、一人称リロードアニメーションを追加。
- ADS開始時の視野角と、横移動・斜め移動・ステップ中の構えを調整。

## [0.0.1-alpha.1] - 2023-12-24

### Added

- Minecraft 1.20.1／Forge 47.2.18／Java 17向けの初回α版JARを配布。

[0.3.0-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.3.0-alpha.1
[0.2.4-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.2.4-alpha.1
[0.2.3-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.2.3-alpha.1
[0.2.2-alpha.3]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.2.2-alpha.3
[0.2.1-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.2.1-alpha.1
[0.2.0-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.2.0-alpha.1
[0.1.0-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/releases/tag/v0.1.0-alpha.1
[0.0.1-alpha.1]: https://github.com/NPJigaK/gunevo-minecraft/commit/a14b5e23dbc818517d45a184e77d7aead623245a

