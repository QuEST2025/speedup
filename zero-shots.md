| Model                  | Num Tokens | HSWAG   | ARC-e   | ARC-c   | PiQA   | Winogrande | Avg. 0-shot | C4 Val Loss |
|------------------------|------------|---------|---------|---------|--------|------------|-------------:|-------------:|
| 800M-BF16              | 80B        | 39.51%  | 53.28%  | 22.44%  | 71.65% | 53.91%     | 48.96%       | 2.461        |
| 800M-W4A4              | 80B        | 39.18%  | 52.40%  | 22.01%  | 71.16% | 52.96%     | 47.94%       | 2.494        |
| 800M-W4A4-NO-HT        | 80B        | 38.03%  | 52.44%  | 22.70%  | 71.11% | 51.38%     | 47.13%       | 2.517        |
| 800M-W4A4-4:8-INT4     | 80B        | 36.26%  | 50.46%  | 21.08%  | 69.04% | 53.75%     | 46.12%       | 2.589        |
