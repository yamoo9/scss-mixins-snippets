<img src="https://raw.githubusercontent.com/yamoo9/scss-mixins-snippets/master/assets/icon.png" alt="" width="60" />

# @euid/scss-mixins 스니펫(Snippets)

[이듬(E.UID)](https://euid.dev)의 블렌디드 러닝 학습용 [@euid/scss-mixins](https://www.npmjs.com/package/@euid/scss-mixins) 라이브러리 활용을 위한 스니펫.

![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/yamoo9.euid-scss-mixins-snippets?style=flat-square&logo=visual-studio-code&labelColor=007ACC&color=000)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/yamoo9.euid-scss-mixins-snippets?style=flat-square&logo=visual-studio-code&labelColor=007ACC&color=000)
![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/yamoo9.euid-scss-mixins-snippets?style=flat-square&logo=visual-studio-code&labelColor=007ACC&color=000)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/yamoo9.euid-scss-mixins-snippets?style=flat-square&logo=visual-studio-code&labelColor=007ACC&color=000)
![License](https://img.shields.io/github/license/yamoo9/scss-mixins-snippets?style=flat-square&logo=github&labelColor=007ACC&color=000)

<!-- ![Maintenance](https://img.shields.io/maintenance/yes/2021?style=flat-square&logo=github) -->
<!-- [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square&logo=github)](https://github.com/yamoo9/scss-mixins-snippets/issues) -->

<img src="https://raw.githubusercontent.com/yamoo9/scss-mixins-snippets/master/assets/demonstration.gif" width="100%" alt="스니펫 실행 화면" />

<br/>

## 사용법

스니펫 키워드 일부를 입력하고 엔터(Enter|Return) 키를 누르면 등록된 스니펫 코드가 출력됩니다.

### Sass 스니펫

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [import](https://sass-lang.com/documentation/at-rules/import) | 모듈 가져오기
| [include](https://sass-lang.com/documentation/at-rules/import) | 믹스인 불러오기
| [include-media](https://sass-lang.com/documentation/at-rules/import) | 믹스인 불러오기 with `@content`
| [mixin](https://sass-lang.com/documentation/at-rules/import) | 믹스인 만들기
| [use](https://sass-lang.com/documentation/at-rules/use) | 모듈 가져오기 (→ 네임스페이스 생성)
| [use-namespace](https://sass-lang.com/documentation/at-rules/use#choosing-a-namespace) | 모듈 가져오기 (→ 네임스페이스 설정)
| [use-with](https://sass-lang.com/documentation/at-rules/use#configuration) | 모듈 가져오기 (→ 기본 값 재정의)
| [forward](https://sass-lang.com/documentation/at-rules/forward) | 모듈을 엔트리 파일에 전달하기
| [debug](https://sass-lang.com/documentation/at-rules/debug) | 디버깅(debuging) 결과 출력
| [warn](https://sass-lang.com/documentation/at-rules/warn) | 경고(warning) 결과 출력
| [error](https://sass-lang.com/documentation/at-rules/error) | 오류(error) 결과 출력
| [default](https://sass-lang.com/documentation/variables#default-values) | 기본 값 플래그(flag) 출력
| [global](https://sass-lang.com/documentation/variables#shadowing) | 글로벌 값 플래그(flag) 출력
| [important](https://sass-lang.com/documentation/syntax/structure#other-expressions) | CSS 임폴턴트 값 플래그(flag) 출력

<br/>

### 라이브러리 모듈

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [euid](https://www.npmjs.com/package/@euid/scss-mixins) | @euid/scss-mixins 라이브러리 모듈 가져오기

<br/>

### 유틸리티 함수 스니펫

#### 단위

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [rem](https://yamoo9.gitbook.io/scss-mixins/utilities/units/rem) | px 단위를 가진 값을 rem 단위 값으로 계산 변경하는 데 사용
| [em](https://yamoo9.gitbook.io/scss-mixins/utilities/units/em) | px 단위를 가진 값을 em 단위 값으로 계산 변경하는 데 사용
| [remove-unit](https://yamoo9.gitbook.io/scss-mixins/utilities/units/remove-unit) | 숫자 값의 단위를 제거하는 데 사용
| [unitless-px](https://yamoo9.gitbook.io/scss-mixins/utilities/units/unitless-px) | 단위가 없는 숫자 값을 px 단위 값으로 변경 (`0` 제외)
| [get-number-or-string](https://yamoo9.gitbook.io/scss-mixins/utilities/units/get-number-or-string) | 전달 받은 값을 분석한 후, 숫자 또는 문자 값을 반환 받아야 할 경우 사용

#### 컬러

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [get-color](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/get-color) | 컬러 이름을 전달해 매칭되는 컬러 값을 추출
| [get-color-name](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/get-color-name) | 등록된 컬러 이름이 생각나지 않을 경우, 16진수 값을 전달해 컬러 이름 값 추출
| [has-color](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/has-color) | 색 구성표에 등록된 컬러 이름이 포함되어 있는 지 여부를 반환
| [alt-color](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/alt-color) | 색 구성표에 등록된 컬러 이름을 우선 사용하되, 이름이 없을 경우 기본 값을 사용하도록 설정
| [a11y-color](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/a11y-color) | WCAG 2.1 명도 대비 기준 AA(4.5:1), AAA(7:1) 레벨에 맞는 전경색을 자동 제안
| [light-or-dark](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/light-or-dark) | 색의 명도 대비 값을 확인 "밝은 색", "어두운 색"인지 분별하여 값을 반환
| [color-contrast](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/color-contrast) | 전달 받은 전경, 배경색의 명도 대비 차를 확인하여 값을 반환
| [most-legible-color](https://yamoo9.gitbook.io/scss-mixins/utilities/colors/most-legible-color) | 특정 배경 색상 위에 검정 또는 하얀색 텍스트를 사용하고 싶을 경우 확인하여 값을 반환

#### 문자

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [str-replace](https://yamoo9.gitbook.io/scss-mixins/utilities/string/str-replace) | 특정 문자의 내용 중 일부 문자를 검색해 다른 문자로 대체
| [str-split](https://yamoo9.gitbook.io/scss-mixins/utilities/string/str-split) | 문자 안에 포함된 특정 분리 기호(예 콤마(`,`))를 찾아 각 아이템으로 구성된 리스트를 반환
| [str-to-num](https://yamoo9.gitbook.io/scss-mixins/utilities/string/str-to-num) | 문자 값을 숫자 값으로 변경
| [str-repeat](https://yamoo9.gitbook.io/scss-mixins/utilities/string/str-repeat) | 문자를 특정 횟수만큼 반복 출력
| [str-extract-count-keyword](https://yamoo9.gitbook.io/scss-mixins/utilities/string/str-extract-count-keyword) | 키워드와 카운트 횟수를 포함하는 문자를 분석해 카운트, 키워드를 맵으로 반환

#### 리스트

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [first](https://yamoo9.gitbook.io/scss-mixins/utilities/list/first) | 리스트 아이템 중 첫번째 아이템을 추출
| [last](https://yamoo9.gitbook.io/scss-mixins/utilities/list/last) | 리스트 아이템 중 마지막 아이템을 추출
| [copy-list](https://yamoo9.gitbook.io/scss-mixins/utilities/list/copy-list) | 리스트 복제
| [merge-list](https://yamoo9.gitbook.io/scss-mixins/utilities/list/merge-list) | 리스트 병합 (믹스인 패턴)
| [get-value-after-key](https://yamoo9.gitbook.io/scss-mixins/utilities/list/get-value-after-key) | `키1 값1 키2 값2 ...` 형식의 리스트에서 키 뒤에 나오는 값 추출
| [get-match-value-of-keys](https://yamoo9.gitbook.io/scss-mixins/utilities/list/get-match-value-of-keys) | 전달 받은 키:값 리스트에서 키 값을 여러가지 값으로 받아 일치할 경우 최종 계산된 값을 반환

#### 검사

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [is-valid-types](https://yamoo9.gitbook.io/scss-mixins/utilities/validation/is-valid-types) | 커스텀 유틸리티 함수 작성 시, 특정 값의 자료형이 기대되는 자료형과 일치하는 지 확인할 때 사용
| [is-valid-keywords](https://yamoo9.gitbook.io/scss-mixins/utilities/validation/is-valid-keywords) | 커스텀 유틸리티 함수 작성 시, 특정 값이 여러 키워드 중 하나와 일치하는 지 확인해야 할 때 사용
| [is-include-items](https://yamoo9.gitbook.io/scss-mixins/utilities/validation/is-include-items) | 리스트(A)가 포함하는 아이템이 다른 리스트(B)에도 포함되는 지 여부를 판단 할 때 사용

#### 이징

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [ease](https://yamoo9.gitbook.io/scss-mixins/utilities/easing/ease) | 이징 키워드로 등록된 이징 함수 반환
| [ease-add](https://yamoo9.gitbook.io/scss-mixins/utilities/easing/ease-add) | 1개의 커스텀 이징 함수를 추가 등록
| [ease-merge](https://yamoo9.gitbook.io/scss-mixins/utilities/easing/ease-merge) | 1개 이상 다수의 커스텀 이징 함수를 추가 등록

<br/>

### 믹스인 스니펫

#### 폰트

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [font](https://yamoo9.gitbook.io/scss-mixins/mixins/font/font) | 설정 가능한 CSS 폰트(Font) 속성 처리 믹스인
| [font-face](https://yamoo9.gitbook.io/scss-mixins/mixins/font/font-face) | 웹폰트를 직접 정의하는 `@font-face` 속성 처리 믹스인
| [font-size-padding](https://yamoo9.gitbook.io/scss-mixins/mixins/font/font-size-padding) | 글자 크기(`rem` 단위) 기준 패딩(`em` 단위) 설정 믹스인

#### 텍스트

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [text](https://yamoo9.gitbook.io/scss-mixins/mixins/text/text) | 설정 가능한 CSS 텍스트(Text) 속성 처리 믹스인
| [text-ellipsis](https://yamoo9.gitbook.io/scss-mixins/mixins/text/text-ellipsis) | 생략(Ellipsis) 텍스트 설정 믹스인

#### 간격

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [margin(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/margin) | 마진(margin)의 개별 속성 처리 믹스인
| [m(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/margin-m) | margin() 단축 믹스인
| [mx(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/mx) | margin x축(left, right) 값 설정 단축 믹스인
| [my(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/my) | margin y축(top, bottom) 값 설정 단축 믹스인 
| [padding(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/padding) | 패딩(padding)의 개별 속성 처리 믹스인
| [p(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/padding-p) | padding() 단축 믹스인
| [px(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/px) | padding x축(left, right) 값 설정 단축 믹스인
| [py(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/py) | padding y축(top, bottom) 값 설정 단축 믹스인 
| [space(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/space) | 포함하는 자식 요소 간 x축, y축 공간(space) 설정 믹스인
| [s(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/space-s) | space() 단축 믹스인
| [sx(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/sx) | space x축(left, right) 값 설정 단축 믹스인
| [sy(](https://yamoo9.gitbook.io/scss-mixins/mixins/spacing/sy) | space y축(top, bottom) 값 설정 단축 믹스인 

#### 디스플레이

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [hide](https://yamoo9.gitbook.io/scss-mixins/mixins/display/hide) | 감춤(hide) 모드 설정 믹스인
| [show](https://yamoo9.gitbook.io/scss-mixins/mixins/display/show) | 표시(show) 모드 설정 믹스인
| [order](https://yamoo9.gitbook.io/scss-mixins/mixins/display/order) | order 속성 설정 믹스인

#### 포지션

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [position](https://yamoo9.gitbook.io/scss-mixins/mixins/position/position) | 포지션(position) 레이아웃을 위한 개별 속성 설정 믹스인
| [relative](https://yamoo9.gitbook.io/scss-mixins/mixins/position/relative) | 상대 위치(relative position) 레이아웃 믹스인
| [absolute](https://yamoo9.gitbook.io/scss-mixins/mixins/position/absolute) | 절대 위치(absolute position) 레이아웃 믹스인
| [fixed](https://yamoo9.gitbook.io/scss-mixins/mixins/position/fixed) | 고정 위치(fixed position) 레이아웃 믹스인
| [sticky](https://yamoo9.gitbook.io/scss-mixins/mixins/position/sticky) | 스티키 위치(sticky position) 레이아웃 믹스인
| [static](https://yamoo9.gitbook.io/scss-mixins/mixins/position/static) | 포지션 레이아웃 해제 설정 믹스인

#### 플렉스박스

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [flex-container](https://yamoo9.gitbook.io/scss-mixins/mixins/flexbox/flex-container/flex-container) | Flex Container 요소에 설정 가능한 속성 믹스인
| [inline-flex-container](https://yamoo9.gitbook.io/scss-mixins/mixins/flexbox/flex-container/flex-container#usage) | 인라인 Flex Container 요소에 설정 가능한 속성 믹스인
| [flex-container-append](https://yamoo9.gitbook.io/scss-mixins/mixins/flexbox/flex-container/flex-container-append) | `display`를 제외한 Flex Container 요소 설정 속성 믹스인
| [flex-item](https://yamoo9.gitbook.io/scss-mixins/mixins/flexbox/flex-item/flex-item) | Flex Item 요소에 설정 가능한 속성 믹스인
| [flex](https://yamoo9.gitbook.io/scss-mixins/mixins/flexbox/flex-item/flex) | `flex` 속성 설정 믹스인

#### CSS 그리드

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [grid-container](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container) | Grid Container 요소에 설정 가능한 속성 믹스인
| [inline-grid-container](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container#usage) | 인라인 Grid Container 요소에 설정 가능한 속성 믹스인
| [grid-container-append](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append) | `display`를 제외한 Grid Container 요소 설정 속성 믹스인
| [grid-rows](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-rows) | `grid-template-rows` 속성 설정 믹스인
| [grid-cols](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-cols) | `grid-template-columns` 속성 설정 믹스인
| [grid-auto](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-auto) | `grid-auto-*` 속성(행/열/흐름) 설정 믹스인
| [auto-rows](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-auto/auto-rows) | `grid-auto-rows` 속성 설정 믹스인
| [auto-cols](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-auto/auto-cols) | `grid-auto-columns` 속성 설정 믹스인
| [auto-flow](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-auto/auto-flow) | `grid-auto-flow` 속성 설정 믹스인
| [grid-areas](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/grid-container-append/grid-areas) | `grid-template-areas` 속성 설정 믹스인
| [gap](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-container/gap) | `gap` 속성 설정 믹스인
| [grid-item](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-item) | Grid Item 요소에 설정 가능한 속성 믹스인
| [grid-area](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-area) | `grid-area` 속성 설정 믹스인
| [grid-row](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-row) | `grid-row` 속성 설정 믹스인
| [row-start](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-row/row-start) | `grid-row-start` 속성 설정 믹스인
| [row-end](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-row/row-end) | `grid-row-end` 속성 설정 믹스인
| [row-span](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-row/row-span) | `grid-row` 속성 `span` 설정 믹스인
| [grid-col](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item/grid-col) | `grid-column` 속성 설정 믹스인
| [col-start](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item//grid-col/col-start) | `grid-column-start` 속성 설정 믹스인
| [col-end](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item//grid-col/col-end) | `grid-column-end` 속성 설정 믹스인
| [col-span](https://yamoo9.gitbook.io/scss-mixins/mixins/css-grid/grid-item//grid-col/col-span) | `grid-column` 속성 `span` 설정 믹스인

#### 박스 정렬

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [box-alignment](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/box-alignment) | CSS 박스 정렬(Box Alignment) 믹스인
| [place](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/place) | box-alignment() 단축 믹스인
| [content](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/place/content) | place(content) 단축 믹스인
| [items](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/place/items) | place(items) 단축 믹스인
| [self](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/place/self) | place(self) 단축 믹스인
| [justify-content](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/justify-content) | `justify-content` 속성 설정 믹스인
| [align-content](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/align-content) | `align-content` 속성 설정 믹스인
| [justify-items](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/justify-items) | `justify-items` 속성 설정 믹스인
| [align-items](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/align-items) | `align-items` 속성 설정 믹스인
| [justify-self](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/justify-self) | `justify-self` 속성 설정 믹스인
| [align-self](https://yamoo9.gitbook.io/scss-mixins/mixins/box-alignment/align-self) | `align-self` 속성 설정 믹스인

#### 반응형 웹

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [media](https://yamoo9.gitbook.io/scss-mixins/mixins/responsive-web/media) | 미디어쿼리 믹스인
| [rwd-img](https://yamoo9.gitbook.io/scss-mixins/mixins/responsive-web/rwd-img) | 반응형 이미지 믹스인
| [rwd-video](https://yamoo9.gitbook.io/scss-mixins/mixins/responsive-web/rwd-video) | 반응형 비디오 믹스인
| [rwd-iframe-wrapper](https://yamoo9.gitbook.io/scss-mixins/mixins/responsive-web/rwd-iframe-wrapper) | 반응형 아이프레임 래퍼 믹스인

#### 이니셜라이즈

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [initialze](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/initialze) | 커스텀 스타일 초기화 믹스인
| [normalize](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/normalize) | 브라우저 기본 스타일 일반화 믹스인 (normalize.css)
| [reset-box](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-box) | 박스 모델 초기화 믹스인
| [reset-box-sizing](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-box-sizing) | 박스 크기 기준 초기화 믹스인 (자손 포함 상속 됨)
| [reset-img](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-img) | 이미지 요소 초기화
| [reset-link](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-link) | 하이퍼링크(앵커) 요소 초기화
| [reset-list](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-list) | 목록 요소 초기화
| [reset-dl](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-dl) | 설명 목록 요소 초기화
| [reset-abbr](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-abbr) | 축약 요소 초기화
| [reset-button](https://yamoo9.gitbook.io/scss-mixins/mixins/initialize/reset-button) | 버튼 요소 초기화

#### 인터페이스

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [appearance](https://app.gitbook.com/@yamoo9/s/scss-mixins/mixins/interface/appearence) | 요소 외관(appearance) 설정 믹스인
| [selection](https://app.gitbook.com/@yamoo9/s/scss-mixins/mixins/interface/selection) | 선택 영역(`::selection`) 스타일 설정 믹스인
| [scrollbar](https://app.gitbook.com/@yamoo9/s/scss-mixins/mixins/interface/scrollbar) | 스크롤바(scrollbar) 스타일 설정 믹스인

#### 접근성

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [a11y-hidden](https://yamoo9.gitbook.io/scss-mixins/mixins/accessibility/a11y-hidden) | 접근성 감춤 설정 믹스인 (스크린 리더에서 읽기 가능)
| [focus-visible](https://yamoo9.gitbook.io/scss-mixins/mixins/accessibility/focus-visible) | `:focus-visible` 가상 클래스를 사용해 키보드 포커스와 마우스 포커스 상태를 다르게 처리

#### 상속

| 스니펫                         | 용도
| ---------------------------- | ---------------------------------------------------
| [inherit-box-sizing](https://yamoo9.gitbook.io/scss-mixins/mixins/inheritance/inherit-box-sizing) | 요소의 박스 크기 기준을 상속 설정하는 믹스인
| [inherit-pseudo-elements](https://yamoo9.gitbook.io/scss-mixins/mixins/inheritance/inherit-pseudo-elements) | 요소의 가상 요소들에 속성을 상속 설정하는 믹스인

<br/>

## 릴리즈 노트

### 0.1.1 (2021-01-10)

- [추가] Sass 기본 스니펫 (`@use`, `@forward`, `@debug`, `!default` 등)
- [개선] README.md → 각 스니펫 별 문서 링크 설정
### 0.1.0 (2021-01-09)

[@euid/scss-mixins](https://www.npmjs.com/package/@euid/scss-mixins) 라이브러리 스니펫 출시

## 알려진 문제

지금까지 알려진 문제가 없습니다.

## 제작자

[@yamoo9](https://github.com/yamoo9)