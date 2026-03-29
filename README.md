# MoCKA External Brain — AI Orchestra Bus

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_overview.svg" width="800">
</p>

> **This is not a chatbot router. Not a prompt chainer. Not a single-AI wrapper.**
> It is the layer where no single AI decides alone.
> ChatGPT, Gemini, Claude, and Perplexity deliberate as a council.
>
> This is governance, not generation.

---

## Position in mocka_Movement

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_architecture_v2.svg" width="720">
</p>
```
MoCKA (core · heart)
      ↓
mocka-knowledge-gate       ② Record
      ↓
mocka-transparency         ③ Incident · ④ Recurrence
      ↓
[ mocka-external-brain ]   ← ⑥ Decision — YOU ARE HERE
      ↓
MoCKA core executes        ⑦ Action
      ↓
mocka-civilization         ⑧ Institutionalize
```

**Loop step: ⑥ Decision**
Upstream: mocka-transparency → sends verified findings
Downstream: MoCKA core → executes the decision

---

## What this repository does

<p align="center">
  <img src="https://raw.githubusercontent.com/m-sirius-k/MoCKA/main/docs/images/mocka_loop_v2.svg" width="720">
</p>

mocka-external-brain enables multiple AI agents to deliberate,
reach consensus, and decide together.

### AI Orchestra Protocol
```
share → ask → reply → decide
```

Every decision is a structured deliberation, not a single prompt.

### The Council

| AI | Role |
|---|---|
| Gemini | Strategy · Consensus |
| Perplexity | Research · Context |
| Claude | Logic · Audit |
| ChatGPT | Execution · General |

### MoCKA Bus Protocol

Every message carries:
- `motion_type`: ask / reply / decide
- `parent_event_id`: links to origin event
- `evidence_ref`: cites proof
- `hash`: cryptographic integrity

---

## No single AI decides alone
```
Incident detected
      ↓
mocka-external-brain shares context to all AI agents
      ↓
Each AI responds with evidence-based reply
      ↓
Council reaches consensus decision
      ↓
Decision recorded in ledger — forever
      ↓
MoCKA core executes
```

This is how MoCKA prevents AI from going unchecked.

---

## Quick Start
```powershell
# Check the orchestra bus is connected
mocka-check

# View recent deliberation logs
Get-Content "logs\bus\events.csv" | Select-Object -Last 10
```

---

## Status

**Active Development**
Part of the MoCKA deterministic governance architecture.
Loop position: ⑥ Decision

---

## 日本語

### MoCKA External Brainとは何か

チャットボットルーターではありません。プロンプトチェーナーでもありません。
単一AIが決定することを許さない層です。
ChatGPT・Gemini・Claude・Perplexityが合議体として審議します。

これは生成ではなく、ガバナンスです。

### mocka_Movementにおける位置づけ
```
MoCKA（コア・心臓部）
      ↓
mocka-knowledge-gate       ② Record
      ↓
mocka-transparency         ③ Incident · ④ Recurrence
      ↓
[ mocka-external-brain ]   ← ⑥ Decision — ここです
      ↓
MoCKAコアが実行            ⑦ Action
      ↓
mocka-civilization         ⑧ 制度化
```

**ループステップ：⑥ Decision（決定）**
上流：mocka-transparency → 検証済み知見を送信
下流：MoCKAコア → 決定を実行

### このリポジトリの役割

複数のAIエージェントが審議し、合意し、共同で決定します。

### AIオーケストラプロトコル
```
share → ask → reply → decide
```

すべての決定は単一プロンプトではなく、構造化された審議です。

### 単一AIが決定しない原則

MoCKAはAIが暴走することを防ぎます。
複数AIが証拠を引用し、合議で決定し、
その決定が台帳に永久記録されます。

---

Part of the [MoCKA Deterministic Governance Architecture](https://github.com/m-sirius-k/MoCKA).
