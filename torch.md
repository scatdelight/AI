## Pytorch 사용법

import torch

- tensor : 
- torch.float() : float형으로 casting
- torch.unsqueeze(1), torch.squeeze(1) : tensor의 첫번째 차원을 없애고 추가하는데 사용, squeeze()에서 숫자를 입력하지 않을 시, 1인 차원을 모두 제거
- torch.from_numpy(input) : input data를 tesor로 변환시켜줌
- torch.stack([a, b], dim = 1) : tensor를 지정하는 차원으로 확장시켜 합치는 함수, 합치는 tensor의 차원이 일치해야함
- torch.optim.Adam(net.parameters(), lr=0.00005) : optimizer의 한 종류로 gradient를 구해서 weight를 조절 # Reference : [Optimizer의 종류와 간단한 정리](https://velog.io/@reversesky/Optimizer%EC%9D%98-%EC%A2%85%EB%A5%98%EC%99%80-%EA%B0%84%EB%8B%A8%ED%95%9C-%EC%A0%95%EB%A6%AC)
-
