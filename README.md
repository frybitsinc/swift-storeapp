# 쇼핑앱 미션

1. ~~시작하기 - 상품 목록~~
2. 오토레이아웃 AutoLayout 적용
3. Custom Section 헤더 적용
4. 패키지 관리 - CocoaPod
5. Network 프로그래밍
6. 병렬처리
7. 상품 상세화면 전환
8. 연결성 확인 Reachability
9. 마무리하기

# Step1. 시작하기 - 상품 목록
<img src="https://raw.githubusercontent.com/frybitsinc/swift-storeapp/store-step2/img/step1.png" height="400">

- Custom TableView Cell에 상품목록 출력 완료
- Section Header 추가
- json 관련 변수, StoreItem 구조체 같은 모델 데이터 별도로 분리. Array<StoreItem>를 포괄하는 StoreModel 객체생성.
- cell 을 채워넣는 부분. 데이터 타입을 한꺼번에 넘기고 StoreItemCell 내부 configureCellFromArray()에서 처리하도록 수정.
- StoreModel 생성자 추가. StoreItemCell에 configureCell()수정.
