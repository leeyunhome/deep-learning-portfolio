# Deep Learning Portfolio

딥러닝 기초 개념을 하나씩 직접 구현하며 정리하는 개인 학습 포트폴리오입니다.

**GitHub Pages**: https://leeyunhome.github.io/deep-learning-portfolio/

## 학습 출처 및 저작권 안내

이 저장소의 코드는 [HongLab AI](https://www.honglab.ai/) 홍정모 님의
[파트1. 딥러닝 첫걸음](https://www.honglab.ai/courses/aipt1) 강의를 학습하며 이해한 개념을
**강의와 무관한 실제 공개 데이터셋으로 직접 재구성하여 작성**한 것입니다.
강의는 이해를 돕기 위한 임의의 숫자 예제를 쓰지만, 이 저장소는 scikit-learn에 내장된
실제 임상 데이터(당뇨병 환자 442명)를 사용하며, 변수명·코드 구조·추가 실험 모두
스스로 다시 작성했습니다.

강의 콘텐츠 저작권은 HongLab, Inc.에 있습니다.

## 구성

| 번호 | 주제 | 노트북 |
|---|---|---|
| 01 | PyTorch 선형회귀 & Autograd 시각화 (실제 당뇨병 임상 데이터, n=442) | [`notebooks/01_linear_regression_pytorch.ipynb`](notebooks/01_linear_regression_pytorch.ipynb) |

앞으로 강의 진도에 맞춰 순차적으로 항목을 추가할 예정입니다.

## 실행 방법

```bash
pip install torch torchviz matplotlib numpy scikit-learn jupyter
jupyter notebook notebooks/01_linear_regression_pytorch.ipynb
```

`torchviz`로 계산 그래프를 렌더링하려면 [Graphviz](https://graphviz.org/download/)가 시스템에 설치되어 있고 `dot`이 PATH에 등록되어 있어야 합니다.
