---
aliases:
tags:
  - 목지관
---
네, MD 파일(Markdown 형식)은 LLM(대규모 언어 모델)들이 매우 잘 인식하고 처리하는 파일 형식입니다. Markdown의 간결하고 구조화된 특성 덕분에 텍스트 추출, 임베딩, 이해가 용이하며, PDF나 HTML보다 우수한 성능을 보입니다​

## Markdown의 LLM 호환성 장점

Markdown은 순수 텍스트 기반으로 헤더, 목록, 테이블 등을 명확히 표현해 LLM이 구조를 쉽게 파싱합니다. RAG(Retrieval-Augmented Generation) 시스템에서 특히 텍스트 추출과 임베딩 정확도가 높아집니다.
ChatGPT나 Claude 같은 모델들은 Markdown을 프롬프트 입력으로 자연스럽게 인식하며, 출력 형식으로도 자주 사용합니다

옵시디언에서 설정한 YAML frontmatter나 inline properties는 LLM에서 대부분 잘 인식됩니다. LLM들은 Markdown 문서의 YAML 블록(---로 감싸인 메타데이터)을 구조화된 데이터로 파싱하며, 이를 활용해 노트 정리나 태그 생성에 자주 사용합니다.​

## 인식 방식

LLM은 YAML frontmatter를 키-값 쌍으로 자연스럽게 추출합니다. 예를 들어 Claude나 Ollama 같은 모델이 Obsidian 노트를 입력받아 title, tags, category 등을 분석·생성하는 스크립트가 일반적입니다.

