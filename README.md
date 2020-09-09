# Airbnb

## Introduction

본 프로젝트에서는 [Airbnb의 오픈 데이터 소스](http://insideairbnb.com/get-the-data.html) 내에 있는 reviews, listings 그리고 calendar 데이터를 사용하여 텍스트 분석을 진행했습니다. 우선 모든 국가에 대한 대용량의 데이터들을 전부 다운로드하여 데이터 베이스에 옮기는 파이프라인을 구축 하였습니다. 그 후 reviews 텍스트 데이터에 대해서 탐색 해보고 전처리하는 과정을 거쳤습니다. 텍스트 데이터내에 존재하는 특성을 추출하고 이를 숙박시설의 특성들에 대한 데이터들을 조합하여 인사이트를 얻기 위한 분석을 시도했습니다. 그후 Sentiment Analysis 기법을 적용하여 Sentiment Score들을 추출하고 이를 이용하여 숙박시설 가격과 평점 예측 분석을 시도하였습니다. 또한 Topic Modelling 기법을 적용하여 리뷰 corpus내에 존재하는 토픽들에 대해서 알아보았습니다. 또한 Topic Modelling 결과를 이용하여 특정 토픽들이 숙박시설의 가격과 평점에 대해 예측력을 가질 수 있는지에 대한 분석을 시도하였습니다. 전체 분석 과정은 [**여기**](https://sakjung.github.io/airbnb)에서 확인 가능합니다.

## airbnb.Rmd

전체 분석과정과 코드가 담긴 R Markdown파일 입니다 

--------

Skill Set: Data Crawling/Scraping, Data Engineering, Text Pre-Processing Techniques, Basic Text Analysis, Sentiment Analysis, Topic Modelling
