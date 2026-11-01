## Multi-Agent System Development with LangGraph

### 프로젝트 소개

LangGraph와 LangChain을 활용하여 여러 AI Agent가 역할을 분담하고 협업하는 주식 분석 시스템을 구현했습니다.

Supervisor Agent가 사용자의 요청을 분석하고, 시장 뉴스, 주가 데이터, 기업 재무정보, 거시경제 지표 등을 담당하는 전문 Agent에게 작업을 분배했습니다. 각 Agent가 수집한 정보를 종합하여 분석 결과를 생성하도록 구현했습니다.

### 기술 스택

- **Language:** Python
- **LLM Framework:** LangChain
- **Agent Workflow:** LangGraph
- **Agent Architecture:** Supervisor Agent
- **Financial Data:** yfinance, Polygon
- **News Data:** Yahoo Finance News
- **API:**: Yahoo Finance Chart API

### 주요 구현 기능

- **Supervisor Agent:** 사용자 요청을 분석하고 적절한 전문 Agent에게 작업 분배
- **Market Research Agent:** Yahoo Finance News 및 Polygon 도구를 활용한 시장 뉴스와 동향 조사
- **Stock Research Agent:** yfinance를 활용한 주가 데이터 수집
- **Company Research Agent:** 기업 재무정보 및 SEC 공시 데이터 수집
- **Economic Research Agent:** S&P 500 및 NASDAQ 지수 데이터 수집을 통해 전체 주식시장 흐름 파악
- **Analyst:** 각 Agent가 수집한 정보를 종합하여 분석 결과 생성
  
