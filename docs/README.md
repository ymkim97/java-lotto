# 🎰 로또 게임

로또 게임은 1장당 1,000원인 로또를 원하는 금액만큼 구입하여 발행 후 입력한 당첨 번호와 비교하여 당첨 내용과 총 수익률을 출력하는 게임이다.
먼저 로또 구입 금액은 1,000원 단위로 입력 받아야 한다. 당첨 번호 6개는 쉼표(,)로 구분되어 입력받아야 하며 숫자 범위는 1~45이다.
이후 보너스 번호 하나를 입력한다. 입력이 끝나면 당첨 내역과 총 수익률을 출력한다.

**당첨 번호 입력 예시**
```
당첨 번호를 입력해 주세요.
13,1,43,33,27,7
```

**구입 금액 입력 예시**
```
구입금액을 입력해 주세요.
7000
```

***

## ✏️ 기능 목록

* 구입금액을 입력받는다.✔️
    * 1,000원 단위로 나누어지지 않을 경우 예외처리한다.✔️
    * 숫자가 아닌 경우 예외처리한다.✔️
  

* 구입한 수량만큼 발행한 당첨번호 6개씩 오름차순으로 출력한다.✔️


* 당첨번호 6개와 보너스 번호를 입력 받는다.✔️
    * 숫자의 범위가 1~45가 아닐 경우 예외처리한다.✔️
    * 숫자가 아닌 경우 예외처리한다.✔️
    * 중복된 갯수를 입력받는 경우 예외처리한다.✔️
    * 당첨번호 6개 의외의 갯수를 입력받는 경우 예외처리한다.✔️


* 당첨 내역을 출력한다.✔️


* 총 수익률을 출력한다.✔️