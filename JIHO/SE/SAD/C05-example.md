###### [*CS*](../../README.md) | [*SE*](../README.md) | [*SAD*](README.md) | [*C05*](C05-00.md)

# 연습문제

## 01

### 다음 비디오 대여점의 업무처리를 분석하고 이를 자료흐름도로 작성해 보시오.

1. 비디오 대여점에서는 고객의 전화번호, 성명 등을 기록한 '고객자료'를 작성 및 관리한다.
2. 비디오 대여점에 비치된 비디오는 고유의 코드 외에 비디오 제목, 납품회사명, 제작회사명, 제작년월일, 장르 등을 식별하는 '비디오자료'를 작성 및 관리한다.
3. 고객이 비디오점을 방문하여 원하는 비디오를 찾아 대여를 원하면 고객자료에서 고객정보를 조회한 후 신분이 확인되면 대여 희망 비디오 정보를 입력한 후 대여료를 징수한 후 대여한다. 이때 고객의 '대여정보'에 대여 내역이 기록된다.
4. 고객이 비디오를 반납하면 고객의 '대여정보'에 반납여부를 표시하며, 연체가 되었으면 연체료를 징수한다.
5. 장기 미회수 비디오가 있는지를 검색한 후 고객에게 회수를 요청한다.
6. 새로운 비디오가 출기되면 신규 비디오 정보를 '비디오자료'에 추가한다. 아울러 폐기되는 비디오는 비디오자료에서 삭제한다.
7. 정기적으로 비디오별 대출회수 등을 조회하여 비인기 비디오는 폐기/반품 처리하며 인기 비디오는 추가로 신청해 비치한다.

<p align="center">
    <img src="https://user-images.githubusercontent.com/75299843/110437878-30456b80-80f9-11eb-8ab1-e415bcf5ff1f.jpg">
    <h6 align="center">
        위의 명세를 보고 작성한 자료흐름도
    </h6>
</p>

## 02

### 위의 사례를 작성한 자료흐름도의 물리적 요인들이 존재하는지 검토한 후 이를 제거하여 논리적 모형으로 전환해 보시오.

<p align="center">
    <img src="">
    <h6 align="center">
        1번의 결과를 바탕으로 작성한 논리적 모형
    </h6>
</p>

---

<p align="center">
    <a href="C05-04.md">prev</a>
    &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp;
    연습문제
    &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp;
    <a href="C06-00.md">next</a>
</p>
