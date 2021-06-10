예측모델
================
Jimin KIM
2021.06.08

-   [분석모델 분석기간](#분석모델-분석기간)
    -   [분석기간 정의](#분석기간-정의)
    -   [분석기간 대상](#분석기간-대상)
    -   [분석기간 정의 - 테이블](#분석기간-정의---테이블)

## 분석모델 분석기간

### 분석기간 정의

    ## [1] "타겟기간 : 3개월"

    ## [1] "학습기간 : 12개월"

    ## [1] "검증기간 : 12개월"

### 분석기간 대상

    ## [1] "작업년월 : 202104"

    ## [1] "타겟 대상기간 : 202101 ~ 202103"

    ## [1] "기준년월 : 202012"

    ## [1] "학습 대상기간 : 202001 ~ 202012"

    ## [1] "검증 대상기간 : 201901 ~ 201912"

### 분석기간 정의 - 테이블

| 작업년월 |     타겟기간     | 기준년월 |     학습기간     |     검증기간     |
|:--------:|:----------------:|:--------:|:----------------:|:----------------:|
|  202104  | 202101 \~ 202103 |  202012  | 202001 \~ 202012 | 201901 \~ 201912 |

    ## Warning: package 'DiagrammeR' was built under R version 4.0.5

<div id="htmlwidget-f69b8ec49bf32d758837" style="width:672px;height:480px;" class="DiagrammeR html-widget"></div>
<script type="application/json" data-for="htmlwidget-f69b8ec49bf32d758837">{"x":{"diagram":"\nsequenceDiagram\n  participant Alice\n  participant Bob\n  Alice->>John: Hello John, how are you?\n  loop Healthcheck\n      John->>John: Fight against hypochondria\n  end\n  Note right of John: Rational thoughts<br/>prevail...\n  John-->>Alice: Great!\n  John->>Bob: How about you?\n  Bob-->>John: Jolly good!\n"},"evals":[],"jsHooks":[]}</script>

#### toc test

    ## [1] "toc 테스트 중입니다."
