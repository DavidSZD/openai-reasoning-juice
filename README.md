# OpenAI Reasoning Budget ("Juice") Benchmarks

Internal reasoning budget (*Juice*) values across OpenAI model generations, platforms (API and Codex), and ChatGPT Web subscription tiers.

> **Note**: OpenAI periodically updates and recalibrates internal reasoning budgets without prior notice. The values below reflect empirical measurements at their time of capture; certain historical figures may have been adjusted by OpenAI since they were originally recorded.

---

## GPT-6.2 *(Measured: November 17, 2026)*

| Model | Platform | Low | Medium | High | XHigh | Max |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **GPT-6.2 Sol** | API | 8 | 48 | 128 | 384 | 832 |
| **GPT-6.2 Sol** | Codex | 16 | 42 | 100 | 200 | 832 |
| **GPT-6.2 Astra** | API | 4 | 16 | 64 | 128 | 832 |
| **GPT-6.2 Astra** | Codex | 4 | 10 | 28 | 64 | 832 |

---

## GPT-6 & GPT-6.1

| Model | Platform | Low | Medium | High | XHigh | Max |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **GPT-6.1 Sol** | API | 4 | 10 | 24 | 64 / 96 | 832 |
| **GPT-6.1 Sol** | Codex | 2 | 7 | 13 | 56 | 168 |
| **GPT-6.1 Terra** | API | 4 | 12 | 24 | 64 | 832 |
| **GPT-6.1 Terra** | Codex | 1 | 2 | 4 | 10 | 128 |
| **GPT-6 Sol** | API | 4 | 12 | 24 | 64 | 768 |
| **GPT-6 Sol** | Codex | 1 | 10 | 15 | 21 | 62 |
| **GPT-6 Astra** | API | 4 | 12 | 24 | 64 | 768 |
| **GPT-6 Astra** | Codex | 2 | 4 | 10 | 32 | 128 |
| **GPT-6 Luna** | API | 4 | 12 | 24 | 64 | 768 |
| **GPT-6 Luna** | Codex | 1 | 3 | 6 | 25 | 70 |

---

## GPT-5.6

| Model | Platform | Low | Medium | High | XHigh | Max |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **GPT-5.6 Sol** | Codex / API | 8.085 | 16.885 | 40 | 128 | 960 |
| **GPT-5.6 Terra** | Codex / API | 12 | 16 | 32 | 84 | 960 |
| **GPT-5.6 Luna** | Codex / API | 8 | 16 | 48 | 128 | 768 |

---

## GPT-5.0 to GPT-5.5

| Model | Platform | None | Minimal | Low | Medium | High | XHigh |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **GPT-5.5** | API | 0 | - | 12 | 48 | 128 | 768 |
| **GPT-5.5** | Codex | - | - | 12 | 24 | 96 | 768 |
| **GPT-5.4** | API | 0 | - | 16 | 48 | 128 | 768 |
| **GPT-5.4** | Codex | - | - | 12 | 20 | 96 | 512 |
| **GPT-5.4 Mini** | API | 0 | - | 8 | 24 | 64 | 768 |
| **GPT-5.4 Nano** | API | 0 | - | 8 | 24 | 64 | 512 |
| **GPT-5.4 Pro** | API | - | - | - | 256 | 512 | 768 |
| **GPT-5.3** | Codex | - | - | 24 | 54 | 256 | 768 |
| **GPT-5.2** | API | 0 | - | 16 | 64 | 256 | 768 |
| **GPT-5.2** | Codex | - | - | 256 | 400 | 600 | 768 |
| **GPT-5.1** | API | 0 | - | 16 | 64 | 256 | - |
| **GPT-5.1** | Codex | - | - | 64 | 192 | 256 | - |
| **GPT-5** | API | - | 5 | 16 | 64 | 200 | - |
| **GPT-5** | Codex | - | - | 64 | 192 | 256 | - |
| **GPT-5 Mini** | API | - | 5 | 8 | 32 | 256 | - |
| **O3** | API | - | - | 32 | 64 | 512 | - |
| **Codex Max** | Codex | - | - | 32 | 144 | 192 | 232 |
| **Codex Web** | Web | - | - | 32 | - | - | - |

---

## ChatGPT Web

### Free Tier

| Model | Instant | Router | Thinking |
| :--- | :---: | :---: | :---: |
| **GPT-5 Mini** | - | 18 | 32 |
| **GPT-6 Luna** | 2 | - | 16 |

### Paid Tier

| Model | Instant | Light | Medium | Standard | Extended | Heavy / High | XHigh | Router | Thinking |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **GPT-5** | - | 5 | - | 18 | 64 | 200 | - | 64 | 128 |
| **GPT-5 Thinking Mini** | - | - | - | - | - | - | - | - | 32 |
| **GPT-5.1** | 16 | 16 | - | 96 | 256 | 512 | - | 48 | 128 |
| **GPT-5.2** | 8 | 16 | - | 64 | 256 | 768 | - | 16 | - |
| **GPT-5.4** | - | 8 | - | 16 | 96 | 512 | - | - | - |
| **GPT-5.5** | - | 12 | - | 24 | 192 | - | 768 | - | - |
| **GPT-5.6 Sol (Initial)** | - | - | 8 | - | - | 48 | 112 | - | - |
| **GPT-5.6 Sol (Updated)** | 2 | - | 6 | - | - | 42 | - | - | - |
| **GPT-6 Sol** | 4 | - | 6 | - | - | 42 | 122 | - | - |
| **O3** | - | - | - | - | - | 128 | - | - | - |

---

## Data Files

- [`data/juice_benchmarks.json`](data/juice_benchmarks.json) : Complete machine-readable JSON dataset.
- [`data/juice_benchmarks.csv`](data/juice_benchmarks.csv) : Tabular CSV dataset.
- [`data/chatgpt_web_tiers.json`](data/chatgpt_web_tiers.json) : ChatGPT Web tiers dataset.
