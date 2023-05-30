# jwp-shopping-order

## 🎯 기능 요구사항

- [ ]  장바구니에 담은 상품을 주문할 수 있다.
    - [ ]  장바구니 중 체크된 항목만 주문한다.
        - [ ]  아무것도 주문하지 않은 경우(체크 0) 예외가 발생한다.
        - [ ]  장바구니에 담기지 않은 상품을 주문할 경우 예외가 발생한다.
    - [ ]  주문 시 장바구니에서 주문한 품목을 삭제한다.
- [ ]  사용자 별로 주문 목록을 확인할 수 있다.
    - [ ]  일정한 개수로 페이징
    - [ ]  시간 역순으로 정렬
- [ ]  특정 주문의 상세 정보를 확인할 수 있다.
- [ ]  포인트 기능을 구현한다.
    - [ ]  총 결제 금액의 10%를 포인트로 적립한다.
    - [ ]  총 결제 금액의 10%까지 포인트로 결제할 수 있다.
        - [ ]  사용자가 가진 포인트를 초과할 경우 예외가 발생한다.
        - [ ]  포인트가 음수로 입력될 경우 예외가 발생한다.

## 🛠 설계

### DB

![image️](https://github.com/woowacourse/happypeople/assets/49433615/f8e0b883-631e-42af-8e36-0bd4645ef95d)

### API

[API 문서️](http://43.200.169.154:8080/docs/docs.html)
