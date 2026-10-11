# listlab-models

On-device models for ListLab, published as release assets. The app only downloads them
when AI is turned on (Settings > AI), checks the SHA-256 of every part and runs them on
the phone. Nothing is sent anywhere.

| File | Model | Used for | Licence |
|---|---|---|---|
| `gemma4-e2b-q4.part1`, `.part2` | Gemma 4 E2B instruct, Q4 GGUF | turning captures into suggestions | Apache-2.0 ([Gemma 4 terms](https://ai.google.dev/gemma/docs/gemma_4_license)) |
| `whisper-base.bin` | Whisper base, ggml | voice notes to text | MIT |

Each release carries the licence and NOTICE files for its models.
