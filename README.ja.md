# CTF & VDP

[English](README.md) | 日本語

公開CTFのwriteup、クラウド／Webセキュリティラボの学習記録、および公開可能なVDP（脆弱性開示プログラム）実践記録をプラットフォーム・イベント別に整理したリポジトリです。

## VDP実践（HackerOne）

実施期間：2026-11-09〜2026-11-21（月〜土、08:00〜09:00 JST）。実対象名、未公開の発見、生ログ、認証情報は本公開リポジトリには一切含めません。

| 文書 | 内容 |
| --- | --- |
| [VDPパイロットの日別進捗](hackerone/vdp-pilot-public-progress-2026-11.md) | 各回の実作業時間、実施概要、成功・失敗、停止理由の公開記録 |
| [2週間・計12時間のVDP実践設計](hackerone/hackerone-vdp-pilot-design-2026-11-08.md) | 対象選定条件、時間配分、AI補助の境界、安全停止ルール |
| [学習・実践ロードマップ](hackerone/hackerone-learning-roadmap.md) | Hacker101・HacktivityからVDPへ進む初期計画 |
| [ctf-vdp-harness](https://github.com/moruku36/ctf-vdp-harness) | 境界付きCTF／VDP検証に使用しているMCP解析ハーネス |

## CTF・ラボ一覧

| イベント／プラットフォーム | 記録状況・スコア | 日付 | 主なリンク |
| --- | --- | --- | --- |
| [Hacker101 CTF](#hacker101-ctf) | 26課題・計283点 | 2026-10-29 – 11-02 | [hacker101/README.md](hacker101/README.md) |
| [PumpkinShell (Wiz)](#pumpkinshell) | 全5問クリア（95/100点） | 2026-10-27 | [一覧](#pumpkinshell) · [証明書](pumpkinshell/pumpkinshell-certificate.png) |
| [Pwned Labs](#pwned-labs) | AWS Blue Teaming 3問・Google Storage 1問 | 2026-10-22 – 10-23 | [一覧](#pwned-labs) |
| [Prompt Airlines](#prompt-airlines) | 全5問クリア＋ライブリプレイ | 2026-10-18 – 10-22 | [一覧](#prompt-airlines) · [証明書](prompt-airlines/prompt-airlines-certificate.png) |
| [Cloud Security Championship](#cloud-security-championship) | #1・#6 クリア、#2・#4・#5・#7 公開解答照合 | 2026-10-16 – 10-22 | [一覧](#cloud-security-championship) · [RESULTS.md](RESULTS.md) |
| [The Cloud Hunting Games](#the-cloud-hunting-games) | 全5問クリア（40点） | 2026-10-18 | [Writeup](cloud-hunting-games/cloud-hunting-games-2026-10-18.md) · [証明書](cloud-hunting-games/cloud-hunting-games-certificate.png) |
| [K8s LAN Party](#k8s-lan-party) | 5問中2問確認（詳細はRESULTS.md） | 2026-10-16 | [RESULTS.md](RESULTS.md) · [証明書](k8s-lan-party/k8s-lan-party-certificate.png) |

## イベント別 Writeup

### Hacker101 CTF

- [Hacker101 CTF 解法記録・進捗一覧](hacker101/README.md)

### PumpkinShell

全5チャレンジクリア、95/100点（2026-10-27）。

- [Dependency Issues](pumpkinshell/pumpkinshell-dependency-issues-2026-10-27.md)
- [Gist of the Problem](pumpkinshell/pumpkinshell-gist-of-the-problem-2026-10-27.md)
- [It Sucks](pumpkinshell/pumpkinshell-it-sucks-2026-10-27.md)
- [Through the Lens](pumpkinshell/pumpkinshell-through-the-lens-2026-10-27.md)
- [Unlock the Core Memory](pumpkinshell/pumpkinshell-unlock-the-core-memory-2026-10-27.md)
- [証明書](pumpkinshell/pumpkinshell-certificate.png)

### Cloud Security Championship

チャレンジ #1 は [RESULTS.md](RESULTS.md) に記録。#2、#4、#5、#6、#7 の writeup と未解決分の調査ログ：

- [#2 — Contain Me If You Can](cloud-security-championship/cloud-security-championship-contain-me-if-you-can-2026-10-22.md)
- [#4 — Needle in a Haystack](cloud-security-championship/cloud-security-championship-needle-in-a-haystack-2026-10-22.md)
- [#5 — Game of Pods](cloud-security-championship/cloud-security-championship-game-of-pods-2026-10-22.md)
- [#6 — Malware Busters!](cloud-security-championship/cloud-security-championship-malware-busters-2026-10-18.md) · [証明書](cloud-security-championship/cloud-security-championship-malware-busters-certificate.png)
- [#7 — State of Affairs](cloud-security-championship/cloud-security-championship-state-of-affairs-2026-10-22.md)
- [未解決チャレンジの調査ログ](cloud-security-championship/cloud-security-championship-partial-progress-2026-10-22.md)

### The Cloud Hunting Games

全5チャレンジクリア、40ポイント（2026-10-18）。

- [Writeup](cloud-hunting-games/cloud-hunting-games-2026-10-18.md) · [証明書](cloud-hunting-games/cloud-hunting-games-certificate.png)

### Prompt Airlines

5/5チャレンジクリア、およびライブリプレイ。

- [5/5チャレンジ（2026-10-18）](prompt-airlines/prompt-airlines-2026-10-18.md)
- [ライブ5/5リプレイ（2026-10-22）](prompt-airlines/prompt-airlines-2026-10-22.md)
- [チャレンジ4用メンバーカード生成スクリプト](prompt-airlines/make-member-card.ps1)
- [証明書](prompt-airlines/prompt-airlines-certificate.png)

### K8s LAN Party

5問中2問確認（2026-10-16、詳細は [RESULTS.md](RESULTS.md)）。

- [初期結果サマリー（RESULTS.md）](RESULTS.md) · [証明書](k8s-lan-party/k8s-lan-party-certificate.png)

### Pwned Labs

- [AWS Blue Teaming — 3問クリア](pwned-labs/pwned-labs-aws-blue-teaming-2026-10-22.md)
- [Reveal Hidden Files in Google Storage](pwned-labs/pwned-labs-reveal-hidden-files-google-storage-2026-10-23.md)
- [無料ラボの進捗ログ](pwned-labs/pwned-labs-partial-progress-2026-10-23.md)

## 記録方針と公開範囲

- **構成**: プラットフォーム・イベントごとに1フォルダー、ファイル名は `<event>-<challenge>-<date>.md`。
- **再現性の区別**: 環境障害時に公開解説のフラグで受理確認したケースと、環境内で独立に再現したケースを明確に区別して記録します（[RESULTS.md](RESULTS.md) 参照）。
- **秘匿化**: 実際の認証情報、パスワード、トークン、未公開VDPの対象・発見内容、個人データは一切記載しません。

## 参考リンク

- [HackerOne](https://www.hackerone.com/) · [HackerOne ドキュメント](https://docs.hackerone.com/en/) · [X の HackerOne](https://x.com/Hacker0x01)
