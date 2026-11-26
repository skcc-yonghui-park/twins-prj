# twins-prj

박C*, 박J* 쌍둥이 형제의 **2027학년도 대학 진학 논술시험**을 준비하는 공간입니다.

## 수험생 및 시험 일정

| 수험생 | 계열 | 대학 | 시험일 | 폴더 |
|---|---|---|---|---|
| 박C* | 문과 | 국민대학교 (kookmin) | 2026-12-05 (토) | [chan-university/kookmin](chan-university/kookmin/) |
| 박J* | 이과 | 가천대학교 (gachon) | 2026-11-30 (월) | [ju-university/gachon](ju-university/gachon/) |
| 박J* | 이과 | 국민대학교 (kookmin) | 2026-12-06 (일) | [ju-university/koomin](ju-university/koomin/) |

## 폴더 구조

```
twins-prj/
├── chan-university/      # 박C* (문과)
│   └── kookmin/
├── ju-university/        # 박J* (이과)
│   ├── gachon/
│   └── koomin/
└── README.md
```

대학별 폴더는 모두 같은 구조를 따릅니다.

- `doc/` - 기출문제·가이드북·해설지(`answer/`)와 수험생 풀이 결과 데이터(`solve/`) 저장소
- `direction/` - 학습 방향 및 전략 기준 문서와 섹터별 작업 프롬프트 (`direction.md`, 작업 전 먼저 읽기)
- `result/` - doc 기반 분석 보고서, 수험생 수준의 준비·단기 전략 정의서, 작업 기록(`result.md`)
