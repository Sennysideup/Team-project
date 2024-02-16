### SQL Analysis Project
- MODE의 kag_conversion_data를 활용한 데이터 분석 프로젝트 <br>
- 개인 프로젝트 <br>
> kag_conversion_data : 페이스북 광고 전환 관련 데이터 <br>
> https://mode.com/

### Process
#### EDA
1. 캠페인 아이디 간 관계 파악하기 : 캠페인 아이디별 주요 범주형 변수 분포 확인 <br>
  > 성별, 연령대, 성별X연령대, 관심사, 성별X연령대X관심사 <br>
2. 광고별 주요 변수 기술통계량 계산 <br>
  > 주요 변수 : 노출수, 클릭수, 광고료, 문의수, 구매자수, CTR, CVR, CPC, CPM <br>
  > 기술통계량 : min, Q1, Q2, 평균, Q3, max

#### 타겟팅 옵션별 분석
1. 타겟팅 옵션이 잘못 설정된 경우 <br>
  > 광고별 CTR이 타겟팅 옵션의 전체 평균 CTR보다 높고, 광고별 CVR이 타겟팅 옵션의 전체 평균 CVR보다 낮음 <br>
2. 광고의 매력도가 떨어지는 경우 <br>
  > 광고별 CTR이 타겟팅 옵션의 전체 평균 CTR보다 낮고, 광고별 CVR이 타겟팅 옵션의 전체 평균 CVR보다 높음 <br>
3. 타겟팅 옵션별 광고 비용 비교 <br>
  > 광고별 CPM이 타겟팅 옵션의 전체 평균 CPM보다 높은 경우 <br>
  > 광고별 CPC가 타겟팅 옵션의 전체 평균 CPC보다 높은 경우
