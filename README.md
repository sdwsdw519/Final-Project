# Final-Project

I. 콜라츠 추측이란?
   
콜라츠 추측이란 1937년 수학자 로타르 콜라츠가 제시한 추측으로, 아래와 같은 추측이다.

수열을 다음과 같이 귀납적으로 정의하자.
1. 첫째 항은 자연수 N이다.
2. 어떤 항이 짝수 a라면, 그 다음 항은 a를 반으로 나눈 값으로 정의한다.
3. 어떤 항이 홀수 a라면, 그 다음 항은 3a+1로 정의한다.

예를 들면, 첫째 항이 13이라면, 수열은 13, 40, 20, 10, 5, 16, 8, 4, 2, 1, 4, 2, 1, ... 이다.
이 수열을 첫째 항이 13인 콜라츠 수열이라 한다. 첫째 항이 13인 콜라츠 수열은 어느 순간 4, 2, 1이 반복되는 루프에 빠지게 된다.

콜라츠 추측은 아래와 같다.
"모든 자연수 N에 대해, 첫째 항이 N인 콜라츠 수열은 언젠가 4, 2, 1이 반복되는 루프에 빠지게 된다."

..........................

II. 기말 프로젝트 설명

(1) 첫 번째 파이썬 코드는 아래와 같다.

![image](https://github.com/user-attachments/assets/b0307eac-3bad-47a9-a993-d2d29d1c17c7)

이 코드는 첫째 항이 n인 콜라츠 수열을 출력해주는 코드이다.
예를 들어, cfunction(13)을 입력하면 첫째 항이 13인 콜라츠 수열을 반환한다. 아래는 코드를 작동한 결과이다.

![image](https://github.com/user-attachments/assets/045a3862-3f05-49b4-9615-74391d2069d4)

임의의 큰 자연수를 입력해도 코드가 문제없이 작동한다. 이는 직접 계산하는 것보다 훨씬 빠르게 콜라츠 수열을 계산하여 우리가 추측을 확인할 수 있게 해준다.
아래는 cfunction(2025)의 결과이다.

![image](https://github.com/user-attachments/assets/e3333527-2efd-436f-ad2b-e8049013119d)
![image](https://github.com/user-attachments/assets/800b1a4c-c9e7-4f02-8a31-c3fb0e1dd226)
![image](https://github.com/user-attachments/assets/09467336-a450-4bfe-b010-adc45f0fb274)
![image](https://github.com/user-attachments/assets/cf1d5f9d-49de-47b0-81e0-d57576c00a33)
![image](https://github.com/user-attachments/assets/9181c508-2850-4bb5-8cdb-7ea170a166ed)

(2) 두 번째 파이썬 코드는 아래와 같다.

![image](https://github.com/user-attachments/assets/0d21c32b-f396-4ee6-8319-4d8e4cd96c59)

이 코드는 첫재 항이 n인 콜라츠 수열의 그래프를 그리고, 첫 번째로 1이 나오는 항이 몇 번째인지 수열의 길이로 알려준다.
예를 들어, collatz(277)을 입력하면 첫째 항이 277인 콜라츠 수열의 그래프와 수열의 길이를 반환한다. 아래는 코드를 작동한 결과이다.

![image](https://github.com/user-attachments/assets/84fc7886-ad8b-47e7-9403-334200aeb889)

앞에서 확인했던 collatz(2025)도 시각적으로 확인할 수 있다.

![image](https://github.com/user-attachments/assets/56e0c8f2-30ac-4dad-876d-0558a3bc17c4)

(3) 세 번째 파이썬 코드는 아래와 같다.

![image](https://github.com/user-attachments/assets/42155b90-5b88-41fb-9a4d-d31e25b82984)

위의 그래프들에서 알 수 있듯이, 첫째 항이 크다면 이 수열의 처음 몇 항이 크기 때문에 뒤의 항들은 시각적으로 잘 표현되지 않는다.
따라서 이 코드는 로그 스케일의 그래프를 반환하여 시각적으로 더 많은 통찰을 얻을 수 있게 해준다.

아래는 첫째 항이 32440870인 콜라츠 수열의 로그 스케일 그래프를 얻은 모습이다.

![image](https://github.com/user-attachments/assets/262fc3bf-4328-4c1c-82c0-158560a66e65)

..........................

III. 기말 프로젝트 결과

이 프로젝트를 통해 확인해 본 모든 수에서, 그 수가 아무리 크더라도 콜라츠 추측이 참임을 확인할 수 있었다.
또한, 수학에서 프로그래밍이 어떻게 쓰일 수 있는지 알 수 있었다.
