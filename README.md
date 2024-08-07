# 쿠키런

[배포처 바로가기](https://www.cookierunfont.com/#section7)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `CookieRun`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'CookieRun';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'CookieRun';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Bold.ttf') format('truetype');
}
@font-face {
    font-family: 'CookieRun';
    font-weight: 900;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Black.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Black.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Black.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/CookieRun-Black.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/subsets/CookieRun-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/CookieRun/subsets/CookieRun-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "CookieRun", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
'쿠키런 글꼴'의 지식 재산권은 데브시스터즈(주)에 있습니다. 
'쿠키런 글꼴'은 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 자유롭게 사용할 수 있습니다. 
'쿠키런 글꼴'은 온/오프라인, 상품, 광고 등 상업적 목적으로 사용할 수 있습니다. 
단, '쿠키런 글꼴' 자체를 유료로 판매하거나, 어떠한 형태로든 임의 수정 및 개작하여 글꼴을 재배포 하는 것은 금지합니다. 
'쿠키런 글꼴'은 배포되는 형태 그대로 사용해야 합니다. 
쿠키런 IP를 상징하는 쿠키런 딩벳 10자1)의 경우 상업적 목적으로 사용할 수 없으며, 비상업적인 용도에 한해 사용이 가능합니다. 그리고, 어떠한 형태로든 임의 수정 및 개작은 금지합니다. 
'쿠키런 글꼴'은 본 저작권 안내와 라이선스 전문을 포함해서 다른 소프트웨어에 임베딩 및 번들하거나 재배포가 가능합니다. 
라이선스 전문을 포함하기 어려울 경우 ‘쿠키런 글꼴'의 출처 표기를 권장합니다. 
예) 이 페이지에는 데브시스터즈에서 제작한 ‘쿠키런 글꼴’이 적용되어 있습니다. 
단, 2020년 11월 01일 이후로 변경된 정책에 의해 아래의 경우 상업적/비상업적 사용을 모두 금지하고 있습니다. 
[금지하는 상업적/비상업적 사용처] 
: 게임산업군 (PC/모바일) 
* 해당 산업군은 소프트웨어에 임베딩 및 번들하거나 재배포를 금지합니다. 
또한 글꼴을 활용한 2차 창작물 사용을 금지합니다. 
'쿠키런 글꼴'을 사용한 온/오프라인, 상품, 광고 등 모든 종류의 창작물은 쿠키런 및 데브시스터즈 프로모션을 위해 활용될 수 있습니다. 
이를 원치 않는 사용자는 언제든지 당사에 요청하실 수 있습니다. 
Update: 2020.11 
문의: bxdesign@devsisters.com
```
