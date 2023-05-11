# 가는 말이 고와야 오는 ChatGPT가 곱다.

> 📖 5월 11일(목) 오후 7시에 시작했습니다.

프론트엔드 개발자가 알려주는 프롬프트 잘 쓰고 답변 잘 받는 방법!

모두연의 프론트엔드 개발자 권택수@Tax Kwon님께서 발표하셨습니다.

🤷🏼ChatGPT! 다른 분들이 올린 답변은 구체적인데, 왜 제 질문에만 답변이 단순하죠. 기분탓인가요?

🧑🏼‍🌾아니오. 그건 프롬프트 탓입니다. 답답하셨나요? 저도요. 답변을 잘 받고싶어 세미나에 참석 !

## 프롬프트 엔지니어링이란?

> 프롬프트 엔지니어링이란?

```
Prompt Engineering

Engineering은 공학이라는 뜻
그럼 Prompt는 ? 사용자가 컴퓨터에 내리는 명령

```

💡 프롬프트 엔지니어링을 통하여,

1. 우리가 희망하는 더 좋은 결과물을 만들어냅니다.
2. `거짓말(틀린 대답을 마치 맞는 것처럼 a.k.a Hallucination (할루시네이션))`을 하지 않도록 해야합니다.

## 그래서 프롬프트를 어떻게 해야하는가?

> 프롬프트는 크게 4가지로 구성 되어있다.

- 명령(Instruction) - 수행하려는 특정 작업 또는 지침입니다.
- 컨텍스트(Context) - 더 나은 응답을 하도록 유도할 수 있는 외부 정보 또는 추가 컨텍스트
- 입력 데이터(Input Data) - 응답을 찾고자 하는 입력 또는 질문입니다.
- 출력 지시(Output Indicator) - 응답의 유형 또는 형식입니다.

이 외에도 다양한 프롬프트 명령 형식이 있으며, 이러한 명령 형식을 조합하여 보다 다양하고 정확한 결과물을 생성할 수 있습니다.

**`Generate`** (**`만들어줘`**)

- "Generate 5 I love to" : "I love to dance.", "I love to cook.", "I love to travel." 등 5개의 문장을 생성합니다.

**`Complete`** (**`완성해줘`**)

- "Complete I enjoy listening to" : "I enjoy listening to music.", "I enjoy listening to podcasts.", "I enjoy listening to audiobooks." 등과 같이 텍스트를 자동 완성합니다.

**`Answer`** (**`알려줘`**)

- "Answer What is the capital of Japan?" : "The capital of Japan is Tokyo."와 같은 답변을 생성합니다.

**`Translate`** (**`번역해줘`**)

- "Translate Good morning to Spanish" : "Buenos dias"와 같이 입력한 텍스트를 지정한 언어로 번역합니다.

**`Explain`** (**`설명해줘`**)

- "Explain What is artificial intelligence?" : 입력한 개념을 자세히 설명하는 문장을 생성합니다.

**`Summarize`** (**`요약해줘`**)

- "Summarize the article about climate change" : 입력한 텍스트에 대한 간략한 요약문을 생성합니다.

**`Compare`** (**`비교해줘`**)

- "Compare democracy and dictatorship" : 두 개념에 대한 비교 문장을 생성합니다.

**`Predict`** (**`예측해줘`**)

- "Predict the stock price of Apple for the next month" : 입력한 데이터를 분석하여 예측 결과를 생성합니다.

- 이러한 프롬프트 명령 형식을 사용하여 다양한 결과물을 생성 할 수 있음!

### [프롬프트 지니 : 자동번역기](https://chrome.google.com/webstore/detail/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8-%EC%A7%80%EB%8B%88-chatgpt-%EC%9E%90%EB%8F%99-%EB%B2%88%EC%97%AD%EA%B8%B0/lhkgpdljnlplgbkonflbhifackjhjmdj/related?hl=en-US)

## 그래서 프롬프트로 시작을 하게되면

chatGPT는 대화형 UX 진행이 되며, 이전 대화의 **맥락** 을 이해하고 있다.

그러므로 처음에는 간단한 **프롬프트**로 시작하여 더 나은 결과를 목표로 더 많은 요소와 **컨텍스트**를 계속 추가할 수 있습니다.

이 과정에서 더 원하는 대답이 나오도록 gpt를 나무라지말고 **프롬프트**를 **반복하는 것**이 중요합니다.

즉, 한 방에 큰 프롬프트를 수행하기 보다는 하위 작업이 포함된 **큰 작업**이 있는 경우일수록 더 간단히 하위 작업으로 나누고 더 나은 결과를 얻을 때까지 계속 쌓아가야 한다.

## 마무리

```
💡 단순하게 시작하자 (Start Simple)

🌟 궁극적인 목표를 바로 직설적으로 쓰는게 아닌, 부연설명과 구체적으로 물어보자

🤩 플러그인, 확장프로그램을 적극 활용해라

```

### [OPEN AI state](https://status.openai.com/)

<details><summary> 실제 프롬프트 엔지니어링 관련 논문
</summary>

- https://arxiv.org/abs/2205.11916
- https://velog.io/@nochesita/%EB%85%BC%EB%AC%B8-%EB%A6%AC%EB%B7%B0-Large-Language-Models-are-Zero-Shot-Reasoners#chain-of-thought-prompting
</details>

<br>

## 🙋‍♂️ 실제로 질문 했던 것들

Q. 지금 현재 chatGPT Ver 중 GPT-3.5 / GPT -4 차이점 기타 등

- 자세한건 이 부분에 관련되서는 비밀로 되어있음.
- 다만, 데이터를 더많이 가지고있으며, 뭔가 사용하였을땐 4가 더 이상하다는... 아무래도 많아서?
- 또한, 밤에 쓰거나 그럴경우 패치중이고 아직은 불안정하다.
- 바드 등 기타 open API 로서 나온것들 중 뭐가 좋다! 라는 확실한건 불문..
- **특히, Chain of Thought Prompting (CoT) 기술은 arithmetic reasoning과 symbolic reasoning 양쪽 모두에서 SOTA를 달성한 바 있습니다.**
  - `의존하지 말자` , `성장을하려면 같이 비교를 해보는게 좋다.`

<s>이 강의가 초급수준인줄은 끝나고알았네..</s>
