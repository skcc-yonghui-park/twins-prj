# twins-prj

박C*, 박J* 쌍둥이 형제의 **2027학년도 대학 논술전형**을 준비하는 저장소입니다.
수험생별 폴더 → 대학별 폴더 → `doc/`·`direction/`·`result/` 순서로 내려가며, 모든 폴더의 README에서 하위 문서로 바로 이동할 수 있습니다.

## 요약

| 수험생 | 계열 | 대학 | 시험일 | 대학 폴더 |
|---|---|---|---|---|
| 박C* | 문과 | 국민대학교 인문계열 | 2026-12-05 (토) | [chan-university/kookmin](chan-university/kookmin/README.md) |
| 박J* | 이과 | 가천대학교 자연계열 | 2026-12-01 (화) | [ju-university/gachon](ju-university/gachon/README.md) |
| 박J* | 이과 | 국민대학교 자연계열 | 2026-12-06 (일) | [ju-university/kookmin](ju-university/kookmin/README.md) |

## 하위 디렉터리

| 디렉터리 | 설명 |
|---|---|
| [chan-university/](chan-university/README.md) | 박C*(문과)의 대학별 논술 준비 공간. 국민대 인문계열 |
| [ju-university/](ju-university/README.md) | 박J*(이과)의 대학별 논술 준비 공간. 가천대·국민대 자연계열 |

```
twins-prj/
├── README.md                 # 이 문서
├── chan-university/          # 박C* (문과)
│   └── kookmin/              # 국민대 인문계열
└── ju-university/            # 박J* (이과)
    ├── gachon/               # 가천대 자연계열
    └── kookmin/              # 국민대 자연계열
```

## 대학 폴더 공통 구조

모든 대학 폴더는 같은 구조를 따릅니다.

| 디렉터리 | 역할 |
|---|---|
| `doc/` | 원천 데이터 저장소. 가이드북·기출·모의고사 PDF, 공식 해설지(`answer/`), 수험생 풀이 결과 데이터(`solve/`) |
| `direction/` | 기준 문서 `direction.md`. 수험생 정보, 학습 방향, 섹터별 작업 프롬프트. **작업 전에 먼저 읽기** |
| `result/` | doc 기반 분석 보고서, 수험생 수준의 준비·단기 전략 정의서, 작업 기록 `result.md` |

## 작성 원칙

- 저장소가 public이므로 실명 대신 `박C*` / `박J*` (본문에서는 `C* 군` / `J* 군`)으로 씁니다.
- 원본 PDF는 수정하지 않고, 분석과 의견은 `result/`에만 씁니다.
