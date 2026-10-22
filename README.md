# Free Korea Transit Tour — Streamlit Dashboard (v3)

실제 설문 원시 데이터(`raw_data_updated.xlsx`, **n=1,088**)를 기반으로 한  
IPA 분석 포함 인터랙티브 대시보드입니다.

---

## 빠른 시작

```bash
# 1. 패키지 설치
pip install -r requirements.txt

# 2. 파일 구조 확인 (동일 폴더에 위치해야 함)
#    app.py
#    raw_data_updated.xlsx
#    requirements.txt

# 3. 앱 실행
streamlit run app.py
```

→ 브라우저가 자동으로 http://localhost:8501 을 엽니다.

---

## 6개 페이지 구성

| 페이지 | 주요 내용 |
|---|---|
| KPI Overview | 종합 만족도 9.29/10, 추천 98.8%, 재방문 의향 등 핵심 KPI |
| Demographics | 성별·연령·국적 Top 10·투어별 참여 현황 (공식 10개 투어) |
| IPA Analysis | 15개 항목 사분면 산점도 + Gap 분석 |
| Airport Competitiveness | 공항 선택 영향 + WTP |
| Business Insights | 소비 분석 + 재방문 의향 |
| Open-Ended Feedback | 키워드 분석 + 응답 샘플 |

---

## 데이터

- **n=1,088** (raw_data_updated.xlsx)
- 기간: ~2026년 9월
- IPA 기준: GRAND_IMP=4.7352, GRAND_SAT=4.7171
