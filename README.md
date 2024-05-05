# Dong-Woo Shin's project portfolio
 
#### 데이터분석가를 꿈꾸는 신동우의 프로젝트 포트폴리오입니다.
---

### 01. Personalized food warnning system - image classification model (2022) - 국제 2등 수상
- 2022년도 Intel AI Global Impact Festival 2022 국제 인공지능 대회 프로젝트
- 프로젝트 소개
   - 한국의 다양한 음식 이미지 선정, 음식 이미질를 크롤링해 음식이미지를 바탕으로 해당 음식이 무엇인지 예측하는 모델링
   - 개인이 가지고 있는 질병에 영향을 주는 음식이 무엇인지 알아볼 수 있었으며, 음식 이미지 분류를 정확히 할 수 있었음
- 프로젝트 역할
  - 각 픽셀 값의 범위를 일정하게 맞추어 모델의 학습을 안정화
  - 모델 검증과정에서 cache()와 prefetch() 메서드를 사용하여 데이터를 캐시하고, 학습속도를 향상
  - 데이터 증강 기법을 적용하여 데이터 다양성 향상
  - drop-out 기법을 적용하여 일반화 성능 향상 및 과적합 문제 완화
    - 모델 학습 데이터에 너무 맞추어지는 것 방지, 새로운 데이터에 대한 일반화 능력 향상
    
- [프로젝트GitHub](https://github.com/XHIN98/DL-ML-Project-image-classification-/blob/main/image_classification_project.ipynb) / [발표자료](https://github.com/XHIN98/Portfolio_XHIN98/blob/main/personalized%20food%20warning%20system.pdf)

#   

### 02. 튼튼하니, 튼튼한 이 - image Detection model (2022) - 대상 수상
- 2022년도 부산 디지털 덴티스트리 데이터톤 대회 프로젝트
- 프로젝트 소개
   - 실제 사람의 구강 이미지를 바탕으로 구강구조를 확인하고 치아번호를 식별하는 프로젝트 
   - 의료 이미지 처리의 자동화로 진단 시간 단축 및 진단 정확도를 향상 시킬 수 있었음 
- 프로젝트 역할
  - 객체 감지 모델을 구축하고 치아번호 인식 기능 구현
  - 해당 이미지에 대한 객체 위치 정보를 입력으로 사용하여 모델을 학습
  - YOLOv5 모델을 사용하여 구강 이미지 치아번호 식별
  - detedct.py 스크립트를 실행시켜 이미지 객체 검출 기능 수행
    
- 문제점
  - 데이터 부족 = 정밀도, 재현율, mAP50, mAP50-95 낮았다.
- 인사이트
  - 증상, 질병 이미지로 전문치료를 검색 및 환자에게 가장 적합한 치료법 제시 가능
  - 다양한 이미지 인식 및 영상 인식 등을 이용한 새로운 형대의 서비스 출시 가능
    
- [프로젝트GitHub](https://github.com/XHIN98/toothnumber_project/blob/main/project_code.ipynb) / [발표자료](https://github.com/XHIN98/Portfolio_XHIN98/blob/main/%E1%84%90%E1%85%B3%E1%86%AB%E1%84%90%E1%85%B3%E1%86%AB%E1%84%92%E1%85%A1%E1%84%82%E1%85%B5%2C%20%E1%84%90%E1%85%B3%E1%86%AB%E1%84%90%E1%85%B3%E1%86%AB%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5.pdf)

#   

### 03. MQL 고객정보를 활용한 고객지수 산출 및 고객영업 전환 예측(2024)
- 2022년도 Intel AI Global Impact Festival 2022 국제 인공지능 대회 프로젝트
- 프로젝트 소개
   - 고객이 행동 및 특성을 정량적으로 측정하고 분석하여 고객 지수를 만들 수 있도록 데이터 전처리
   - 지수를 통해 많은 고객 중 영업 성공 가능성이 높은 고객을 선별하고, 영업 기회 전환율을 높여 B2B 매출 상승에 기여
- 프로젝트 역할
  - MQL 고객정보 데이터 전처리
    - response_region 컬럼 데이터 전처리
    - 각 지역별 전환율(target)을 계산하고 카이제곱 검정을 통해 지역과 전환율 간의 관계를 확인
    - 각 지역에서 고객 영업 전환 성공 여부의 평균을 계산하여 각 지역별 전환율을 제공
    - 각 지역에서 영업 성공한 비율을 확인
    - 결과: 고객 전환 성공 여부(Yes) 200 → 1000개 달성
 - 인사이트
    - 선제적인 고객 이슈 대응
    - 고객 맞춤형 서비스 제공
      
- [발표자료](https://github.com/XHIN98/Portfolio_XHIN98/blob/main/MQL%20%E1%84%80%E1%85%A9%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%87%E1%85%A9%E1%84%85%E1%85%B3%E1%86%AF%20%E1%84%92%E1%85%AA%E1%86%AF%E1%84%8B%E1%85%AD%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%80%E1%85%A9%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8C%E1%85%B5%E1%84%89%E1%85%AE%20%E1%84%89%E1%85%A1%E1%86%AB%E1%84%8E%E1%85%AE%E1%86%AF%20%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%80%E1%85%A9%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8B%E1%85%A7%E1%86%BC%E1%84%8B%E1%85%A5%E1%86%B8%20%E1%84%8C%E1%85%A5%E1%86%AB%E1%84%92%E1%85%AA%E1%86%AB%20%E1%84%8B%E1%85%A8%E1%84%8E%E1%85%B3%E1%86%A8.pdf)

#   

 
### 04. E-commerce 데이터 분석을 통한 KPI 도출 및 비즈니스 전략 제시(2024)
- 2022년도 Intel AI Global Impact Festival 2022 국제 인공지능 대회 프로젝트
- 프로젝트 소개
   - 실제 비즈니스 환경에서 발생하는 복잡한 데이터를 분석하여 비즈니스의 문제점과 해결점 찾기
   - 기업의 성장과 고객 만족을 도모할 수 있는 kpi 및 인사이트 도출 
- 프로젝트 역할
  - 누적 판매금액 및 누적 판매량을 구하여 인기상품 식별
  - 날짜별 고객 만족도 수집 및 분석
  - 시계열 예측 모델(Arima)을 사용하여 향후 일정 기간 동안의 고객 만족도를 예측
  - KPI 도출 및 비즈니스 전략 분석

- 인사이트
  - 서비스 개선 및 조정
    - 고객 만족도가 낮은 경우, 서비스나 제품의 품질을 개선하고 문제를 해결
  - 고객 관계 관리
    - 고객 만족도를 기반으로 관계를 더욱 세밀하게 관리하고 개별 고객에게 맞춤형 서비스를 제공
