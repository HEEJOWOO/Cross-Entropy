# Cross-Entropy


![image](https://user-images.githubusercontent.com/61686244/134468687-720b508b-9daa-42ee-82e6-7acd20d72ae4.png)

  * Classification 문제에 사용되는 Cross Entropy에 대해 정리
    - Multi Class Classification : 여러 이미지에서 C개의 클래스 중 하나의 클래스로 분류하는 문제 ex) 나무만 있는 이미지에서 나무만 Classification
    - Multi label Classification : 여러 이미지에서 각 샘플 마다 있는 클래스 들을 여러 클래스 들로 분류하는 문제 ex ) 나무와 사람이 있는 이미지에서 나무와 사람 각각 Classification
  
  * Sigmoid
    - 합성 곱 신경망 마지막 층에서 출력된 값을 (0,1)사이의 값으로 압축 

![image](https://user-images.githubusercontent.com/61686244/134469078-f49ba6ec-9f57-447a-8601-a9ba681cc67a.png)

![image](https://user-images.githubusercontent.com/61686244/134469102-b295b96d-713b-4e92-bf35-bdfa1bfae06a.png)

  * Softmax
    - 클래스의 점수를 나타내는 벡터 각각의 요소가 (0,1)사이의 값으로 변경되고, 모든 합이 1이 되도록 만듦
    
![image](https://user-images.githubusercontent.com/61686244/134469274-0e4648b3-7b06-4b99-b99f-50122e55e36f.png)

![image](https://user-images.githubusercontent.com/61686244/134469296-109272e2-577b-46df-b63e-83f49020bf1f.png)

  * Cross Entropy Loss

    - 두 확률 분포의 차이를 구하기 위해서 사용, 실제 데이터의 확률 분포와, 학습된 모델이 계산한 확률 분포의 차이 
  
![image](https://user-images.githubusercontent.com/61686244/134469365-719129c8-9f58-44aa-b072-f2caf7329f14.png)

![image](https://user-images.githubusercontent.com/61686244/134469698-60133730-cbf8-48ff-8ad8-8541dd7217d1.png)

