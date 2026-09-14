# assign01: 소인수 분해

숫자를 입력하면 소인수 분해 결과를 보여주는 아주 기초적인 정적 웹 앱입니다.
함수, 조건문, 반복문을 한 번에 연습할 수 있도록 만들었습니다.

## Project structure

```text
my-app/
├── index.html   # 앱 화면, 스타일, 소인수 분해 함수
└── README.md    # 실행 및 배포 안내
```

## How it works

`factorize(number)` 함수가 가장 작은 수부터 반복하면서 나머지가 0인지 조건문으로
확인합니다. 나누어 떨어지면 해당 수를 소인수 목록에 추가하고, 더 이상 나누어
떨어지지 않으면 다음 수를 확인한 뒤 결과를 화면에 출력합니다.

## Programming concepts

- **함수**: `factorize(number)`로 소인수 분해 과정을 하나의 작업으로 묶었습니다.
- **조건문**: `if`와 `else`로 나누어 떨어지는 경우와 다음 약수를 확인하는 경우를 구분했습니다.
- **반복문**: `while`로 입력한 숫자가 1이 될 때까지 소인수를 차례로 확인했습니다.

## Deploy with Cloudflare Pages

The app needs no framework preset, dependencies, or build command.

배포 주소: https://assign01.pages.dev/

이 프로젝트는 빌드 단계가 없는 정적 사이트입니다. Cloudflare Pages에서
프로젝트 이름을 `assign01`로 만들고, 배포 폴더를 `.`로 지정하면 됩니다.
