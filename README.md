## **考勤管理常见问题**

## 钉钉有打卡记录但薪酬系统无考勤记录

一、[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)，重新拉取考勤记录，看是否能够拉取成功，如果拉取不到出勤记录详见[出勤记录无法拉取](#出勤记录无法拉取)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/MTY4ODg1NzM4NzY1MzgwOQ_108072_yA2VR82Gl8QrXIEe_1765166087)

二、能成功拉取考勤记录，但是计算后员工考勤记录会进入到无效打卡记录

无效打卡记录查询路径：[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/无效打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)

![image-20260407182815549](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407182815549.png)

无效打卡的情景

1、员工使用外勤打卡，需要核实员工对应时间段是否有

2、员工

## 出勤记录无法拉取

1、[薪酬管理/员工管理/员工档案](http://121.28.192.238:8562/salary/staff/staffmanagement)-详情查看员工钉钉手机号与钉钉号与[钉钉后台/成员管理](https://oa.dingtalk.com/contacts.htm#/contacts)对应信息是否一致，不一致的按照实际情况修改正确，详见[钉钉号修改](#钉钉号修改)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407102548768.png)

![imge](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407102842384.png)

2、如果信息一致的，导出考勤记录看是否有多个钉钉号

![image-20260407120227937](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407120227937.png)

如果有多条钉钉号的需要在[薪酬管理/考勤管理/出勤记录/不同钉钉号维护](http://121.28.192.238:8562/salary/attend/attendancerecordrest)对应月份进行维护

![image-20260407175654599](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407175654599.png)

<font color="red">注意：对于有多个钉钉号的，此页面中员工现有钉钉号的创建时间要为最新的</font>

![image-20260407180733581](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407180733581.png)

## 钉钉号修改

需要修改钉钉号的情景

一、没有钉钉号

在职员工在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉编号不完整-在职](http://121.28.192.238:8562/salary/attend/attendancerecordrest)查询后完善钉钉号

离职员工在[薪酬管理/考勤管理/出勤记录/钉钉打卡记录/钉钉编号不完整-离职](http://121.28.192.238:8562/salary/attend/attendancerecordrest)查询后完善钉钉号

二、钉钉号不正确

点击[薪酬管理/员工管理/员工档案](http://121.28.192.238:8562/salary/staff/staffmanagement)详情按照以下步骤修改

1、先置空员工钉钉号，然后修改员工钉钉手机号为正确的，然后保存信息

![image-20260407181801529](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407181801529.png)

2、[薪酬管理/考勤管理/出勤记录/钉钉打卡记录](http://121.28.192.238:8562/salary/attend/attendancerecordrest)按人重新拉取考勤记录或入职补卡，更新员工钉钉号

![image-20260407182430654](https://gitee.com/bytxrl/wiki-images/raw/master/image-20260407182430654.png)
