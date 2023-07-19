# 4.3.2.2. Connectors

The following figure shows the locations and usage of various connectors installed on BD632T (Safety IO Module).

![](../../../_assets/그림_4.24_BD632T(Safety_IO_Board)의_커넥터_및_스위치_배치.png  )

Figure 4.4 Placement of the Connectors and Switches of the BD632T (Safety IO Board)</br></br>

Table 4-3 Types and Usage of the Connectors of the BD632 (Safety IO Board)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNTP1</strong></p></td>
<td><p>Inputs of the emergency stop switch, mode switch, and enable switch of the teach pendant</p></td>
<td><p>Teach Pendant</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNLS1</strong></p></td>
<td><p>Limit switch input for the detection of arm interference and over-travel</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>CNLS2</strong></p></td>
<td><p>Additional axis, extended axis, limit switch input for the detection of over-travel</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNSCH1</strong></p></td>
<td><p>Multi-robot safety chain input and output</p></td>
<td><p>External controller</p></td>
</tr>
<tr class="even">
<td><p><strong>CNOPSW</strong></p></td>
<td><p>Inputs of the mode switch and keys of the Operational Panel (OP)</p></td>
<td>Operational Panel (OP)</td>
</tr>
<tr class="odd">
<td><p><strong>CNOPLP1</strong></p></td>
<td><p>Lamp output of the Operational Panel (OP)</p></td>
<td>Operational Panel (OP)</td>
</tr>
<tr class="even">
<td><p><strong>CNEMSW1</strong></p></td>
<td><p>Emergency stop input of the Operational Panel (OP)</p></td>
<td>Operational Panel (OP)</td>
</tr>
<tr class="odd">
<td><p><strong>TBEM</strong></p></td>
<td><p>External safety inputs
(Emergency stop, auto mode safety guard 1, auto mode safety guard 2, and general safety guard input)
</p></td>
<td><p>User IO</p></td>
</tr>
<tr class="even">
<td><p><strong>TBPLC</strong></p></td>
<td><p>Connection of the safety PLC safety signals</p></td>
<td><p>Safety PLC</p></td>
</tr>
<tr class="odd">
<td><p><strong>A_JATG</strong></p></td>
<td><p>JTAG connector</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>B_JATG</strong></p></td>
<td><p>JTAG connector</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNJTAG</strong></p></td>
<td><p>JTAG connector</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW1</strong></p></td>
<td><p>OP(Operational Panel) setup switch</p></td>
<td>-</td>
</tr>
<tr class="odd">
<td><p><strong>SW2</strong></p></td>
<td><p>OP(Operational Panel) setup switch</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW3</strong></p></td>
<td><p>Setup switch for arm interference and overtravel </p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>SW4</strong></p></td>
<td><p>Setup switch for arm interference and overtravel</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW5</strong></p></td>
<td><p>Multi-robot setup switch</p></td>
<td>-</td>
</tr>
</tbody>
</table>

\(1\) External Safety Signal Terminal Block of the BD632T: TBEM

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.5 BD632T(Safety IO Board) TBEM

{% hint style="caution" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Works When Operating the Robot.”
{% endhint %}

Table 4-4 Description of TBEM of the BD632T (Safety IO Board) 

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>EMEX2+</td>
    <td rowspan="2">External emergency stop chain 2 input</td>
    <td rowspan="2">If the external emergency stop chain 2 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>EMEX1+</td>
    <td rowspan="2">External emergency stop chain 1 input</td>
    <td rowspan="2">If the external emergency stop chain 1 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
    <td>18</td>
    <td>SGA22+</td>
    <td rowspan="2">Automatic safety guard 2 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SGA22-</td>
  </tr>
  <tr>
    <td>17</td>
    <td>SGA12+</td>
    <td rowspan="2">Automatic safety guard 2 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SGA12-</td>
  </tr>
  <tr>
    <td>16</td>
    <td>SGA21+</td>
    <td rowspan="2">Automatic safety guard 1 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>5</td>
    <td>SGA21-</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SGA11+</td>
    <td rowspan="2">Automatic safety guard 1 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>SGA11-</td>
  </tr>
  <tr>
    <td>14</td>
    <td>SGG2+</td>
    <td rowspan="2">General safety guard chain 2 input</td>
    <td rowspan="2">If the general safety guard chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>SGG2-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>SGG1+</td>
    <td rowspan="2">General safety guard chain 1 input</td>
    <td rowspan="2">If the general safety guard chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
  <tr>
    <td>19</td>
    <td>EXMON_C+</td>
    <td rowspan="2">Contact type external motor on</td>
    <td rowspan="2">If the contact type external motor on is not to be used, it should be open-up. </td>
  </tr>
  <tr>
    <td>9</td>
    <td>EXMON_C-</td>
  </tr>
  <tr>
    <td>20</td>
    <td>EXMON1</td>
    <td rowspan="2">PNP type external motor on</td>
    <td rowspan="2">If the PNP type external motor on is not to be used, it should be open-up.</td>
  </tr>
  <tr>
    <td>10</td>
    <td>M1</td>
  </tr>
</tbody>
</table>


\(2\) Safety PLC Connection Terminal Block of the BD632T: TBPLC

![](../../../_assets/그림_4.26_BD632(Safety_IO_Board)_TBPLC.png  )

Figure 4.6 TBPLC of the BD632T (Safety IO Board)

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Works When Operating the Robot.”
{% endhint %}

Table 4-5 Description of TBPLC of BD632T (Safety IO Board)

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>PLC_P</td>
    <td>Safety PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>10</td>
    <td>PLC_G</td>
    <td>Safety PLC GND</td>
    <td>To function as Common for the SG/ES signal </td>
  </tr>
  <tr>
    <td>12</td>
    <td>N.C</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>9</td>
    <td>N.C</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>N.C</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>8</td>
    <td>N.C</td>
    <td>-</td>
    <td>-</td>
  </tr>
    <tr>
    <td>4</td>
    <td>SYS_T10</td>
    <td rowspan="2">Relay state monitoring terminal Safety chain 1</td>
    <td rowspan="2">Open when not used</td>
  </tr>
  <tr>
    <td>7</td>
    <td>FDBK10</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SYS_T20</td>
    <td rowspan="2">Relay state monitoring terminal Safety chain 2</td>
    <td rowspan="2">Open when not used</td>
  </tr>
  <tr>
    <td>6</td>
    <td>FDBK20</td>
  <tr>
    <td>16</td>
    <td>PLC_TO1</td>
    <td>Input terminal for the monitoring output of the safety IO</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>Feedback signal output for T0 of the safety IO</td>
  </tr>
  <tr>
    <td>17</td>
    <td>SG1</td>
    <td>Chain 1 for the safety guard input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>Chain 2 for the safety guard input from the safety PLC</td>
  </tr>
  <tr>
    <td>18</td>
    <td>ES1</td>
    <td>Chain 1 for the emergency stop input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>Chain 2 for the emergency stop input from the safety PLC</td>
  </tr>
  <tr>
    <td>19</td>
    <td>EMOUT11+</td>
    <td rowspan="2">Internal emergency stop output chain 1</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>20</td>
    <td>EMOUT21+</td>
    <td rowspan="2">Internal emergency stop output chain 2</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>  
  </tr>
</tbody>
</table>
