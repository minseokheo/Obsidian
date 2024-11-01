
|     | Category | Confidence | TP/FP |
| --- | -------- | ---------- | ----- |
| 1   | Plastic  | 72%        | TP    |
| 2   | Plastic  | 80%        | TP    |
| 3   | Plastic  | 41%        | FP    |
| 4   | Plastic  | 10%        | TP    |
| 5   | Plastic  | 60%        | TP    |
| 6   | Plastic  | 32%        | FP    |
| 7   | Plastic  | 82%        | FP    |
| 8   | Plastic  | 95%        | TP    |
| 9   | Plastic  | 90%        | TP    |
| 10  | Plastic  | 70%        | FP    |
|     |          |            |       |

|     | Category | Confidence | TP/FP | 누적 TP | 누적 FP | Precision  | Recall     |
| --- | -------- | ---------- | ----- | ----- | ----- | ---------- | ---------- |
| 8   | Plastic  | 95%        | TP    | 1     | -     | 1/1 = 1    | 1/10 = 0.1 |
| 9   | Plastic  | 90%        | TP    | 2     | -     | 2/2 = 1    | 2/10 = 0.2 |
| 7   | Plastic  | 82%        | FP    | 2     | 1     | 2/3 = 0.66 | 2/10 = 0.2 |
| 2   | Plastic  | 80%        | TP    | 3     | 1     | 3/4 = 0.75 | 3/10 = 0.3 |
| 1   | Plastic  | 72%        | TP    | 4     | 1     | 4/5 = 0.8  | 4/10 = 0.4 |
| 10  | Plastic  | 70%        | FP    | 4     | 2     | 4/6 = 0.66 | 5/10 = 0.5 |
| 5   | Plastic  | 60%        | TP    | 5     | 2     | 5/7 = 0.71 | 5/10 = 0.5 |
| 3   | Plastic  | 41%        | FP    | 5     | 3     | 5/8 = 0.63 | 5/10 = 0.5 |
| 6   | Plastic  | 32%        | FP    | 5     | 4     | 5/9 = 0.56 | 5/10 = 0.5 |
| 4   | Plastic  | 10%        | TP    | 6     | 4     | 6/10 = 0.6 | 6/10 = 0.6 |
