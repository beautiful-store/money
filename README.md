# Description
<<<<<<< HEAD
금액을 보여줄 때 사용자의 가독성을 높이기 위해 사용하는 React component 입니다. <br/>
세 자릿수마다 콤마(,)를 붙여줍니다.
화폐 단위와 단위의 위치를 지정해서 보여줄 수 있습니다.

## Examples

```jsx
import { Money } from "@beautifulstore/money";
render() {
  return (
    <Money amount={10000000} currency='₩' currencyPosition="left" />
  );
};
```
![img_3.png](img.png)
=======
금액을 보여줄 때 콤마(,)와 단위(원)를 붙여서 보여주는 React 컴포넌트 입니다.


```jsx
import { Money } from "@beautifulstore/money";

render() {
  return (
    <Money amount={1000} />
  );
};

```


화면

>>>>>>> 9954b3e (first commit)

## Installation

```bash
npm install @beautifulstore/money
```

## Props
|Name|Default|Description|
|------|:---:|---|
<<<<<<< HEAD
|amount <a href="#" title="required">*</a>|null|보여주려는 금액|
|currency|'원'|화폐 단위 ( '원' or '₩' ) |
|currencyPosition|'right'|단위 표시 위치 ( 'left' or 'right' )|
=======
|amount|null|금액|
|currency|'원'|화폐 단위 ( '원' or '₩' ) |
|currencyPosition|'right'|단위 표시 위치 ()|

## Examples


>>>>>>> 9954b3e (first commit)
