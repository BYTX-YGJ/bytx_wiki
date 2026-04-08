## **考勤管理常见问题**

## 钉钉后台有打卡记录但薪酬系统无考勤记录

一、[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)，重新拉取考勤记录，看是否能够拉取成功，如果拉取不到出勤记录详见[出勤记录无法拉取](#出勤记录无法拉取)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/MTY4ODg1NzM4NzY1MzgwOQ_108072_yA2VR82Gl8QrXIEe_1765166087)

二、能成功拉取考勤记录，但是计算后员工考勤记录会进入到无效打卡记录

无效打卡记录查询路径：[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/无效打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)

![image-20260407182815549](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407182815549.png)

无效打卡的情景

1、员工使用外勤打卡，[外勤打卡无效](#外勤打卡无效)

2、员工在考勤机打卡，[考勤机打卡无效](#考勤机打卡无效)

## 出勤记录无法拉取

1、[薪酬管理/员工管理/员工档案](http://121.28.192.238:8562/salary/staff/staffmanagement)-详情查看员工钉钉手机号与钉钉号与[钉钉后台/成员管理](https://oa.dingtalk.com/contacts.htm#/contacts)对应信息是否一致，不一致的按照实际情况修改正确，详见[钉钉号修改](#钉钉号修改)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407102548768.png)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407102842384.png)

2、如果信息一致的，导出考勤记录看是否有多个钉钉号

![image-20260407120227937](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407120227937.png)

如果有多条钉钉号的需要在[薪酬管理/考勤管理/出勤记录/不同钉钉号维护](http://121.28.192.238:8562/salary/attend/attendancerecordrest)对应月份进行维护

![image-20260407175654599](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407175654599.png)

<font color="red">注意：对于有多个钉钉号的，此页面中员工现有钉钉号的创建时间要为最新的</font>

![image-20260408115959179](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408115959179.png)

## 钉钉号修改

需要修改钉钉号的情景

一、没有钉钉号

在职员工在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉编号不完整-在职](http://121.28.192.238:8562/salary/attend/attendancerecordrest)查询后完善钉钉号

离职员工在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉编号不完整-离职](http://121.28.192.238:8562/salary/attend/attendancerecordrest)查询后完善钉钉号

二、钉钉号不正确

点击[薪酬管理/员工管理/员工档案](http://121.28.192.238:8562/salary/staff/staffmanagement)详情按照以下步骤修改

先置空员工钉钉号，然后修改员工钉钉手机号为正确的保存信息，保存信息后员工没有钉钉号按照没有钉钉号的流程完善

![image-20260407181801529](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407181801529.png)

## 外勤打卡无效

需要核实员工使用外勤打卡期间是否有以下流程或登记信息

一、查看[薪酬管理/考勤管理/管理员流程查询及申请/外出申请审批](http://121.28.192.238:8562/salary/attend/allapply)是否有对应审批通过的外出流程

<font color="red">注：对于外出地点为公司职场的例如：XX职场的使用外勤打卡无效，只有外出地点为外部地点的外勤打卡有效</font>

![image-20260408094508164](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408094508164.png)

二、查看[薪酬管理/考勤管理/管理员流程查询及申请/出差申请审批](http://121.28.192.238:8562/salary/attend/allapply)是否有对应审批通过的出差流程

![image-20260408094821172](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408094821172.png)

<font color="red">注意核实外勤打卡时间是否在开始结束时间内</font>

三、[薪酬管理/考勤管理/管理员流程查询及申请/外派申请审批](http://121.28.192.238:8562/salary/attend/allapply)

![image-20260408095123033](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408095123033.png)

<font color="red">注意核实外勤打卡时间是否在开始结束时间内</font>

四、查询该员工或员工所属项目是否在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/外勤项目设置](http://121.28.192.238:8562/salary/attend/attendancerecordrest)登记

注：登记的数据“确认考勤是否有效状态”必须为<font color="red">是</font>且外勤打卡时间必须处于外勤开始时间和外勤结束时间之内



![image-20260408095241517](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408095241517.png)

## 考勤机打卡无效

[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/无效打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)中有打卡机编号的记录为考勤机打卡无效的，常见情况为员工在非常驻工作地打卡，根据打卡地点查看员工在哪个职场打卡

![image-20260408100059455](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408100059455.png)

一、查看[薪酬管理/考勤管理/管理员流程查询及申请/外出申请审批](http://121.28.192.238:8562/salary/attend/allapply)是否有对应审批通过的外出流程

注：外出地点必须选择正确的公司职场，例如：外出到总部的，外出地点必须为<font color="red">总部交付职场</font>，外出地点填写为博岳大厦、总部基地、总部职能办公职场的流程在总部打卡都是无效的

![image-20260408094508164](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408094508164.png)

二、查看[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/多工作基地打卡绑定](http://121.28.192.238:8562/salary/attend/attendancerecordrest)中员工是否有对应的工作基地

该页面自动生成员工的常驻工作地数据，例如：图中员工2025年11月1日入职A职场；2026年4月1日转岗至B职场。那么该员工2025-11-01到2026-04-01的在A职场的打卡记录是有效的，自2026-04-01以后在B职场打卡是有效的![image-20260408102208059](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408102208059.png)

三、如果满足上述两种情形中的任意一种，员工在外职场打卡仍然无效，那么需要查询员工无效打卡的考勤机是否正确登记

首先在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/无效打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)中查询无效的打卡记录对应的打卡机编号![image-20260408100059455](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408100059455.png)

复制编号在[薪酬管理/考勤管理/考勤及门禁设备管理/考勤机登记和调拨/登记新](http://121.28.192.238:8562/salary/attend/attendanceequipmentmanagement)中查询该打卡机登记在哪个职场，注意要看考勤机的登记开始结束时间，如果没有对应信息需要登记完善

![image-20260408103725525](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260408103725525.png)
