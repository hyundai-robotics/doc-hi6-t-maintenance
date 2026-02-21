# 4.3.2.2. 连接器

下图显示了安装在 BD632T（安全 IO 模块）上的各种连接器的位置和用法。

![](../../../_assets/图_4.24_BD632T(安全_IO_板)的_连接器_和_开关_布局.png)

图 4.4 BD632T（安全 IO 板）的连接器和开关的布局</br></br>

表 4-3 BD632（安全 IO 板）连接器的类型和用法

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用法</strong></p></td>
<td><p><strong>外部设备的连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNTP1</strong></p></td>
<td><p>急停开关、模式开关和教学挂件的使能开关的输入</p></td>
<td><p>教学挂件</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNLS1</strong></p></td>
<td><p>用于检测机械臂干涉和超行程的限位开关输入</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>CNLS2</strong></p></td>
<td><p>附加轴、扩展轴、用于检测超行程的限位开关输入</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNSCH1</strong></p></td>
<td><p>多机器人安全链输入和输出</p></td>
<td><p>外部控制器</p></td>
</tr>
<tr class="even">
<td><p><strong>CNOPSW</strong></p></td>
<td><p>操作面板（OP）的模式开关和按键的输入</p></td>
<td>操作面板（OP）</td>
</tr>
<tr class="odd">
<td><p><strong>CNOPLP1</strong></p></td>
<td><p>操作面板（OP）的灯输出</p></td>
<td>操作面板（OP）</td>
</tr>
<tr class="even">
<td><p><strong>CNEMSW1</strong></p></td>
<td><p>操作面板（OP）的急停输入</p></td>
<td>操作面板 (OP)</td>
</tr>
<tr class="odd">
<td><p><strong>TBEM</strong></p></td>
<td><p>外部安全输入
(紧急停止, 自动模式安全保护装置 1, 自动模式安全保护装置 2, 及一般安全保护输入)
</p></td>
<td><p>用户 IO</p></td>
</tr>
<tr class="even">
<td><p><strong>TBPLC</strong></p></td>
<td><p>安全 PLC 安全信号的连接</p></td>
<td><p>安全 PLC</p></td>
</tr>
<tr class="odd">
<td><p><strong>A_JATG</strong></p></td>
<td><p>JTAG 连接器</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>B_JATG</strong></p></td>
<td><p>JTAG 连接器</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNJTAG</strong></p></td>
<td><p>JTAG 连接器</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW1</strong></p></td>
<td><p>OP(操作面板) 设置开关</p></td>
<td>-</td>
</tr>
<tr class="odd">
<td><p><strong>SW2</strong></p></td>
<td><p>OP(操作面板) 设置开关</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW3</strong></p></td>
<td><p>用于臂干扰和过行程的设置开关</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>SW4</strong></p></td>
<td><p>用于臂干扰和过行程的设置开关</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>SW9</strong></p></td>
<td><p>多机器人设置开关</p></td>
<td>-</td>
</tr>
</tbody>
</table>

\(1\) BD632T的外部安全信号端子块：TBEM

![](../../../_assets/图_4.25_BD632(安全_IO_板)_TBEM.png  )

图 4.5 BD632T（安全 IO 板） TBEM

{% hint style="info" %}
当安全相关输入连接并激活时，您必须检查通过参考 "1.11 当机器人运行时的安全工作" 以查看功能是否正常运行。
{% endhint %}

表 4-4 BD632T（安全 IO 板）TBEM的描述

<table>
<thead>
  <tr>
    <th>端子编号</th>
    <th>端子名称</th>
    <th>用途</th>
    <th>其他</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>EMEX2+</td>
    <td rowspan="2">外部紧急停止链路 2 输入</td>
    <td rowspan="2">如果不使用外部紧急停止链路 2，应该进行短接。</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>EMEX1+</td>
    <td rowspan="2">外部紧急停止链路 1 输入</td>
    <td rowspan="2">如果不使用外部紧急停止链路 1，应该进行短接。</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
```html
<td>13</td>
<td>SGA22+</td>
<td rowspan="2">自动安全保护装置 2 链 2 输入</td>
<td rowspan="2">如果不使用自动安全保护装置 2 链 2 输入，则应将其短路。</td>
</tr>
<tr>
<td>3</td>
<td>SGA22-</td>
</tr>
<tr>
<td>14</td>
<td>SGA12+</td>
<td rowspan="2">自动安全保护装置 2 链 1 输入</td>
<td rowspan="2">如果不使用自动安全保护装置 2 链 1 输入，则应将其短路。</td>
</tr>
<tr>
<td>4</td>
<td>SGA12-</td>
</tr>
<tr>
<td>15</td>
<td>SGA21+</td>
<td rowspan="2">自动安全保护装置 1 链 2 输入</td>
<td rowspan="2">如果不使用自动安全保护装置 1 链 2 输入，则应将其短路。</td>
</tr>
<tr>
<td>5</td>
<td>SGA21-</td>
</tr>
<tr>
<td>16</td>
<td>SGA11+</td>
<td rowspan="2">自动安全保护装置 1 链 1 输入</td>
<td rowspan="2">如果不使用自动安全保护装置 1 链 1 输入，则应将其短路。</td>
</tr>
<tr>
<td>6</td>
<td>SGA11-</td>
</tr>
<tr>
<td>17</td>
<td>SGG2+</td>
<td rowspan="2">一般安全保护装置链 2 输入</td>
<td rowspan="2">如果不使用一般安全保护装置链 2 输入，则应将其短路。</td>
</tr>
<tr>
<td>7</td>
<td>SGG2-</td>
</tr>
```
<td>18</td>
    <td>SGG1+</td>
    <td rowspan="2">一般安全防护链 1 输入</td>
    <td rowspan="2">如果一般安全防护链 1 输入不使用，应进行短路处理。</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
  <tr>
    <td>19</td>
    <td>EXMON_C+</td>
    <td rowspan="2">接触类型外部电机开启</td>
    <td rowspan="2">如果不使用接触类型外部电机开启，应保持打开状态。</td>
  </tr>
  <tr>
    <td>9</td>
    <td>EXMON_C-</td>
  </tr>
  <tr>
    <td>20</td>
    <td>EXMON1</td>
    <td rowspan="2">PNP类型外部电机开启</td>
    <td rowspan="2">如果不使用PNP类型外部电机开启，应保持打开状态。</td>
  </tr>
  <tr>
    <td>10</td>
    <td>M1</td>
  </tr>
</tbody>
</table>


\(2\) BD632T 的安全 PLC 连接端子块：TBPLC

![](../../../_assets/图_4.26_BD632(安全_IO_板)_TBPLC.png  )

图 4.6 BD632T 的 TBPLC (安全 IO 板)

{% hint style="warning" %}
连接并激活与安全相关的输入时，必须通过参考“1.11 验证机器人操作时的安全工作”来检查功能是否正常运作。
{% endhint %}

表 4-5 BD632T 的 TBPLC 描述 (安全 IO 板)

<table>
<thead>
  <tr>
    <th>端子编号</th>
    <th>端子名称</th>
<th>使用</th>
    <th>其他</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>11</td>
    <td>PLC_P</td>
    <td>安全PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>10</td>
    <td>PLC_G</td>
    <td>安全PLC GND</td>
    <td>作为SG/ES信号的公共端工作</td>
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
    <td rowspan="2">继电器状态监控端子 安全链路 1</td>
    <td rowspan="2">未使用时打开</td>
  </tr>
  <tr>
    <td>7</td>
    <td>FDBK10</td>
</tr>
  <tr>
    <td>15</td>
    <td>SYS_T20</td>
    <td rowspan="2">继电器状态监测终端安全链 2</td>
    <td rowspan="2">不使用时打开</td>
  </tr>
  <tr>
    <td>6</td>
    <td>FDBK20</td>
  <tr>
    <td>16</td>
    <td>PLC_TO1</td>
    <td>安全IO的监测输出的输入端子</td>
    <td rowspan="2">仅适用PNP输出类型</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>安全IO的T0反馈信号输出</td>
  </tr>
  <tr>
    <td>17</td>
    <td>SG1</td>
    <td>来自安全PLC的安全保护输入链 1</td>
    <td rowspan="2">仅适用PNP输出类型</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>来自安全PLC的安全保护输入链 2</td>
  </tr>
  <tr>
    <td>18</td>
    <td>ES1</td>
    <td>来自安全PLC的紧急停止输入链 1</td>
    <td rowspan="2">仅适用PNP输出类型</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>来自安全PLC的紧急停止输入链 2</td>
  </tr>
  <tr>
    <td>19</td>
    <td>EMOUT11+</td>
    <td rowspan="2">内部紧急停止输出链 1</td>
    <td rowspan="2">仅适用PNP输出类型</td>
  </tr>
  <tr>
<td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>20</td>
    <td>EMOUT21+</td>
    <td rowspan="2">内部紧急停止输出链 2</td>
    <td rowspan="2">仅适用 PNP 输出类型</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>  
  </tr>
</tbody>
</table>