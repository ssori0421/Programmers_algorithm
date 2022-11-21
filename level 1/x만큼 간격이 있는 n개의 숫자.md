# x만큼 간격이 있는 n개의 숫자

## **📝문제 설명**
함수 solution은 정수 x와 자연수 n을 입력 받아, x부터 시작해 x씩 증가하는 숫자를 n개 지니는 리스트를 리턴해야 합니다. 다음 제한 조건을 보고, 조건을 만족하는 함수, solution을 완성해주세요.
### **⚠제한사항**
- x는 -10000000 이상, 10000000 이하인 정수입니다.
- n은 1000 이하인 자연수입니다.
### **입출력 예**
![](https://velog.velcdn.com/images/ssori0421/post/9d3c9ad7-0c3b-49c0-b63c-3193c3af43c1/image.png)

## **🧐CODE REVIEW**
### **🧾나의 풀이**

```js
function solution(x, n) {
    let answer = [];
    for (let i = 1; i <= n; i++) {
        answer. push(x*i);
    }
    return answer;
}

```

#### **📝해설**
push를 사용해 새로 배열을 만들었다.

- **🔗문제 링크**<br/>
https://school.programmers.co.kr/learn/courses/30/lessons/12954

