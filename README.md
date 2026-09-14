# assign01: 약수 찾기 연습

숫자를 입력하면 모든 약수를 보여주는 아주 기초적인 정적 웹 앱입니다.
함수, 조건문, 반복문을 한 번에 연습할 수 있도록 만들었습니다.

## Project structure

```text
my-app/
├── index.html   # 앱 화면, 스타일, 약수 찾기 함수
└── README.md    # 실행 및 배포 안내
```

## Run locally

This is a plain static site. Open `index.html` in any modern browser to view it.

For a local server (useful if the project grows later), from the project folder run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## How it works

`findDivisors(number)` 함수가 1부터 입력한 숫자까지 반복하면서 나머지가 0인지
조건문으로 확인합니다. 조건을 만족하는 숫자는 약수 배열에 추가한 뒤 화면에
출력합니다.

## Deploy with Cloudflare Pages

The app needs no framework preset, dependencies, or build command.

배포 주소: https://assign01.pages.dev/

이 프로젝트는 빌드 단계가 없는 정적 사이트입니다. Cloudflare Pages에서
프로젝트 이름을 `assign01`로 만들고, 배포 폴더를 `.`로 지정하면 됩니다.
