# MoCKA External Brain

MoCKA External Brain is the controlled interoperability layer of the MoCKA Ecosystem.

It manages structured interaction with external knowledge systems, APIs, and auxiliary intelligence sources while preserving deterministic governance constraints.

It connects.
It does not override.

## Architecture Overview

External Brain bridges outfield synchronization with external systems under governance constraints defined by Civilization.

![MoCKA Architecture Overview](docs/architecture/mocka_architecture_overview.png)

## Security Model

Threat assumptions:

- External data poisoning
- Non-deterministic side effects
- Leakage of canonical state
- Unbounded API behavior

Controls:

- Strict separation between canonical (infield) and external interaction (outfield)
- Explicit import/export boundaries
- Hash-based traceability for imported artifacts
- Governance-defined access policies
- Deterministic wrapper protocols

External Brain is treated as a boundary layer.
All interactions are mediated and auditable.

## Repository Responsibility

This repository focuses on:

- External synchronization adapters
- Controlled data import/export logic
- Protocol wrappers for external systems
- Isolation of canonical state from non-deterministic inputs

## Relationship to Ecosystem

- MoCKA: consumes validated external inputs
- Knowledge Gate: records interaction traces
- Civilization: defines permitted interaction scope
- Transparency: may publish verified extracts

---

# MoCKA External Brain（日本語）

MoCKA External Brain は、MoCKA エコシステムの制御された相互接続層です。

外部知識システムやAPIとの構造化連携を行いますが、決定論的統治制約を維持します。

接続します。
上書きはしません。

## Architecture Overview（全体図）

External Brain は、outfield 同期と外部システムを橋渡しします。
その際、Civilization が定義した統治制約に従います。

![MoCKA Architecture Overview](docs/architecture/mocka_architecture_overview.png)

## Security Model（脅威と対策）

想定脅威：

- 外部データ汚染
- 非決定的副作用
- 正本状態の漏洩
- 制御不能なAPI挙動

対策：

- 正本（infield）と外部接続（outfield）の厳格分離
- 明示的な入出力境界
- 取り込み成果物のハッシュ追跡
- 統治定義によるアクセス制御
- 決定的ラッパープロトコル

External Brain は境界層として扱われます。
すべての接続は媒介され、監査可能です。

## 本リポジトリの責務

- 外部同期アダプタの実装
- 制御されたデータ入出力ロジック
- 外部システム用プロトコルラッパー
- 正本状態の隔離

## エコシステム関係

- MoCKA：検証済み入力を消費
- Knowledge Gate：接続痕跡を保存
- Civilization：接続範囲を定義
- Transparency：検証済み抽出を公開
