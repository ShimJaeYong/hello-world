# hello git

## git 명령어 요약

- clone: 원격 저장소 복사
- add: 스테이지 영역에 작업 파일 추가
- commit: 세이브, 스테이지 영역의 파일들을 가지고 커밋(=세이브)을 만들 수 있다.
- push: 원격 저장소에 커밋을 업로드한다.

## 추가사항

## 브랜치 변경하기

- 브랜치: 기존 내용을 유지한 체 새로운 내용을 추가하고 싶을 때 사용한다.
- 체크아웃: 특정 브랜치(혹은 커밋) 으로 돌아가고 싶을 때 사용.
- 소스트리의 체크아웃: 브랜치 이름을 더블 클릭하는 것만으로 체크아웃 가능.


## 병합하기 1

- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로부터 시작된 경우
- 아주 쉽게 병합 가능 = Fast-forward

## 병합하기 2

- 헤드 브랜치에 추가적인 커밋이 생기는 경우
- 진짜 병합이 필요해 진다.
- 충돌이 안 나면 좋은데, 충돌이 나도 겁내지 말자.

## 오늘의 기분

- 내 기분과는 달리 하늘이 푸르르다.
## 충돌 행결하기

- 제일 중요한 점: 겁내지 말아요!

## 커밋 되돌리기

### reset 사용하기

- 장점: 쉬워요.
- 단점1: 커밋이 날아간다.
- 단점2: 강제푸시가 필요하다.

### branch 만들어서 되돌리기

- reset 과는 달리 내용이 사라지지 않는다.
- 장점: 쉽다.
- 단점: 트리가 지저분해진다.

### revert

- 역시 커밋은 없어지지 않는다.
- 장점: 가장 정석적
- 단점: 충돌이 날 수 있다.

## 기타 주의 사항

- 코드를 남기려고 주석을 달지 말자.
- 커밋 메시지를 잘 쓰자.
- 한가지 구현이 완료될 때 마다 커밋을 하자.

## rebase

- merge 처럼 두 브랜치를 합칠 때 사용
- 현재 브랜치가 대상 브랜치 위로 올라간다.
- 위험하니 조심하게 사용.
