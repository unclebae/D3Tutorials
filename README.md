# D3 (Data Driven Document)

D3는 Data Driven Document의 의미로 D가 3개 들어있다고 하여 D3라고 합니다.

## D3 특징

D3는 다음과 같은 특징이 있습니다.

-   Custom Interactive data visualization 가능
-   SVG 이용 (Scalable Vector Graphics) 으로 벡터그래픽을 지원합니다. (즉, 확대/축소에 화면이 깨지지 않습니다.)
-   HTML 과 CSS 를 지원하여 디자인 할 수 있습니다.

## D3 Install

D3를 이용하기 위해서는 다음 몇가지 요소가 필요합니다.

### D3 library

D3룰 이용하기 위해서 다음 링크를 header 에 추가해 줍니다.

```
<script src="https://d3js.org/d3.v5.min.js"></script>
```

혹은 실제 소스 코드를 로컬에 설치하고자 한다면 다음 zip 파일을 다운받아 압축을 풀어주세요.

[d3.zip](https://github.com/d3/d3/releases/download/v5.9.7/d3.zip) 에서 다운로드.

우리는 D3 version 5를 이용하여 튜토리얼을 진행할 계획입니다.
v5는 기존 버젼과 호환되지 않습니다.

### Web Server

Web Server 는 개발할때 d3가 지원하는 데이터 로더를 원활하게 사용하기 위해서 필요합니다.

일반적으로 chrome 브라우저에서는 file:// 의 형식으로 html 을 열게되면, d3.csv, d3.tsv 등과 같은 기능이 동작하지 않습니다.

그러므로 로컬 웹 서버를 이용하면 편리합니다.

### Editor

에디터는 개발자의 취향에 따라 선택하면 됩니다.

-   visual studio code
-   WebStorm (유료)
-   Eclipse
-   SublimeText

등이 있습니다. 저는 여기서 Visual Studio Code 를 이용할 예정입니다.
최근 VSCode 는 편리한 Extension 들이 쉽게 설치할 수 있고, 사용성도 매우 편리하여 인기가 있는 개발 툴입니다.
