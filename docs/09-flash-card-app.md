---
layout: default
title: 9. Flash card app
nav_order: 10
nav_exclude: false
---

# Flash card app
단어 암기 앱을 만들어봅시다

<div class="code-example" markdown="1">
> # Apple
</div>

## 1. 단계 
- 단어와 뜻을 담은 JSON object를 만듭니다. 
- 단어만 화면에 출력합니다
- 단어를 클릭하면 뜻을 보여주고, 다시 뜻을 클릭하면 단어를 보여줍니다


<details>
<summary>완료 후 다음 기능을 추가하세요</summary>
<div markdown="1">

## 2. 단계
- 단어와 뜻을 JSON 배열로 만듦니다.
- 아래에 버튼을 추가하고 누르면 다음 단어를 보여줍니다
- 단어의 끝까지 진행하면 처음으로 되돌아 갑니다.
</div>
</details>


<details>
<summary>다음 단계</summary>
<div markdown="1">

## 3. 단계
- 단어 JSON object에 count 값을 추가합니다.
- 단어가 화면에 1번 보여지면 count 값을 1 증가 시킵니다.
</div>
</details>

<details>
<summary>다음 단계</summary>
<div markdown="1">

## 4. 단계
- 다음 버튼 대신 O, X 버튼을 추가 합니다
- O를 누르면 해당 단어의 count 값을 1 증가 시키고 다음 단어를 보여줍니다.
- X를 누르면 해당 단어의 count 값을 1 감소 시키고 다음 단어를 보여줍니다.
</div>
</details>

<details>
<summary>다음 단계</summary>
<div markdown="1">

## 5. 단계
- count 값이 3이상인 단어는 버튼을 눌러도 더이상 화면에 나오지 않도록 합니다.
</div>
</details>

