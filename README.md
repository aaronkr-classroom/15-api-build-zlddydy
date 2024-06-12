[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15254719)

# 15-node-api-build

A보강 Node 실습 - Unit 6 lessons 26, 27, 28, 29

# API 빌드

이번 과제에서는 "API 빌드" 배웁니다.

이 과제는 4 부분으로 나뉩니다.

1. '애플리케이션에 API 추가' (26장)
2. '애플리케이션에서 API 액세스' (27장)
3. 'API 보안' (28장)
4. '캡스톤 6: API 구현' (29장) - 추가한 코드가 없습니다.

---

## 1. 애플리케이션에 API 추가

1. Configure routes and namespaces with a new `routes` folder.<br>
   새로운 `routes` 폴더로 라우트와 네임스페이스를 구성합니다.
2. Create an API endpoint to respond in JSON.<br>
   JSON으로 응답하는 API 엔드포인트를 생성합니다.
3. Use Ajax to make a request from a view, and add a `join` action.<br>
   뷰에서 요청을 보내기 위해 Ajax를 사용하고 `join` 액션을 추가합니다.

---

## 2. 애플리케이션에서 API 액세스

1. Create an API namespace, add `apiRoutes` for handling.<br>
   API 네임스페이스를 생성하고 처리하기 위한 `apiRoutes`를 추가합니다.
2. Create a Bootstrap modal to show asynchronous data.<br>
   비동기 데이터를 보여주기 위해 부트스트랩 모달을 생성합니다.
3. Connect MongoDB data methods with the models, Ajax, and Bootstrap modal.<br>
   MongoDB 데이터 메소드를 모델, Ajax, 부트스트랩 모달과 연결합니다.

---

## 3. API 보안

1. Add security token validation middleware, create a generic public token.<br>
   보안 토큰 검증 미들웨어를 추가하고 일반 공개 토큰을 생성합니다.
2. Create a `pre("save")` hook to generate individual security tokens for each user.<br>
   각 사용자에 대한 개별 보안 토큰을 생성하기 위해 `pre("save")` 훅을 생성합니다.
3. Practice: Implement JWT header authentication.<br>
   연습: JWT 헤더 인증을 구현합니다.

---

## 4. API 구현

추가한 코드가 없습니다.

---

## 과제 파일

These files will need to be updated to complete the assignment. / 이 파일들을 업데이트하여 과제를 완료해야 합니다.

- **15-api-build `(18/18)`** _(6월 24일까지)_
  - [lesson-26](./lesson-26) (Routes + JSON)
    - /routes/\* `(2/2)`
    - /controllers/\* `(2/2)`
    - /views/courses/\_courseModal.ejs + /public/js/modal.js `(2/2)`
    - /app.js `(2/2)`
  - [lesson-27](./lesson-27) (apiRoutes + Bootstrap modal 완성!)
    - /routes/apiRoutes.js `(2/2)`
    - /controllers/coursesController.js `(2/2)`
    - /public/js/joinFunctions.js `(2/2)`
  - [lesson-28](./lesson-28) (API 보안)
    - /models/User.js `(2/2)`
    - /controllers/usersController.js `(2/2)`
  - [lesson-29](./lesson-29) (추가한 코드 없음)
