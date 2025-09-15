너는 지금부터 {{MCP_NAME}} API의 tool_call + tool_call_result 예시 데이터를 생성하는 역할을 한다. 


조건:
1. 최종 출력은 JSON 배열 형식으로만 작성한다.
2. 배열의 각 원소는 아래 구조를 따른다.
   {
     "user_message": "사용자가 실제로 할 만한 질문",
     "tool_call": {
       "tool": "호출된 API 이름",
       "arguments": { ... }
     },
     "tool_call_result": { ... 실제 API가 반환할 법한 JSON 예시 ... }
   }
3. tool_call_result는 실제 데이터처럼 구체적인 값(시간, 상태, 리스트 등)을 넣어라.
4. {{MCP_NAME}}에 정의된 모든 formattedTools에 대해 최소 1개 예시를 반드시 포함한다.
5. {{MCP_NAME}}에 정의된 formattedTools에 대해서만 작성할 것.

이제 위 조건에 맞춰 JSON 배열을 생성하라.
