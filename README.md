#  환경부 기후 대기 사업 재정 데이터 시각화
## **Collaborator : 장경준, 장동혁**



## ※목차


[Ⅰ.서론](#Ⅰ.서론)

1) 주제 선정배경
    
2) 프로젝트 목적


[Ⅱ.본론](#Ⅱ.본론)

1) 환경부 예산 배정 현황

2) 환경부 부서별, 연도별 투자 비율

3) 신재생에너지 자동차의 증가

4) 에너지 정책 현황

5) 세계 탄소 배출량 현황

6) 국내 탄소 배출량 추이


[Ⅲ.결론](#Ⅲ.결론)



[IV.기타](#IV.기타)

1) 데이터 출처

2) 원본 데이터

3) 전처리 과정



---

# Ⅰ.서론
## 1) 주제 선정 배경
지속적인 온실가스 배출 증가와 환경 파괴에 따른 **지구 온난화**로 세계 곳곳에서 폭염, 폭설, 태풍, 산불 등 이상기후 현상이 나타나고 있다.

#### ◎ 관련기사

1. ["탄소 감축만이 살길"...기후변화 대응에 분주한 세계 각국](https://www.hani.co.kr/arti/society/environment/1007068.html)
2. [지구 온난화'코드 레드'... 유엔 기후변화 보고서 경고](https://www.bbc.com/korean/news-58155013)
3. ["온난화는 인간 때문"... IPCC"2040년까지 지구온도 1.5도 상승"](https://news.kbs.co.kr/news/view.do?ncd=5252484)

유엔 기후변화 보고서에 따르면 지구 온난화는 "통제 불가능"한 상태에 가까워지고 있다. 세계 기후 전문가들은 향후 20년안에 지구의 평균 온도가 19세기 말보다 섭씨 1.5도 상승할 수 있다고 전망했다.

<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/0a6c477e-c02a-480b-9b38-0d7efbf37232/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210909%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210909T082744Z&X-Amz-Expires=86400&X-Amz-Signature=b1525b4ab9a6255724624b7cac863526c6b1d9402d599bf05f33973a84fe2960&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22" width="400" height="400"/>
▲1850년 이후 연간 기온 상승 그래프(출처 : 영국 기상청)

석탄,석유를 원료로 사용하는 화력 발전소를 필두로 화석연료 비중이 높은 제조업 중심의 산업구조를 가진 __우리나라도 최근 30년간 기온이 1.4도 상승__ 하며 온난화를 몸소 체감하고 있다.

이러한 급격한 기후변화에 대응하기 위해 국제사회는 1992년 UN 기후변화 협약을 채택한 것을 시작으로, 1997년 선진국에 탄소 배출량 저감 의무를 부여하는 '교토의정서'를 채택하였고, 2015년에는 선진국과 개도국 등 197개국이 참여하는 '파리기후협약'을 채택하였다.

우리나라 정부는 2016년 11월 파리협정을 비준하였고, 2030년까지 배출 전망치(BAU)대비 37% 감축을 목표로 다양한 정책을 시행하고 있다.

2020년에는 '2050 탄소중립 정책'을 발표하며 배출되는 탄소와 흡수되는 탄소량을 같게 해 순배출이 '0'이 되게 하는 __"탄소 중립 정책"__ 을 추진하고 있다.

특히 환경부는 '탄소중립' 정책의 주요 부처로서 탄소중립 사회로의 공정 전환을 위해 다양한 정책을 시행하고 있다.

## 2) 프로젝트 목적

본 시각화 프로젝트를 통해 국가 재정의 편성과 이에따른 부처별 정책 시행 현황에 대해 알리고자 한다.

특히 기후 변화에 대응하기 위한 환경부의 주요 정책 및 사업들을 기획재정부 공공데이터를 통해 알아보고,
현재 시행되고 있는 정책 효용성에 대해서도 몇가지 지표들을 통해서 검증할 수 있을 것으로 기대된다.
