# kor-eng-translator

![image](https://user-images.githubusercontent.com/121621858/214286959-ab6b4b2b-a9d7-4db4-b831-d050b9086465.png)


Tensorflow tutorial을 참고하여 만든 일상생활 및 구어체 번역기 미니 프로젝트입니다. <br>
Bidirectional GRU layer으로 process한 임베딩한 sequence들을 참고해 다음에 나올 output을 예측하는 Attention model을 저장해 <br>
Streamlit application에 내장함수로 입력해 한국어 문장을 입력하면 번역한 영어 문장을 출력하는 시스템을 만들었습니다. <br>
데이터셋으로는 Ai-Hub 일상생활 및 구어체 한-영 번역 병렬 말뭉치 데이터의 Training 원천데이터 TS1 1,200,307개를 사용했습니다.<br><br>
출처는 다음과 같습니다: <br>
1. https://www.tensorflow.org/text/tutorials/nmt_with_attention <br>
2. https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=71265
