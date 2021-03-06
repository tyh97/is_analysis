# 借出图书规约表 | [上一张表](./usercase7.md) | [下一张表](./usercase9.md) | [返回](../README.md) 
<table>
    <tr>
        <td width="150"> <b>&nbsp;用例名称</b></td>
        <td colspan="2" width="700">&nbsp;借出图书</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;参与者</b></td>
        <td colspan="2" width="700">&nbsp;图书管理员</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;前置条件</b></td>
        <td colspan="2" width="700">&nbsp;图书已预定</td>
    </tr>
    <tr>
        <td width="150"> <b>&nbsp;后置条件</b></td>
        <td colspan="2" width="700">&nbsp;将修改后的图书信息和读者信息更新到系统</td>
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
            <span>&nbsp;1.管理员登录；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;3.管理员进入出借图书功能；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;5.管理员输入出借的图书与读者信息；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;7.管理员确认出借图书；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;9.管理员确认出借，用例结束；</span>
        </td>
        <td width="480">
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;2.系统查询登录是否被允许；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;4.系统显示出借图书界面；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;6.系统核对输入信息并返回结果；</span>
            <br>
            <span>&nbsp;</span>
            <br>
            <span>&nbsp;8.系统将出借信息进行更新，并反馈出借结果；</span>
            <br>
            <span>&nbsp;</span>
        </td>
    </tr>
    <tr>
        <td colspan="3" width="200"> <b>&nbsp;备选时间流</b></td>
    </tr>
    <tr>
        <td colspan="3" width="200">
            <span>&nbsp;2a.管理员密码错误</span>
            <br>
            <span>&nbsp;&emsp;1.提示查询信息，返回第1步</span>
            <br>
            <span>&nbsp;5a.管理员退出出借图书功能</span>
            <br>
            <span>&nbsp;&emsp;1.清除界面，返回第3步</span>
            <br>
            <span>&nbsp;6a.核对出借信息失败</span>
            <br>
            <span>&nbsp;&emsp;1.显示失败信息，返回第5步</span>
            <br>
            <span>&nbsp;7a.管理员取消出借图书</span>
            <br>
            <span>&nbsp;&emsp;1.清除界面，返回第5步</span>
            <br>
            <span>&nbsp;8a.系统出借信息更新失败</span>
            <br>
            <span>&nbsp;&emsp;1.显示错误信息，返回第5步</span>
        </td>
    </tr>
    <tr>
        <td colspan="3" width="200"> <b>&nbsp;业务规则</b></td>
    </tr>
    <tr>
        <td colspan="3" width="200">
            <span>&nbsp;1.管理员只有在登录的情况下才能进行图书出借，否则返回登录界面</span>
            <br>
            <span>&nbsp;2.可以提供管理员的忘记密码功能</span>
            <br>
            <span>&nbsp;3.出借图书只能是已经被读者预定了的图书</span>
            <br>
            <span>&nbsp;4.系统应该提示并验证管理员所输入的数据的合法性，并及时提示管理员</span>
        </td>
    </tr>
</table>