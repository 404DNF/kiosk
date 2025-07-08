# kiosk
[키오스크 개발] 고령자의 키오스크 환경에서 Neuro-Symbolic AI 기반 다크 패턴 탐지 및 사용자 보조 시스템 제작

# 25 ICROS 학회
SW / HW 재료비 지원을 위한 사이드 프로젝트

조건 : 25 ICROS 학술대회 참가

제출 분야 : HRI(인간∙로봇 상호작용)

<b>주제</b>

고령자 키오스크 환경의 HRI 기반 다크 패턴 대응 시스템 제안: Neuro-Symbolic 실시간 판단 구조

<b>사용성 평가</b>

대상 : 60세 이상의 고령자
- 월계문화복지센터 총 20명 모집 후 진행 완료

<b>사용한 툴</b>

![figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![nodejs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![mongoDB](	https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

<b>Github 폴더 설명</b>
```bash
📁 ABtest/
├── raw/                 # 사용성 평가 전·후 설문 응답, 원본 클릭로그 데이터
├── editdata/            # 시나리오별 전처리된 클릭로그 및 설문 결과
├── analysis.ipynb       # 실험 결과 분석용 Jupyter Notebook
└── clicklogs_*.ipynb    # 시나리오 분리 및 분석 코드

📁 kiosk/
├── client/              # React 기반 키오스크 UI 구현
├── server/              # Node.js 기반 백엔드 (API, MongoDB 연동 등)
└── README.md            # 키오스크 시스템 설명서

📁 kiosk_90/
└── ...                  # 평가 대상 모니터 환경에 맞춰 비율 조정된 키오스크 UI 버전
```

