# 4.3.6.3. 显示设备

![](../../../_assets/4.3.6.3_BD667T_표시장치.PNG  )

图 4.24 BD667T 的显示设备 (PN 再生放电模块)
<br><br>

表 4-27 BD667T 显示设备的描述 (PN 再生放电模块)

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>状态</strong></p></td>
<td><p><strong>颜色</strong></p></td>
<td><p><strong>正常时</strong></p></td>
<td><p><strong>发生异常时的应对措施</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>D24</strong></p></td>
<td><p>放电信号的控制信号</p></td>
<td><p>黄色</p></td>
<td><p>关闭</p><p>发生放电时将开启。 (电机关闭)</p></td>
<td><p>现象：电机关闭时关闭</p>
<p>行动 1：检查输入电压 (15V)。</p>
<p>行动 2：目视检查元件是否有损坏。</p>
<p>行动 3：更换 BD667T 板。</p></td>
</tr>
<tr class="odd">
<td><p><strong>D23</strong></p></td>
<td><p>15V 电源</p></td>
<td><p>黄色</p></td>
<td><p>黄色点亮</p></td>
<td><p>现象：关闭</p>
<p>行动 1：检查输入电压 (15V)。</p>
<p>行动 2：检查 U7 的 4 针输出电压。</p>
<p>行动 3：更换 BD667T 板。</p></td>
</tr>
<tr class="even">
<td><p><strong>D26</strong></p></td>
<td><p>再生放电操作</p></td>
<td><p>黄色</p></td>
<td><p>关闭</p><p>发生放电时将开启。 (电机关闭)</p></td>
<td><p>现象：黄色 LED 点亮，或在机器人未操作的情况下发生闪烁。</p>
<p>行动 1：检查 R54 电压设置。</p>
<p>行动 2：检查 5.45V 再生放电电压设置。</p>
<p>行动 3：更换 BD667T 板。</p></td>
</tr>
<tr class="odd">
<td><p><strong>D25</strong></p></td>
<td><p>放电电阻器继电器驱动状态</p></td>
<td><p>黄色</p></td>
<td><p>在电源开启后会立即开启。<p>过一段时间后会关闭。<p>在电机关闭时会重新开启。</p></td>
<td><p>持续开启，或者在电机关闭时会关闭。</p>
<p>行动 1：检查输入电压 (15V)。</p>
<p>行动 2：检查安全继电器 (RY 1) NC 状态。</p>
<p>行动 3：更换 BD667T 板。</p></td>
</tr>
<tr class="even">
<td><p><strong>D18</strong></p></td>
<td><p>PN 电源状态</p></td>
<td><p>绿色</p></td>
<td><p>绿色 LED 灯已开启</p></td>
<td><p>现象：已关闭</p>
<p>行动 1：检查 BD602T 板的 220VAC 电源。</p>
<p>行动 2：更换 BD667T。</p></td>
</tr>
</tbody>
</table>