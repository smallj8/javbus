# javbus
javbus论坛每日签到
根据https://github.com/leeairw/Enshan 项目修改而来
只需将上述连接教程中的cookie_enshan改成cookie_javbus即可


Github Actions版本
1.点击项目右上角的Fork，Fork此项目
2.到自己Fork的项目点击Setting→Secrets→New secrets
3.Name填写cookie_enshan，Value填写 获取到的cookie
4.在"Actions"中的"run"下点击"Run workflow"即可手动执行签到，后续运行按照schedule，默认在每天凌晨0:30自动签到，可自行修改
