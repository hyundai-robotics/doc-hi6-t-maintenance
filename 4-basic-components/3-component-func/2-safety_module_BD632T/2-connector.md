# 4.3.2.2. 커넥터

다음 그림은 BD632T(Safety IO Module)에 있는 각종 커넥터의 위치와 용도를 나타낸 것입니다.

![](../../../_assets/그림_4.24_BD632T(Safety_IO_Board)의_커넥터_및_스위치_배치.png  )

그림 4.4 BD632T(Safety IO Board)의 커넥터 및 스위치 배치

표 4-3 BD632T(Safety IO Board)커넥터 종류 및 용도

<table>
<tbody>
<tr class="odd">

<td><p><strong>명칭</strong></p></td>
<td><p><strong>용도</strong></p></td>
<td><p><strong>외부장치접속</strong></p></td>
</tr>
<tr class="even">

<td><p><strong>CNTP1</strong></p></td>
<td><p>티칭 펜던트의 전원, 비상정지, 모드스위치, 인에이블링 스위치 입력</p></td>
<td><p>티치펜던트</p></td>
</tr>
<tr class="odd">

<td><p><strong>CNLS1</strong></p></td>
<td><p>Arm간섭, Over-travel검지용 리밋스위치 입력</p></td>
<td><p></p></td>
</tr>
<tr class="even">

<td><p><strong>CNLS2</strong></p></td>
<td><p>부가축, 확장축 Over-travel검지용 리밋스위치 입력</p></td>
<td><p></p></td>
</tr>
<tr class="odd">

<td><p><strong>CNSCH1</strong></p></td>
<td><p>멀티로봇 안전체인 입출력</p></td>
<td><p>외부 제어기</p></td>
</tr>
<tr class="even">

<td><p><strong>CNOPSW1</strong></p></td>
<td><p>OP(Operational Panel)의 모드스위치, 키입력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">

<td><p><strong>CNOPLP1</strong></p></td>
<td><p>OP(Operational Panel)의 LAMP출력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="even">

<td><p><strong>CNEMSW1</strong></p></td>
<td><p>OP(Operational Panel)의 비상정지 입력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">

<td><p><strong>TBEM</strong></p></td>
<td><p>외부 안전 입력
(비상정지, AUTO모드 안전가드1, AUTO모드 안전가드2, 일반안전가드, 외부모터온 입력)
</p>
<td><p>유저 IO</p></td>
</tr>
<tr class="even">

<td><p><strong>TBPLC</strong></p></td>
<td><p>안전 PLC용 안전신호 접속</p></td>
<td><p>Safety PLC</p></td>
</tr>
<tr class="odd">

<td><p><strong>A_JATG</strong></p></td>
<td><p>JTAG커넥터</p></td>
<td></td>
</tr>
<tr class="even">

<td><p><strong>B_JATG</strong></p></td>
<td><p>JTAG커넥터</p></td>
<td></td>
</tr>
<tr class="odd">

<td><p><strong>CNJTAG</strong></p></td>
<td><p>JTAG커넥터</p>
<td><p></p></td>
</tr>
<tr class="even">

<td><p><strong>SW1</strong></p></td>
<td><p>OP(Operational Panel) 셋업 스위치</p></td>
<td></td>
</tr>
<tr class="odd">

<td><p><strong>SW2</strong></p></td>
<td><p>OP(Operational Panel) 셋업 스위치</p></td>
<td></td>
</tr>
<tr class="even">

<td><p><strong>SW3</strong></p></td>
<td><p>ARM간섭, OVER-TRAVEL 스위치 셋업 스위치 </p></td>
<td><p></p></td>
</tr>
<tr class="odd">

<td><p><strong>SW4</strong></p></td>
<td><p>ARM간섭, OVER-TRAVEL 스위치 셋업 스위치</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">

<td><p><strong>SW5</strong></p></td>
<td><p>멀티로봇 셋업 스위치</p></td>
<td></td>
</tr>
<tr class="odd">
</tr>
</tbody>
</table>

\(1\) BD632T 외부안전신호용 터미널블럭: TBEM

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

그림 4.5 BD632T(Safety IO Board) TBEM

{% hint style="caution" %}
안전관련 입력을 연결하여 활성화를 한경우 반드시 “1.11. 로봇 조작시 안전대책”을 참고하여 기능 정상 동작 여부를 확인하여 주십시오.
{% endhint %}

표 4-4 BD632T(Safety IO Board) TBEM 설명

<table>
<thead>
  <tr>
    <th>단자번호</th>
    <th>단자명</th>
    <th>용도</th>
    <th>기타</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>EMEX2+</td>
    <td rowspan="2">외부비상정지 체인2 입력</td>
    <td rowspan="2">외부장치의 비상정지 체인2을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>EMEX1+</td>
    <td rowspan="2">외부비상정지 체인1 입력</td>
    <td rowspan="2">외부장치의 비상정지 체인1을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
    <td>18</td>
    <td>SGA22+</td>
    <td rowspan="2">자동안전가드2 체인2입력</td>
    <td rowspan="2">자동안전가드2 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SGA22-</td>
  </tr>
  <tr>
    <td>17</td>
    <td>SGA12+</td>
    <td rowspan="2">자동안전가드2 체인1입력</td>
    <td rowspan="2">자동안전가드2 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SGA12-</td>
  </tr>
  <tr>
    <td>16</td>
    <td>SGA21+</td>
    <td rowspan="2">자동안전가드1 체인2입력</td>
    <td rowspan="2">자동안전가드1 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>5</td>
    <td>SGA21-</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SGA11+</td>
    <td rowspan="2">자동안전가드1 체인1입력</td>
    <td rowspan="2">자동안전가드1 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>6</td>
    <td>SGA11-</td>
  </tr>
  <tr>
    <td>14</td>
    <td>SGG2+</td>
    <td rowspan="2">일반안전가드 체인2입력</td>
    <td rowspan="2">일반안전가드 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>7</td>
    <td>SGG2-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>SGG1+</td>
    <td rowspan="2">일반안전가드 체인1입력</td>
    <td rowspan="2">일반안전가드 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
   <tr>
    <td>19</td>
    <td>EXMON_C+</td>
    <td rowspan="2">접점 타입 외부 모터온</td>
    <td rowspan="2">사용하지 않을 경우 개방시킵니다.</td>
  </tr>
  <tr>
    <td>9</td>
    <td>EXMON_C</td>
  </tr>
   <tr>
    <td>20</td>
    <td>EXMON1</td>
    <td rowspan="2">PNP 타입 외부 모터온</td>
    <td rowspan="2">사용하지 않을 경우 개방시킵니다.</td>
  </tr>
  <tr>
    <td>10</td>
    <td>M1</td>
  </tr>
</tbody>
</table>


\(2\)   BD632T 안전 PLC 연결용 터미널블럭: TBPLC

![](../../../_assets/그림_4.26_BD632(Safety_IO_Board)_TBPLC.png  )

그림 4.6 BD632T(Safety IO Board) TBPLC

{% hint style="caution" %}
안전관련 입력을 연결하여 활성화를 한경우 반드시 “1.11. 로봇 조작시 안전대책”을 참고하여 기능 정상 동작 여부를 확인하여 주십시오.
{% endhint %}

표 4-5 BD632T(Safety IO Board) TBPLC 설명

<table>
<thead>
  <tr>
    <th>단자번호</th>
    <th>단자명</th>
    <th>용도</th>
    <th>기타</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>PLC_P</td>
    <td>안전 PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>10</td>
    <td>PLC_G</td>
    <td>안전 PLC GND</td>
    <td>SG/ES신호의 Common역할을 함.</td>
  </tr>
   <tr>
    <td>12</td>
    <td>N.C</td>
    <td>-</td>
    <td></td>
  </tr>
   <tr>
    <td>9</td>
    <td>N.C</td>
    <td>-</td>
    <td></td>
  </tr>
   <tr>
    <td>13</td>
    <td>N.C</td>
    <td>-</td>
    <td></td>
  </tr>
   <tr>
    <td>8</td>
    <td>N.C</td>
    <td>-</td>
    <td></td>
  </tr>
    <tr>
    <td>14</td>
    <td>SYS_T10</td>
    <td rowspan="2">릴레이 상태 모니터링 단자 안전체인 1</td>
    <td rowspan="2">미사용 시 OPEN</td>
  </tr>
  <tr>
    <td>7</td>
    <td>FDBK10</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SYS_T20</td>
    <td rowspan="2">릴레이 상태 모니터링 단자 안전체인 2</td>
    <td rowspan="2">미사용 시 OPEN</td>
  </tr>
  <tr>
    <td>6</td>
    <td>FDBK20</td>
  </tr>
  <tr>
    <td>16</td>
    <td>PLC_TO1</td>
    <td>Safety IO의 모니터링용 출력에 대한 입력단자</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>Safety IO의 T0에 대한 피드백신호 출력</td>
  </tr>
  <tr>
    <td>17</td>
    <td>SG1</td>
    <td>안전PLC로부터의 안전가드 입력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>안전PLC로부터의 안전가드 입력 체인 2</td>
  </tr>
  <tr>
    <td>18</td>
    <td>ES1</td>
    <td>안전PLC로부터의 비상정지 입력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>안전PLC로부터의 비상정지 입력 체인 2</td>
  </tr>
  <tr>
    <td>19</td>
    <td>EMOUT11+</td>
    <td rowspan="2">내부 비상정지 출력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>20</td>
    <td>EMOUT21+</td>
    <td rowspan="2">내부 비상정지 출력 체인 2</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>
</tbody>
</table>

