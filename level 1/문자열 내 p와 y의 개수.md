# 문자열 내 p와 y의 개수

## **📝문제 설명**
대문자와 소문자가 섞여있는 문자열 s가 주어집니다. s에 'p'의 개수와 'y'의 개수를 비교해 같으면 True, 다르면 False를 return 하는 solution를 완성하세요. 'p', 'y' 모두 하나도 없는 경우는 항상 True를 리턴합니다. 단, 개수를 비교할 때 대문자와 소문자는 구별하지 않습니다.

예를 들어 s가 "pPoooyY"면 true를 return하고 "Pyy"라면 false를 return합니다.


### **⚠제한사항**
- 문자열 s의 길이 : 50 이하의 자연수
- 문자열 s는 알파벳으로만 이루어져 있습니다.
### **입출력 예**
![](https://velog.velcdn.com/images/ssori0421/post/d165d1d7-5729-49ff-9d63-06e4b1ac5b22/image.png)

## **🧐CODE REVIEW**
### **🧾나의 풀이**

```js
function solution(s){
    let str = s.toLowerCase();
    let count = 0;
    for (let i = 0; i < s.length; i++) {
        if (str[i] === "p") count++;
        else if (str[i] === "y") count--;
    }
    return count === 0 ? true : false;
}
```

#### **📝해설**

```js
```

#### **😅개선점**

1. `for i in range():` 

### **다른 풀이**

```js
```

#### **📝해설**

```js
```

### **🔖정리**

1. 배운점

## 📚참고 사이트

- **🔗문제 링크**<br/>
https://school.programmers.co.kr/learn/courses/30/lessons/12916
- **[제목]**<br/>
사이트 주소
