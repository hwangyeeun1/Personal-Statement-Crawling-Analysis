# 자기소개서 크롤링 및 텍스트 데이터 분석

## :bulb: 배경 및 주제
- 자기소개서 텍스트 데이터 수집 및 분석
- 크롤링을 통해 수집된 데이터셋을 바탕으로 각 직군별 자기소개서의 특징과 키워드를 추출하여 분석을 진행함으로써 취업준비생들이 자기소개서를 작성할 때 참고하도록 하는 것을 목표로 한다.
</br>


## 💁 팀원
- 총 2인 : **황예은, 권민지**
</br>


## 📅 진행 기간 
- 2024.05 ~ 2024.06 (2개월)
</br>


## :thought_balloon: Pipeline
1. 크롤링을 통해 데이터셋 구축
2. 텍스트 데이터 전처리
3. 워드클라우드 & LDA를 활용한 시각화
4. 모델 활용
</br>


## ⚙️ 데이터셋
- Selenium 라이브러리를 이용한 JOB KOREA 사이트 크롤링을 통해 "합격 자기소개서" 텍스트 데이터 수집
- 각 직군 카테고리별 합격 자기소개서, 즉 2개의 컬럼 정보를 수집한다.

</br>

  
## 🔎 전처리 
- Kiwi 모듈을 활용하여 전처리 진행
- 수집한 데이터셋에 적합한 불용어 사전을 직접 구축하여 전처리 진행

</br>

## 💻 주요 분석 방식
- 워드클라우드
- LDA
- TF-IDF
- Bert

</br>
   
## 👏 결론
