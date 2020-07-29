# cracking-the-pandas-cheat-sheet

https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf

# 전체강좌보기

:tv: https://www.inflearn.com/course/판다스-Pandas

### Pandas cheat sheet
Python에서 엑셀과 유사한 기능을 사용할 수 있는 라이브러리로 Pandas cheat sheet을 따라해 봅니다.
데이터 분석이나 전처리를 하다보면 주로 사용하는 기능들 위주로 사용하게 됩니다. 이런 핵심적인 내용만 정리되어 있는 cheat sheet 을 함께 보면 좋겠다는 생각이 들어서 영상으로 만들어 보게 되었습니다.  cheat sheet 은 두 장으로 되어 있고 각 내용들을 10분 내외로 실습과 함께 정리해 보았습니다.

### 주피터 노트북에서 docstring 활용하기
총 29개의 영상으로 되어 있고 많은 메소드를 다 외우시지 않고 도움말과 다큐멘트를 보고 학습하실 수 있도록 주피터 노트북에서 공식문서를 찾아보며 실습하는 방법을 주로 다루고 있습니다. 

### 데이터 시각화
시각화 부분은 짧게만 다루려고 했는데 어떤 데이터에 어떤 그래프를 사용하는게 적절할지, 막대그래프, 도수분포표, 히스토그램, 정규분포의 차이와 사용법에 대해서도 다루고 있습니다.

### 서울 코로나19 발생현황 분석
2020년 6월 30일까지의 코로나19 발생현황 데이터를 판다스로 크롤링, 전처리, 분석, 시각화를 다루고 있습니다.

## Pandas cheat sheet 따라하기

* [1] 판다스 10분 완성소개, cheat sheet 보고 데이터프레임 만들어보기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/01-02-pandas_dataframe_and_rows.ipynb)
https://youtu.be/lspu830SzC8

* [2] 판다스 데이터프레임 생성하고 데이터 가져오기
https://youtu.be/kdiO27ZuZJw

* [3] 판다스 데이터프레임 비교연산자로 색인하기, drop_duplicates()
https://youtu.be/XS-eOEUZQKM

* [4] and, or, not, xor, any, all 연산 이해하기
https://youtu.be/n0pysUeamzw

* [5] head, tail로 데이터 미리보기 df.sample(frac=0.5), df.sample(n=10), df.nlargest, df.nsmallest
https://youtu.be/t5yKK-JxQPY

* [6] 일부 컬럼을 기준으로 데이터 가져오기 Subset Variables (Columns) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/06-pandas_cheat_sheet_columns.ipynb)
https://youtu.be/eobqZVDd8uA

* [7] 파이썬 판다스로 기본 통계 하기 value_counts, nunique, sum, count, mean, median [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/07-08-Summarize_Data.ipynb)
https://youtu.be/D5ep0-slc6U

* [8] 파이썬 판다스로 apply 활용하기 lambda 익명함수 사용하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/07-08-Summarize_Data.ipynb)
https://youtu.be/0yjNRB5ljew

* [9] Pandas Handling Missing Data, fillna, dropna로 결측치 다루기[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/09-Pandas_Handling_Missing_Data.ipynb)
https://youtu.be/lUvv47ko7Ww

* [10] Pandas assign 으로 새로운 컬럼 만들기, qcut으로 binning, bucketing 하기[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/10-Pandas_Make_New_Columns.ipynb)
https://youtu.be/CGEhwAd7Dbk

* [11] Pandas df.sort_values, rename, sort_index, reset_index로 데이터 프레임 Reshaping [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/11-Pandas_Reshaping_Data.ipynb)
https://youtu.be/iICCBjAHRq8

* [12] Pandas melt, pivot 으로 Tidy Data 만들기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/12-Pandas_melt_pivot.ipynb)
https://youtu.be/mVr1OWLpI_M

* [13] Pandas pd.concat([df1,df2]) 시리즈, 데이터프레임 합치기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/13-Pandas_concat.ipynb)
https://youtu.be/vbr4xrFEbyw

* [14] merge로 데이터프레임 합치기 left, right, inner, outer 옵션 사용하기 - 파이썬 판다스로 데이터 분석 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/14-Pandas_merge.ipynb)
https://youtu.be/cUoJDBFsJ8Y

* [15] 파이썬 판다스로 groupby 활용하여 다양한 데이터 집계를 활용하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/15-Pandas_group.ipynb)
https://youtu.be/gd5faB32xs0

* [16] 시계열 데이터(Time Series Data) 분석을 위한 판다스 Expanding and Rolling 이해하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/16-Pandas_Expanding_and_Rolling.ipynb)
https://youtu.be/Sq_uhK_GFIQ

* [17] 파이썬 판다스로 Series 와 DataFrame 데이터 시각화 하기 소개 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/17-Pandas_Plot_Series_DataFrame.ipynb)
https://youtu.be/yw4SX6KRGJw

* [18] 파이썬 데이터 시각화 판다스로 bar plot 막대그래프 그리기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/18-Pandas_bar_plot.ipynb)
https://youtu.be/YTAd1TmgPv0

* [19] 파이썬 데이터 시각화 히스토그램과 도수분포표 이해하기, 막대그래프 vs 히스토그램 차이점 이해하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/19-20-Pandas_hist_plot.ipynb)
https://youtu.be/L_UXVLz5Sxw

* [19] 부록 random의 rand, randn, randint 차이 이해하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/19-1-numpy_rand_randn_randint.ipynb)

* [20] 파이썬 판다스로 차분 diff 값을 구하고 히스토그램으로 표현하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/19-20-Pandas_hist_plot.ipynb)
https://youtu.be/zFOvKkEtpEg

* [21] 파이썬 시각화 상자 수염 그림(box plot) 그리기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/21-Pandas_box_plot.ipynb)
https://youtu.be/q-SrfR_amhQ

* [22] 파이썬 데이터 시각화 Area plot, Grid 옵션으로 그래프 격자 만들기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/22-Pandas_area_plot.ipynb)
https://youtu.be/dRu0BfJ0uDg

* [23] 파이썬 데이터 시각화 scatter plot, 산점도 그리기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/23-Pandas_scatter_plot.ipynb)
https://youtu.be/hlIivkjKzKY

* [24] 파이썬 데이터 시각화 히스토그램과 산점도를 보완한 Hexbin plot 그리기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/24-Hexagonal_Bin_Plot.ipynb)
https://youtu.be/8tbF6kT9fZ8

* [25] Pandas pie plot, 원 그래프, 왜  seaborn  에는 파이차트가 없을까? [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/25-Pandas_Pie_plot.ipynb)
https://youtu.be/zAgVZ_jZHNg

* [26] Scatter Matrix Plot 산점도를 diagonal='kde'옵션을 사용해서 커널밀도함수를 표현해 보도록 합니다.[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/26-Scatter_Matrix_Plot.ipynb)
https://youtu.be/PtSofOihtZs

* [27] 파이썬 시각화  분포도 정규분포, 분포도 그리기, Kernel Density Estimate plot 커널밀도함수, 밀도함수[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/corazzon/cracking-the-pandas-cheat-sheet/blob/master/27-Kernel_Density_Estimate_plot.ipynb)
https://youtu.be/xthZxPOU_cA

* [28] 소스코드 위치 안내와 다운로드 방법, 추가로 참고하면 좋을 자료들
https://youtu.be/9hi8C2yie1o

* [29] colab(google colaboratory) 에서 github 에 있는 파이썬 판다스 실습코드를 실행해 보는 방법
https://youtu.be/P1Z7BfsWhek

## 서울시 코로나19 발생현황 분석하기

* 2020년 6월 30일까지의 코로나 발생현황을 판다스로 크롤링, 분석, 시각화를 합니다.

* 판다스로 크롤링 하기 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/seoul-covid19-crawling-output)

* 판다스로 데이터 로드해서 분석하기 
  * 코드를 직접 타이핑하며 실습할 수 있는 파일 : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/seoul-covid19-eda-input)
  
  * 결과코드가 함께 있는 파일 : [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://bit.ly/seoul-covid19-eda-output)
