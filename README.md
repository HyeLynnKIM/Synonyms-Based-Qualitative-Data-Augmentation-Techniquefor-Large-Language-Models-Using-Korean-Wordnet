# Synonyms-Based-Qualitative-Data-Augmentation-Techniquefor-Large-Language-Models-Using-Korean-Wordnet
✏KIICE 추계 - 한국어 어휘의미망을 활용한 동의어 기반거대 언어 모델을 위한 질적 데이터 증강 기법

## Introduction
최근 거대 언어 모델(Large Language Models, LLMs)에 대한 관심이 뜨거워지면서 이를 활용하는 경우가 증가하고 았다. 자연스럽게 모델이 각 상황에 맞게 학습할 데이터 또한 중요해지는데, 데이터셋의 제작에는 상당한 비용과 노력이 들어가게 된다. 보다 빠르고, 비용이 적게 들지만 동시에 퀄리티는 유지할 수 있는 방법이 필요해지고 있음을 의미한다.
따라서 본 연구에서는 거대 언어 모델을 학습하기 위한 질적 데이터 증강 기법에 대해 제안하고자 한다. 한국어 어휘의미망인 KorLex 1.5를 활용하여 단어의 동의어 및 유의어를 찾아 대체해 언어 모델이 비슷한 표현에도 다양한 어휘를 학습 가능함에 중점을 두었다. 제안 증강 방법을 네 가지 한국어 데이터셋에 적용하여 나타난 성능 차이를 통해 데이터셋의 중요성과 방법의 유의미함을 확인할 수 있었고, 앞으로의 발전 방향성에 대해서도 재고할 수 있었다.

---
## Method
![image](https://github.com/HyeLynnKIM/Synonyms-Based-Qualitative-Data-Augmentation-Techniquefor-Large-Language-Models-Using-Korean-Wordnet/assets/64192139/0be3427b-691f-4aeb-9cdb-55cff43ffd79)
![image](https://github.com/HyeLynnKIM/Synonyms-Based-Qualitative-Data-Augmentation-Techniquefor-Large-Language-Models-Using-Korean-Wordnet/assets/64192139/2d0c197d-2205-4fef-abe8-e53975bb4ab7)

---
## Dataset
- KLUE Benchmark
- 모두의 말뭉치
- 한국어 혐호 표현 데이터 (https://github.com/kocohub/korean-hate-speech)
- 일상대화 챗봇 데이터 (https://github.com/songys/Chatbot_data)
---
## Result
![image](https://github.com/HyeLynnKIM/Synonyms-Based-Qualitative-Data-Augmentation-Techniquefor-Large-Language-Models-Using-Korean-Wordnet/assets/64192139/79c99c6a-fb49-4b4c-8d51-25f26c509508)
