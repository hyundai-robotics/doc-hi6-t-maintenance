# 4.3.2.4. Setting Devices

![](../../../_assets/그림_4.31_BD632T(Safety_IO_Board)의_설정장치_설명.png  )

Figure 4.8 Description of the Setting Devices of the BD632T (Safety IO Board)

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Works When Operating the Robot.”
{% endhint %}

Table 4-7 Description of the SW1, SW2, SW3, SW4, SW7 and SW9 Setting Devices of BD632T (Safety IO Module)


<table>
<thead>
  <tr>
    <th colspan="2">Switch</th>
    <th rowspan="2">SW1</th>
    <th rowspan="2">SW2</th>
    <th rowspan="2">SW3</th>
    <th rowspan="2">SW4</th>
    <th rowspan="2">SW7</th>
    <th rowspan="2">SW9</th>
  </tr>
  <tr>
    <th colspan="2">number</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">Usage</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 1)</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 2)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 1)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 2)</td>
    <td>1: ES1<br>2: ES2<br>3: SG1<br>4: SG2</td>
    <td>1: safety chain1<br>2: safety chain2<br>3: N.C<br>4: ACFLT</td>
  </tr>
  <tr>
    <td rowspan="2">Contents of setting</td>
    <td>OFF</td>
    <td>Non-installation</td>
    <td>Non-installation</td>
    <td>1: Installation of OVT6</br>2: Installation of LS<br>3: Installation of OVT7</br>4: Installation of OVT8
</td>
    <td>1: Installation of OVT6</br>2: Installation of LS</br>3: Installation of OVT7</br>4: Installation of OVT8</br>
</td>
    <td>1: Installation (Chain 1)<br>2: Installation (Chain 2)</td>
    <td>1: Installation<br>2: Installation<br>3: Installation<br>4: Installation</td>
  </tr>
  <tr>
    <td>ON</td>
    <td>Installation</td>
    <td>Installation</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation (Chain 1)<br>2: No installation (Chain 2)</td>
    <td>1:No installation<br>2:No installation<br>3:No installation<br>4:No installation</td>
  </tr>
  <tr>
    <tr>
    <td colspan="2">Setting when shipped from<br>the factory</td>
    <td>OFF</td>
    <td>OFF</td>
    <td>1: OFF<br>2, 3, 4: ON</td>
    <td>1: OFF<br>2, 3, 4: ON</td>
    <td>1, 2, 3, 4: ON</td>
    <td>1, 2, 3, 4: ON</td>
  </tr>
</tbody>
</table>
