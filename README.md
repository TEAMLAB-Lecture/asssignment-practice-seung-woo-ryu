# Homework - Assignment Practice
 
## 개요

본 과제에서는 처음 숙제 제출하는 방법을 여러분에게 알려드립니다.
## 숙제 다운로드 방법

1. 아래링크를 클릭하여 숙제 github repository를 복사함
   [https://classroom.github.com/a/wp8ruQkX](https://classroom.github.com/a/wp8ruQkX)
2. 아래 코드를 사용하여 숙제 코드 github repository를 자신의 컴퓨터로 클론함
    ```
    git clone <레포지토리 URL>
    ```
    ![](img/code_repository_example.png)
3. 해당 폴더로 이동하여 자신의 코드를 수정함

## 함수 리스트

- addition
```
    # Input:
    #   -a: 실수 값 (Integer or float)
    #   -b: 실수 값 (Integer or float)
    # Output:
    #   -두 값의 합
    # Examples:
    #   >>> addition(3,5)
    #   8
    #   >>> addition(3,2)
    #   
    # '''
```

- minus
```
    # Input:
    #   -a: 실수 값 (Integer or float)
    #   -b: 실수 값 (Integer or float)
    # Output:
    #   -두 값의 차
    # Examples:
    #   >>> minus(3,5)
    #   -2
    #   >>> minus(3,2)
    #   1
    # '''
```

- multiplication
```
    # Input:
    #   -a: 실수 값 (Integer or float)
    #   -b: 실수 값 (Integer or float)
    # Output:
    #   -두 값의 곱
    # Examples:
    #   >>> multiplication(3,5.1)
    #   15.3
    #   >>> multiplication(3,2)
    #   6
    # '''
    # pass
    # ===Modify codes below=============

    result = None

    # ==================================

    return result
```

- division

```
    # Input:
    #   -a: 실수 값 (Integer or float)
    #   -b: 실수 값 (Integer or float)
    # Output:
    #   -a를 b로 나눈 값
    # Examples:
    #   >>> division(5,5)
    #   1
    #   >>> division(4,2)
    #   2
````

## 제출방법
1. 숙제 코드를 수정한 후 commit 수행
   ```
   git add *.py
   git commit -m "Update my code"
   ```
2. 자신의 code repository에 코드를 push함
    ```
    git push origin main
    ```
3. 자신의 코드가 all pass를 받았는지 확인함
    ![](img/submit_example.png)