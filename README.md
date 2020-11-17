# Airbnb

4인 팀 프로젝트<br><br>
역할: DB 구축, 데이터 파이프라인 구축, 텍스트 데이터 전처리, 토픽 모델링 및 통계 분석

## Introduction

본 팀 프로젝트에서는 [Airbnb의 공개 데이터 소스](http://insideairbnb.com/get-the-data.html) 내에 있는 reviews, listings 그리고 calendar 데이터를 사용하여 텍스트 분석을 진행했습니다. 우선 총 103개 도시에 대한 700GB 가량의 Airbnb 전체 아카이브 csv.gz 데이터를 크롤링하여 SQLite 데이터 베이스에 옮기는 파이프라인을 구축 하였습니다. 그 후 reviews 텍스트 데이터를 다양한 자연어 전처리기술을 활용하여 전처리하는 과정을 거쳤습니다. 이 과정에서 방대한 데이터 양 떄문에 쿼리 속도가 현저히 떨어지는 문제점을 도시별 인덱싱을 통해 DB 쿼리 속도를 900% 개선했습니다. 또한 Parallel Processing 기법을 적용해 데이터 전처리 속도를 400% 개선했습니다. 또한, Topic Modelling 기법을 적용하여 리뷰 corpus내에 존재하는 토픽들에 대해서 알아보았습니다. Topic Modelling 결과치를 이용하여 특정 토픽들이 숙박시설의 가격과 평점에 대해 예측력을 높일 수 있는지에 대한 Multiple Regression 분석을 시도하였습니다. 전체 분석 과정은 [**여기**](https://sakjung.github.io/airbnb)에서 확인 가능합니다.
이 프로젝트를 통해 처음으로 대용량 데이터를 직접 다뤄보는 경험을 할 수 있었습니다. 그리고 빠르고 효율적인 코드 및 데이터 엔지니어링 프로세스가 많은 양의 데이터를 분석하는 과정에 있어서 얼마나 중요한지 깨달았습니다.

## airbnb.Rmd

전체 분석과정과 코드가 담긴 R Markdown파일 입니다 

--------

Skill Set: Data Crawling/Scraping, Data Engineering, Text Pre-Processing Techniques, Basic Text Analysis, Sentiment Analysis, Topic Modelling

