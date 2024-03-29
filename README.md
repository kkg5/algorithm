<div align="center">

## Algorithm

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=kkg0510)](https://solved.ac/profile/kkg0510)

</div>

---

[365일 동안의 알고리즘 하루 한 문제 후기 링크](https://kkg0.tistory.com/87)

<details markdown="1">
<summary><strong>하루 한 문제 / 백준 - 단계별로 풀어보기<br>2022/01/27 ~ 2022/06/01</strong></summary>

<br>

<div align="center">

<table>

<th colspan="3">Contents</th>
<tr>
<td width="33%"  align="center"><a href="#브루트-포스">브루트 포스</a></td>
<td width="33%" align="center"><a href="#정렬">정렬</a></td>
<td width="33%" align="center"><a href="#백트래킹">백트래킹</a></td>
</tr>
<tr>
<td align="center"><a href="#동적-계획법-1">동적 계획법 1</a></td>
<td align="center"><a href="#그리디-알고리즘">그리디 알고리즘</a></td>
<td align="center"><a href="#정수론-및-조합론">정수론 및 조합론</a></td>
</tr>
<tr>
<td align="center"><a href="#스택">스택</a></td>
<td align="center"><a href="#큐-덱">큐, 덱</a></td>
<td align="center"><a href="#분할-정복">분할 정복</a></td>
</tr>
<tr>
<td align="center"><a href="#이분-탐색">이분 탐색</a></td>
<td align="center"><a href="#우선순위-큐">우선순위 큐</a></td>
<td align="center"><a href="#동적-계획법-2">동적 계획법 2</a></td>
</tr>
<tr>
<td align="center"><a href="#dfs와-bfs">DFS와 BFS</a></td>
<td align="center"><a href="#최단-경로">최단 경로</a></td>
<td align="center"><a href="#투-포인터">투 포인터</a></td>
</tr>
<tr>
<td align="center"><a href="#동적-계획법과-최단거리-역추적">동적 계획법과 최단거리 역추적</a></td>
<td align="center"><a href="#트리">트리</a></td>
<td align="center"><a href="#유니온-파인드">유니온 파인드</a></td>
</tr>
<tr>
<td align="center"><a href="#최소-신장-트리">최소 신장 트리</a></td>
<td align="center"><a href="#트리에서의-동적-계획법">트리에서의 동적 계획법</a></td>
<td align="center"><a href="#기하">기하</a></td>
</tr>
<tr>
<td align="center"><a href="#동적-계획법-3">동적 계획법 3</a></td>
<td align="center"><a href="#문자열-알고리즘-1">문자열 알고리즘 1</a></td>
<td align="center"><a href="#위상-정렬">위상 정렬</a></td>
</tr>
<tr>
<td align="center"><a href="#최소-공통-조상">최소 공통 조상</a></td>
<td align="center"><a href="#강한-연결-요소">강한 연결 요소</a></td>
<td align="center"><a href="#세그먼트-트리">세그먼트 트리</a></td>
</tr>

</table>

<!-- Contents -->

---

### 브루트 포스

|                                         난이도                                         |     번호     |        이름        | 날짜  | 체크 |
| :------------------------------------------------------------------------------------: | :----------: | :----------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/4.svg" width="20px" height="25px"></img> | [2798][2798] |       블랙잭       | 01/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/4.svg" width="20px" height="25px"></img> | [2231][2231] |       분해합       | 01/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [7568][7568] |        덩치        | 01/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [1018][1018] | 체스판 다시 칠하기 | 01/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [1436][1436] |    영화감독 숌     | 01/29 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 정렬

|                                         난이도                                         |      번호      |      이름       | 날짜  | 체크 |
| :------------------------------------------------------------------------------------: | :------------: | :-------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/5.svg" width="20px" height="25px"></img> |  [2750][2750]  |   수 정렬하기   | 01/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> |  [2751][2751]  |  수 정렬하기 2  | 01/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [10989][10989] |  수 정렬하기 3  | 01/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img> |  [2108][2108]  |     통계학      | 01/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> |  [1427][1427]  |  소트인사이드   | 01/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [11650][11650] |  좌표 정렬하기  | 01/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [11651][11651] | 좌표 정렬하기 2 | 01/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> |  [1181][1181]  |    단어 정렬    | 01/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img> | [10814][10814] |   나이순 정렬   | 01/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img> | [18870][18870] |    좌표 압축    | 01/30 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 백트래킹

|                                         난이도                                          |      번호      |      이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [15649][15649] |    N과 M (1)    | 01/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [15650][15650] |    N과 M (2)    | 01/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [15651][15651] |    N과 M (3)    | 01/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [15652][15652] |    N과 M (4)    | 01/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [9663][9663]  |     N-Queen     | 02/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [2580][2580]  |     스도쿠      | 02/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [14888][14888] | 연산자 끼워넣기 | 02/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [14889][14889] |  스타트와 링크  | 02/02 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 동적 계획법 1

|                                         난이도                                          |      번호      |            이름            | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1003][1003]  |       피보나치 함수        | 02/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [9184][9184]  |      신나는 함수 실행      | 02/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1904][1904]  |           01타일           | 02/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [9461][9461]  |        파도반 수열         | 02/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1149][1149]  |          RGB거리           | 02/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1932][1932]  |        정수 삼각형         | 02/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [2579][2579]  |        계단 오르기         | 02/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1463][1463]  |         1로 만들기         | 02/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [10844][10844] |        쉬운 계단 수        | 02/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [2156][2156]  |        포도주 시식         | 02/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [11053][11053] | 가장 긴 증가하는 부분 수열 | 02/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [11054][11054] | 가장 긴 바이토닉 부분 수열 | 02/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2565][2565]  |           전깃줄           | 02/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [9251][9251]  |            LCS             | 02/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [1912][1912]  |           연속합           | 02/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [12865][12865] |        평범한 배낭         | 02/11 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 그리디 알고리즘

|                                         난이도                                          |      번호      |     이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [11047][11047] |    동전 0     | 02/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1931][1931]  |  회의실 배정  | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [11399][11399] |      ATM      | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [1541][1541]  | 잃어버린 괄호 | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [13305][13305] |    주유소     | 02/12 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 정수론 및 조합론

|                                         난이도                                          |      번호      |          이름           | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :---------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/3.svg" width="20px" height="25px"></img>  |  [5086][5086]  |       배수와 약수       | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  |  [1037][1037]  |          약수           | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  |  [2609][2609]  | 최대공약수와 최소공배수 | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  |  [1934][1934]  |       최소공배수        | 02/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2981][2981]  |          검문           | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [3036][3036]  |           링            | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/5.svg" width="20px" height="25px"></img>  | [11050][11050] |       이항 계수 1       | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [11051][11051] |       이항 계수 2       | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  |  [1010][1010]  |        다리 놓기        | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [9375][9375]  |      패션왕 신해빈      | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  |  [1676][1676]  |    팩토리얼 0의 개수    | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [2004][2004]  |      조합 0의 개수      | 02/13 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 스택

|                                         난이도                                          |      번호      |     이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [10828][10828] |     스택      | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [10773][10773] |     제로      | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  |  [9012][9012]  |     괄호      | 02/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  |  [4949][4949]  | 균형잡힌 세상 | 02/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1874][1874]  |   스택 수열   | 02/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [17298][17298] |    오큰수     | 02/15 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 큐, 덱

|                                         난이도                                          |      번호      |      이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [18258][18258] |      큐 2       | 02/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  |  [2164][2164]  |      카드2      | 02/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [11866][11866] | 요세푸스 문제 0 | 02/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1966][1966]  |    프린터 큐    | 02/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [10866][10866] |       덱        | 02/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  |  [1021][1021]  |   회전하는 큐   | 02/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [5430][5430]  |       AC        | 02/18 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 분할 정복

|                                         난이도                                          |      번호      |              이름               | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [2630][2630]  |          색종이 만들기          | 02/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1992][1992]  |            쿼드트리             | 02/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [1780][1780]  |           종이의 개수           | 02/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1629][1629]  |              곱셈               | 02/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [11401][11401] |           이항 계수 3           | 02/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/5.svg" width="20px" height="25px"></img>  |  [2740][2740]  |            행렬 곱셈            | 02/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [10830][10830] |            행렬 제곱            | 02/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [11444][11444] |          피보나치 수 6          | 02/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [6549][6549]  | 히스토그램에서 가장 큰 직사각형 | 02/20 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 이분 탐색

|                                         난이도                                          |      번호      |             이름             | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  |  [1920][1920]  |           수 찾기            | 02/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/7.svg" width="20px" height="25px"></img>  | [10816][10816] |         숫자 카드 2          | 02/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [1654][1654]  |         랜선 자르기          | 02/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [2805][2805]  |         나무 자르기          | 02/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2110][2110]  |         공유기 설치          | 02/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [1300][1300]  |           K번째 수           | 02/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [12015][12015] | 가장 긴 증가하는 부분 수열 2 | 02/23 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 우선순위 큐

|                                         난이도                                          |      번호      |      이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [11279][11279] |     최대 힙     | 02/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  |  [1927][1927]  |     최소 힙     | 02/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [11286][11286] |    절댓값 힙    | 02/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [1655][1655]  | 가운데를 말해요 | 02/24 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 동적 계획법 2

|                                         난이도                                          |      번호      |      이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [11066][11066] |  파일 합치기   | 02/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [11049][11049] | 행렬 곱셈 순서 | 02/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1520][1520]  |   내리막 길    | 02/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [10942][10942] |   팰린드롬?    | 02/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2629][2629]  |    양팔저울    | 02/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2293][2293]  |     동전 1     | 02/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [7579][7579]  |       앱       | 03/01 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### DFS와 BFS

|                                         난이도                                          |     번호     |        이름        | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :----------: | :----------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [1260][1260] |     DFS와 BFS      | 03/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [2606][2606] |      바이러스      | 03/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [2667][2667] |   단지번호붙이기   | 03/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [1012][1012] |    유기농 배추     | 03/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [2178][2178] |     미로 탐색      | 03/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [7576][7576] |       토마토       | 03/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [7569][7569] |       토마토       | 03/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [1697][1697] |      숨바꼭질      | 03/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [2206][2206] | 벽 부수고 이동하기 | 03/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [7562][7562] |   나이트의 이동    | 03/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [1707][1707] |    이분 그래프     | 03/12 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 최단 경로

|                                         난이도                                          |      번호      |       이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1753][1753]  |     최단경로     | 03/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1504][1504]  | 특정한 최단 경로 | 03/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [9370][9370]  |  미확인 도착지   | 03/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [11657][11657] |     타임머신     | 03/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [11404][11404] |     플로이드     | 03/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [10217][10217] |    KCM Travel    | 03/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1956][1956]  |       운동       | 03/19 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 투 포인터

|                                         난이도                                          |     번호     |     이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :----------: | :-----------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [3273][3273] |  두 수의 합   | 03/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [2470][2470] |    두 용액    | 03/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [1806][1806] |    부분합     | 03/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [1644][1644] | 소수의 연속합 | 03/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [1450][1450] |   냅색문제    | 03/24 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 동적 계획법과 최단거리 역추적

|                                         난이도                                          |      번호      |             이름             | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> | [12852][12852] |         1로 만들기 2         | 03/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14002][14002] | 가장 긴 증가하는 부분 수열 4 | 03/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> | [14003][14003] | 가장 긴 증가하는 부분 수열 5 | 03/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [9252][9252]  |            LCS 2             | 03/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [2618][2618]  |            경찰차            | 03/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [13913][13913] |          숨바꼭질 4          | 03/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [9019][9019]  |             DSLR             | 03/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [11779][11779] |      최소비용 구하기 2       | 04/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [11780][11780] |          플로이드 2          | 04/02 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 트리

|                                         난이도                                          |      번호      |       이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/9.svg" width="20px" height="25px"></img>  | [11725][11725] | 트리의 부모 찾기 | 04/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1167][1167]  |   트리의 지름    | 04/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1967][1967]  |   트리의 지름    | 04/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/10.svg" width="20px" height="25px"></img> |  [1991][1991]  |    트리 순회     | 04/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [2263][2263]  |   트리의 순회    | 04/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [5639][5639]  |  이진 검색 트리  | 04/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [4803][4803]  |       트리       | 04/06 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 유니온 파인드

|                                         난이도                                          |      번호      |     이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1717][1717]  |  집합의 표현  | 04/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1976][1976]  |   여행 가자   | 04/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [4195][4195]  | 친구 네트워크 | 04/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [20040][20040] |  사이클 게임  | 04/10 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 최소 신장 트리

|                                         난이도                                          |      번호      |       이름       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  |  [9372][9372]  |  상근이의 여행   | 04/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1197][1197]  | 최소 스패닝 트리 | 04/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [4386][4386]  |  별자리 만들기   | 04/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1774][1774]  | 우주신과의 교감  | 04/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2887][2887]  |    행성 터널     | 04/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [17472][17472] |  다리 만들기 2   | 04/16 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 트리에서의 동적 계획법

|                                         난이도                                          |      번호      |        이름        | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :----------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [15681][15681] |    트리와 쿼리     | 04/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2213][2213]  |  트리의 독립집합   | 04/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2533][2533]  | 사회망 서비스(SNS) | 04/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [1949][1949]  |     우수 마을      | 04/20 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 기하

|                                         난이도                                          |      번호      |     이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2166][2166]  | 다각형의 면적 | 04/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [11758][11758] |      CCW      | 04/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [17386][17386] |  선분 교차 1  | 04/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [17387][17387] |  선분 교차 2  | 04/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> | [20149][20149] |  선분 교차 3  | 04/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [2162][2162]  |   선분 그룹   | 04/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [7869][7869]  |     두 원     | 04/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1069][1069]  |    집으로     | 04/28 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 동적 계획법 3

|                                         난이도                                          |      번호      |      이름      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/6.svg" width="20px" height="25px"></img>  | [11723][11723] |      집합      | 04/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [1311][1311]  | 할 일 정하기 1 | 04/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2098][2098]  |  외판원 순회   | 04/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [1086][1086]  |     박성원     | 05/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [17404][17404] |   RGB거리 2    | 05/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [2482][2482]  |     색상환     | 05/02 |  ✔   |

<div align=right>
 
[TOP](#algorithm)
 
</div>

---

### 문자열 알고리즘 1

|                                         난이도                                          |      번호      |    이름     | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :---------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [1786][1786]  |    찾기     | 05/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [4354][4354]  | 문자열 제곱 | 05/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [1305][1305]  |    광고     | 05/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> | [10266][10266] | 시계 사진들 | 05/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [14725][14725] |   개미굴    | 05/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/8.svg" width="20px" height="25px"></img>  | [14425][14425] | 문자열 집합 | 05/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [5670][5670]  | 휴대폰 자판 | 05/08 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 위상 정렬

|                                         난이도                                          |     번호     |   이름    | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :----------: | :-------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [2252][2252] | 줄 세우기 | 05/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [3665][3665] | 최종 순위 | 05/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [1766][1766] |  문제집   | 05/11 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 최소 공통 조상

|                                         난이도                                          |      번호      |         이름          | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [3584][3584]  | 가장 가까운 공통 조상 | 05/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [17435][17435] |    합성함수와 쿼리    | 05/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> | [11438][11438] |         LCA 2         | 05/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [3176][3176]  |     도로 네트워크     | 05/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/18.svg" width="20px" height="25px"></img> | [13511][13511] |     트리와 쿼리 2     | 05/16 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 강한 연결 요소

|                                         난이도                                          |      번호      |             이름             | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :--------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [2150][2150]  | Strongly Connected Component | 05/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [4196][4196]  |            도미노            | 05/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [3977][3977]  |          축구 전술           | 05/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/19.svg" width="20px" height="25px"></img> |  [4013][4013]  |             ATM              | 05/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> | [11280][11280] |          2-SAT - 3           | 05/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/18.svg" width="20px" height="25px"></img> | [11281][11281] |          2-SAT - 4           | 05/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [3648][3648]  |            아이돌            | 05/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/18.svg" width="20px" height="25px"></img> | [16367][16367] |         TV Show Game         | 05/24 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>

---

### 세그먼트 트리

|                                         난이도                                          |      번호      |            이름            | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :------------------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2042][2042]  |       구간 합 구하기       | 05/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [11505][11505] |       구간 곱 구하기       | 05/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2357][2357]  |      최솟값과 최댓값       | 05/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [1517][1517]  |         버블 소트          | 05/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/18.svg" width="20px" height="25px"></img> |  [9345][9345]  | 디지털 비디오 디스크(DVDs) | 05/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> | [16975][16975] |       수열과 쿼리 21       | 05/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> | [12899][12899] |        데이터 구조         | 05/31 |  ✔   |
| <img src="https://static.solved.ac/tier_small/17.svg" width="20px" height="25px"></img> |  [1168][1168]  |      요세푸스 문제 2       | 06/01 |  ✔   |

<div align=right>

[TOP](#algorithm)

</div>
<!-- ### -->

[2798]: https://www.acmicpc.net/problem/2798
[2231]: https://www.acmicpc.net/problem/2231
[7568]: https://www.acmicpc.net/problem/7568
[1018]: https://www.acmicpc.net/problem/1018
[1436]: https://www.acmicpc.net/problem/1436
[2750]: https://www.acmicpc.net/problem/2750
[2751]: https://www.acmicpc.net/problem/2751
[10989]: https://www.acmicpc.net/problem/10989
[2108]: https://www.acmicpc.net/problem/2108
[1427]: https://www.acmicpc.net/problem/1427
[11650]: https://www.acmicpc.net/problem/11650
[11651]: https://www.acmicpc.net/problem/11651
[1181]: https://www.acmicpc.net/problem/1181
[10814]: https://www.acmicpc.net/problem/10814
[18870]: https://www.acmicpc.net/problem/18870
[15649]: https://www.acmicpc.net/problem/15649
[15650]: https://www.acmicpc.net/problem/15650
[15651]: https://www.acmicpc.net/problem/15651
[15652]: https://www.acmicpc.net/problem/15652
[9663]: https://www.acmicpc.net/problem/9663
[2580]: https://www.acmicpc.net/problem/2580
[14888]: https://www.acmicpc.net/problem/14888
[14889]: https://www.acmicpc.net/problem/14889
[1003]: https://www.acmicpc.net/problem/1003
[9184]: https://www.acmicpc.net/problem/9184
[1904]: https://www.acmicpc.net/problem/1904
[9461]: https://www.acmicpc.net/problem/9461
[1149]: https://www.acmicpc.net/problem/1149
[1932]: https://www.acmicpc.net/problem/1932
[2579]: https://www.acmicpc.net/problem/2579
[1463]: https://www.acmicpc.net/problem/1463
[10844]: https://www.acmicpc.net/problem/10844
[2156]: https://www.acmicpc.net/problem/2156
[11053]: https://www.acmicpc.net/problem/11053
[11054]: https://www.acmicpc.net/problem/11054
[2565]: https://www.acmicpc.net/problem/2565
[9251]: https://www.acmicpc.net/problem/9251
[1912]: https://www.acmicpc.net/problem/1912
[12865]: https://www.acmicpc.net/problem/12865
[11047]: https://www.acmicpc.net/problem/11047
[1931]: https://www.acmicpc.net/problem/1931
[11399]: https://www.acmicpc.net/problem/11399
[1541]: https://www.acmicpc.net/problem/1541
[13305]: https://www.acmicpc.net/problem/13305
[5086]: https://www.acmicpc.net/problem/5086
[1037]: https://www.acmicpc.net/problem/1037
[2609]: https://www.acmicpc.net/problem/2609
[1934]: https://www.acmicpc.net/problem/1934
[2981]: https://www.acmicpc.net/problem/2981
[3036]: https://www.acmicpc.net/problem/3036
[11050]: https://www.acmicpc.net/problem/11050
[11051]: https://www.acmicpc.net/problem/11051
[1010]: https://www.acmicpc.net/problem/1010
[9375]: https://www.acmicpc.net/problem/9375
[1676]: https://www.acmicpc.net/problem/1676
[2004]: https://www.acmicpc.net/problem/2004
[10828]: https://www.acmicpc.net/problem/10828
[10773]: https://www.acmicpc.net/problem/10773
[9012]: https://www.acmicpc.net/problem/9012
[4949]: https://www.acmicpc.net/problem/4949
[1874]: https://www.acmicpc.net/problem/1874
[17298]: https://www.acmicpc.net/problem/17298
[18258]: https://www.acmicpc.net/problem/18258
[2164]: https://www.acmicpc.net/problem/2164
[11866]: https://www.acmicpc.net/problem/11866
[1966]: https://www.acmicpc.net/problem/1966
[10866]: https://www.acmicpc.net/problem/10866
[1021]: https://www.acmicpc.net/problem/1021
[5430]: https://www.acmicpc.net/problem/5430
[2630]: https://www.acmicpc.net/problem/2630
[1992]: https://www.acmicpc.net/problem/1992
[1780]: https://www.acmicpc.net/problem/1780
[1629]: https://www.acmicpc.net/problem/1629
[11401]: https://www.acmicpc.net/problem/11401
[2740]: https://www.acmicpc.net/problem/2740
[10830]: https://www.acmicpc.net/problem/10830
[11444]: https://www.acmicpc.net/problem/11444
[6549]: https://www.acmicpc.net/problem/6549
[1920]: https://www.acmicpc.net/problem/1920
[10816]: https://www.acmicpc.net/problem/10816
[1654]: https://www.acmicpc.net/problem/1654
[2805]: https://www.acmicpc.net/problem/2805
[2110]: https://www.acmicpc.net/problem/2110
[1300]: https://www.acmicpc.net/problem/1300
[12015]: https://www.acmicpc.net/problem/12015
[11279]: https://www.acmicpc.net/problem/11279
[1927]: https://www.acmicpc.net/problem/1927
[11286]: https://www.acmicpc.net/problem/11286
[1655]: https://www.acmicpc.net/problem/1655
[11066]: https://www.acmicpc.net/problem/11066
[11049]: https://www.acmicpc.net/problem/11049
[1520]: https://www.acmicpc.net/problem/1520
[10942]: https://www.acmicpc.net/problem/10942
[2629]: https://www.acmicpc.net/problem/2629
[2293]: https://www.acmicpc.net/problem/2293
[7579]: https://www.acmicpc.net/problem/7579
[1260]: https://www.acmicpc.net/problem/1260
[2606]: https://www.acmicpc.net/problem/2606
[2667]: https://www.acmicpc.net/problem/2667
[1012]: https://www.acmicpc.net/problem/1012
[2178]: https://www.acmicpc.net/problem/2178
[7576]: https://www.acmicpc.net/problem/7576
[7569]: https://www.acmicpc.net/problem/7569
[1697]: https://www.acmicpc.net/problem/1697
[2206]: https://www.acmicpc.net/problem/2206
[7562]: https://www.acmicpc.net/problem/7562
[1707]: https://www.acmicpc.net/problem/1707
[1753]: https://www.acmicpc.net/problem/1753
[1504]: https://www.acmicpc.net/problem/1504
[9370]: https://www.acmicpc.net/problem/9370
[11657]: https://www.acmicpc.net/problem/11657
[11404]: https://www.acmicpc.net/problem/11404
[10217]: https://www.acmicpc.net/problem/10217
[1956]: https://www.acmicpc.net/problem/1956
[3273]: https://www.acmicpc.net/problem/3273
[2470]: https://www.acmicpc.net/problem/2470
[1806]: https://www.acmicpc.net/problem/1806
[1644]: https://www.acmicpc.net/problem/1644
[1450]: https://www.acmicpc.net/problem/1450
[12852]: https://www.acmicpc.net/problem/12852
[14002]: https://www.acmicpc.net/problem/14002
[14003]: https://www.acmicpc.net/problem/14003
[9252]: https://www.acmicpc.net/problem/9252
[2618]: https://www.acmicpc.net/problem/2618
[13913]: https://www.acmicpc.net/problem/13913
[9019]: https://www.acmicpc.net/problem/9019
[11779]: https://www.acmicpc.net/problem/11779
[11780]: https://www.acmicpc.net/problem/11780
[11725]: https://www.acmicpc.net/problem/11725
[1167]: https://www.acmicpc.net/problem/1167
[1967]: https://www.acmicpc.net/problem/1967
[1991]: https://www.acmicpc.net/problem/1991
[2263]: https://www.acmicpc.net/problem/2263
[5639]: https://www.acmicpc.net/problem/5639
[4803]: https://www.acmicpc.net/problem/4803
[1717]: https://www.acmicpc.net/problem/1717
[1976]: https://www.acmicpc.net/problem/1976
[4195]: https://www.acmicpc.net/problem/4195
[20040]: https://www.acmicpc.net/problem/20040
[9372]: https://www.acmicpc.net/problem/9372
[1197]: https://www.acmicpc.net/problem/1197
[4386]: https://www.acmicpc.net/problem/4386
[1774]: https://www.acmicpc.net/problem/1774
[2887]: https://www.acmicpc.net/problem/2887
[17472]: https://www.acmicpc.net/problem/17472
[15681]: https://www.acmicpc.net/problem/15681
[2213]: https://www.acmicpc.net/problem/2213
[2533]: https://www.acmicpc.net/problem/2533
[1949]: https://www.acmicpc.net/problem/1949
[2166]: https://www.acmicpc.net/problem/2166
[11758]: https://www.acmicpc.net/problem/11758
[17386]: https://www.acmicpc.net/problem/17386
[17387]: https://www.acmicpc.net/problem/17387
[20149]: https://www.acmicpc.net/problem/20149
[2162]: https://www.acmicpc.net/problem/2162
[7869]: https://www.acmicpc.net/problem/7869
[1069]: https://www.acmicpc.net/problem/1069
[11723]: https://www.acmicpc.net/problem/11723
[1311]: https://www.acmicpc.net/problem/1311
[2098]: https://www.acmicpc.net/problem/2098
[1086]: https://www.acmicpc.net/problem/1086
[17404]: https://www.acmicpc.net/problem/17404
[2482]: https://www.acmicpc.net/problem/2482
[1786]: https://www.acmicpc.net/problem/1786
[4354]: https://www.acmicpc.net/problem/4354
[1305]: https://www.acmicpc.net/problem/1305
[10266]: https://www.acmicpc.net/problem/10266
[14725]: https://www.acmicpc.net/problem/14725
[14425]: https://www.acmicpc.net/problem/14425
[5670]: https://www.acmicpc.net/problem/5670
[2252]: https://www.acmicpc.net/problem/2252
[3665]: https://www.acmicpc.net/problem/3665
[1766]: https://www.acmicpc.net/problem/1766
[3584]: https://www.acmicpc.net/problem/3584
[17435]: https://www.acmicpc.net/problem/17435
[11438]: https://www.acmicpc.net/problem/11438
[3176]: https://www.acmicpc.net/problem/3176
[13511]: https://www.acmicpc.net/problem/13511
[2150]: https://www.acmicpc.net/problem/2150
[4196]: https://www.acmicpc.net/problem/4196
[3977]: https://www.acmicpc.net/problem/3977
[4013]: https://www.acmicpc.net/problem/4013
[11280]: https://www.acmicpc.net/problem/11280
[11281]: https://www.acmicpc.net/problem/11281
[3648]: https://www.acmicpc.net/problem/3648
[16367]: https://www.acmicpc.net/problem/16367
[2042]: https://www.acmicpc.net/problem/2042
[11505]: https://www.acmicpc.net/problem/11505
[2357]: https://www.acmicpc.net/problem/2357
[1517]: https://www.acmicpc.net/problem/1517
[9345]: https://www.acmicpc.net/problem/9345
[16975]: https://www.acmicpc.net/problem/16975
[12899]: https://www.acmicpc.net/problem/12899
[1168]: https://www.acmicpc.net/problem/1168

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/06/02 ~ 2022/06/30</strong></summary>

<br>

<div align="center">

|                                         난이도                                          |      번호      |        이름        |       분류       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :----------------: | :--------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [14503][14503] |    로봇 청소기     |       구현       | 06/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2550][2550]  |        전구        |        DP        | 06/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1107][1107]  |       리모컨       |    브루트포스    | 06/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [2133][2133]  |    타일 채우기     |        DP        | 06/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [7868][7868]  |     해밍 수열      |    브루트포스    | 06/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1041][1041]  |       주사위       |      그리디      | 06/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [16954][16954] | 움직이는 미로 탈출 |       BFS        | 06/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [12869][12869] |     뮤탈리스크     |        DP        | 06/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [3055][3055]  |        탈출        |       BFS        | 06/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [16929][16929] |      Two Dots      |       DFS        | 06/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2230][2230]  |     수 고르기      |    투 포인터     | 06/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [3661][3661]  |     생일 선물      |      그리디      | 06/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [14852][14852] |   타일 채우기 3    |        DP        | 06/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1354][1354]  |    무한 수열 2     |        DP        | 06/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1759][1759]  |    암호 만들기     |    브루트포스    | 06/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [10993][10993] |    별 찍기 - 18    |       재귀       | 06/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1261][1261]  |      알고스팟      |    다익스트라    | 06/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [23843][23843] |       콘센트       |      그리디      | 06/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2812][2812]  |    크게 만들기     |      그리디      | 06/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [5014][5014]  |     스타트링크     |       BFS        | 06/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [1365][1365]  |    꼬인 전깃줄     |    이분 탐색     | 06/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [23296][23296] |  엘리베이터 조작   |    위상 정렬     | 06/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [14262][14262] |    그림 그리기     |       구현       | 06/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [13023][13023] |       ABCDE        |       DFS        | 06/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [21924][21924] |     도시 건설      | 최소 스패닝 트리 | 06/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1240][1240]  |  노드사이의 거리   |       BFS        | 06/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [10422][10422] |        괄호        |      조합론      | 06/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [24463][24463] |        미로        |       DFS        | 06/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [22867][22867] |        종점        |      스위핑      | 06/30 |  ✔   |

[14503]: https://www.acmicpc.net/problem/14503
[2550]: https://www.acmicpc.net/problem/2550
[1107]: https://www.acmicpc.net/problem/1107
[2133]: https://www.acmicpc.net/problem/2133
[7868]: https://www.acmicpc.net/problem/7868
[1041]: https://www.acmicpc.net/problem/1041
[16954]: https://www.acmicpc.net/problem/16954
[12869]: https://www.acmicpc.net/problem/12869
[3055]: https://www.acmicpc.net/problem/3055
[16929]: https://www.acmicpc.net/problem/16929
[2230]: https://www.acmicpc.net/problem/2230
[3661]: https://www.acmicpc.net/problem/3661
[14852]: https://www.acmicpc.net/problem/14852
[1354]: https://www.acmicpc.net/problem/1354
[1759]: https://www.acmicpc.net/problem/1759
[10993]: https://www.acmicpc.net/problem/10993
[1261]: https://www.acmicpc.net/problem/1261
[23843]: https://www.acmicpc.net/problem/23843
[2812]: https://www.acmicpc.net/problem/2812
[5014]: https://www.acmicpc.net/problem/5014
[1365]: https://www.acmicpc.net/problem/1365
[23296]: https://www.acmicpc.net/problem/23296
[14262]: https://www.acmicpc.net/problem/14262
[13023]: https://www.acmicpc.net/problem/13023
[21924]: https://www.acmicpc.net/problem/21924
[1240]: https://www.acmicpc.net/problem/1240
[10422]: https://www.acmicpc.net/problem/10422
[24463]: https://www.acmicpc.net/problem/24463
[22867]: https://www.acmicpc.net/problem/22867

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/07/01 ~ 2022/07/31</strong></summary>

<br>

<div align="center">

|                                         난이도                                          |      번호      |            이름            |      분류      | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :------------------------: | :------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2170][2170]  |          선 긋기           |     스위핑     | 07/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [9997][9997]  |            폰트            |   비트마스크   | 07/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [15831][15831] |       준표의 조약돌        |   투 포인터    | 07/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1501][1501]  |         영어 읽기          |      해시      | 07/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [24391][24391] |       귀찮은 해강이        | 유니온 파인드  | 07/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [15553][15553] |            난로            |     그리디     | 07/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2251][2251]  |            물통            |      BFS       | 07/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [13398][13398] |          연속합 2          |       DP       | 07/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2528][2528]  |           사다리           |      구현      | 07/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1516][1516]  |         게임 개발          |   위상 정렬    | 07/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [6087][6087]  |        레이저 통신         |   다익스트라   | 07/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14466][14466] |  소가 길을 건너간 이유 6   |      BFS       | 07/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [12896][12896] |       스크루지 민호        |      트리      | 07/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [13460][13460] |        구슬 탈출 2         |      구현      | 07/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [12100][12100] |        2048 (Easy)         |      구현      | 07/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [3190][3190]  |             뱀             |      구현      | 07/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2065][2065]  |           나룻배           |      구현      | 07/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14499][14499] |       주사위 굴리기        |      구현      | 07/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [13334][13334] |            철로            |     스위핑     | 07/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2836][2836]  |         수상 택시          |     스위핑     | 07/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> | [14428][14428] |       수열과 쿼리 16       | 세그먼트 트리  | 07/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> |  [1761][1761]  |       정점들의 거리        | 최소 공통 조상 | 07/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1865][1865]  |            웜홀            |   벨만 포드    | 07/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [7511][7511]  | 소셜 네트워킹 어플리케이션 | 유니온 파인드  | 07/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1245][1245]  |         농장 관리          |      DFS       | 07/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1106][1106]  |            호텔            |       DP       | 07/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [18116][18116] |         로봇 조립          | 유니온 파인드  | 07/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [3109][3109]  |            빵집            |      DFS       | 07/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1043][1043]  |           거짓말           | 유니온 파인드  | 07/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [10711][10711] |           모래성           |      BFS       | 07/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1744][1744]  |          수 묶기           |     그리디     | 07/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [14567][14567] |  선수과목 (Prerequisite)   |   위상 정렬    | 07/31 |  ✔   |

[2170]: https://www.acmicpc.net/problem/2170
[9997]: https://www.acmicpc.net/problem/9997
[15831]: https://www.acmicpc.net/problem/15831
[1501]: https://www.acmicpc.net/problem/1501
[24391]: https://www.acmicpc.net/problem/24391
[15553]: https://www.acmicpc.net/problem/15553
[2251]: https://www.acmicpc.net/problem/2251
[13398]: https://www.acmicpc.net/problem/13398
[2528]: https://www.acmicpc.net/problem/2528
[1516]: https://www.acmicpc.net/problem/1516
[6087]: https://www.acmicpc.net/problem/6087
[14466]: https://www.acmicpc.net/problem/14466
[12896]: https://www.acmicpc.net/problem/12896
[13460]: https://www.acmicpc.net/problem/13460
[12100]: https://www.acmicpc.net/problem/12100
[3190]: https://www.acmicpc.net/problem/3190
[2065]: https://www.acmicpc.net/problem/2065
[14499]: https://www.acmicpc.net/problem/14499
[13334]: https://www.acmicpc.net/problem/13334
[2836]: https://www.acmicpc.net/problem/2836
[14428]: https://www.acmicpc.net/problem/14428
[1761]: https://www.acmicpc.net/problem/1761
[1865]: https://www.acmicpc.net/problem/1865
[7511]: https://www.acmicpc.net/problem/7511
[1245]: https://www.acmicpc.net/problem/1245
[1106]: https://www.acmicpc.net/problem/1106
[18116]: https://www.acmicpc.net/problem/18116
[3109]: https://www.acmicpc.net/problem/3109
[1043]: https://www.acmicpc.net/problem/1043
[10711]: https://www.acmicpc.net/problem/10711
[1744]: https://www.acmicpc.net/problem/1744
[14567]: https://www.acmicpc.net/problem/14567

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/08/01 ~ 2022/08/31</strong></summary>

<br>

<div align="center">

|                                         난이도                                          |      번호      |           이름            |      분류       | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :-----------------------: | :-------------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [3078][3078]  |         좋은 친구         | 슬라이딩 윈도우 | 08/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [15723][15723] |         n단 논법          |  플로이드 워셜  | 08/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [18231][18231] |        파괴된 도시        |     그리디      | 08/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14267][14267] |        회사 문화 1        |       DP        | 08/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2096][2096]  |         내려가기          | 슬라이딩 윈도우 | 08/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [15703][15703] |        주사위 쌓기        |     그리디      | 08/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [17265][17265] | 나의 인생에는 수학과 함께 |       BFS       | 08/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1013][1013]  |          Contact          |     정규식      | 08/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [11056][11056] |      두 부분 문자열       |       DP        | 08/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [23294][23294] |       웹 브라우저 1       |      구현       | 08/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [4781][4781]  |         사탕 가게         |       DP        | 08/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [15573][15573] |           채굴            |       BFS       | 08/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [6068][6068]  |       시간 관리하기       |     그리디      | 08/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [11509][11509] |        풍선 맞추기        |     그리디      | 08/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [16197][16197] |          두 동전          |       BFS       | 08/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [16120][16120] |           PPAP            |     그리디      | 08/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [23793][23793] |    두 단계 최단 경로 1    |   다익스트라    | 08/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [17433][17433] |        신비로운 수        |     정수론      | 08/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [2327][2327]  |          말아톤           |       DP        | 08/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2143][2143]  |       두 배열의 합        |    이분 탐색    | 08/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2467][2467]  |           용액            |    이분 탐색    | 08/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> | [14948][14948] |       군대탈출하기        |       BFS       | 08/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [9084][9084]  |           동전            |       DP        | 08/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [5052][5052]  |       전화번호 목록       |     트라이      | 08/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1953][1953]  |          팀배분           |       DFS       | 08/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2310][2310]  |       어드벤처 게임       |       DFS       | 08/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [9944][9944]  |     NxM 보드 완주하기     |    백트래킹     | 08/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [17070][17070] |      파이프 옮기기 1      |       DP        | 08/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1584][1584]  |           게임            |     0-1 BFS     | 08/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [17396][17396] |          백도어           |   다익스트라    | 08/30 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2294][2294]  |          동전 2           |       DP        | 08/31 |  ✔   |

[3078]: https://www.acmicpc.net/problem/3078
[15723]: https://www.acmicpc.net/problem/15723
[18231]: https://www.acmicpc.net/problem/18231
[14267]: https://www.acmicpc.net/problem/14267
[2096]: https://www.acmicpc.net/problem/2096
[15703]: https://www.acmicpc.net/problem/15703
[17265]: https://www.acmicpc.net/problem/17265
[1013]: https://www.acmicpc.net/problem/1013
[11056]: https://www.acmicpc.net/problem/11056
[23294]: https://www.acmicpc.net/problem/23294
[4781]: https://www.acmicpc.net/problem/4781
[15573]: https://www.acmicpc.net/problem/15573
[6068]: https://www.acmicpc.net/problem/6068
[11509]: https://www.acmicpc.net/problem/11509
[16197]: https://www.acmicpc.net/problem/16197
[16120]: https://www.acmicpc.net/problem/16120
[23793]: https://www.acmicpc.net/problem/23793
[17433]: https://www.acmicpc.net/problem/17433
[2327]: https://www.acmicpc.net/problem/2327
[2143]: https://www.acmicpc.net/problem/2143
[2467]: https://www.acmicpc.net/problem/2467
[14948]: https://www.acmicpc.net/problem/14948
[9084]: https://www.acmicpc.net/problem/9084
[5052]: https://www.acmicpc.net/problem/5052
[1953]: https://www.acmicpc.net/problem/1953
[2310]: https://www.acmicpc.net/problem/2310
[9944]: https://www.acmicpc.net/problem/9944
[17070]: https://www.acmicpc.net/problem/17070
[1584]: https://www.acmicpc.net/problem/1584
[17396]: https://www.acmicpc.net/problem/17396
[2294]: https://www.acmicpc.net/problem/2294

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/09/01 ~ 2022/09/30</strong></summary>

<br>

<div align="center">

|                                         난이도                                          |      번호      |           이름           |    분류    | 날짜  | 체크 |
| :-------------------------------------------------------------------------------------: | :------------: | :----------------------: | :--------: | :---: | :--: |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1963][1963]  |        소수 경로         |    BFS     | 09/01 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [11909][11909] |        배열 탈출         |     DP     | 09/02 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2023][2023]  |       신기한 소수        |  백트래킹  | 09/03 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1689][1689]  |       겹치는 선분        |   스위핑   | 09/04 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2011][2011]  |         암호코드         |     DP     | 09/05 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [18188][18188] |      다오의 데이트       |    BFS     | 09/06 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [3649][3649]  |      로봇 프로젝트       | 투 포인터  | 09/07 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [12429][12429] |      생존자 (Small)      |     DP     | 09/08 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [22944][22944] |        죽음의 비         |    BFS     | 09/09 |  ✔   |
| <img src="https://static.solved.ac/tier_small/16.svg" width="20px" height="25px"></img> | [12430][12430] |      생존자 (Large)      |   비트셋   | 09/10 |  ✔   |
| <img src="https://static.solved.ac/tier_small/21.svg" width="20px" height="25px"></img> | [18185][18185] |    라면 사기 (Small)     |   그리디   | 09/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/22.svg" width="20px" height="25px"></img> | [18186][18186] |    라면 사기 (Large)     |   그리디   | 09/11 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [17141][17141] |         연구소 2         |    BFS     | 09/12 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [1916][1916]  |     최소비용 구하기      | 다익스트라 | 09/13 |  ✔   |
| <img src="https://static.solved.ac/tier_small/15.svg" width="20px" height="25px"></img> |  [2718][2718]  |       타일 채우기        |     DP     | 09/14 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [2437][2437]  |           저울           |   그리디   | 09/15 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14722][14722] |        우유 도시         |     DP     | 09/16 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> |  [1005][1005]  |        ACM Craft         | 위상 정렬  | 09/17 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [14502][14502] |          연구소          |    BFS     | 09/18 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [16397][16397] |           탈출           |    BFS     | 09/19 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [23740][23740] |    버스 노선 개편하기    |   스위핑   | 09/20 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [23254][23254] | 나는 기말고사형 인간이야 |   그리디   | 09/21 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> |  [1720][1720]  |        타일 코드         |     DP     | 09/22 |  ✔   |
| <img src="https://static.solved.ac/tier_small/14.svg" width="20px" height="25px"></img> |  [1918][1918]  |       후위 표기식        |    스택    | 09/23 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [20035][20035] |        이동하기 5        |   그리디   | 09/24 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2056][2056]  |           작업           |     DP     | 09/25 |  ✔   |
| <img src="https://static.solved.ac/tier_small/12.svg" width="20px" height="25px"></img> | [12851][12851] |        숨바꼭질 2        |    BFS     | 09/26 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> | [14677][14677] |       병약한 윤호        |     DP     | 09/27 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [2174][2174]  |     로봇 시뮬레이션      |    구현    | 09/28 |  ✔   |
| <img src="https://static.solved.ac/tier_small/13.svg" width="20px" height="25px"></img> | [18235][18235] |    지금 만나러 갑니다    |    BFS     | 09/29 |  ✔   |
| <img src="https://static.solved.ac/tier_small/11.svg" width="20px" height="25px"></img> |  [5582][5582]  |     공통 부분 문자열     |     DP     | 09/30 |  ✔   |

[1963]: https://www.acmicpc.net/problem/1963
[11909]: https://www.acmicpc.net/problem/11909
[2023]: https://www.acmicpc.net/problem/2023
[1689]: https://www.acmicpc.net/problem/1689
[2011]: https://www.acmicpc.net/problem/2011
[18188]: https://www.acmicpc.net/problem/18188
[3649]: https://www.acmicpc.net/problem/3649
[12429]: https://www.acmicpc.net/problem/12429
[22944]: https://www.acmicpc.net/problem/22944
[12430]: https://www.acmicpc.net/problem/12430
[18185]: https://www.acmicpc.net/problem/18185
[18186]: https://www.acmicpc.net/problem/18186
[17141]: https://www.acmicpc.net/problem/17141
[1916]: https://www.acmicpc.net/problem/1916
[2718]: https://www.acmicpc.net/problem/2718
[2437]: https://www.acmicpc.net/problem/2437
[14722]: https://www.acmicpc.net/problem/14722
[1005]: https://www.acmicpc.net/problem/1005
[14502]: https://www.acmicpc.net/problem/14502
[16397]: https://www.acmicpc.net/problem/16397
[23740]: https://www.acmicpc.net/problem/23740
[23254]: https://www.acmicpc.net/problem/23254
[1720]: https://www.acmicpc.net/problem/1720
[1918]: https://www.acmicpc.net/problem/1918
[20035]: https://www.acmicpc.net/problem/20035
[2056]: https://www.acmicpc.net/problem/2056
[12851]: https://www.acmicpc.net/problem/12851
[14677]: https://www.acmicpc.net/problem/14677
[2174]: https://www.acmicpc.net/problem/2174
[18235]: https://www.acmicpc.net/problem/18235
[5582]: https://www.acmicpc.net/problem/5582

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/10/01 ~ 2022/10/31</strong></summary>

<br>

<div align="center">

| 난이도 |          링크           |       이름        |       분류       | 날짜  | 체크 |
| :----: | :---------------------: | :---------------: | :--------------: | :---: | :--: |
| Lv. 3  | [프로그래머스][43105p]  |    정수 삼각형    |        DP        | 10/01 |  ✔   |
| Lv. 3  | [프로그래머스][42884p]  |    단속카메라     |      스위핑      | 10/02 |  ✔   |
| Lv. 3  | [프로그래머스][43162p]  |     네트워크      |       BFS        | 10/03 |  ✔   |
| Lv. 3  | [프로그래머스][64064p]  |    불량 사용자    |    브루트포스    | 10/04 |  ✔   |
| Lv. 3  | [프로그래머스][43163p]  |     단어 변환     |       BFS        | 10/05 |  ✔   |
| Lv. 3  | [프로그래머스][42628p]  |  이중우선순위큐   |        힙        | 10/06 |  ✔   |
| Lv. 3  | [프로그래머스][12938p]  |    최고의 집합    |      그리디      | 10/07 |  ✔   |
| Lv. 3  | [프로그래머스][42898p]  |      등굣길       |        DP        | 10/08 |  ✔   |
| Lv. 3  | [프로그래머스][49191p]  |       순위        |      그래프      | 10/09 |  ✔   |
| Lv. 3  | [프로그래머스][12927p]  |     야근 지수     |      그리디      | 10/10 |  ✔   |
| Lv. 3  | [프로그래머스][42579p]  |    베스트앨범     |       해시       | 10/11 |  ✔   |
| Lv. 3  | [프로그래머스][49189p]  |   가장 먼 노드    |       BFS        | 10/12 |  ✔   |
| Lv. 3  | [프로그래머스][12987p]  |     숫자 게임     |      그리디      | 10/13 |  ✔   |
| Lv. 3  | [프로그래머스][12907p]  |     거스름돈      |        DP        | 10/14 |  ✔   |
| Lv. 3  | [프로그래머스][12904p]  | 가장 긴 팰린드롬  |    브루트포스    | 10/15 |  ✔   |
| Lv. 3  | [프로그래머스][118669p] |  등산코스 정하기  |    다익스트라    | 10/16 |  ✔   |
| Lv. 3  | [프로그래머스][12979p]  |    기지국 설치    |      스위핑      | 10/17 |  ✔   |
| Lv. 3  | [프로그래머스][77886p]  |    110 옮기기     |      그리디      | 10/18 |  ✔   |
| Lv. 3  | [프로그래머스][42895p]  |    N으로 표현     |        DP        | 10/19 |  ✔   |
| Lv. 3  | [프로그래머스][76503p]  | 모두 0으로 만들기 |    위상 정렬     | 10/20 |  ✔   |
| Lv. 3  | [프로그래머스][70130p]  |     스타 수열     |      그리디      | 10/21 |  ✔   |
| Lv. 3  | [프로그래머스][77486p]  | 다단계 칫솔 판매  |       DFS        | 10/22 |  ✔   |
| Lv. 3  | [프로그래머스][43164p]  |     여행경로      |       DFS        | 10/23 |  ✔   |
| Lv. 3  | [프로그래머스][92343p]  |     양과 늑대     |       트리       | 10/24 |  ✔   |
| Lv. 3  | [프로그래머스][132266p] |     부대복귀      |       BFS        | 10/25 |  ✔   |
| Lv. 4  | [프로그래머스][42897p]  |      도둑질       |        DP        | 10/26 |  ✔   |
| Lv. 3  | [프로그래머스][42861p]  |    섬 연결하기    | 최소 스패닝 트리 | 10/27 |  ✔   |
| Lv. 3  | [프로그래머스][68646p]  |   풍선 터트리기   |      그리디      | 10/28 |  ✔   |
| Lv. 3  | [프로그래머스][42627p]  |  디스크 컨트롤러  |        힙        | 10/29 |  ✔   |
| Lv. 3  | [프로그래머스][12971p]  | 스티커 모으기(2)  |        DP        | 10/30 |  ✔   |
| Lv. 3  | [프로그래머스][72413p]  |  합승 택시 요금   |  플로이드 워셜   | 10/31 |  ✔   |

[43105p]: https://school.programmers.co.kr/learn/courses/30/lessons/43105
[42884p]: https://school.programmers.co.kr/learn/courses/30/lessons/42884
[43162p]: https://school.programmers.co.kr/learn/courses/30/lessons/43162
[64064p]: https://school.programmers.co.kr/learn/courses/30/lessons/64064
[43163p]: https://school.programmers.co.kr/learn/courses/30/lessons/43163
[42628p]: https://school.programmers.co.kr/learn/courses/30/lessons/42628
[12938p]: https://school.programmers.co.kr/learn/courses/30/lessons/12938
[42898p]: https://school.programmers.co.kr/learn/courses/30/lessons/42898
[49191p]: https://school.programmers.co.kr/learn/courses/30/lessons/49191
[12927p]: https://school.programmers.co.kr/learn/courses/30/lessons/12927
[42579p]: https://school.programmers.co.kr/learn/courses/30/lessons/42579
[49189p]: https://school.programmers.co.kr/learn/courses/30/lessons/49189
[12987p]: https://school.programmers.co.kr/learn/courses/30/lessons/12987
[12907p]: https://school.programmers.co.kr/learn/courses/30/lessons/12907
[12904p]: https://school.programmers.co.kr/learn/courses/30/lessons/12904
[118669p]: https://school.programmers.co.kr/learn/courses/30/lessons/118669
[12979p]: https://school.programmers.co.kr/learn/courses/30/lessons/12979
[77886p]: https://school.programmers.co.kr/learn/courses/30/lessons/77886
[42895p]: https://school.programmers.co.kr/learn/courses/30/lessons/42895
[76503p]: https://school.programmers.co.kr/learn/courses/30/lessons/76503
[70130p]: https://school.programmers.co.kr/learn/courses/30/lessons/70130
[77486p]: https://school.programmers.co.kr/learn/courses/30/lessons/77486
[43164p]: https://school.programmers.co.kr/learn/courses/30/lessons/43164
[92343p]: https://school.programmers.co.kr/learn/courses/30/lessons/92343
[132266p]: https://school.programmers.co.kr/learn/courses/30/lessons/132266
[42897p]: https://school.programmers.co.kr/learn/courses/30/lessons/42897
[42861p]: https://school.programmers.co.kr/learn/courses/30/lessons/42861
[68646p]: https://school.programmers.co.kr/learn/courses/30/lessons/68646
[42627p]: https://school.programmers.co.kr/learn/courses/30/lessons/42627
[12971p]: https://school.programmers.co.kr/learn/courses/30/lessons/12971
[72413p]: https://school.programmers.co.kr/learn/courses/30/lessons/72413

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/11/01 ~ 2022/11/31</strong></summary>

<br>

<div align="center">

| 난이도 |          링크          |                  이름                   |     분류      | 날짜  | 체크 |
| :----: | :--------------------: | :-------------------------------------: | :-----------: | :---: | :--: |
| Lv. 3  | [프로그래머스][67258p] |                보석 쇼핑                |    그리디     | 11/01 |  ✔   |
| Lv. 3  | [프로그래머스][64062p] |             징검다리 건너기             |   이분 탐색   | 11/02 |  ✔   |
| Lv. 3  | [프로그래머스][43238p] |                입국심사                 |   이분 탐색   | 11/03 |  ✔   |
| Lv. 4  | [프로그래머스][43236p] |                징검다리                 |   이분 탐색   | 11/04 |  ✔   |
| Lv. 3  | [프로그래머스][67259p] |               경주로 건설               |      BFS      | 11/05 |  ✔   |
| Lv. 3  | [프로그래머스][17678p] |             [1차] 셔틀버스              |     구현      | 11/06 |  ✔   |
| Lv. 3  | [프로그래머스][81303p] |                 표 편집                 |     구현      | 11/07 |  ✔   |
| Lv. 2  | [프로그래머스][42577p] |              전화번호 목록              |     해시      | 11/08 |  ✔   |
| Lv. 2  | [프로그래머스][12909p] |               올바른 괄호               |     스택      | 11/08 |  ✔   |
| Lv. 2  | [프로그래머스][42586p] |                기능개발                 |    그리디     | 11/08 |  ✔   |
| Lv. 2  | [프로그래머스][42587p] |                 프린터                  |      큐       | 11/09 |  ✔   |
| Lv. 2  | [프로그래머스][42583p] |           다리를 지나는 트럭            |      큐       | 11/09 |  ✔   |
| Lv. 2  | [프로그래머스][42584p] |                주식가격                 |     스택      | 11/09 |  ✔   |
| Lv. 2  | [프로그래머스][42839p] |                소수 찾기                |  브루트포스   | 11/10 |  ✔   |
| Lv. 2  | [프로그래머스][87946p] |                 피로도                  |  브루트포스   | 11/10 |  ✔   |
| Lv. 2  | [프로그래머스][86971p] |          전력망을 둘로 나누기           |  브루트포스   | 11/10 |  ✔   |
| Lv. 2  | [프로그래머스][84512p] |                모음 사전                |  브루트포스   | 11/11 |  ✔   |
| Lv. 2  | [프로그래머스][42885p] |                구명보트                 |    그리디     | 11/11 |  ✔   |
| Lv. 2  | [프로그래머스][1844p]  |            게임 맵 최단거리             |      BFS      | 11/12 |  ✔   |
| Lv. 2  | [프로그래머스][42860p] |                조이스틱                 |  브루트포스   | 11/12 |  ✔   |
| Lv. 3  | [프로그래머스][87694p] |               아이템 줍기               |      BFS      | 11/13 |  ✔   |
| Lv. 4  | [프로그래머스][1843p]  |                사칙연산                 |      DP       | 11/14 |  ✔   |
| Medium |     [리트코드][2l]     |           2. Add Two Numbers            |  Linked List  | 11/15 |  ✔   |
| Medium |    [리트코드][54l]     |            54. Spiral Matrix            |  Simulation   | 11/16 |  ✔   |
| Medium |    [리트코드][15l]     |                15. 3Sum                 |     Hash      | 11/17 |  ✔   |
| Medium |    [리트코드][19l]     | 19. Remove Nth Node<br>From End of List |  Linked List  | 11/18 |  ✔   |
| Medium |    [리트코드][50l]     |              50. Pow(x, n)              |   Recursion   | 11/19 |  ✔   |
| Medium |    [리트코드][74l]     |         74. Search a 2D Matrix          | Binary Search | 11/20 |  ✔   |
| Medium |    [리트코드][73l]     |          73. Set Matrix Zeroes          |     Array     | 11/21 |  ✔   |
| Medium |    [리트코드][49l]     |           49. Group Anagrams            |     Hash      | 11/22 |  ✔   |
| Medium |    [리트코드][334l]    |   334. Increasing Triplet Subsequence   |    Greedy     | 11/23 |  ✔   |
| Medium |    [리트코드][38l]     |            38. Count and Say            |   Recursion   | 11/24 |  ✔   |
| Medium |    [리트코드][55l]     |              55. Jump Game              |      DP       | 11/25 |  ✔   |
| Medium |    [리트코드][75l]     |             75. Sort Colors             |    Sorting    | 11/26 |  ✔   |
| Medium |    [리트코드][75l]     |            62. Unique Paths             |      DP       | 11/27 |  ✔   |
| Medium |    [리트코드][322l]    |            322. Coin Change             |      DP       | 11/28 |  ✔   |
| Medium |    [리트코드][347l]    |      347. Top K Frequent Elements       |    Sorting    | 11/29 |  ✔   |
| Medium |    [리트코드][56l]     |           56. Merge Intervals           | Two Pointers  | 11/30 |  ✔   |

[67258p]: https://school.programmers.co.kr/learn/courses/30/lessons/67258
[64062p]: https://school.programmers.co.kr/learn/courses/30/lessons/64062
[43238p]: https://school.programmers.co.kr/learn/courses/30/lessons/43238
[43236p]: https://school.programmers.co.kr/learn/courses/30/lessons/43236
[67259p]: https://school.programmers.co.kr/learn/courses/30/lessons/67259
[17678p]: https://school.programmers.co.kr/learn/courses/30/lessons/17678
[81303p]: https://school.programmers.co.kr/learn/courses/30/lessons/81303
[42577p]: https://school.programmers.co.kr/learn/courses/30/lessons/42577
[12909p]: https://school.programmers.co.kr/learn/courses/30/lessons/12909
[42586p]: https://school.programmers.co.kr/learn/courses/30/lessons/42586
[42587p]: https://school.programmers.co.kr/learn/courses/30/lessons/42587
[42583p]: https://school.programmers.co.kr/learn/courses/30/lessons/42583
[42584p]: https://school.programmers.co.kr/learn/courses/30/lessons/42584
[42839p]: https://school.programmers.co.kr/learn/courses/30/lessons/42839
[87946p]: https://school.programmers.co.kr/learn/courses/30/lessons/87946
[86971p]: https://school.programmers.co.kr/learn/courses/30/lessons/86971
[84512p]: https://school.programmers.co.kr/learn/courses/30/lessons/84512
[42885p]: https://school.programmers.co.kr/learn/courses/30/lessons/42885
[1844p]: https://school.programmers.co.kr/learn/courses/30/lessons/1844
[42860p]: https://school.programmers.co.kr/learn/courses/30/lessons/42860
[87694p]: https://school.programmers.co.kr/learn/courses/30/lessons/87694
[1843p]: https://school.programmers.co.kr/learn/courses/30/lessons/1843
[2l]: https://leetcode.com/problems/add-two-numbers
[54l]: https://leetcode.com/problems/spiral-matrix
[15l]: https://leetcode.com/problems/3sum
[19l]: https://leetcode.com/problems/remove-nth-node-from-end-of-list
[50l]: https://leetcode.com/problems/powx-n
[74l]: https://leetcode.com/problems/search-a-2d-matrix
[73l]: https://leetcode.com/problems/set-matrix-zeroes
[49l]: https://leetcode.com/problems/group-anagrams
[334l]: https://leetcode.com/problems/increasing-triplet-subsequence
[38l]: https://leetcode.com/problems/count-and-say
[55l]: https://leetcode.com/problems/jump-game
[75l]: https://leetcode.com/problems/sort-colors
[322l]: https://leetcode.com/problems/coin-change
[347l]: https://leetcode.com/problems/top-k-frequent-elements
[56l]: https://leetcode.com/problems/merge-intervals

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2022/12/01 ~ 2022/12/31</strong></summary>

<br>

<div align="center">

| 난이도 |          링크          |                              이름                              |       분류       | 날짜  | 체크 |
| :----: | :--------------------: | :------------------------------------------------------------: | :--------------: | :---: | :--: |
| Medium |    [리트코드][78l]     |                          78. Subsets                           |   Backtracking   | 12/01 |  ✔   |
| Medium |    [리트코드][22l]     |                    22. Generate Parentheses                    |   Backtracking   | 12/02 |  ✔   |
| Medium |    [리트코드][200l]    |                     200. Number of Islands                     |       BFS        | 12/03 |  ✔   |
| Medium |    [리트코드][46l]     |                        46. Permutations                        |       DFS        | 12/04 |  ✔   |
| Medium |     [리트코드][6l]     |                      6. Zigzag Conversion                      |     Simulate     | 12/05 |  ✔   |
| Medium |    [리트코드][11l]     |                 11. Container With Most Water                  |   Two Pointer    | 12/06 |  ✔   |
| Medium |    [리트코드][39l]     |                      39. Combination Sum                       |   Backtracking   | 12/07 |  ✔   |
| Medium |    [리트코드][93l]     |                    93. Restore IP Addresses                    |   Backtracking   | 12/08 |  ✔   |
| Medium |    [리트코드][237l]    |              237. Delete Node<br>in a Linked List              |   Linked List    | 12/09 |  ✔   |
| Medium |    [리트코드][198l]    |                       198. House Robber                        |        DP        | 12/10 |  ✔   |
| Medium |    [리트코드][91l]     |                        91. Decode Ways                         |        DP        | 12/11 |  ✔   |
| Medium |    [리트코드][34l]     | 34. Find First and Last Position<br>of Element in Sorted Array |  Binary Search   | 12/12 |  ✔   |
| Medium |    [리트코드][299l]    |                      299. Bulls and Cows                       |       Hash       | 12/13 |  ✔   |
| Medium |    [리트코드][337l]    |                   337. House Robber III<br>                    |       DFS        | 12/14 |  ✔   |
| Medium |   [리트코드][1143l]    |              1143. Longest Common Subsequence<br>              |        DP        | 12/15 |  ✔   |
| Lv. 3  | [프로그래머스][42579p] |                       베스트앨범 (Java)                        |       해시       | 12/15 |  ✔   |
| Lv. 3  | [프로그래머스][42628p] |                     이중우선순위큐 (Java)                      |        힙        | 12/15 |  ✔   |
| Lv. 3  | [프로그래머스][42861p] |                       섬 연결하기 (Java)                       | 최소 스패닝 트리 | 12/16 |  ✔   |
| Medium |    [리트코드][47l]     |                      47. Permutations II                       |   Backtracking   | 12/17 |  ✔   |
| Medium |    [리트코드][343l]    |                       343. Integer Break                       |      Greedy      | 12/18 |  ✔   |
| Medium |    [리트코드][328l]    |                   328. Odd Even Linked List                    |   Linked List    | 12/19 |  ✔   |
| Medium |    [리트코드][848l]    |                     848. Shifting Letters                      |    Prefix Sum    | 12/20 |  ✔   |
| Medium |    [리트코드][238l]    |               238. Product of Array Except Self                |    Prefix Sum    | 12/21 |  ✔   |
| Medium |    [리트코드][648l]    |                       648. Replace Words                       |       Hash       | 12/22 |  ✔   |
| Medium |    [리트코드][442l]    |            442. Find All Duplicates<br>in an Array             |       Hash       | 12/23 |  ✔   |
| Medium |    [리트코드][994l]    |                      994. Rotting Oranges                      |       BFS        | 12/24 |  ✔   |
| Medium |    [리트코드][89l]     |                         89. Gray Code                          | Bit Manipulation | 12/25 |  ✔   |
| Medium |    [리트코드][16l]     |                        16. 3Sum Closest                        |   Two Pointers   | 12/26 |  ✔   |
| Medium |   [리트코드][2279l]    |       2279. Maximum Bags<br>With Full Capacity of Rocks        |      Greedy      | 12/27 |  ✔   |
| Medium |   [리트코드][1962l]    |           1962. Remove Stones to Minimize the Total            |  Priority Queue  | 12/28 |  ✔   |
| Medium |   [리트코드][1834l]    |                   1834. Single-Threaded CPU                    |  Priority Queue  | 12/29 |  ✔   |
| Medium |    [리트코드][797l]    |              797. All Paths From Source to Target              |   Backtracking   | 12/30 |  ✔   |
| Medium |    [리트코드][886l]    |                   886. Possible Bipartition                    |       DFS        | 12/31 |  ✔   |

[78l]: https://leetcode.com/problems/subsets
[22l]: https://leetcode.com/problems/generate-parentheses
[200l]: https://leetcode.com/problems/number-of-islands
[46l]: https://leetcode.com/problems/permutations
[6l]: https://leetcode.com/problems/zigzag-conversion
[11l]: https://leetcode.com/problems/container-with-most-water
[39l]: https://leetcode.com/problems/combination-sum
[93l]: https://leetcode.com/problems/combination-sum
[237l]: https://leetcode.com/problems/delete-node-in-a-linked-list
[198l]: https://leetcode.com/problems/house-robber
[91l]: https://leetcode.com/problems/decode-ways
[34l]: https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array
[299l]: https://leetcode.com/problems/bulls-and-cows
[337l]: https://leetcode.com/problems/house-robber-iii
[1143l]: https://leetcode.com/problems/longest-common-subsequence
[47l]: https://leetcode.com/problems/permutations-ii
[343l]: https://leetcode.com/problems/integer-break
[328l]: https://leetcode.com/problems/odd-even-linked-list
[848l]: https://leetcode.com/problems/shifting-letters
[238l]: https://leetcode.com/problems/product-of-array-except-self
[648l]: https://leetcode.com/problems/replace-words
[442l]: https://leetcode.com/problems/find-all-duplicates-in-an-array
[994l]: https://leetcode.com/problems/rotting-oranges
[89l]: https://leetcode.com/problems/gray-code
[16l]: https://leetcode.com/problems/3sum-closest
[2279l]: https://leetcode.com/problems/maximum-bags-with-full-capacity-of-rocks
[1962l]: https://leetcode.com/problems/remove-stones-to-minimize-the-total
[1834l]: https://leetcode.com/problems/single-threaded-cpu
[797l]: https://leetcode.com/problems/all-paths-from-source-to-target
[886l]: https://leetcode.com/problems/possible-bipartition

</div>

</details>

<details markdown="1">
<summary><strong>하루 한 문제<br>2023/01/01 ~ 2023/01/27</strong></summary>

<br>

<div align="center">

| 난이도 |       링크        |                              이름                               |       분류       | 날짜  | 체크 |
| :----: | :---------------: | :-------------------------------------------------------------: | :--------------: | :---: | :--: |
| Medium | [리트코드][204l]  |                        204. Count Primes                        |        DP        | 01/01 |  ✔   |
| Medium | [리트코드][2275l] | 2275. Largest Combination<br>With Bitwise AND Greater Than Zero | Bit Manipulation | 01/02 |  ✔   |
| Medium | [리트코드][518l]  |                       518. Coin Change II                       |        DP        | 01/03 |  ✔   |
| Medium | [리트코드][1472l] |                  1472. Design Browser History                   |   Linked List    | 01/04 |  ✔   |
| Medium | [리트코드][452l]  |       452. Minimum Number<br>of Arrows to Burst Balloons        |      Greedy      | 01/05 |  ✔   |
| Medium | [리트코드][396l]  |                      396. Rotate Function                       |        DP        | 01/06 |  ✔   |
| Medium | [리트코드][134l]  |                        134. Gas Station                         |      Greedy      | 01/07 |  ✔   |
| Medium | [리트코드][1833l] |                  1833. Maximum Ice Cream Bars                   |      Greedy      | 01/08 |  ✔   |
| Medium | [리트코드][2244l] |          2244. Minimum Rounds<br>to Complete All Tasks          |       Hash       | 01/08 |  ✔   |
| Medium | [리트코드][172l]  |                 172. Factorial Trailing Zeroes                  |       Math       | 01/09 |  ✔   |
| Medium | [리트코드][2091l] |        2091. Removing Minimum<br>and Maximum From Array         |      Greedy      | 01/10 |  ✔   |
| Medium | [리트코드][526l]  |                   526. Beautiful Arrangement                    |   Backtracking   | 01/11 |  ✔   |
| Medium | [리트코드][1855l] |       1855. Maximum Distance<br>Between a Pair of Values        |   Two Pointer    | 01/12 |  ✔   |
| Medium | [리트코드][436l]  |                    436. Find Right Interval                     |  Binary Search   | 01/13 |  ✔   |
| Medium | [리트코드][1963l] |  1963. Minimum Number of Swaps<br>to Make the String Balanced   |      Greedy      | 01/14 |  ✔   |
| Medium | [리트코드][1887l] | 1887. Reduction Operations<br>to Make the Array Elements Equal  |     Sorting      | 01/15 |  ✔   |
| Medium | [리트코드][735l]  |                     735. Asteroid Collision                     |      Stack       | 01/16 |  ✔   |
| Medium |  [리트코드][57l]  |                       57. Insert Interval                       |      Array       | 01/17 |  ✔   |
| Medium | [리트코드][486l]  |                     486. Predict the Winner                     |        DP        | 01/18 |  ✔   |
| Medium | [리트코드][1016l] |   1016. Binary String<br>With Substrings Representing 1 To N    |       Hash       | 01/19 |  ✔   |
| Medium | [리트코드][2530l] |       2530. Maximal Score<br>After Applying K Operations        |  Priority Queue  | 01/20 |  ✔   |
| Medium | [리트코드][2012l] |                2012. Sum of Beauty in the Array                 |      Array       | 01/21 |  ✔   |
| Medium | [리트코드][457l]  |                    457. Circular Array Loop                     |       DFS        | 01/22 |  ✔   |
| Medium | [리트코드][665l]  |                    665. Non-decreasing Array                    |      Array       | 01/23 |  ✔   |
| Medium | [리트코드][1358l] |  1358. Number of Substrings<br>Containing All Three Characters  |  Sliding Window  | 01/24 |  ✔   |
| Medium | [리트코드][451l]  |                451. Sort Characters By Frequency                |       Hash       | 01/25 |  ✔   |
| Medium | [리트코드][1288l] |                 1288. Remove Covered Intervals                  |      Greedy      | 01/26 |  ✔   |
| Medium |  [리트코드][45l]  |                        45. Jump Game II                         |        DP        | 01/27 |  ✔   |

<!-- new -->

[204l]: https://leetcode.com/problems/count-primes
[2275l]: https://leetcode.com/problems/largest-combination-with-bitwise-and-greater-than-zero
[518l]: https://leetcode.com/problems/coin-change-ii
[1472l]: https://leetcode.com/problems/design-browser-history
[452l]: https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons
[396l]: https://leetcode.com/problems/rotate-function
[134l]: https://leetcode.com/problems/gas-station
[1833l]: https://leetcode.com/problems/maximum-ice-cream-bars
[2244l]: https://leetcode.com/problems/minimum-rounds-to-complete-all-tasks
[172l]: https://leetcode.com/problems/factorial-trailing-zeroes
[2091l]: https://leetcode.com/problems/removing-minimum-and-maximum-from-array
[526l]: https://leetcode.com/problems/beautiful-arrangement
[1855l]: https://leetcode.com/problems/maximum-distance-between-a-pair-of-values
[436l]: https://leetcode.com/problems/find-right-interval
[1963l]: https://leetcode.com/problems/minimum-number-of-swaps-to-make-the-string-balanced
[1887l]: https://leetcode.com/problems/reduction-operations-to-make-the-array-elements-equal
[735l]: https://leetcode.com/problems/asteroid-collision
[57l]: https://leetcode.com/problems/insert-interval
[486l]: https://leetcode.com/problems/predict-the-winner
[1016l]: https://leetcode.com/problems/binary-string-with-substrings-representing-1-to-n
[2530l]: https://leetcode.com/problems/maximal-score-after-applying-k-operations
[2012l]: https://leetcode.com/problems/sum-of-beauty-in-the-array
[457l]: https://leetcode.com/problems/circular-array-loop
[665l]: https://leetcode.com/problems/non-decreasing-array
[1358l]: https://leetcode.com/problems/number-of-substrings-containing-all-three-characters
[451l]: https://leetcode.com/problems/sort-characters-by-frequency
[1288l]: https://leetcode.com/problems/remove-covered-intervals
[45l]: https://leetcode.com/problems/jump-game-ii

<!-- new-link -->

</div>

</details>
