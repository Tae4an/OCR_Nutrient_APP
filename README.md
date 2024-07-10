# OCR Nutrient App

이 프로젝트는 OCR(Optical Character Recognition) 기술을 사용하여 영양소 데이터를 추출하고 분석하는 애플리케이션입니다. 

## 목차
1. [프로젝트 개요](#프로젝트-개요)
2. [설치 방법](#설치-방법)
3. [사용법](#사용법)

## 프로젝트 개요
OCR Nutrient App은 이미지를 통해 영양소 정보를 추출하고 이를 바탕으로 사용자가 손쉽게 영양 상태를 관리할 수 있도록 돕는 애플리케이션입니다.

## 설치 방법
### 백엔드 설치
1. 저장소를 클론합니다.
    ```bash
    git clone https://github.com/yourusername/OCR_Nutrient_APP.git
    cd OCR_Nutrient_APP/back
    ```
2. 가상 환경을 생성하고 활성화합니다.
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # 윈도우의 경우 `venv\Scripts\activate`
    ```
3. 필요한 패키지를 설치합니다.
    ```bash
    pip install -r requirements.txt
    ```

### 프론트엔드 설치
1. 프론트엔드 디렉토리로 이동합니다.
    ```bash
    cd ../front
    ```
2. 필요한 패키지를 설치합니다.
    ```bash
    npm install
    ```

## 사용법
### 백엔드 실행
1. 백엔드 디렉토리로 이동하여 서버를 시작합니다.
    ```bash
    cd back
    uvicorn main:app --reload
    ```

### 프론트엔드 실행
1. 프론트엔드 디렉토리로 이동하여 애플리케이션을 시작합니다.
    ```bash
    cd front
    npm start
    ```
