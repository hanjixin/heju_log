# heju_log
## 2017/10/17
```
vonic 组件开发及使用
OA系统前端样式修改
A:link {
    /* COLOR: #000; */
    /* TEXT-DECORATION: underline; */
}
.nav-icon img {
    width: 100%;
    height: 100%;
    position: relative;
    top: 15px;
    left: -10px;
}
```
## 2017/10/18
```
完善我的页面

完成登录页面
vonic 模态框的关闭 ## 待解决
使用vuex解决模态框无法关闭的问题
登录界面完成
```
## 2017/10/19
```
- 修改
超链接样式，不要下划线	1
头像图片改为圆形的	1
搜索项默认第一个是人员，搜索结果在内容展示区域iframe里呈现	
左侧菜单，去掉下划线，可以通过后台配置菜单项，需要带icon	保持写死状态
所有系统内部弹出页面，全部在右侧内容展示区域iframe呈现，保留上部登录状态，外部页面直接弹出	
需要增加雾霾指数	
增加版本号，自行设计规则。	1
和君新闻、通知公告、我的课程、培训手册内容需要完善	
右上角登录菜单加一个修改密码链接	1
顶部空白区域去掉	1
后端应用中心菜单，加在门户上，用权限控制	
       ## 流程下面修改链接
              * 待办事宜：/workflow/request/RequestView.jsp
              * 新建流程：/workflow/request/RequestType.jsp
              * 已办事宜：/workflow/request/RequestHandled.jsp
              * 流程督办：/workflow/search/RequestSupervise.jsp
              * 我的请求：/workflow/request/MyRequestView.jsp
              * 流程代理：/workflow/request/wfAgentStatistic.jsp
              * 查询流程：/workflow/search/WFSearch.jsp
              * 批量打印：/workflow/request/WorkflowMultiPrintTree.jsp
              * 流程监控：/system/systemmonitor/workflow/WorkflowMonitor.jsp
              * 自定义查询：/workflow/search/CustomSearch.jsp
              * 流程存为文档：/system/systemmonitor/workflow/WorkflowToDoc.jsp
              * 流程回收站：/workflow/search/RequestDeleteSearch.jsp
        ## 知识模块
               新建文档：/docs/docs/DocList.jsp?
               我的文档：/docs/search/DocMain.jsp?urlType=5
               查询文档：/docs/search/DocMain.jsp?urlType=14
               文档目录：/docs/search/DocMain.jsp?urlType=6
               虚拟目录：/docs/docdummy/DocDummyList.jsp
               最新文档：/docs/search/DocMain.jsp?urlType=0
               知识排名：/docs/search/DocMain.jsp?urlType=2
               文档订阅：/docs/search/DocMain.jsp?urlType=7
               批量共享：/docs/search/DocMain.jsp?urlType=13
               移动复制：/docs/search/DocSearchTab.jsp?_fromURL=3
               文档监控：/docs/search/DocSearchTab.jsp?_fromURL=5
               我的云盘：/rdeploy/chatproject/doc/index.jsp
        ## 人事模块
        人事模块下链接：
                查询人员：/hrm/search/HrmResourceSearch_frm.jsp
                新建人员：/hrm/resource/HrmResource_frm.jsp
                我的卡片：/hrm/HrmTab.jsp?_fromURL=HrmResource
                我的下属：/hrm/HrmTab.jsp?_fromURL=HrmResourceView
                我的培训：/hrm/HrmTab.jsp?_fromURL=HrmResourceTrainRecord
                我的工资：/hrm/HrmTab.jsp?_fromURL=HrmResourceFinanceView
                奖惩考核：/hrm/HrmTab.jsp?_fromURL=HrmResourceRewardsRecord
                我的考勤：/hrm/HrmTab.jsp?_fromURL=HrmResourceAbsense
                在线人员：/hrm/resource/OnlineUser_frm.jsp
                密码设置：/hrm/HrmTab.jsp?_fromURL=HrmResourcePassword
                人员生日：/hrm/HrmTab.jsp?_fromURL=HrmBirthdayInfo
                外勤签到：/hrm/HrmTab.jsp?_fromURL=mobileSignIn
                我的排班：/hrm/schedule/hrmScheduleSet/tab.jsp?topage=myschedule

```
## 免费接口API
       http://blog.csdn.net/lixuce1234/article/details/65937155
## 2017/10/20
    :
首页:/homepage/Homepage.jsp?hpid=23&subCompanyId=44
通知与新闻：
```
    综合新闻页：
    财务新闻页：
    人力资源新闻页：
    流程中心：/workflow/request/RequestView.jsp
    报表中心：
    人力资源：/hrm/search/HrmResourceSearch_frm.jsp
    会议：/meeting/data/MeetingCalView.jsp
    项目中心：/formmode/search/CustomSearchBySimple.jsp?customid=1
    客户中心：/formmode/search/CustomSearchBySimple.jsp?customid=41
    资产中心：/formmode/search/CustomSearchBySimple.jsp?customid=82
    课程中心：
    资产与文档：/docs/search/DocSearchTab.jsp?_fromURL=4
    :
    会议：/meeting/report/MeetingRoomPlan.jsp?canEdit=1
```
## 2017/10/23
```
oa 移动端登录页面
OA home页面
OA list 页面


OA 和君登录系统 
     删除 oa-main-arrange部分
     修改首页链接
     以及页面优化的问题
```
## 2017/10/25
 > 修改滚动条，头部我的流程，与我相关，左侧菜单弹出方式，固定宽高
 ## 2017/10/26
 ```
 
 
 :
1)流程中心：新建流程、待办流程、我的流程、已办流程、流程监控（管理员）
2)人力资源：通讯录、查询人员、新建人员（管理员）、我的下属（没有下属不显示）、我的培训、在线人员（管理员）、密码设置、人员生日（不带手机号）
3)资产与文档：新建文档、我的文档、查询文档、文档目录、最新文档、知识排名、移动复制（管理员）、文档监控（管理员）
:
通知与新闻链接：/docs/search/DocCommonContent.jsp?hasTab=1&offical=&officalType=-1&dspreply=&seccategory=104&urlType=6
 ```
 ## 2017/10/27
 ```
   修改菜单的左侧权限、
   页面再次修改宽度1250
   修改左侧的菜单宽度
   增加左上的    与我相关   和我的流程提示
   修改祝福语随机出现    及动画的添加
   修改快捷功能的顺序和样式

 ```
 ## 2017/12/11
 ```
   调研后台模板
 ```
  ## 2017/12/12
 ```
   打通权限验证（ing...）
 ```

  ## 2017/12/13
 ```
   打通权限验证（finish）
 ```
