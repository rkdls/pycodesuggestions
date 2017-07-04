파이썬 코드 suggestion구현

논문링크 : [https://arxiv.org/abs/1611.08307](https://arxiv.org/abs/1611.08307)

이 모델은 현재 컨텍스트에 기반하여서

pointer네트워크를 이용해 long-range-dependencies를 선택할지, local phenomena를 다루기위해

자유로운 형식을 만들지를 선택하기 위한 learning을 한다.

여기선 attention mechanism과 sparse pointer network를 활용하고, controller(lambda)란 개념을

도입해서 무엇을 선택해야할지 정한다.

어텐션 메카니즘은 일반적인 방식과 같이 구하는데,

메모리에 저장되는 context가 history에 저장되었던 identifiers만 포함되어서, 해당하는 메모리에서만

attention이 수행되어진다.

