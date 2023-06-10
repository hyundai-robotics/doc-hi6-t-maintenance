# 4.3.6.3. Display Devices

![](../../../_assets/4.3.6.3_BD667T_표시장치.PNG  )

Figure 4.24 Display Devices of BD667T (PN Regenerative Discharge Module)
<br><br>

Table 4-27 Description of the Display Devices of BD667T (PN Regenerative Discharge Module)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>State</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>When normal</strong></p></td>
<td><p><strong>Actions to take when an abnormality occurs</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>D24</strong></p></td>
<td><p>Control signal for the discharge signal</p></td>
<td><p>Yellow</p></td>
<td><p>Turned off</p><p>Will be turned on when discharge occurs. (Motor off)</p></td>
<td><p>Phenomenon: Turned off when the motor is turned off</p>
<p>Action 1: Check the input voltage (15V).</p>
<p>Action 2: Visually check the element for any damage.</p>
<p>Action 3: Replace the BD667T board.</p></td>
</tr>
<tr class="odd">
<td><p><strong>D23</strong></p></td>
<td><p>15V power</p></td>
<td><p>Yellow</p></td>
<td><p>Yellow점등</p></td>
<td><p>Phenomenon: Turned off</p>
<p>Action 1: Check the input voltage (15V).</p>
<p>Action 2: Check the 4-pin output voltage of U7.</p>
<p>Action 3: Replace the BD667T board.</p></td>
</tr>
<tr class="even">
<td><p><strong>D26</strong></p></td>
<td><p>Regenerative discharge operation</p></td>
<td><p>Yellow</p></td>
<td><p>Turned off</p><p>Will be turned on when discharge occurs. (Motor off)</p></td>
<td><p>Phenomenon: Yellow LED turned on, or blinking occurs without the robot being operated.</p>
<p>Action 1: Check the R54 voltage setting.</p>
<p>Action 2: Check the 5.45V regenerative discharge voltage setting.</p>
<p>Action 3: Replace the BD667T board.</p></td>
</tr>
<tr class="odd">
<td><p><strong>D25</strong></p></td>
<td><p>Discharge resistor relay drive state 

</p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on right after the power is turned on.<p>Will be then turned off after a while.<p>Will be turned on when the motor is turned off. </p></td>
<td><p>Continues to be turned on, or will be turned off when the motor is turned off.</p>
<p>Action 1: Check the input voltage (15V).</p>
<p>Action 2: Check the safety relay (RY 1) NC state.</p>
<p>Action 3: Replace the BD667T board.</p></td>
</tr>
<tr class="even">
<td><p><strong>D18</strong></p></td>
<td><p>PN power state</p></td>
<td><p>Green</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon: Turned off</p>
<p>Action 1: Check the 220VAC power supply of the BD602T board.</p>
<p>Action 2: Replace the BD667T.</p></td>
</tr>
</tbody>
</table>