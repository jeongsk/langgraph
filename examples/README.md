# LangGraph examples

This directory should NOT be used for documentation. All new documentation must be added to `docs/docs/` directory.

---

## Map of Content

### Basic Concepts

- [async.ipynb](./async.ipynb) - 비동기 작업을 처리하는 그래프 구성 방법을 다룹니다.
- [branching.ipynb](./branching.ipynb) - 조건부 분기를 사용하여 그래프의 흐름을 제어하는 방법을 보여줍니다.
- [configuration.ipynb](./configuration.ipynb) - 그래프의 다양한 설정 옵션을 구성하는 방법을 설명합니다.
- [input_output_schema.ipynb](./input_output_schema.ipynb) - 입력과 출력 스키마를 정의하여 타입 안전성을 확보하는 방법을 다룹니다.
- [state-model.ipynb](./state-model.ipynb) - 상태 모델을 정의하고 사용하는 방법을 보여줍니다.
- [visualization.ipynb](./visualization.ipynb) - 그래프를 시각화하여 구조를 이해하는 방법을 다룹니다.

### ReAct Agents

- [create-react-agent.ipynb](./create-react-agent.ipynb) - 기본 ReAct 에이전트를 생성하는 방법을 보여줍니다.
- [create-react-agent-hitl.ipynb](./create-react-agent-hitl.ipynb) - Human-in-the-loop 기능을 갖춘 ReAct 에이전트를 구현합니다.
- [create-react-agent-memory.ipynb](./create-react-agent-memory.ipynb) - 대화 기록을 유지하는 메모리 기능이 있는 ReAct 에이전트를 만듭니다.
- [create-react-agent-system-prompt.ipynb](./create-react-agent-system-prompt.ipynb) - 커스텀 시스템 프롬프트를 사용하는 ReAct 에이전트를 구성합니다.
- [react-agent-from-scratch.ipynb](./react-agent-from-scratch.ipynb) - 헬퍼 함수 없이 처음부터 ReAct 에이전트를 직접 구축합니다.
- [react-agent-structured-output.ipynb](./react-agent-structured-output.ipynb) - 구조화된 출력을 반환하는 ReAct 에이전트를 만듭니다.

### Persistence

- [persistence.ipynb](./persistence.ipynb) - 기본 체크포인터를 사용하여 그래프 상태를 저장하고 복원합니다.
- [persistence_mongodb.ipynb](./persistence_mongodb.ipynb) - MongoDB를 백엔드로 사용하는 영속성을 구현합니다.
- [persistence_postgres.ipynb](./persistence_postgres.ipynb) - PostgreSQL을 사용하여 상태를 영구 저장합니다.
- [persistence_redis.ipynb](./persistence_redis.ipynb) - Redis를 활용한 빠른 상태 저장소를 구성합니다.

### Streaming

- [stream-multiple.ipynb](./stream-multiple.ipynb) - 여러 스트림을 동시에 처리하는 방법을 다룹니다.
- [stream-updates.ipynb](./stream-updates.ipynb) - 그래프 실행 중 업데이트를 스트리밍하여 중간 결과를 확인합니다.
- [stream-values.ipynb](./stream-values.ipynb) - 노드에서 생성되는 값들을 스트리밍합니다.
- [streaming-content.ipynb](./streaming-content.ipynb) - LLM이 생성하는 컨텐츠를 실시간으로 스트리밍합니다.
- [streaming-events-from-within-tools.ipynb](./streaming-events-from-within-tools.ipynb) - LangChain 도구 내부에서 이벤트를 스트리밍합니다.
- [streaming-events-from-within-tools-without-langchain.ipynb](./streaming-events-from-within-tools-without-langchain.ipynb) - LangChain 없이 도구에서 이벤트를 스트리밍합니다.
- [streaming-from-final-node.ipynb](./streaming-from-final-node.ipynb) - 그래프의 최종 노드에서만 결과를 스트리밍합니다.
- [streaming-subgraphs.ipynb](./streaming-subgraphs.ipynb) - 서브그래프의 실행 결과를 스트리밍합니다.
- [streaming-tokens.ipynb](./streaming-tokens.ipynb) - LLM 토큰을 실시간으로 스트리밍합니다.
- [streaming-tokens-without-langchain.ipynb](./streaming-tokens-without-langchain.ipynb) - LangChain 없이 토큰을 스트리밍하는 방법을 보여줍니다.

### Subgraphs

- [subgraph.ipynb](./subgraph.ipynb) - 서브그래프를 정의하고 메인 그래프에 통합하는 방법을 다룹니다.
- [subgraph-transform-state.ipynb](./subgraph-transform-state.ipynb) - 서브그래프로 전달할 때 상태를 변환하는 방법을 보여줍니다.
- [subgraphs-manage-state.ipynb](./subgraphs-manage-state.ipynb) - 서브그래프 간 상태를 효과적으로 관리하는 패턴을 설명합니다.

### Tool Usage

- [pass-config-to-tools.ipynb](./pass-config-to-tools.ipynb) - 실행 시 도구에 설정을 전달하는 방법을 다룹니다.
- [pass-run-time-values-to-tools.ipynb](./pass-run-time-values-to-tools.ipynb) - 런타임에 동적으로 값을 도구에 전달합니다.
- [pass_private_state.ipynb](./pass_private_state.ipynb) - 노드 간 비공개 상태를 안전하게 전달하는 방법을 보여줍니다.
- [tool-calling.ipynb](./tool-calling.ipynb) - LLM 도구 호출의 기본 사용법을 설명합니다.
- [tool-calling-errors.ipynb](./tool-calling-errors.ipynb) - 도구 호출 중 발생하는 오류를 처리하는 방법을 다룹니다.

### Advanced Patterns & Use Cases

#### Chatbot Examples
- [agent-simulation-evaluation.ipynb](./chatbot-simulation-evaluation/agent-simulation-evaluation.ipynb) - 에이전트 시뮬레이션을 실행하고 평가하는 방법을 보여줍니다.
- [langsmith-agent-simulation-evaluation.ipynb](./chatbot-simulation-evaluation/langsmith-agent-simulation-evaluation.ipynb) - LangSmith를 활용한 에이전트 시뮬레이션 평가를 다룹니다.
- [information-gather-prompting.ipynb](./chatbots/information-gather-prompting.ipynb) - 정보 수집을 위한 프롬프팅 전략을 구현합니다.

#### Cloud & Infrastructure
- [langgraph_to_langgraph_cloud.ipynb](./cloud_examples/langgraph_to_langgraph_cloud.ipynb) - LangGraph를 클라우드 환경으로 배포하는 방법을 설명합니다.

#### Code Assistant
- [langgraph_code_assistant.ipynb](./code_assistant/langgraph_code_assistant.ipynb) - 코드 작성 및 분석을 돕는 어시스턴트를 구현합니다.
- [langgraph_code_assistant_mistral.ipynb](./code_assistant/langgraph_code_assistant_mistral.ipynb) - Mistral 모델을 사용하는 코드 어시스턴트를 만듭니다.

#### Customer Support & Human-in-the-Loop
- [customer-support.ipynb](./customer-support/customer-support.ipynb) - 고객 지원 시스템을 구축하는 패턴을 보여줍니다.
- [wait-user-input.ipynb](./human_in_the_loop/wait-user-input.ipynb) - 사용자 입력을 대기하는 워크플로우를 구현합니다.

#### Data Extraction
- [retries.ipynb](./extraction/retries.ipynb) - 실패한 추출 작업을 재시도하여 구조화된 정보를 추출합니다.

#### Advanced Search & Planning
- [lats.ipynb](./lats/lats.ipynb) - Language Agent Tree Search 알고리즘을 구현합니다.
- [LLMCompiler.ipynb](./llm-compiler/LLMCompiler.ipynb) - LLM Compiler 패턴을 사용하여 병렬 작업 실행을 최적화합니다.
- [map-reduce.ipynb](./map-reduce.ipynb) - Map-Reduce 패턴을 활용한 병렬 처리를 구현합니다.
- [plan-and-execute.ipynb](./plan-and-execute/plan-and-execute.ipynb) - 계획 수립 후 실행하는 에이전트 패턴을 구현합니다.

#### Memory Management
- [manage-conversation-history.ipynb](./memory/manage-conversation-history.ipynb) - 대화 기록을 효과적으로 관리하는 방법을 다룹니다.
- [add-summary-conversation-history.ipynb](./memory/add-summary-conversation-history.ipynb) - 대화 기록에 요약을 추가하여 컨텍스트를 압축합니다.
- [delete-messages.ipynb](./memory/delete-messages.ipynb) - 메시지를 선택적으로 삭제하여 메모리를 관리합니다.

#### Multi-Agent Systems
- [multi-agent-collaboration.ipynb](./multi_agent/multi-agent-collaboration.ipynb) - 여러 에이전트가 협력하는 시스템을 구축합니다.
- [hierarchical_agent_teams.ipynb](./multi_agent/hierarchical_agent_teams.ipynb) - 계층적 구조의 에이전트 팀을 구성합니다.

#### RAG (Retrieval-Augmented Generation)
- [langgraph_adaptive_rag.ipynb](./rag/langgraph_adaptive_rag.ipynb) - 적응형 RAG 시스템을 구현합니다.
- [langgraph_adaptive_rag_cohere.ipynb](./rag/langgraph_adaptive_rag_cohere.ipynb) - Cohere를 사용한 적응형 RAG를 다룹니다.
- [langgraph_adaptive_rag_local.ipynb](./rag/langgraph_adaptive_rag_local.ipynb) - 로컬 모델을 활용한 적응형 RAG를 구현합니다.
- [langgraph_agentic_rag.ipynb](./rag/langgraph_agentic_rag.ipynb) - 에이전트 기반 RAG 시스템을 만듭니다.
- [langgraph_crag.ipynb](./rag/langgraph_crag.ipynb) - Corrective RAG (CRAG) 패턴을 구현합니다.
- [langgraph_crag_local.ipynb](./rag/langgraph_crag_local.ipynb) - 로컬 모델을 사용하는 CRAG를 다룹니다.
- [langgraph_self_rag.ipynb](./rag/langgraph_self_rag.ipynb) - Self-RAG 알고리즘을 구현합니다.
- [langgraph_self_rag_local.ipynb](./rag/langgraph_self_rag_local.ipynb) - 로컬 환경에서 Self-RAG를 실행합니다.
- [langgraph_self_rag_pinecone_movies.ipynb](./rag/langgraph_self_rag_pinecone_movies.ipynb) - Pinecone과 영화 데이터를 활용한 Self-RAG를 구축합니다.

#### Reflection & Self-Improvement
- [reflection.ipynb](./reflection/reflection.ipynb) - 에이전트가 자신의 출력을 반성하고 개선하는 패턴을 보여줍니다.
- [reflexion.ipynb](./reflexion/reflexion.ipynb) - Reflexion 알고리즘을 구현하여 자기 개선 루프를 만듭니다.

#### Advanced Reasoning Patterns
- [rewoo.ipynb](./rewoo/rewoo.ipynb) - ReWOO (Reasoning WithOut Observation) 패턴을 구현합니다.
- [self-discover.ipynb](./self-discover/self-discover.ipynb) - Self-Discover 프롬프팅 기법을 적용합니다.
- [storm.ipynb](./storm/storm.ipynb) - STORM (Synthesis of Topic Outline through Retrieval and Multi-perspective question asking) 구현을 제공합니다.

#### Tutorials & Specialized Use Cases
- [sql-agent.ipynb](./tutorials/sql-agent.ipynb) - SQL 쿼리를 생성하고 실행하는 에이전트를 만듭니다.
- [tnt-llm.ipynb](./tutorials/tnt-llm/tnt-llm.ipynb) - TNT-LLM (Topology-aware Neural Transformation) 튜토리얼을 제공합니다.
- [usaco.ipynb](./usaco/usaco.ipynb) - USACO 알고리즘 문제를 해결하는 에이전트를 구현합니다.
- [web_voyager.ipynb](./web-navigation/web_voyager.ipynb) - 웹사이트를 탐색하고 상호작용하는 에이전트를 만듭니다.

### Utilities & Configuration

- [node-retries.ipynb](./node-retries.ipynb) - 실패한 노드를 자동으로 재시도하는 방법을 설정합니다.
- [recursion-limit.ipynb](./recursion-limit.ipynb) - 그래프의 최대 재귀 깊이를 제한하여 무한 루프를 방지합니다.
- [run-id-langsmith.ipynb](./run-id-langsmith.ipynb) - LangSmith와 통합하여 실행을 추적하고 디버깅합니다.
