Latest Score 0.75837 V7  features = ["Ageclass", "Fclass", "Sex"] RandomForestClassifier.

Best Score 0.76555 V5   features = ["Fclass", "Sex", "Age"] RandomForestClassifier.

Training data analysis
Classes determined by XL percentile 0.10, 0.25, 0.50, 0.75, 0.90 on train data.

YA = Age > 14 & <= 20.1

| Fare   | Fclass | Age  | Ageclass |
|--------|--------|------|----------|
| $7.55  | 1      | 14.0 | C        |
| $7.91  | 2      | 20.1 | YA       |
| $14.45 | 3      | 28.0 | A        |
| $31.00 | 4      | 38.0 | AA       |
| $77.96 | 5      | 50.0 | S        |

### Survival Counts
| Age Class | Fclass 1 | Fclass 2 | Fclass 3 | Fclass 4 | Fclass 5 |
|-----------|----------|----------|----------|----------|----------|
| C         | 1        | 0        | 5        | 13       | 5        |
| YA        | 2        | 4        | 7        | 6        | 10       |
| A         | 2        | 5        | 12       | 12       | 16       |
| AA        | 0        | 0        | 14       | 22       | 41       |
| S         | 0        | 0        | 3        | 4        | 13       |
| U         | 2        | 14       | 1        | 9        | 10       |

### Deceased Counts
| Age Class | Fclass 1 | Fclass 2 | Fclass 3 | Fclass 4 | Fclass 5 | 
|-----------|----------|----------|----------|----------|----------|
| C         | 0        | 1        | 1        | 6        | 6        |
| YA        | 1        | 1        | 2        | 5        | 1        |
| A         | 0        | 3        | 8        | 3        | 2        |
| AA        | 0        | 3        | 5        | 10       | 4        |
| S         | 0        | 0        | 1        | 1        | 0        |
| U         | 1        | 3        | 3        | 7        | 3        |  


### Survival counts:
| Pclass | 1  | 2  | 3  |
|--------|----|----|----|
| C      | 1  | 10 | 13 |
| YA     | 12 | 6  | 11 |
| A      | 14 | 19 | 14 |
| AA     | 41 | 28 | 8  |
| S      | 14 | 5  | 1  |
| U      | 9  | 2  | 25 |
