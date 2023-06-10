# 4.3.6.3. 표시장치

![](../../../_assets/4.3.6.3_BD667T_표시장치.PNG  )

그림 4.24 BD667T(PN 회생방전 모듈)의 표시장치
<br><br>

표 4-27 BD667T(PN 회생방전 모듈) 표시장치 설명

<table>
<tbody>
<tr class="odd">
<td><p><strong>명칭</strong></p></td>
<td><p><strong>표시내용</strong></p></td>
<td><p><strong>색상</strong></p></td>
<td><p><strong>정상시</strong></p></td>
<td><p><strong>이상발생시 조치 내용</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>D24</strong></p></td>
<td><p>방전신호 컨트롤신호</p></td>
<td><p>노란색</p></td>
<td><p>소등</p><p>방전시 점등 (Motor off)</p></td>
<td><p>현상: Motor off시 소등</p>
<p>조치1: 입력전압 확인(15V)</p>
<p>조치2: 소자 손상 육안검사</p>
<p>조치3: BD667T보드 교체</p></td>
</tr>
<tr class="odd">
<td><p><strong>D23</strong></p></td>
<td><p>15V전원</p></td>
<td><p>노란색</p></td>
<td><p>노란색점등</p></td>
<td><p>현상: 소등</p>
<p>조치1: 입력전압 확인(15V)</p>
<p>조치2: U7의 4 pin 출력전압 확인</p>
<p>조치3: BD667T보드 교체</p></td>
</tr>
<tr class="even">
<td><p><strong>D26</strong></p></td>
<td><p>회생방전 동작</p></td>
<td><p>노란색</p></td>
<td><p>소등</p><p>방전시 점등 (Motor off)</p></td>
<td><p>현상: 노란색 점등 or<p>로봇 구동없이 점멸</p>
<p>조치1: R54전압 세팅 설정 확인</p>
<p>조치2: 5.45V 회생방전전압 설정</p>
<p>조치3: BD667T보드교체</p></td>
</tr>
<tr class="odd">
<td><p><strong>D25</strong></p></td>
<td><p>방전저항 릴레이 구동 상태표시</p></td>
<td><p>노란색</p></td>
<td><p>전원 on 직후 점등<p>잠시후 소등<p>모터 off시 점등</p></td>
<td><p>현상: 지속적인점등, 모터 off시 소등</p>
<p>조치1: 입력전압 확인(15V)</p>
<p>조치2: Safety Relay(RY1)<p>NC 상태확인</p>
<p>조치3: BD667T보드교체</p></td>
</tr>
<tr class="even">
<td><p><strong>D18</strong></p></td>
<td><p>PN전원 상태표시</p></td>
<td><p>녹색</p></td>
<td><p>녹색점등</p></td>
<td><p>현상: 소등</p>
<p>조치1: BD602T보드의 220VAC 전원공급 확인</p>
<p>조치2: BD667T 보드 교체</p></td>
</tr>
</tbody>
</table>