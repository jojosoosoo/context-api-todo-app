# 1. State와 Props로 할 일 목록 앱 개발 (JSX 버전)

- 실제로는 이렇게까지 복잡하게 컴포넌트를 구성하지 않음
- Context API 실습을 위해 구조를 이렇게 해 봄

## 1.1 컴포넌트 구조

- App
  - TodoList Data
    - DataView
      - TItle
      - TodoList
        - TodoItem
  - Todo Data
    - Input
      - TodoInput
        - TextInput
        - AddButton
      - InputButton

### 1.1.1 컴포넌트 관심사 분리 기준

- 이 구조는 프로젝트마다 달라질 수 있음

- PageComponent: 데이터의 상태 관리를 할 수 있도록 해 보자
- UiComponent: 화면 또는 페이지를 구성하는 UI 로직을 가지도록 해 보자
- ApiComponent: API로직을 분리해 보자
