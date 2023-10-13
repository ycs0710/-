# 학생 성적 시각화 프로젝트

## 프로젝트 설명

이 프로젝트는 학생들의 중간고사와 기말고사 성적을 시각화하여 한 눈에 성적 분포와 경향을 파악할 수 있게 합니다. 두 개의 CSV 파일(`class_score_kr.csv`와 `class_score_en.csv`)을 사용하여 각각 한국어반과 영어반 학생들의 성적 데이터를 분석하고 시각화합니다.

## 기능

1. **데이터 읽기**: CSV 파일에서 성적 데이터를 읽어옵니다.
2. **점수 계산**: 읽어온 성적으로부터 학생들의 총점을 계산합니다.
3. **데이터 시각화**: 학생들의 중간고사, 기말고사, 총점을 다양한 형태의 그래프로 시각화합니다.

### 사용된 기술 스택

- **Python**: 데이터 처리와 시각화를 위한 프로그래밍 언어
- **Matplotlib**: 그래프를 그리기 위한 파이썬 라이브러리

## 설치 및 사용 방법

이 프로젝트를 사용하기 위해서는 Matplotlib 라이브러리의 설치가 필요합니다. 아래의 절차대로 진행해주세요.

### 2. Matplotlib 설치

터미널 또는 커맨드 프롬프트에서 아래의 명령어로 Matplotlib를 설치합니다.

```bash
pip install matplotlib
