# [머신러닝 정리] 서포트 벡터 머신 (Support Vector Machine)

본 포스팅 시리즈는 다양한 머신러닝 테크닉에 대해 수학적 관점과 실용적 관점에서 정리한다.

필자는 수학을 전공했기 때문에 수학적 접근과 용어에 대해 익숙하게 사용한 것이 있지만, 수학을 전공하지 않은 사람들에겐 다소 낯선 접근과 용어가 있을 수 있다.

최대한 그러한 부분을 자세히 설명하려 노력하였지만 필자의 타전공자에 대한 '공감능력부족'으로 효과적으로 전달되지 못한 부분이 있을 것으로 생각된다.

이 글을 읽어주시는 분께 일차적으로 감사드리며, 해당 부분에 대해 질문이나 코멘트를 남겨주시는 분께는 거듭제곱으로 감사드림을 말씀드린다.

## Support Vector Machine

서포트 벡터 머신은 딥러닝이 등장하기 이전에 가장 유명하고 성능 좋은 머신러닝 모델이었다고 한다. 
현재는 다소 실무에서 사용되는 정도가 줄어들었겠지만, 서포트 벡터 머신에 적용되는 다양한 수학적 테크닉들은 인공지능을 이해하고 연구하는 데에 여전히 훌륭한 인사이트를 준다고 생각한다.
특히 서포트 벡터 머신의 아이디어는 유클리드 기하학과 최적화 이론으로 설명이 된다는 점은 수학자들에게 있어서 굉장히 매력적이다.

본 포스팅의 내용은 다음의 자료들을 참고했다.

> 1. Mathematics for Machine Learning (Deisenroth, Marc Peter and Faisal, A. Aldo and Ong, Cheng Soon)
> 2. The Elements for Statistical Learning (Trevor Hastie, Robert Tibshirani, Jerome Friedman)
> 3. 김민준님(이화여자대학교, 수학과 석사)의 SVM Lecture note
> 4. 김원화 교수님(포항공과대학교, 인공지능대학원 교수)의 데이터 마이닝 Lecture note
> 5. Hands-On Machine Learning with Scikit-Learn, Keras, and Tensorflow (Aurelien, Geron)




클릭하면 포스팅된 블로그로 넘어갑니다.

### [01. Introduction](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-Support-Vector-Machine-01.-Introduction)

### [02. Binary Classification](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-Support-Vector-Machine-02.-Binary-Classification)

### [03. Hard Margin SVM (1)](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-Support-Vector-Machine-03.-Hard-Margin-SVM-1)

### [04. Hard Margin SVM (2)](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-Support-Vector-Machine-04.-Hard-Margin-SVM-2)

### [05. Why does SVM maximize margin?](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-Support-Vector-Machine-05.-Why-does-SVM-maximize-margin)

### [06. Soft-margin SVM (1)](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-%EC%84%9C%ED%8F%AC%ED%8A%B8-%EB%B2%A1%ED%84%B0-%EB%A8%B8%EC%8B%A0Support-Vector-Machine-06.-Soft-margin-SVM-1)

### [07. Soft-margin SVM (2)](https://velog.io/@shlee0125/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%A0%95%EB%A6%AC-%EC%84%9C%ED%8F%AC%ED%8A%B8-%EB%B2%A1%ED%84%B0-%EB%A8%B8%EC%8B%A0Support-Vector-Machine-07.-Soft-margin-SVM-2)


