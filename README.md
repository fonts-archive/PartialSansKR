# 파셜산스

[배포처 바로가기](https://drive.google.com/file/d/1qVVw3rCd9GDAn5lfFIJ2Q07SwCkjEy0a/view?pli=1)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Partial Sans KR`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Partial Sans KR';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/PartialSansKR.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/subsets/PartialSansKR-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/PartialSansKR/subsets/PartialSansKR-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "Partial Sans KR", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
1. 파셜산스와 단조는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공 되며 모든 용도의 상업적 사용이 가능합니다. 
2. 글꼴 자체의 유료 판매는 할 수 없습니다 
3. 부정적 영향을 미칠 수 있거나 반 사회적 제작물에는 사용할 수 없습니다. 
 
해당 서체의 지적재산권은 박준영(@typejjun__)에게 있습니다.
```
