# 📊 StockInsight: Intelligent Stock Analysis Platform

**StockInsight**는 실시간 미국 주식 데이터를 기반으로 고도화된 기술적 분석과 지능형 매수 전략을 제공하는 데이터 인텔리전스 분석 플랫폼입니다. 특히 성장주 투자와 역추세 매매 전략에 최적화되어 있습니다.

## 🚀 핵심 기능

### 1. PAMS 지능형 전략 메커니즘
**PAMS (Probability-Adaptive Multi-step Strategy)** 로직을 통해 단순한 지표 확인을 넘어 실질적인 투자 가이드를 제시합니다.
- **진입 게이팅 (Entry Gating)**: 분석 점수에 따라 1회차 매수 시점을 현재가 또는 지지선으로 자동 조정
- **자금 스케일링 (Weight Scaling)**: 반등 확률에 따라 차수별 매수 비중(마틴게일 등)을 동적 배분
- **변동성 간격 (Dynamic Spacing)**: 하락 에너지의 세기에 따라 추가 매수 간격을 유연하게 조절
- **기술적 앵커링 (Anchoring)**: 볼린저 밴드 하단, MA200, 52주 최저가 등 물리적 지지선을 타겟가로 설정

### 2. 정밀 데이터 분석 시스템
- **성장주 특화 밸류에이션**: PER뿐만 아니라 **PEG(주가이익성장비율)**를 반영한 성장주 맞춤형 스코어링
- **멀티 지표 스코어링**: RSI, 볼린저 밴드, MA200 이격도, MDD를 종합하여 0~100점 사이의 투자 매력도 산출
- **실시간 마켓 데이터**: FMP API를 통한 실시간 가격, 변동률 및 펀더멘털 지표 제공

### 3. 분할 매수 시뮬레이션
- **3~6회 분할 선택**: 사용자 투자 성향에 맞는 단계별 매수 계획 수립
- **예상 평단가 계산**: 모든 차수 매수 완료 시의 최종 평균 단가 및 수량 실시간 시뮬레이션
- **안전 마진 확인**: 현재가 대비 최종 평단의 방어율(%) 제공

### 4. 최적화된 UX/UI
- **모바일 완벽 대응**: 다양한 기기 환경에 최적화된 반응형 레이아웃 적용
- **다크/라이트 밸런스**: 가독성이 뛰어난 전문적인 금융 대시보드 디자인

## 🛠 기술 스택
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Data Source**: Financial Modeling Prep (FMP) API
- **Design Elements**: SVG Icons, Dynamic HSL Color Scoring System

## ⚠️ 면책 조항 (Disclaimer)
본 플랫폼에서 제공하는 모든 데이터 및 분석 결과는 투자 참고용이며, 어떠한 경우에도 수익을 보장하거나 투자를 권유하지 않습니다. 모든 투자 결정의 책임은 본인에게 있으며, 실제 시장 환경과 데이터 간에는 차이가 발생할 수 있습니다.

---
Developed with Intelligent Data Strategy for Smart Investors.
