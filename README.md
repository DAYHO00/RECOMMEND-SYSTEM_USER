# 기초추천시스템 (Introduction to Recommender Systems)

- 본 저장소는 **기초추천시스템(Introduction to Recommender Systems)** 과목에서 수행한 과제를 정리한 저장소입니다.
- 본 과제에서는 추천시스템의 기본 개념을 이해하고, **유사도 기반 추천 알고리즘**을 직접 구현하여 추천 결과의 특성과 성능을 분석하는 것을 목표로 합니다.
- 모든 실습은 **Python** 기반으로 수행되었습니다.

---

## 📌 과제 목록

- [과제 1. 유사도 기반 추천시스템 구현](#-과제-1-유사도-기반-추천시스템-구현)

---

## 🔹 과제 1. 유사도 기반 추천시스템 구현

### 개요
사용자–아이템 평점 데이터를 기반으로, 사용자 간 유사도를 계산하여 추천을 수행하는 **기초적인 추천시스템을 구현**하는 과제입니다.

### 주요 내용
- 추천시스템 기본 구조 이해
- 사용자–아이템 행렬(User–Item Matrix) 구성
- 결측치(missing value) 처리
- 유사도 기반 추천 알고리즘 구현
  - 유클리디안 거리(Euclidean Distance)
  - 코사인 유사도(Cosine Similarity)
- k-최근접 이웃(k-NN) 방식 적용
- 예측 평점 계산

### 분석 및 평가
- 실제 평점과 예측 평점 비교
- 오차 분석
  - 절대 오차
  - 평균 오차
- 파라미터(k, 유사도 척도)에 따른 추천 결과 비교
- 추천 결과에 대한 해석 및 한계점 분석

---

## 🧪 개발 환경

- **Language**: Python
- **Environment**: Jupyter Notebook (.ipynb)
- **Libraries**
  - NumPy
  - Pandas
  - Matplotlib

---
