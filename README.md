

그동안 훈련 진행하면서 과정이 많이 꼬였습니다. </br>
7/6 회의 이후 7/7에 훈련한 코드들이 현재 상황에서 가장 최신 파일들이고 이름 앞에 '0707' 파일들이 해당 파일들입니다. </br>
해당 코드 파일들 참고 바랍니다. 이름 명에서 어떤 파일인지 유추 가능합니다!
</br>
### 폴더 설명
폴더 명이 사용한 모델 이름을 의미합니다.
- meta-llama-instruct : 챗봇에 특화되어 있는 meta-llama-instruct 모델을 파인튜닝한 파일들입니다.
  
- llama-3-open-KO-8B : 가장 최근 발표된 라마 모델을 파인튜닝한 파일들입니다.
- augment : 기존 데이터셋 증강시키는 코드 파일입니다.
- eeve : 야놀자의 eeve 모델을 이용하여 데이터셋 준비와 파인튜닝 진행하는 파일들입니다.

  
### 허깅페이스에 업로드한 파일 요약
- Dataset의 sangthree/0707 : 가장 최근 업로드한 데이터 파일입니다.
- Model의 sangthree/0707 : 가장 최근 업로드한 파인튜닝 완료한 모델입니다. 해당 모델은 Llama3으로 파인튜닝된 모델과 기존 Llama3모델을 merge하여 구성하였습니다.
- Model의 sangthree/0707_gguf : 파인튜닝한 모델을 gguf로 변형한 파일입니다. gguf 파일의 경우, 허깅페이스에는 모델로 업로드해야 하기 때문에 모델로 업로드 하였습니다.
  <최종 서비스에 적용된 데이터셋과 모델>
- Dataset의 sangthree/FinalDatasets : 병원놀이, 요리놀이가 포함된 최종 데이터셋 파일입니다.
- Model의 sangthree/final_eeve : 파인튜닝된 eeve 모델
- Model의 sangthree/final_eeve_guf : gguf 로 변형된 eeve 모델


### 데이터셋 증강과 성능 평가
-https://midnight-menu-31c.notion.site/3027bebfc1464f268e80cf7e41e48150?pvs=4
