# langgraph-rag-agent-note
RAG system implemented with AI agent (w. LangGraph)

## Poetry 실행
```bash
poetry new langgraph_agent       # 프로젝트 뼈대 생성
cd langgraph_agent
poetry env use python3.11        # 이 프로젝트의 venv는 python3.11로 만들어라
code .                           # VS Code 열기
poetry install       
```
**👉 의미** (출처: ChatGPT)
- .venv/ 또는 Poetry 캐시 경로에 프로젝트 전용 가상환경을 자동 생성
- pyproject.toml에 기록된 의존성 관리
- 이후 `poetry env activate` 로 해당 환경에 접근

### 기초 Poetry 명령어
- 현재 프로젝트와 연관된 모든 가상 환경 나열
    ```bash
    poetry env list
    ```
- 현재 활성화된 가상 환경에 대한 기본 정보 획득
    ```
    poetry env info
    ```
