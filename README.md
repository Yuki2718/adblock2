[![syntax](https://img.shields.io/badge/syntax-AdGuard-brightgreen.svg)](https://kb.adguard.com/en/general/how-to-create-your-own-ad-filters)
[![syntax](https://img.shields.io/badge/syntax-uBlock%20Origin-%23c61300.svg)](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax)

# adblock2
Personal filters and rules for AdGuard/uBlock Origin

I can't guarantee these filers/rules won't cause problems. If you found problems, report that via [Issue ticket](https://github.com/Yuki2718/adblock2/issues). Anyone who uses my filters/rules shall be deemed to have agreed that I have no responsibility or liability for costs, losses, damages, etc. arising from the use of the filters/rules. Unless Subscribe link is provided, these filters/rules are assumed to be copied and pasted, or imported, into My filters/rules (uBlock Origin) or User Rules (AdGuard).

個人作成のAdGuard/uBlock Origin用フィルタないしルールです。これらの使用により不具合が発生することがあります。いかなる形であれこれらのフィルタないしルールを使用する方は、それによる被害や損失に対し、管理人Yuki2718と当レポジトリのすべての貢献者が一切の責任を負わないことに同意するものとします。不具合についてはIssueを通じてご報告ください。

## AdGuard Japanese filter Plus

This complements [AdGuard Japanese filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt) and mainly consists of 1) additional generic rules to counter circumvention ads and anti-adblock, and 2) specific rules to address sites not addresed in the Japanese filters. Only AdGuard AdBlocker (browser extension), uBlock Origin, AdGuard AdBlocker MV3, and uBlock Origin Lite are officially supported.

Please report any incorrect blocking or error via [Issue ticket](https://github.com/Yuki2718/adblock2/issues). OTOH unblocked ads, placeholder, or anti-adblock should first be reproted to [AdGuard](https://reports.adguard.com/en/new_issue.html). If the issue is not addressed by AdGuard, it can potentially be reported here; however, I accept reports only from those who have contribution history to any of public adblocking repository in case of unblocking. This policy is to avoid too many reports of those unblocking cases and may change in future.

[AdGuard Japanese filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt)を補完するフィルタで、迂回広告や悪質ポップアップ、一部のアンチ広告ブロックへの汎用的な追加対策と、AdGuard Japanese filterで対応しないサイトへの対応を主眼とします。サポート対象はAdGuard 広告ブロッカー（ブラウザ拡張機能）とuBlock Originです。AdGuard AdBlocker MV3とuBlock Origin Liteもサポートいたしますが、本稿執筆時点ではこれらはまだベータ版以前の実験的段階であることにご注意ください。AdGuard for Windows/Mac/Android/Safari/iOSでも自己責任でのご利用はできますが、正式にはサポートしません。とくにSafari/iOSでは多くのルールが機能しません。上記以外のブロッカー、たとえばAdblock PlusやVivaldiの組込みブロッカーでの使用は強く非推奨とします。

このフィルタによる不具合や誤植などの報告は[Issue](https://github.com/Yuki2718/adblock2/issues)か[したらば掲示板](https://jbbs.shitaraba.net/internet/25463/)から受けつけます。一方、ブロック漏れやアンチ広告ブロックの対応漏れについては、個別対応を最小限とする方針ですのでまずは[AdGuardに報告](https://reports.adguard.com/ja/new_issue.html)してください。AdGuardで対応されない場合はGithubのIssueを通してのみ、かつ広告ブロックコミュニティに貢献歴<sup>1</sup>のある方からの報告のみ受け付けます。これはAdGuard基準外のサイトの報告が大量に流れ込むのを防ぐためのさしあたりの措置で、今後変更する可能性があります。よい考えをお持ちの方はIssueなどでご提案ください。

<sub>1: プルリクエストに限らずIssue報告でも構いませんが、長期的（おおむね半年以上）に同一のGithubアカウントを保持していることが条件です。対象は[AdGuard](https://github.com/AdguardTeam)（[AdguardFilters](https://github.com/AdguardTeam/AdguardFilters)に限らない）、[Easylist](https://github.com/easylist/easylist)、[uBlock Origin](https://github.com/uBlockOrigin)、[Yuki2718/adblock](https://github.com/Yuki2718/adblock)など、よく知られた広告ブロックコミュニティであればどこでも構いません。</sub>

#### 対象

以下のうち、汎用的に対策可能かAdGuard Japaneseで対応されないもの
- 広告、アフィリエイトリンク
- ネイティブ広告
- 侵襲性の高いセルフプロモーション
- 主に上記をブロックしたため生じた枠や不要なスペース
- アンチ広告ブロック
- 迷惑・有害なポップアップ、ポップアンダー、リダイレクト
- 一部の詐欺・悪質サイト（セキュリティーソフトの代わりにはなりません）

#### 対象外
- サイトの内容と強く関連しており（例：具体的な商品のレビュー）、かつ量が過剰でなくユーザーに不利益・不快感を与えない広告（「ゲームのブログだからゲームの広告」程度では強く関連しているとみなしません。また、積極的にブロックしないだけで、すでにAdGuard Japanese等でブロックされている場合は手を出しません）
- 運営母体の系列サイトへのリンクバナーで、それほど不快でないもの
- アフィリエイトリンクの汎用非表示
- 広告ブロッカー検知用の罠スクリプト
- Google Safe Browsingでカバーされている悪質サイト
- 失効ドメイン

<a href="https://subscribe.adblockplus.org?location=https://raw.githubusercontent.com/Yuki2718/adblock2/main/japanese/jpf-plus.txt&title=AdGuard%20Japanese%20filters%20Plus">Subscribe/購読する</a>
[View List/中身を見る](https://raw.githubusercontent.com/Yuki2718/adblock2/main/japanese/jpf-plus.txt)

## AdGuard DNS filter Unbreaker for Japanese（AdGuard DNSフィルタ不具合修正パッチ）

This list fixes known problems in AdGuard DNS filter mostly for Japanese user. Do not report any problem of AdGuard DNS filter directly to this repo, but open an issue ticket in AdGuardSDNSFilter repo.

<strong>ブロックよりも不具合の低減を優先するユーザー向けです。コンテンツブロック/ブロッカーではなくDNSフィルタに追加購読してください。</strong>

AdGuard DNSフィルタの既知の不具合を独自に修正します。DNSフィルタはブロックするかしないかの二択しかなく、融通が利きません。しかし、AndroidのAdGuard無料版ユーザーやiOSユーザーはこれを使わずにアプリ内広告をブロックする手段があまりなく、他に代替となるリストも多くはないと思われます。また、不具合を報告してもブロック漏れとの兼ね合いがあるため必ずしも対処されません。

- 直接こちらに不具合を報告する前に、まず[AdGuardに報告](https://reports.adguard.com/ja/new_issue.html)してください。メンテンナンスは主に、AdGuardに報告された問題の中から任意に行う予定です
- あらゆる不具合に対処する予定はありません。公式より緩い基準とはいえ、ブロック除外により漏れる広告が多い場合は対応しません
- 今後とも、モバイルアプリの問題を積極的にサポートする予定はありません。メンテンナンスコストが高くなった場合、公開停止もあり得ます

[View List/中身を見る](https://raw.githubusercontent.com/Yuki2718/adblock2/main/japanese/dns-unbreak.txt)

## Yuki's uBlock Dynamic Rules

Nooplists for medium mode of uBlock Origin dedicated for English user. The objective is to help those non-techie, yet security-conscious, people to use the mode. Payment services and mobile sites are out-of-scope.

ミディアムモード用のnoopリストで、英語圏向けです。

[View Rules/中身を見る](https://raw.githubusercontent.com/Yuki2718/adblock2/main/medium_mode/dynamic-rules.txt)

## Yuki's uBlock Dynamic Rules for Mobile

Mobile version of Yuki's uBlock Dynamic Rules

Yuki's uBlock Dynamic Rulesのモバイル版です。

[View Rules/中身を見る](https://raw.githubusercontent.com/Yuki2718/adblock2/main/medium_mode/dynamic-rules-mob.txt)
