# NEIS Auto Self Check 

현 2020년 9월 기준, NEIS 건강 자가진단을 무증상 시 간편하게 할 수 있는 프로그램입니다. <br>
**(유증상이 있을 경우, 반드시 수동으로 진행해주시기 바랍니다)**


### 구동환경

Chrome이 설치된 모든 Windows, MAC 기기 


### 설치하기

Windows (윈도우) 사용자 - [다운로드 링크](http://bit.ly/vank0n-windows)

Mac (맥) 사용자 - [다운로드 링크](http://bit.ly/vank0n-mac)

#### 설치 후 필수 과정 

[user_data.json](./user_data.json)에 개인정보를 입력하고 저장하세요
```
# user_data.json 
{
    "city": "01",
    "school_level": "4",
    "school_name": "OO고등학교",
    "name": "홍길동",
    "birthdate": "030101",
    "password": "0000"
}

```
| Data | Description 
| ---- | --- | 
| `city` | 시/도 (아래 시/도 코드 참고)  
| `school_level` | 학교급 (유치원: 1, 초등학교: 2, 중학교: 3, 고등학교: 4, 특수학교: 5)
| `school_name` | 학교 이름 (OO고 or OO고등학교) 
| `birthdate` | 사용자 생년월일(`ex.030101` 6자리 숫자) 
| `password` | 사용자 비밀번호 (4자리 숫자) 

| 시/도 코드 | 시/도 명칭
| ---- | --- | 
| 01 | 서울특별시
| 02 | 부산광역시
| 03 | 대구광역시
| 04 | 인천광역시 
| 05 | 광주광역시
| 06 | 대전광역시
| 07 | 울산광역시
| 08 | 세종특별자치시
| 10 | 경기도
| 11 | 강원도
| 12 | 충청북도
| 13 | 충청남도
| 14 | 전라북도
| 15 | 전라남도
| 16 | 경상북도
| 17 | 경상남도
| 18 | 제주특별자치도

## 자가진단 실행하기

1. NEIS 자동 자가진단 응용프로그램 실행 
2. 프로세스가 완료될 때까지 대기 (평균 약 15~25초 정도 소요)

## 개발자

* **Vank0n (SJJeon)**

## 라이센스

이 프로젝트는 MIT 허가서를 사용합니다 - [LICENSE.md](LICENSE.md) 파일에서 자세히 알아보세요.

---
오류제보 및 개선사항 등은 Comment (댓글) 로 남겨주시면 수정해드리겠습니다.<br>이 프로그램을 사용하면서 발생하는 그 어떤 결과에도 책임지지 않습니다.<br>다시 한 번 강조하지만, 코로나19 증상이 있는 경우 **반드시 수동으로 진행해주시기 바랍니다.**
