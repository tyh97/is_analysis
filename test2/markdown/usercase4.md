# 查询借阅情况规约表 | [上一张表](./usercase3.md) | [下一张表](./usercase5.md) | [返回](../README.md) 
<table>
    <tr>
        <td width="150"> <b>&nbsp;用例名称</b></td>
        <td colspan="2" width="600">&nbsp;查询借阅情况</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;参与者</b></td>
        <td colspan="2" width="600">&nbsp;读者</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;前置条件</b></td>
        <td colspan="2" width="600">&nbsp;读者已注册</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;后置条件</b></td>
        <td colspan="2" width="600">&nbsp;无</td>
    </tr>
    <tr>
        <td colspan="3" width="200"> <b>&nbsp;主事件流</b></td>
    </tr>
    <tr>
        <td colspan="2" width="180"> <b>&nbsp;参与者动作</b></td>
        <td width="410"> <b>&nbsp;系统行为</b></td>
    </tr>
    <tr>
        <td colspan="2" width="180">
            <span>&nbsp;1.读者登录系统；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;4.读者查看自己的预定情况，用例结束；</span>
        </td>
        <td width="410">
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;2.系统查询登录是被允许；</span>
            <br>
            <span>&nbsp;3.系统返回读者的借阅情况；</span>
            <br>
            <span>&nbsp;</span>
        </td>
    </tr>
    <tr>
        <td colspan="3" width="200"> <b>&nbsp;备选时间流</b></td>
    </tr>
    <tr>
        <td colspan="3" width="200">
            <span>&nbsp;2a.读者密码错误</span>
            <br>
            <span>&nbsp;&emsp;1.系统返回登录界面，转第1步</span>
            <br>
            <span>&nbsp;2b.读者未注册</span>
            <br>
            <span>&nbsp;&emsp;1.系统返回登录界面，转第1步</span>
        </td>
    </tr>
    <tr>
        <td colspan="3" width="200"> <b>&nbsp;业务规则</b></td>
    </tr>
    <tr>
        <td colspan="3" width="200">
            <span>&nbsp;1.读者登录只有登陆后才能观看自己的借阅信息</span>
            <br>
            <span>&nbsp;2.读者不能查看别人的借阅信息</span>
        </td>
    </tr>
</table>