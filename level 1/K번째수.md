# 서울에서 김서방 찾기

## **📝문제 설명**
예를 들어 array가 [1, 5, 2, 6, 3, 7, 4], i = 2, j = 5, k = 3이라면

array의 2번째부터 5번째까지 자르면 [5, 2, 6, 3]입니다.
1에서 나온 배열을 정렬하면 [2, 3, 5, 6]입니다.
2에서 나온 배열의 3번째 숫자는 5입니다.
배열 array, [i, j, k]를 원소로 가진 2차원 배열 commands가 매개변수로 주어질 때, commands의 모든 원소에 대해 앞서 설명한 연산을 적용했을 때 나온 결과를 배열에 담아 return 하도록 solution 함수를 작성해주세요.
### **⚠제한사항**
- array의 길이는 1 이상 100 이하입니다.
- array의 각 원소는 1 이상 100 이하입니다.
- commands의 길이는 1 이상 50 이하입니다.
- commands의 각 원소는 길이가 3입니다.
### **입출력 예**
![](https://velog.velcdn.com/images/ssori0421/post/c61fc846-e692-4571-b654-e6e508c558d3/image.png)
## **🧐CODE REVIEW**
### **🧾나의 풀이**

```js
function solution(array, commands) {
  const answer = [];

  for (let i = 0; i < commands.length; i++) {
    const [start, end, k] = commands[i];
    const arr = array.slice(start - 1, end).sort((a, b) => a - b);
    answer.push(arr[k - 1]);
  }

  return answer;
}
```

#### **📝해설**
1) commands 배열을 순회하면서, 각 요소에서 start, end, k 값을 추출함. 
2) 이후, slice() 메소드를 사용하여 배열의 start-1부터 end까지의 부분 배열을 추출하고, sort() 메소드를 사용하여 오름차순으로 정렬함. 
3) 마지막으로, k번째 원소를 구하여 answer 배열에 push함.


## 📚참고 사이트

- **🔗문제 링크**<br/>
https://school.programmers.co.kr/learn/courses/30/lessons/12919

