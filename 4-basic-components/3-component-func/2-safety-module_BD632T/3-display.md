# 4.3.2.3. Display Devices

![](../../../_assets/그림_4.27_BD632T(Safety_IO_Board)의_표시장치.png  )

Figure 4.7 Display Devices of BD632T (Safety IO Board)
</br></br>

Table 4-6 Description of the Display Devices of the BD632T (Safety IO Module)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Contents of display</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>When normal</strong></p></td>
<td><p><strong>Actions to take when an abnormality occurs</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>LED1</strong></p></td>
<td><p>24V power (Chain1)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon: Red LED turned on or off</p>
<p>Action 1: Check the input voltage (24V)</p>
<p>Action 2: If the LED is turned off, check the fuse (F1)</p>
<p>Action 3: Replace the BD632T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LED2</strong></p></td>
<td><p>24Vpower(Chain2)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon: Red LED turned on or off</p>
<p>Action1: Check the input voltage (24V)</p>
<p>Action2: If the LED is turned off, check the fuse (F2)</p>
<p>Action3: Replace the BD632T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LED3</strong></p></td>
<td><p>24Vpower(Chain1)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon: Red LED turned on or off </p>
<p>Action1: Check the input voltage(24V)</p>
<p>Action2: If the LED is turned off, check the fuse (F3)</p>
<p>Action3: Replace the BD632T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LED4</strong></p></td>
<td><p>24Vpower(Chain2)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon: Red LED turned on or off </p>
<p>Action1: Check the input voltage(24V)</p>
<p>Action2: If the LED is turned off, check the fuse (F5)</p>
<p>Action3: Replace the BD632T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDR1</strong></p></td>
<td><p>Reset</p></td>
<td><p>Red</p></td>
<td><p>Turned off</p></td>
<td><p>Phenomenon: Red LED turned on</p>
<p>Action1: Replace the BD632T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDR2</strong></p></td>
<td><p>EtherCAT<br>communication error LED</p></td>
<td><p>Red</p></td>
<td><p>Turned off</p></td>
<td><p>Phenomenon: Red LED turned on</p>
<p>Action1: Check the EtherCAT cable connection state</p>
<p>Action2: Replace the BD632T board</p>
<p>Action3: Inspect H6COM or BD641T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG3</strong></p></td>
<td><p>OP installation LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>Switch on (if the OP is installed)<br>Green LED turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Inspect the cable</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG4</strong></p></td>
<td><p>OP installation LED (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>Switch On (if the OP is installed)<br>Green LED turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Inspect the cable</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG5</strong></p></td>
<td><p>STO output LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>STO On: turned on</p>
<p>STO OFF: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG6</strong></p></td>
<td><p>STO output LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>STO On: turned on</p>
<p>STO OFF: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG7</strong></p></td>
<td><p>MC state check LED (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>MC Close: turned on</p>
<p>MC Open: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG8</strong></p></td>
<td><p>MC state check LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>MC Close: turned on</p>
<p>MC Open: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD632T board</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG9</strong></p></td>
<td><p>Teach pendant manual mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG10</strong></p></td>
<td><p>Teach pendant manual mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG11</strong></p></td>
<td><p>Teach pendant auto mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG12</strong></p></td>
<td><p>Teach pendant auto mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG13</strong></p></td>
<td><p>Teach pendant remote mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG14</strong></p></td>
<td><p>Teach pendant remote mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG15</strong></p></td>
<td><p>Teach pendant enable input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG16</strong></p></td>
<td><p>Teach pendant enable input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG17</strong></p></td>
<td><p>Teach pendant emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG18</strong></p></td>
<td><p>Teach pendant emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the teach pendant</p>
<p>Action2: Replace the BD602T board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG19</strong></p></td>
<td><p>OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the OVT switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG20</strong></p></td>
<td><p>OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the OVT switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG21</strong></p></td>
<td><p>Hard limit input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the hard limit switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG22</strong></p></td>
<td><p>Hard limit input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the hard limit switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG23</strong></p></td>
<td><p>Additional axis OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the additional axis OVT switch.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG24</strong></p></td>
<td><p>Additional axis OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the additional axis OVT switch.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG25</strong></p></td>
<td><p>Expansion axis OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: : Replace the extended axis OVT switch.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG26</strong></p></td>
<td><p>Expansion axis OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: : Replace the extended axis OVT switch.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG27</strong></p></td>
<td><p>Safety guard input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the safety guard.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG28</strong></p></td>
<td><p>Safety guard input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the safety guard.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG29</strong></p></td>
<td><p>Auto mode safety guard 1 input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the auto mode 1 safety guard</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG30</strong></p></td>
<td><p>Auto mode safety guard 1 input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the auto mode 1 safety guard</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG31</strong></p></td>
<td><p>Auto mode safety guard 2 input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the auto mode 2 safety guard.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG32</strong></p></td>
<td><p>Auto mode safety guard 2 input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the auto mode 2 safety guard.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG33</strong></p></td>
<td><p>External motor on input (Contact type)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the external motor on contact switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG34</strong></p></td>
<td><p>External emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the external emergency stop switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG35</strong></p></td>
<td><p>External emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the external emergency stop switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG36</strong></p></td>
<td><p>Servo state input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace BD641T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG37</strong></p></td>
<td><p>Safety module state output (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When outputted: Turned off</p>
<p>When not outputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG38</strong></p></td>
<td><p>Servo state input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace BD641T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG39</strong></p></td>
<td><p>Safety module state output (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When outputted: Turned off</p>
<p>When not outputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG40</strong></p></td>
<td><p>OP emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the OP emergency stop switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG41</strong></p></td>
<td><p>OP emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace the BD602T board</p>
<p>Action3: Replace the OP emergency stop switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG52</strong></p></td>
<td><p>PLC power</p></td>
<td><p>Green</p></td>
<td><p>When connected: turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the fuse (F6)</p>
<p>Action2: Inspect the cable</p>
<p>Action3: Replace the BD602T board</p>
<p>Action4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG53</strong></p></td>
<td><p>Emergency stop (npn type) input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect LEDG52 (When abnormal, take an action for LEDG52)</p>
<p>Action2: Inspect the cable</p>
<p>Action3: Replace the BD602T board</p>
<p>Action4: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG54</strong></p></td>
<td><p>Emergency stop (npn type) input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect LEDG52 (When abnormal, take an action for LEDG52)</p>
<p>Action2: Inspect the cable</p>
<p>Action3: Replace the BD602T board</p>
<p>Action4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG55</strong></p></td>
<td><p>Safety guard (npn type) input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect LEDG52 (When abnormal, take an action for LEDG52)</p>
<p>Action2: Inspect the cable</p>
<p>Action3: Replace the BD602T board</p>
<p>Action4: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG56</strong></p></td>
<td><p>Safety guard (npn type) input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect LEDG52 (When abnormal, take an action for LEDG52)</p>
<p>Action2: Inspect the cable</p>
<p>Action3: Replace the BD602T board</p>
<p>Action4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG57</strong></p></td>
<td><p>24V power input</p></td>
<td><p>Green</p></td>
<td><p>Green turned on</p></td>
<td><p>Phenomenon: Turned off</p>
<p>Action1: Inspect the 24V power cable and voltage (Power for connecting CNSMS1 connector)</p>
<p>Action2: Inspect the fuse (F1)</p>
<p>Action3: Replace the BD602T board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG58</strong></p></td>
<td><p>EtherCAT input act LED</p></td>
<td><p>Green</p></td>
<td><p>When EtherCAT cable connected: turned on</p>
<p>When EtherCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG59</strong></p></td>
<td><p>EtherCAT output act LED</p></td>
<td><p>Green</p></td>
<td><p>When EtherCAT cable connected: turned on</p>
<p>When EtherCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG60</strong></p></td>
<td><p>EtherCAT state LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: Blinking</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG61</strong></p></td>
<td><p>EtherCAT run LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: Blinking</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG62</strong></p></td>
<td><p>EtherCAT input speed LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: turned on</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG63</strong></p></td>
<td><p>EtherCAT input act LED</p></td>
<td><p>Yellow</p></td>
<td><p>When EtherCAT cable connected: turned on</p>
<p>When EtherCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG64</strong></p></td>
<td><p>EtherCAT output speed LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: turned on</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p>
</td>
</tr>
<tr class="even">
<td><p><strong>LEDG65</strong></p></td>
<td><p>EtherCAT output act LED</p></td>
<td><p>Yellow</p></td>
<td><p>When EtherCAT cable connected: turned on</p>
<p>When EtherCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG66</strong></p></td>
<td><p>Motor on signal LED  (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When the motor is turned off: turned on</p>
<p>When the motor is turned on: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG67</strong></p></td>
<td><p>Motor on signal LED  (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When the motor is turned off: turned on</p>
<p>When the motor is turned on: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the connected cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace BD641T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG68</strong></p></td>
<td><p>Safety chain input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the connected cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG69</strong></p></td>
<td><p>Safety chain input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: turned on</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the connected cable</p>
<p>Action2: Replace BD632T</p>
<p>Action3: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG70</strong></p></td>
<td><p>EtherCAT input link LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Blinking</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Check the firmware</p>
<p>Action3: Replace BD632T</p>
<p>Action4: Replace BD641T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG71</strong></p></td>
<td><p>EtherCAT output link  LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Blinking</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon: States other than normal state</p>
<p>Action1: Inspect the EtherCAT cable</p>
<p>Action2: Check the firmware</p>
<p>Action3: Replace BD632T</p>
<p>Action4: Replace BD641T</p></td>
</tr>
<tr class="odd">
<td><p><strong>SEG1*</strong></p></td>
<td><p>Safety module state LED (Chain 1)</p></td>
<td><p>7-seg</p></td>
<td><p>When normal: A number will be displayed and the dot will blink</p></td>
<td><p>Phenomenon: Turned off, or the dot stops blinking</p>
<p>Action1: Replace BD632T</p></td>
</tr>
<tr class="even">
<td><p><strong>SEG2*</strong></p></td>
<td><p>Safety module state LED (Chain 2)</p></td>
<td><p>7-seg</p></td>
<td><p>When normal: A number will be displayed and the dot will blink</p></td>
<td><p>Phenomenon: Turned off, or the dot stops blinking</p>
<p>Action1: Replace BD632T</p></td>
</tr>
</tbody>
</table>
SEG*: For the meaning of the display of the 7-SEG, refer to the troubleshooting manual.