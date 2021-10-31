# Hello-World
practice
Moto: Anyone can be cynical. Dare to be an optimist

# Data Analysis setting
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import matplotlib
from matplotlib import font_manager, rc

## colab 내 그래프를 바로 그리기 위한 설정
%matplotlib inline

## unicode minus를 사용하지 않기 위한 설정 (minus 깨짐현상 방지)
plt.rcParams['axes.unicode_minus'] = False

## font 적용
plt.rc('font', family = 'NanumBarunGothic')

## ggplot 으로 그래프 스타일 설정
plt.style.use('ggplot')

## 레티나 설정 : 글자가 흐릿하게 보이는 현상 방지
%config InlineBackend.figure_format = 'retina'

## 소수점 세자리
pd.options.display.float_format = '{:.3f}'.format
