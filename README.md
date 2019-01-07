<h1 align="center"> 청와대 국민청원 및 제안 목록으로부터 국민의 생각 알아보기 </h1>

![COM LAB LOGO](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546608400699_13.png)

# 개요

 문재인 정부에서는 국민과의 소통을 통하여 국정에 반영하고자 청와대 홈페이지에 국민소통광장을 마련하였습니다. 국민소통광장의 ‘국민청원 및 제안’에서는 국민 누구나 청원을 올릴 수 있으며, 청와대로부터 답변을 받을 수 있습니다. 2019년 1월 1일 현재, 371,229개의 청원이 있으며, 본 연구에서는 웹 크롤링(web crawling)을 통해 국민이 올린 모든 글을 모두 데이터화하여 분석하여, 국민의 청원을 과학적으로 분석합니다. 특히, 국민 청원 글을 단어 단위로 분석하여, 국민의 관심이 집중되는 키워드와 키워드 간의 관계 네트워크,  더 나아가 분류된 분야별 단위의 키워드를 분석하여, 국민 청원의 단순한 통계가 아닌, 국민의 글 전체를 포괄하는 단어 수준의 분석을 수행합니다. 
 
 인공지능 자연어처리를 통하여 글의 내용을 파악하는 연구는 다양한 분야에서 수행되어 왔으며, 기계학습 및 인공지능의 발전과 함께 많은 응용분야에 적용되고 있습니다. 그러나 아직까지 자연어처리를 통한 연구는 데이터의 수집이 용이한 특정분야에 한정 돼있으며, 특히 정치분야에는 아직 활발히 진행되지 못하고 있다. 그러나, 이번 국민소통광장을 통하여 본 연구소는 양질의 데이터를 확보하여, 정치분야의 연구를 통해 국민의 소리에 더 기울일 수 있는 기회를 제공하는 것이 이번 연구의 목적 중 하나라고 할 수 있습니다다. 국민 청원 데이터는 첫째 청와대의 관리를 받고 있기에(데이터 전처리) 양질의 데이터 확보의 커다란 장점을 갖고 있습니다. 또한 국민의 추천수를 통해 글의 파급력이나 국민의 의견(동의)을 과학적으로 분석할 수 있는 기회를 제공합니다. 마지막으로 주제별/ 분야별로 청원이 분류되어 있어 분야별 분석을 용이하게 할 뿐 아니라 추후 지도학습 (supervised learning)도 고려할 수 있습니다. 

## 관련 뉴스

| 뉴스 | 링크   |
| ------ | -------------------------------------------------------------------------------------------- |
| SBS 뉴스 | https://news.sbs.co.kr/news/endPage.do?news_id=N1005076738&plink=THUMB&cooper=SBSNEWSPROGRAM |
| KBS 뉴스 | https://www.youtube.com/watch?v=EeMZ7IsdQjg |
|| https://www.youtube.com/watch?v=_JH8CizfcAY|
|| https://www.youtube.com/watch?v=iqaCqvxweRY |

## 데이터
https://www.dropbox.com/s/5kkiq9pbuy92xl4/petition_data_all.csv?dl=0

## 분류별 청원 숫자

```
경제민주화  :  15,870
안전,환경  :  29,098
보건복지  :  23,170
반려동물  :  3,752
교통,건축,국토  :  26,517
농산어촌  :  1,734
저출산/고령화대책  :  3,407
외교,통일,국방  :  25,277
인권/성평등  :  33,035
문화,예술,체육,언론  :  16,942
성장동력  :  6,853
기타  :  45,658
정치개혁  :  57,865
육아,교육  :  24,569
일자리  :  21,593
미래  :  16,852
행정  :  19,038
all  :  371,230
```

## 월별 청원 숫자

```
2017-08  :  1,171
2017-09  :  17,040
2017-10  :  5,930
2017-11  :  29,425
2017-12  :  18,377
2018-01  :  31,251
2018-02  :  25,696
2018-03  :  21,624
2018-04  :  23,044
2018-05  :  25,254
2018-06  :  25,387
2018-07  :  25,772
2018-08  :  27,783
2018-09  :  23,916
2018-10  :  25,740
2018-11  :  23,360
2018-12  :  20,125
2019-01  :  335
avg  :  19,538.42
all  :  371,230
```


## 데이터 해석
| 분류 | 설명   |
| ---------- | ----------------------------------------------------------------------------------------- |
| Time   | 2018-01-01-15:20|
| URL| https://www1.president.go.kr/petitions/21 ~ https://www1.president.go.kr/petitions/484339 |
| Size   | 371,230개 |
| Code   | https://github.com/com-lab/National-Petition-Crawler   |
| 하루 평균  | 739.50개|
| 가장 많이 나온 날 | 2017-11-11  :  9,614개   |
| 달 평균   | 19,538.42개 |
| 가장 많이 나올 달 | 2017-11  :  29,425개   |
| 분류 평균  | 21,837.05개  |
| 가장 많은 분류   | 정치개혁  :  57,865개 |
| 답변한 청원 수   | 68개  |
| 답변 확률  | 0.000183%|
| 추천수| 55,706,135개 |
| 평균 추천수 | 150.05개  |
| 가장 많은 추천수  | 1,192,049개 |
| 하루 평균 추천수  | 111,189.89개  |



# 데이터 분석 

국민청원의 데이터를 분석합니다.

https://trello.com/c/cjlrf379



## 분야별 청원의 추천 그래프 화 

 분야별로 청원의 숫자를 그래프 화 시킬 수 있습니다. 하지만 위에서 보다시피 분야별 청원 수가 매우 다릅니다. 지금 알고 싶은 것은 어떤 지지를 많이 받는 인기 있는 분야는 추천 수가 증가함에 따라 조금만 감소할 수도 있고 어떤 지지를 조금만 받는 인기 없는 분야는 추천 수가 증가함에 따라 급감할 수도 있습니다. 이러한 것을 알기 위해서 분야별 청원의 수가 모두 동일하게 1이라고 가정하고 진행하겠습니다. 이렇게 하면 어떤 분야가 인기가 있고 어떤 분야가 인기가 없는지 알 수 있습니다.

 아래 코드로 데이터들을 정규화시킵니다.
 
```
from sklearn import preprocessing

x = df.values #returns a numpy array
min_max_scaler = preprocessing.MinMaxScaler()
x_scaled = min_max_scaler.fit_transform(x)
dfs = pd.DataFrame(x_scaled,  columns= names)
dfs
```
그리고 이제 그래프를 그려봅니다. (all은 청원 전체에 대한 그래프 즉 평균을 의미합니다)

### 30개까지의 분야별 데이터 그래프

![데이터의 절반 1](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414793639_graph_half1_30.png)
![데이터의 절반 2](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414793646_graph_half2_30.png)

![중요한 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414793650_graph_important_30.png)
![전체 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414793657_graph_all_30.png)


### 100개까지의 분야별 데이터 그래프

![데이터의 절반 1](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414847590_graph_half1_100.png)
![데이터의 절반 2](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414847594_graph_half2_100.png)

![중요한 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414847135_graph_important_100.png)
![전체 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546414847580_graph_all_100.png)



## 분야별 분석 결과
1. 위 과정을 통해서 동의하는 수가 적은 반려동물이 가장 큰 관심을 두고 있다는 것을 알 수 있습니다. 이유는 아래 위드클라우드에서 볼 수 있는 것과 같이 반려동물의 경우 자극적인 키워드를 가집니다. 또한 반려동물을 키우는 사람들이 예민하게 반응하기 위와 같은 결과가 나온 것으로 예상됩니다.
  
2. 농산어촌과 일자리, 성장동력은 큰 인기가 없습니다. 농산어촌은 해당하는 사람이 적어 청원 수 자체도 적습니다. 일자리와 성장동력의 경우 청원의 수는 많지만 워드클라우드에서 본 것과 같이 무난한 키워드들 그리고 큰 변화가 없을 거라고 예상하는 것으로 생각되어 큰 인기가 없습니다.


3. 국민청원이 국민의 삶을 대변하는 것으로 보입니다. 반려동물이 가장 큰 인기를 얻고 있습니다. 글의 수는 적으나 그 지지도는 상상 이상입니다. 만약 정부를 비난하는 세력이 지배적이라면 반려동물이 아닌 다른 분야가 더 큰 인기를 얻어야 합니다. 사람들의 실생활과 밀접한 반려동물이 가장 인기가 있는 것으로 보아 국민청원은 국민의 삶을 대변하는 것으로 보입니다.


## 월별 청원의 추천 그래프 화

 월별 청원의 숫자를 알아봅시다. 그리고 그 숫자가 추천 수가 증가함에 따라 얼마나 떨어졌는지 알 수 있습니다. 이 과정으로 달에 글이 많은지 그리고 어떤 달이 인기가 있는지를 알 수 있습니다. 위에 분야별 분석과 달리 월은 모두 30일로 동일하게 데이터가 분포돼 있다고 가정하고 진행하겠습니다.

### 30개까지의 월별 데이터 그래프

![데이터의 절반 1](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481925810_graph_half2_m30.png)
![데이터의 절반 2](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481925787_graph_half1_m30.png)

![중요한 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481925831_graph_important_m30.png)
![전체 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481925763_graph_all_m30.png)


### 100개까지의 월별 데이터 그래프

![데이터의 절반 1](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481971452_graph_half2_m100.png)
![데이터의 절반 2](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481971430_graph_half1_m100.png)

![중요한 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481971487_graph_important_m100.png)
![전체 데이터](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546481971401_graph_all_m100.png)

## 월별 분석 결과

 월별 분석은 정규화를 진행하지 않고 그 숫자를 그대로 반영하였습니다. 2017년 11월이 제일 글 수는 많은데 추천 수는 증가는 크게 없었고 글의 분류가 대부분이 정치개혁에 있습니다. 그리고 2017-11-11일 하루동안 9614개 청원이 작성됐습니다. 그 내용의 대부분은 이명박 출국금지로 도배가 이뤄졌습니다. 그러나 화력이 집중되지 않아서 아래에 국민의 관심사를 보시면 추천수가 0개 그리고 1~3개일 때 이명박 출국 금지가 엄청나게 크게 작용했지만 4개 이상부터는 급감하는 것을 알 수 있습니다. 즉 화력이 집중됐을 때는 큰 이슈가 되지 못합니다. 일자리 추천이 급감하는 이유와 같습니다. 애완동물은 이와 반대로 중복된 내용이 없을 거 같습니다.
 
```
2017-11  :  29425
2017-11-11 : 9614
정치개혁  :  10488
```
 
 

# 워드클라우드

 워드클라우드란 문서를 구름처럼 그림으로 표현하는 것 입니다. 특정 단어가 크면 클수록 그 단어가 많이 등장했다는 뜻이고 특정 단어가 작으면 그 단어가 조금 등장했다는 의미입니다. 단어의 색과 위치는 임의적으로 구성된 것입니다. 큰 의미가 있는 것은 오직 글자의 크기입니다.
 
  이제 워드클라우드를 진행하여 국민들의 생각을 한눈에 알아봅시다.
 

https://trello.com/c/x9F7xJEO

분야별 워드클라우드

 의미있는 워드클라우드를 진행하기 위해서 분야별로 동의 수가 100번을 초과한 청원을 가지고 워드클라우드를 진행합니다. 
 
```
df = df[df["conut"]>100]
```

![정치개혁](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308655_.png)
![성장동력](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308604_.png)

![외교/통일/국방](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308736___.png)
![육아/교육](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308636_.png)

![행정](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415837700_.png)
![일자리](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415861067_.png)

![문화/예술/체육/언론](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308713_.png)
![농산어촌](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308699_.png)

![저출산/고령화대책](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415795586__.png)

![미래](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546609271418_.png)
![교통/건축/국토](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308675___.png)

![인권/성평등](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308762__.png)

![안전/환경](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546609654039_.png)
![반려동물](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308855_.png)

![경제민주화](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308794_.png)
![기타](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308685_.png)

![보건복지](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546415308505_.png)


 

## 월별 워드클라우드

 월별 데이터를 가지고 워드클라우드를 진행합니다. 각 그림은 해당하는 월에 탄생석의 모습으로 워드클라우드를 진행했습니다. 위와 동일하게 100번을 초과한 청원만 가지고 워드클라우드를 진행합니다.


![2017-08](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546520162314_2017-08.png)
![2017-09](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484237174_2017-09.png)

![2017-10](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484237381_2017-10.png)
![2017-11](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484262580_2017-11.png)

![2017-12](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484262641_2017-12.png)
![2018-01](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484262531_2018-01.png)

![2018-02](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484519395_2018-02.png)
![2018-03](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484519593_2018-03.png)

![2018-04](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484519558_2018-04.png)
![2018-05](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484656466_2018-05.png)

![2018-06](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484656553_2018-06.png)
![2018-07](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484656675_2018-07.png)

![2018-08](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484311180_2018-08.png)
![2018-09](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484311231_2018-09.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484841702_2018-10.png)
![2018-11](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484311629_2018-11.png)

![2018-12](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484311740_2018-12.png)
![2019-01](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546484311398_2019-01.png)




# 네트워크 Old 청치개혁 Top 50

 키워드 간에 관련된 네트워크를 찾습니다. 네트워크는 같은 문서에 등장하는 단어들을 연결합니다. 여러 문서에서 특정 단어들의 연결이 많으면 화살표 그리고 단어를 표시하는 동그라미가 더 커집니다. 

 워드클라우드의 경우 단어들을 표시할 수 있지만 해석을 하기에는 무리가 있습니다. 예를 들어 “가짜”라는 키워드가 자주 등장을 했다면 워드클라우드에서는 크게 표시될 뿐입니다. 네트워크의 경우에는 어떤 키워들이 관련이 있다는 것을 쉽게 알아서 해석을 하기 쉽습니다.


https://trello.com/c/n3uIGbBH

## 네트워크 예시

### 가짜

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435057445_.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435049449_.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546416349297_image.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435057469_.png)


### 김상돈

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435081742_2.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435150977_.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435081762_3.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435093778_5.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435088493_4.png)


### 문재인

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435170849_.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435177250_.png)


### 이재명


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435192294_1.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435196975_.png)


### 정의


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435241728_2.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435270146_5.png)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435285532_5.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435273812_5.png)


### 특검


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435319036_.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435318959_3.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546435319089_30.png)

## 네트워크 해석
1. 네트워크는 해당 키워드에 대한 사실을 보여줍니다. 특검 네트워크를 보면 국민, 야당, 개헌, 국회 등 특검과 관련된 네트워크가 나오는 것을 확인할 수 있습니다. 즉 네트워크는 사실과 관련된 것이 나온다는 것을 알 수 있습니다.
  
2. 네트워크는 한눈에 가장 화젯거리인 사실을 알 수 있습니다. 
  1. 의혹 네트워크를 보면 의왕시, 김상돈, 당선자와 같은 것들이 가장 큰 관련이 있습니다. 그리고 김상돈에 대한 네트워크를 제작해보면 동신대학교의 부정입학을 한 것과 같은 네트워크를 볼 수 있습니다. 그리고 아래를 보면 관련된 청원 글을 보며 김상돈 의원이 부정을 저질렀다는 것을 할 수 있습니다. 
  2. 가짜 네트워크를 보면 김진성, 공적, 포상, 독립유공자가 가장 큰 관련이 있습니다. 이를 바로 해석한다면 가짜 독립유공자 김진성이 가짜 공적으로 포상을 받았다는 일이 큰 이슈로 발생했다는 것을 할 수 있습니다.


3. 네트워크는 국민이 바라는 것을 볼 수 있습니다. 정의 네트워크를 보면 살인자, 뉴스, 가짜, 경찰, 시민이 가장 관련이 있습니다. 간단하게 생각하면 정의는 살인자와 가짜 뉴스 그리고 경찰로 인해 지켜지지 않으며 시민들이 피해를 보고 있다고 생각할 수도 있습니다. 네트워크를 보면 살인자가 가장 큰 관심을 받으며 이를 강력처별하는 것을 바란다고 봐도 될 것입니다.


# 네트워크 브리핑

 브리핑이 완료된 청원에 대해서 네트워크를 제작합니다. 


## 네트워크 예시

### 심신

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546614884371_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710788376_2.PNG)


### 조두순

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712628148_1.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712690600_.PNG)

![5개](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710775272_5.PNG)


### 난민

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710759857_.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710759883_2.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712737799_.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710759743_5.PNG)



### 비서

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546710822267_.PNG)


### 뉴미디어


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712781798_.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546711293596_.PNG)


### 음주운전

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712807223_.PNG)


### 피해자

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546712832421_.PNG)



## 네트워크 해석 


# 네트워크 Top 1000


## 네트워크 예시

### 여성

![5](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546759242271_1.PNG)
![5](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546759242329_2.PNG)
![5](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546759242363_3.PNG)


### 살인자

![10](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546759658617_.PNG)
![30](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546759773657_2.PNG)


### 무슬림


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546760366741_1.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546760366783_2.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546760366915_4.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546760366814_3.PNG)


### 교사

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761097390_2.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761097459_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761097504_4.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761097535_5.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761097565_1.PNG)


### 어린이집

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761525874_1.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761525917_2.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761526016_4.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761525986_3.PNG)


### 전용

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761916447_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761916502_1.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761916472_4.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546761916522_2.PNG)


### 인스타

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762274892_1.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762275063_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762274955_2.PNG)


### 일베

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559705_6.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559762_1.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559802_2.PNG)

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559842_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559874_4.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762559905_5.PNG)


### 인증

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762997773_2.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762997911_3.PNG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546762997941_1.PNG)



## 네트워크 해석



# 정부의 관심사 알아보기

 국민청원 사이트를 만든 이유는 국민과 소통을 하기 위해서라고 생각합니다. 그리고 소통은 해당하는 청원에 정부가 답변하는 경우입니다. 정부에서 답변한 청원이 정부가 관심이 있는 청원이라고 생각할 수 있습니다. 물론 답변을 하는 조건으로 추천이 20만 번 이 된 청원을 한다는 원칙이 있습니다. 그래도 답변을 한 청원을 분석하여 정부의 관심사를 알아볼 수 있다고 생각합니다.
 

https://trello.com/c/K9nvUuqR

## 답변한 청원 정리

 답변을 한 청원은 68개로 답변을 받을 확률은 0.00018317534459861702%입니다.
 
### 분야별 답변 수(답변한 분야만)
```
보건복지  :  3
반려동물  :  3
육아/교육  :  2
기타  :  7
인권/성평등  :  21
안전/환경  :  8
성장동력  :  2
미래  :  1
교통/건축/국토  :  2
문화/예술/체육/언론  :  7
행정  :  1
정치개혁  :  5
외교/통일/국방  :  4
경제민주화  :  2
all :  68
```
### 달별 답변 수
```
2017-08  :  0
2017-09  :  3
2017-10  :  0
2017-11  :  3
2017-12  :  2
2018-01  :  7
2018-02  :  7
2018-03  :  6
2018-04  :  5
2018-05  :  8
2018-06  :  7
2018-07  :  3
2018-08  :  0
2018-09  :  2
2018-10  :  12
2018-11  :  3
2018-12  :  0
all :  68
```
### 답변 정리
```
| 설명| 개수  |
| ----- | ----------- |
| 최다 추천 | 1,192,049개  |
| 최소 추천 | 201,590개|
| 추천 평균 | 285,297.05개 |
| 추천 합계 | 19,400,200개 |
```


## 답변 워드클라우드

 정부에서 답변을 한 글들에 대해서 워드클라우드를 진행합니다. 한쪽은 해당하는 청원 글에 대한 워드클라우드를 진행하고 다른 한쪽에서는 청원 답변에 대한 워드클라우드를 진행합니다. 아래는 답변을 한 글에 전체에 대한 워드클라우드입니다.

![청원 키워드](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546599419684_tr1.png)
![답변 키워드](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546703939804_ga.png)

![All](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546705054775_all1.png)



## 청원 키워드 Top 15
```
{'피해자': 138,
 '사람': 124,
 '국민': 110,
 '생각': 97,
 '가해자': 91,
 '사건': 87,
 '아이': 87,
 '법': 79,
 '링크': 66,
 '처벌': 64,
 '일': 62,
 '첨부': 60,
 '동생': 59,
 '인증': 58}
```


## 답변 키워드 Top 15
```
{'청원': 660,
 '국민': 466,
 '비서': 444,
 '사건': 367,
 '처벌': 348,
 '정혜승': 344,
 '피해자': 313,
 '범죄': 236,
 '정부': 235,
 '수사': 213,
 '법': 206,
 '불법': 206,
 '뉴미디어': 205,
 '문제': 200,
 '센터': 198}
```

## 전체에 대한 키워드 Top 30
```
{'청원': 714,
 '국민': 576,
 '사건': 454,
 '피해자': 451,
 '비서': 444,
 '처벌': 412,
 '정혜승': 344,
 '법': 285,
 '범죄': 274,
 '정부': 256,
 '문제': 246,
 '생각': 244,
 '보호': 240,
 '수사': 237,
 '불법': 233}
```

# 국민의 관심사 알아보기

 국민청원에는 동의하는 기능 즉 추천하는 기능이 있습니다. 청원글은 총 371,230개가 있습니다. 그런데 청원의 총 추천 수는 우리나라 인구수보다 많은 55,706,135이며 하루 평균 111,190여 번 이뤄집니다. 국민들의 관심을 알기 위해서는 어느 정도의 추천에 어느 키워드가 존재하는지를 알면 됩니다. 이제 추천 수를 보면서 국민의 관심사를 분석합니다.

https://trello.com/c/DZUmlVUr

## 추천수 별 개수
| 추천수  | 개수 |
| -------- | ------ |
| 0| 53,410 |
| 1 ~ 2| 74,522 |
| 3 ~ 5| 66,493 |
| 6 ~ 10   | 55,902 |
| 11 ~ 20  | 47,826 |
| 21 ~ 40  | 33,249 |
| 41 ~ 100 | 22,522 |
| 101 ~| 17,306 |



## 워드클라우드

 추천이 몇 개 있을 때 어떤 키워드들이 등장하는지를 보면서 국민들이 어떤 청원에 큰 관심이 없고 어떤 청원에 어느 정도의 관심이 있는지를 유추할 수 있습니다.

![0](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525725786_0.png)
![1~2](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546602313868_1-2.png)

![3~5](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546602368253_35.png)
![6~10](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525742656_6-10.png)

![11~20](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525804082_11-20.png)

![21~40](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525825566_21-40.png)

![41~100](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525839041_41-100.png)

![100~](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546525841840_100-.png)



## 추천 수 0개 키워드
```
{'폐지': 6,807,
 '이명박': 5,917,
 '법': 5,095,
 '출국금지': 4,846,
 '청소년': 4,585,
 '반대': 3,974,
 '조두순': 3,218,
 '청원': 3,200,
 '보호': 2,886,
 '소년법': 2,190,
 '대통령': 1,656,
 '화폐': 1,521,
 '가상': 1,421,
 '금지': 1,366,
 '국민': 1,345}
```

## 1~2개 추천 키워드
```
{'청원': 4,760,
 '폐지': 4,278,
 '법': 3,147,
 '이명박': 2,823,
 '국민': 2,715,
 '대통령': 2,367,
 '출국금지': 2,205,
 '반대': 2,140,
 '청소년': 1,851,
 '화폐': 1,756,
 '처벌': 1,586,
 '요청': 1,575,
 '가상': 1,571,
 '정부': 1,513,
 '보호': 1,450}
```

## 3~5개 추천 키워드
```
{'청원': 4,512,
 '국민': 2,890,
 '폐지': 2,774,
 '대통령': 2,316,
 '처벌': 2,043,
 '법': 1,938,
 '반대': 1,740,
 '정부': 1,720,
 '화폐': 1,463,
 '대한민국': 1,341,
 '요청': 1,323,
 '문재인': 1,292,
 '가상': 1,279,
 '공무원': 1,203,
 '개선': 1,179}
```

## 6~10개 추천 키워드
```
{'청원': 3,889,
 '국민': 2,785,
 '폐지': 2,504,
 '대통령': 2,303,
 '처벌': 2,182,
 '반대': 1,665,
 '정부': 1,627,
 '법': 1,581,
 '문재인': 1,462,
 '대한민국': 1,227,
 '요청': 1,126,
 '국민연금': 1,111,
 '공무원': 1,096,
 '화폐': 1,071,
 '부동산': 1,003}
```

## 11~20개 추천 키워드
```
{'청원': 3,199,
 '국민': 2,771,
 '폐지': 2,445,
 '처벌': 2,207,
 '대통령': 2,133,
 '반대': 1,688,
 '문재인': 1,579,
 '국민연금': 1,454,
 '정부': 1,436,
 '법': 1,318,
 '국회의원': 1,274,
 '부동산': 1,130,
 '공무원': 1,054,
 '요청': 1,015,
 '대한민국': 1,015}
```

## 21~40개 추천 키워드
```
{'폐지': 2,393,
 '청원': 2,265,
 '국민': 1,943,
 '반대': 1,657,
 '처벌': 1,615,
 '대통령': 1,590,
 '난민': 1,262,
 '국민연금': 1,251,
 '국회의원': 1,236,
 '문재인': 1,191,
 '정부': 1,008,
 '법': 918,
 '사건': 910,
 '부동산': 874,
 '요청': 798}
```

## 41~100개 추천 키워드
```
{'난민': 2,071,
 '청원': 1,863,
 '폐지': 1,829,
 '반대': 1,502,
 '국민': 1,325,
 '처벌': 1,306,
 '국회의원': 1,064,
 '사건': 980,
 '법': 826,
 '조사': 779,
 '대통령': 743,
 '국민연금': 698,
 '요청': 684,
 '폭행': 581,
 '문재인': 517}
```

## 100개 이상 추천 키워드
```
{'청원': 1,874,
 '처벌': 1,425,
 '폐지': 1,044,
 '반대': 965,
 '사건': 941,
 '요청': 808,
 '조사': 786,
 '국민': 694,
 '국회의원': 592,
 '법': 561,
 '폭행': 473,
 '수사': 467,
 '난민': 408,
 '대통령': 407,
 '대한항공': 380}
```

## 특이한 점

### 찾은 계기
 난민, 국회의원의 경우에는 추천 수가 매우 높습니다. 이명박 출국금지 같은 것들은 생각보다 인기가 적습니다.  위에 월별 분석 결과에서 이병박과 출국금지 내용이 도배되었다는 것을 알고 있습니다. 때문에 특정한 달에만 많이 나온 키워드는 큰 인기지 받지 못할 것으로 예상했습니다. 왜냐하면 비슷한 글들이 중복되어 나오면 시선이 분산될 것이기 때문입니다. 만약에 집중을 받는 글이 있다고 해도 전체 글에서 매우 소수 비중을 차지할 거라고 예상했습니다.
 
### 그래프화
 추천수가 100개 이상에서 나온 키워드들과 추천수가 0개인 키워드들이 달별로 얼마나 등장했는지를 찾는다면 쉽게 위에 가설이 사실인지 아닌지 판단할 수 있다고 생각했습니다. 또한 추천수가 0개일때부터 100개일 때까지 여러번 등장하는 키워드들은 어떻게 작용을 할지 궁금했습니다. 아래에 키워드들을 가지고 달마다 해당하는 키워드가 청원 제목에서 몇 번 등장했는지 그래프화 시켜봅니다.
 
```
t_0 = ["이명박", "출국금지", "조두순","가상","화폐"] #추천이 0개인 키워드
t_100 = ["난민", "폭행", "처벌", "국회의원", "대한항공"] #추천이 100개 이상인 키워드
t_a = ["국민", "처벌", "대통령","청원","폐지"] #여러 추천에서 나오는 키워드
```
![추천이 0개인 키워드에 대한 빈도수 그래프](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546780724005_0.png)

![추천이 100개 이상인 키워드에 대한 빈도수 그래프](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546780728221_100.png)

![여러곳에서 등장하는 키워드에 대한 빈도수 그래프](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546782979948_a.png)


  
### 해석
 예상대로 추천이 0개인이 키워드들은 특정한 달 딱 한 달 동안만 빈도수가 늘고 다른 달은 특정한 달에 비해서 매우 낮은 것으로 확인 되었습니다. 반면 추천이 100개 이상인 키워드의 경우 특정한 1개의 달에서가 아닌 여러 달에서 여러번 등장하는 것을 알 수 있습니다.
 
 한 달에만 반짝 인기를 가진 키워드들은 국민들의 큰 관심을 받을 수 없다는 것을 보여줍니다. 또한 추천이 적은 키워드들은 반짝 인기를 가진다는 것을 알 수 있습니다.
 
 또한 추천 수가 특히 많은 난민 처벌 국회의원 등이 우리나라에서 지속적인 관심을 보이는 것을 알 수 있습니다. 즉 추천 수가 많은 키워드들은 어느정도는 우리나라에서 지속적인 관심을 갖는 키워드라고 생각할 수 있습니다.
 
  예외로는 모든 곳에 등장하는 청원, 국민, 폐지, 처벌 등인데 이는 두 그래프를 합친듯한 양상을 보입니다. 어떤 키워드는 여러달에 골고로 등장하고 어떤 키워드는 몇개의 달에 특히 급증합니다. 하지만 0개 추천 처럼 오직 한 달에만 등장하는 급증하는 모습은 보이지 않습니다.

# 중요 키워드 정리

 중요한 키워드들에 대해서 네트워크 제작, 워드클라우드를 진행하고 이에 대한 해석을 합니다. 이 과정을 통해서 중요한 키워들을 국민들이 어떻게 생각하고 있는지를 한 눈에 파악할 수 있습니다.
 

## 군대

 국민청원에서 보는 군대에 대해서 알아봅시다.
 
### 네트워크


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835540468_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835540497_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546786155199_.png)


### 키워드 Top 15
```
{'병원': 105982,
 '아들': 32482,
 '군': 18564,
 '일병': 7852,
 '군대': 4053,
 '치료': 2265,
 '의사': 2097,
 '에이즈': 2020,
 '환자': 1764,
 '아이': 1694,
 '간호사': 1507,
 '재활': 1358,
 '사망': 1327,
 '의료': 1120,
 '학생': 1099}
```

### 해석



## 서민

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546828772487_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546828772729_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546786566973_.png)


### 키워드 Top 15
```
{'분양': 73480,
 '공사': 30061,
 '전환': 29546,
 '서민': 28105,
 '주택': 23365,
 '건설': 3784,
 '임대': 3231,
 '공급': 2861,
 '택지': 2820,
 '국토부': 2771,
 '집': 2541,
 '주거': 2278,
 '국가': 2237,
 '감정': 2166,
 '가액': 2007}
```

### 해석


## 소통

### 네트워크


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835754420_.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835754523_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789699749_.png)


### 키워드 Top 15
```
{'교육': 251422,
 '학교': 147493,
 '노동': 21184,
 '교사': 18094,
 '비정규직': 14778,
 '학생': 12090,
 '노동자': 10006,
 '교장': 4744,
 '사회': 4400,
 '영양사': 3642,
 '사람': 3528,
 '업무': 3507,
 '공무원': 3489,
 '무슬림': 3380,
 '정부': 3180}
```

### 해석



## 대기업

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835806708_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835806727_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789707796_.png)


### 키워드 Top 15
```
{'저희': 129118,
 '기술': 26899,
 '대기업': 10173,
 '특허': 7896,
 '텔레콤': 6876,
 '패션': 5786,
 '사건': 2910,
 '아이': 1677,
 '둘째딸': 1666,
 '딸': 1578,
 '아빠': 1571,
 '소송': 1521,
 '병원': 1317,
 '침해': 1207,
 '엄마': 1138,
 '중소기업': 1113}
```
### 해석



## 성장

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835934148_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835934232_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789712660_.png)


### 키워드 Top 15

{'책': 38416,
 '주식시장': 19888,
 '국민연금': 13215,
 '구매': 10820,
 '대여': 8744,
 '성장': 3352,
 '공매도': 2892,
 '불법': 1907,
 '주식': 1796,
 '감소': 1512,
 '도서': 1457,
 '출판': 1455,
 '서점': 1358,
 '국민': 1151,
 '투자자': 1087}

### 해석




## 탄핵

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835946663_.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835946875_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789721649_.png)


### 키워드 Top 15
```
{'국민': 488614,
 '대통령': 85140,
 '청원': 84869,
 '국회의원': 11394,
 '여성': 10782,
 '국회': 9146,
 '대한민국': 7301,
 '난민': 6767,
 '정부': 6728,
 '국가': 6232,
 '사람': 6051,
 '한국': 4588,
 '정책': 4327,
 '사회': 4059,
 '외국인': 3833}
```
### 해석



## 경제

### 네트워크


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836093256_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836093451_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789758641_.png)


### 키워드 Top 15
```
{'사람': 260874,
 '한국': 227097,
 '공매도': 98681,
 '나라': 88488,
 '무슬림': 63252,
 '경제': 30775,
 '사회': 11832,
 '국민': 9695,
 '이민자': 9328,
 '이민': 8532,
 '아랍': 8261,
 '여성': 8145,
 '난민': 7813,
 '교육': 7676,
 '생각': 7349}
```
### 해석



## 국회의원

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836049774_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836049792_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789817334_.png)


### 키워드 Top 15
```
{'국민': 244165,
 '요구': 77475,
 '의원': 57999,
 '자료': 19488,
 '제출': 16013,
 '국회의원': 12196,
 '여성': 8529,
 '정부': 4545,
 '대한민국': 3946,
 '국가': 3633,
 '난민': 3587,
 '사람': 3167,
 '남성': 2922,
 '법': 2877,
 '지원': 2724}
```
### 해석




## 북한

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836257211_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546836257238_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789807828_.png)


### 키워드 Top 15
```
{'국민': 491559,
 '정부': 146082,
 '대한민국': 113732,
 '여성': 16009,
 '합의': 13617,
 '난민': 8176,
 '국가': 8111,
 '북한': 7029,
 '사람': 6807,
 '정책': 5592,
 '지원': 5453,
 '남성': 5433,
 '한국': 4589,
 '대통령': 4490,
 '무고': 4480,
 '외국인': 4377}
```
### 해석




## 대통령

### 네트워크

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835724869_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835725060_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789801998_.png)


### 키워드 Top 15

{'국민': 497863,
 '여성': 319555,
 '사람': 264325,
 '정부': 150289,
 '한국': 117601,
 '대통령': 87718,
 '남성': 19163,
 '사회': 16075,
 '국가': 13518,
 '대한민국': 13434,
 '정책': 11676,
 '남자': 11659,
 '무고': 11597,
 '지원': 10648,
 '피해자': 10529}

### 해석




## 갑질

### 네트워크


![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835696766_1.JPG)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546835696773_2.JPG)


### 워드클라우드

![](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546789797423_.png)


### 키워드 Top 15
```
{'국민': 244654,
 '말': 217367,
 '병원': 107206,
 '업체': 48050,
 '여성': 9752,
 '승무원': 8159,
 '사람': 7112,
 '갑질': 4138,
 '대한민국': 4121,
 '아이': 4027,
 '생각': 3959,
 '정부': 3764,
 '국가': 3732,
 '사건': 3520,
 '치료': 3460,
 '의사': 3374,
 '피해자': 3270}
```
### 해석




# 글을 마치며


## 소통

 문재인 정권이 강조한 소통이 잘 이뤄지지 않고 있습니다. 국민과 소통을 하는 방법은 정부가 국민의 생각에 답변을 하는 것 입니다. 하지만 데이터를 기반으로 현재 답변률은 0.00018317534459861702%입니다. 매우 적은 확률입니다. 위 연구를 통해 국민청원의 모든 글들을 한눈에 볼 수 있는 기회가 제공이 된다면 국민의 생각이 국정에 더 깊이 반영될 것입니다.


| 총 청원 수 | 답변 수 | 비율  |
| ------ | ---- | ----------------------- |
| 371229 | 68   | 0.00018317534459861702% |

## 서민


http://www.asiae.co.kr/news/view.htm?idxno=2018082509355045889


  

## 4차 산업혁명




## 혁신  
 

https://news.joins.com/article/21913293


 


## 군대
 

http://www.hani.co.kr/arti/international/china/813735.html#csidxb431fe906b7b26c82fdd9488c977049



## 갑질
 

http://www.nocutnews.co.kr/news/5083303



## 경제
![청와대 그림](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546502638628_28dgIg4gLZeMjVWTSdT1LuHqKUoV1cozU00uEMv7.jpeg)


https://www1.president.go.kr/econo_num


## 북한


## 미래
![청와대 그림](https://d2mxuefqeaa7sj.cloudfront.net/s_6BA2A63FD25F3FE0CBB3C54FF3212310B170B7FB25E38BF989986B9924C49C1E_1546503782667_president_pic9.jpg)

 위 연구를 통해 국민청원의 모든 글들을 한눈에 볼 수 있는 기회가 제공이 된다면 국민의 생각이 국정에 더 깊이 반영될 것입니다.

 현재 정치개혁 분류에 57,865개의 청원이 올라와 있습니다. 많은 국민들이 개혁을 바라고 있습니다. 위대한 정의로운 자랑스러운 무엇보다 당당한 대한민국이 되기 위해서는 이제 변화가 필요합니다.
 

## Contributor
@sejongds @newhiwoong

## Connect
```
# github : https://github.com/newhiwoong
# email  : newhiwoong@gmail.com
```