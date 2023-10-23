# SageMaker Immersion Day
---

## Overview

머신 러닝(ML) 모델은 딥러닝 아키텍처와 GPU의 발전으로 최근 몇 년간 매우 빠르게 진보되었지만, 고도화되지 못한 ML 워크플로로 많은 고객들이 production 적용에 많은 어려움을 겪고 있습니다. 

머신 러닝 알고리즘은 지난 10여년 간 급속도로 발전했으며, 수많은 사전 훈련된(pre-trained) 모델을 그대로 활용하거나 파인 튜닝으로 특정 유즈케이스에 적합한 모델로 개선함으로써 다양한 어플리케이션을 빠르게 개발할 수 있습니다. 특히, MLOps가 비즈니스와 함께 확장됨에 따라 인프라 구축의 중요성이 대두되고 있습니다. 하지만, 온프레미스에서 머신 러닝 모델을 프로덕션에 배포하고 관리하려면 인프라 구축 및 관리에 많은 노력과 비용이 들어가며 머신 러닝, 인프라 관리, 소프트웨어 엔지니어링에 모두 능숙한 실무자가 필요합니다. 

Amazon SageMaker는 대용량 모델 훈련과 모델 서빙에 필요한 인프라 관리에 대한 부담을 덜고 핵심 로직에 집중할 수 있게 도와 주는 AWS의 핵심 머신 러닝 서비스입니다. 컴퓨팅 인프라의 비용을 최적화하고 서비스 인프라를 탄력적으로 확장할 수 있으며, 마이크로서비스 배포에 특화되어 있기에 빠른 실험 및 배포에 적합합니다.

하지만, 기존 온프레미스 환경에서 머신 러닝 모델을 개발하는 데에 익숙한 데이터 과학자와 머신 러닝 엔지니어들은 SageMaker 도입에 어려움을 느끼고 있습니다. 온프레미스에서는 개발 서버에서 ML 코드를 작성하고 동일한 서버에서 모델을 학습/배포했지만, SageMaker는 개발 환경에서 머신 러닝 작업에 필요한 인프라 프로비저닝을 위한 API 코드를 작성하고 실제 학습과 배포는 프로비저닝된 인프라에서 수행하기 때문입니다. 이런 개념에 익숙해지면 러닝 커브가 가파르게 되어 ML 워크플로를 쉽고 빠르게 구축할 수 있지만, 그렇지 못하다면 계속 기본 컨셉에서 방황할 수 있는 거죠.

이에, AWS에서는 ML 워크플로를 쉽고 빠르게 구축하고자 하는 머신 러닝 인력들을 위해 SageMaker 스페셜 웨비나 워크샵을 마련했습니다. 본 워크샵을 통해 End-to-end 머신 러닝 파이프라인을 쉽게 체험할 수 있습니다.

AWS AIML 전문가들이 진행하는 이번 워크샵을 놓치지 마세요!

## SageMaker For Beginners
본 워크샵은 SageMaker에 대한 기초 개념을 이해했다고 가정합니다. 만약 SageMaker를 처음 접해 보신 분들은 아래 링크 자료들을 사전에 학습하고 오시는 것을 권장 드립니다.
- [SageMaker Overview - 50 mins](https://www.youtube.com/watch?v=jF2BN98KBlg)
- [SageMaker Demo - 60 mins](https://www.youtube.com/watch?v=miIVGlq6OUk)
- [Containers for Amazon SageMaker](CONTAINERS_FOR_SM.md)
- [Self Study on SageMaker](https://github.com/gonsoomoon-ml/Self-Study-On-SageMaker)
  
## Hands-on Labs

### [Setup: 워크샵 진행을 위한 필수 가이드](setup) 

### [Lab 1. Training](lab_1_training)

### [Lab 2. Serving](lab_2_serving)

### [Lab 3. ML Pipeline](lab_3_pipeline)
