[![syntax](https://img.shields.io/badge/syntax-AdGuard-brightgreen.svg)](https://kb.adguard.com/en/general/how-to-create-your-own-ad-filters)
[![syntax](https://img.shields.io/badge/syntax-uBlock%20Origin-%23c61300.svg)](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax)

# adblock2
Personal filters and rules for AdGuard/uBlock Origin

I can't guarantee these filers/rules won't cause problems. If you found problems, report that by filling in all the mandatory items in Issue template; otherwise reports may not be addressed. Anyone who uses my filters/rules shall be deemed to have agreed that I have no responsibility or liability for costs, losses, damages, etc. arising from the use of the filters/rules. Unless Subscribe link is provided, these filters/rules are assumed to be copied and pasted, or imported, into My filters/rules (uBlock Origin) or User Rules (AdGuard).

個人作成のAdGuard/uBlock Origin用フィルタないしルールです。これらの使用により不具合が発生することがあります。いかなる形であれこれらのフィルタないしルールを使用する方は、それによる被害や損失に対し、管理人Yuki2718と当レポジトリのすべての貢献者が一切の責任を負わないことに同意するものとします。不具合についてはIssueテンプレートの必要事項をすべて記入の上、Issueを通じてご報告ください。

## AdGuard Japanese filters Plus

[AdGuard Japanese filter](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt)を補完するフィルタです。

<a href="https://subscribe.adblockplus.org?location=https://raw.githubusercontent.com/Yuki2718/adblock2/main/japanese/jpf-plus.txt&title=AdGuard%20Japanese%20filters%20Plus">購読する</a>
[中身を見る](https://raw.githubusercontent.com/Yuki2718/adblock2/main/japanese/jpf-plus.txt)

## AdGuard DNS filter Unbreaker for Japanese（AdGuard DNSフィルタ不具合修正パッチ）

This list fixes known problems in AdGuard DNS filter mostly for Japanese user. Do not report any problem of AdGuard DNS filter directly to this repo, but open an issue ticket in AdGuardSDNSFilter repo.

<strong>ブロックよりも不具合の低減を優先するユーザー向けです。コンテンツブロック/ブロッカーではなくDNSフィルタに追加購読してください。</strong>

AdGuard DNSフィルタの既知の不具合を独自に修正します。DNSフィルタはブロックするかしないかの二択しかなく、融通が利きません。しかし、AndroidのAdGuard無料版ユーザーやiOSユーザーはこれを使わずにアプリ内広告をブロックする手段があまりなく、他に代替となるリストも多くはないと思われます。また、不具合を報告してもブロック漏れとの兼ね合いがあるため必ずしも対処されません。

- 直接こちらに不具合を報告する前に、まずAdGuard公式に報告してください。メンテンナンスは主に、AdGuardに報告された問題の中から任意に行う予定です
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
