# zbsxmenu
爬取闸北实验小学网站菜单，输出到日历  
 文件说明：      
 ### creater_ics_v1   
  * 仅更新网站第一页的菜单列表，需要每周生成一次ics    
 ### creater_ics_v2 
  * 优化v1部分代码  
  * 增加课程表信息
    
    > 字典course_schedule  自义定课程表  
    > 列表holidays         自定义假期  
    > 字典specialworkdays  自定义换休工作日和对应星期号  
    > 字典time_schedule    自定义常规时间  
  * 增加天气预报（5天,来源：上海气象局api）  
    ————————————————————
    ### 更新计划   
*  代码暂时需要每周手动执行  
*  跨年时日期会产生bug，代码待更新  
*  后续加上课程表（V2已完成）  
*  增加自定义课表 （完成）  
*  增加天气预报（完成）  
