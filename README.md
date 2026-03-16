# trading-backtest-engine

Lightweight Python backtesting engine for portfolio strategy simulation.

Python으로 구현한 **포트폴리오 전략용 트레이딩 백테스트 엔진**입니다.

이 프로젝트에서는 다양한 포트폴리오 전략을 동일한 환경에서 테스트할 수 있는
경량 백테스트 엔진을 구현했습니다.

백테스트 엔진을 활용하여 다음 전략들을 시뮬레이션할 수 있습니다.

- Buy & Hold
- Annual Rebalancing
- Band Rebalancing

---

# 백테스트 엔진 기능

구현된 백테스트 엔진은 다음 기능을 제공합니다.

- 포트폴리오 가치 시뮬레이션
- 리밸런싱 전략 적용
- 거래비용 반영
- Turnover 계산
- 성과지표 계산
- Drawdown 분석

엔진은 다양한 포트폴리오 전략을 동일한 환경에서 비교·분석할 수 있도록 설계되었습니다.

---

# 구현한 전략

## Buy & Hold

초기 포트폴리오 비중을 설정한 뒤 추가적인 리밸런싱 없이 장기간 보유하는 전략입니다.

---

## Annual Rebalancing

매년 일정 시점에 포트폴리오를 목표 비중으로 다시 조정하는 전략입니다.

---

## Band Rebalancing

자산 비중이 목표 비중에서 일정 범위를 벗어났을 때만 리밸런싱을 수행하는 전략입니다.

예시:

- 5% Band
- 10% Band

---

# 성과 평가 지표

전략 비교를 위해 다음 지표를 사용합니다.

- Cumulative Return
- Annual Return
- Volatility
- Sharpe Ratio
- Max Drawdown
- Turnover
- Transaction Cost

또한 다음과 같은 시각화를 제공합니다.

- Equity Curve
- Drawdown Comparison
- Transaction Cost Comparison

---

# 사용 기술

Python 기반으로 구현되었습니다.

사용 라이브러리

- pandas
- numpy
- matplotlib
- yfinance

자세한 의존성은 `requirements.txt`를 참고하세요.

---

# 실행 방법

1. 저장소 클론

2. 라이브러리 설치

3. Jupyter Notebook 실행

4. `Trading_Backtest_Engine.ipynb` 실행

---

# 향후 확장 가능성

본 백테스트 엔진은 다음과 같은 방향으로 확장할 수 있습니다.

- 머신러닝 기반 트레이딩 전략 적용
- 다양한 자산군 추가
- Walk-forward validation
- 리스크 기반 포트폴리오 전략
- 고급 백테스트 기능 추가

---

# Author

본 프로젝트는 포트폴리오 전략 분석 및 백테스트 엔진 구현을 목적으로 제작되었습니다.
