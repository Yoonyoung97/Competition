본 경진대회에 사용한 데이터는 [데이콘](https://dacon.io/competitions/official/235624/data/)에서 제공된 데이터를 사용하였습니다.



Dataset:

​		학습 데이터 :

​			    Column 1(time) : 관측 시각

​				Column 2~59(P1_B2004 ~ P4.P4.ST_TT01): 제어시스템(센서, 엑추에이터, 제어기기) 상태 관측 정보	

​			    Column 60~63(attack, attack.P1, attack.P2, attack.P3) : 공격 라벨 (정상: '0', 공격: '1')

​		        attack.P1 ~ attack.P3 : 각 공정(P1, P2, P3)에 대한 공격 라벨

​		검증 데이터: 

​		        Column 1(time) : 관측 시각

​				Column 2~59(P1_B2004 ~ P4.P4.ST_TT01): 제어시스템(센서, 엑추에이터, 제어기기) 상태 관측 정보	

​			    Column 60~63(attack, attack.P1, attack.P2, attack.P3) : 공격 라벨 (정상: '0', 공격: '1')

​		        attack.P1 ~ attack.P3 : 각 공정(P1, P2, P3)에 대한 공격 라벨