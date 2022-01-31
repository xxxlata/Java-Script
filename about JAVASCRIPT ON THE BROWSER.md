# Html값을 Js로 
document 는 브라우저의 모든 것을 의미한다.<br>
document.를 이용하여 html의 요소를 선택하여 변경하거나 추가하는 것이 가능하다.
```document.getElementById("title");```
document.getElementById 는 지정된 id 값을 가진 태그를 선택한다.
```document.getElementByClassName("title");```
document.getElementsByClassName 는 지정된 class 값을 가진 태그를 전부 선택한다.<br>
그러나, getElementBy 함수는 array 형식으로 가져오기때문에 까다로운 편이다. 


```document.querySelector``` 과 ```document.querySelectorAll```을 사용하면 css selector로써 css를 사용하는 것처럼 내용을 편리하게 변경하거나 추가할 수 있다. 
queryselector은 해당값의 첫번째 요소를 선택하고 all 을 사용하면 해당값 전부를 가지고 올 수 있다.

```title.innerText= "got u";```
innerText는 js 를 이용해 html태그 내용을 변경하거나 추가할 수 있다.<br>

console에 .style을 출력하면 다양한 스타일 오브젝트를 볼 수 있다. 우리는 그것을 이용하여 js에서 스타일 변경을 할 수 있다.
```
function handleTitleClick(){
    title.style.color = "blue";
}

title.addEventListener("click",handleTitleClick);
```
