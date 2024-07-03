---
layout: post
categories: [Projects]
title: 머신러닝 기반 캠핑장 추천 웹애플리케이션 'CampingNavi'
date: 2024-07-03 15:41:06 +0800
last_modified_at: 2024-07-03 16:34:06 +0800
toc:  true
---
<h1>Project Overview</h1>
<h4>프로젝트 기획의도</h4>
<ul>
  <li><strong>캠핑의 인기 증가</strong>: 최근 몇 년간 자연에서의 휴식과 여가를 즐기려는 사람들이 증가하면서 캠핑의 인기가 높아졌습니다. 다양한 캠핑장 정보와 사용자 리뷰를 제공하여 사용자들이 보다 쉽게 캠핑장을 선택할 수 있도록 돕는 것이 필요합니다.</li><br>
  <table>
    <tr>
      <th colspan="5">코로나19 이후</th>
      <th colspan="5">2022</th>
    </tr>
    <tr>
      <td>전혀 선호하지 않음</td>
      <td>선호하지 않음</td>
      <td>보통</td>
      <td>선호한다</td>
      <td>매우 선호한다</td>
      <td>전혀 선호하지 않음</td>
      <td>선호하지 않음</td>
      <td>보통</td>
      <td>선호한다</td>
      <td>매우 선호한다</td>
    </tr>
    <tr>
      <td>2.8</td>
      <td>15.3</td>
      <td>40.3</td>
      <td><span style="color:red">36.0</span></td>
      <td>5.6</td>
      <td>1.9</td>
      <td>11.4</td>
      <td>30.9</td>
      <td><span style="color:green">46.1</span></td>
      <td>9.8</td>
    </tr>
  </table>
  <em><strong>출처</strong>: 통계청, 농촌진흥청 농촌관광실태조사 / 농촌관광 활용선호도 농촌지역 캠핑(2022) 中 발췌</em>
  <br><br>
  <li><strong>맞춤형 추천의 필요성</strong>: 사용자의 선호도와 경험을 반영한 맞춤형 캠핑장 추천 시스템이 있으면, 사용자들이 더욱 만족스러운 캠핑 경험을 할 수 있을 것입니다. 이를 위해 사용자 리뷰와 선호도를 분석하여 개인화된 추천을 제공하는 시스템이 요구됩니다.</li>
</ul>

<h4>프로젝트 설명</h4>
<ul>
  <li><strong>CampNavi</strong>는 사용자의 리뷰 데이터를 분석하여 맞춤형 캠핑장을 추천해주는 웹 애플리케이션입니다. 사용자들은 웹사이트에서 캠핑장을 추천받고, 상세 정보를 얻고, 자신의 경험을 리뷰로 남겨 여러 사람들과 공유 할 수 있는 정보 웹사이트입니다.</li>
</ul>
<hr>
<h1>Project Duration</h1>
<span><strong>Start date</strong>: 2024.06.03</span><br>
<span><strong>Sprint 1(요구사항 분석 및 설계)</strong>: 2024.06.03 ~ 2024.06.07</span><br>
<span><strong>Sprint 2(FE & BE 구현, 데이터베이스 설계)</strong>: 2024.06.10 ~ 2024.06.21</span><br>
<span><strong>Sprint 3(기능 테스트 및 버그 수정)</strong>: 2024.06.24 ~ 2024.06.28</span><br>
<hr>
<h1>Technology Stack</h1>
<table>
  <tr>
    <th>FE</th>
    <td>HTML, CSS, JavaScript, Thymeleaf, Vue.Js</td>
  </tr>
  <tr>
    <th>BE</th>
    <td>Java(17), Spring Boot(3.2.4), Spring Data JPA, Spinrg Security</td>
  </tr>
  <tr>
    <th>Database</th>
    <td>Oracle(18.0.0), MongoDB</td>
  </tr>
  <tr>
    <th>Recommend System</th>
    <td>Python, scikit-surprise, Selenium, BeautifulSoup</td>
  </tr>
  <tr>
    <th>Build</th>
    <td>gradle</td>
  </tr>
  <tr>
    <th>External API</th>
    <td>Google, Kakao, Naver, Facebook, Daum Post, 공공데이터 포털</td>
  </tr>
  <tr>
    <th>SCM</th>
    <td>Git</td>
  </tr>
</table>
<hr>
<h1>Main function</h1>

![캠핑네비 추천](https://github.com/checkIn97/checkIn97.github.io/assets/158795073/b77801dc-395e-4044-906f-f1f5c3048c37)
<ul>
  <li><strong>Document</strong>: https://docs.google.com/spreadsheets/d/e/2PACX-1vS14NYZ3CrQIOoKTgYCjoqc27NbBMHGUlJuikHTEBgmnbCqZjqdVjDyvPmJPZdkCxIT7cwGqaj3rgM2/pubhtml</li>
  <li><strong>Details</strong>: https://docs.google.com/presentation/d/e/2PACX-1vTjJcBed-5hD0TJaLrer0IDXNX60kuF6C7zNHbSqS7e2W8a8aFJhvRJGLgbVFJVGmTCvIr2eBjL_FK2/pub?start=false&loop=false&delayms=3000</li>
  <li><strong>Github repository</strong>: https://github.com/checkIn97/CampingNavi</li>
</ul>
-----
