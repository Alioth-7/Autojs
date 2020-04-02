
var comparewrite=
[
    {
        title:"help",
        num:"&help\n&搜索......     (电影....)\n$.....              (和Alioth聊天)\n&百科......        (百科全书)",
    },
    {
        title:"自重启教程",
        num:"http://rrd.me/g3gWp"
    },
    {
        title:"教程",
        num:"这里可能会有你想要的，补充中...\nhttp://rrd.me/g2ed2",
    },
    {
        title:"JavaScript",
        num:"JavaScript教程\nhttps://www.w3school.com.cn/js/index.asp",
    },
    {
        title:"Json",
        num:"Json教程  \nhttps://www.w3school.com.cn/json/index.asp",
    },
    {
        title:"Java",
        num:"Java教程\nhttps://www.w3school.com.cn/p.asp#java",
    },
    {
        title:"条件",
        num:"条件语法\nhttps://www.w3school.com.cn/js/js_if_else.asp",
    },
    {
        title:"对象",
        num:"JS对象\nhttps://www.w3school.com.cn/js/js_objects.asp",
    },
    {
        title:"日期",
        num:"日期\nhttps://www.w3school.com.cn/js/js_dates.asp",
    },
    {
        title:"正则表达式",
        num:"正则表达式\nhttps://www.w3school.com.cn/js/js_regexp.asp",
    },
    {
        title:"性能",
        num:"JS性能\nhttps://www.w3school.com.cn/js/js_performance.asp",
    },
    {
        title:"JS Json",
        num:"JS Json\nhttps://www.w3school.com.cn/js/js_json_intro.asp",
    },
    {
        title:"多线程",
        num:"多线程\nhttps://hyb1996.github.io/AutoJs-Docs/#/threads",
    },
    {
        title:"应用",
        num:"应用\nhttps://hyb1996.github.io/AutoJs-Docs/#/app",
    },
    {
        title:"全局函数",
        num:"全局函数\nhttps://hyb1996.github.io/AutoJs-Docs/#/globals",
    },
    {
        title:"控制台",
        num:"控制台\nhttps://hyb1996.github.io/AutoJs-Docs/#/console",
    },
    {
        title:"坐标",
        num:"坐标\nhttps://hyb1996.github.io/AutoJs-Docs/#/coordinatesBasedAutomation",
    },
    {
        title:"设备",
        num:"设备\nhttps://hyb1996.github.io/AutoJs-Docs/#/device",
    },
    {
        title:"对话框",
        num:"对话框\nhttps://hyb1996.github.io/AutoJs-Docs/#/dialogs",
    },
    {
        title:"脚本引擎",
        num:"脚本引擎\nhttps://hyb1996.github.io/AutoJs-Docs/#/engines",
    },
    {
        title:"事件监听",
        num:"事件监听\nhttps://hyb1996.github.io/AutoJs-Docs/#/events",
    },
    {
        title:"悬浮框",
        num:"悬浮框\nhttps://hyb1996.github.io/AutoJs-Docs/#/events",
    },
    {
        title:"文件系统",
        num:"文件系统\nhttps://hyb1996.github.io/AutoJs-Docs/#/files",
    },
    {
        title:"HTTP",
        num:"HTTP\nhttps://hyb1996.github.io/AutoJs-Docs/#/http",
    },
    {
        title:"图片与颜色",
        num:"图片与颜色\nhttps://hyb1996.github.io/AutoJs-Docs/#/images",
    },
    {
        title:"画布",
        num:"画布\nhttps://hyb1996.github.io/AutoJs-Docs/#/canvas",
    },
    {
        title:"按键模拟",
        num:"按键模拟\nhttps://hyb1996.github.io/AutoJs-Docs/#/keys",
    },
    {
        title:"多媒体",
        num:"多媒体\nhttps://hyb1996.github.io/AutoJs-Docs/#/media",
    },
    {
        title:"模块",
        num:"模块\nhttps://hyb1996.github.io/AutoJs-Docs/#/modules",
    },
    {
        title:"基于控件的操作",
        num:"基于控件的操作\nhttps://hyb1996.github.io/AutoJs-Docs/#/widgetsBasedAutomation",
    },
    {
        title:"传感器",
        num:"传感器\nhttps://hyb1996.github.io/AutoJs-Docs/#/sensors",
    },
    {
        title:"shell",
        num:"shell\nhttps://hyb1996.github.io/AutoJs-Docs/#/shell",
    },
    {
        title:"本地存储",
        num:"本地存储\nhttps://hyb1996.github.io/AutoJs-Docs/#/storages",
    },
    {
        title:"定时器",
        num:"定时器\nhttps://hyb1996.github.io/AutoJs-Docs/#/timers",
    },
    {
        title:"用户界面",
        num:"用户界面\nhttps://hyb1996.github.io/AutoJs-Docs/#/ui",
    },
    {
        title:"调用",
        num:"调用\nhttps://developer.mozilla.org/zh-CN/docs/Mozilla/Projects/Rhino/Scripting_Java",
    },
]
files.write("/sdcard/Pictures/脚本/compare.json" , JSON.stringify(comparewrite))
var compareload=JSON.parse(files.read("/sdcard/Pictures/脚本/compare.json" ))
for(i=0;compareload[i];i++)
{
    log(compareload[i].title)
    log(compareload[i].num)
}





//t.put("items", "compare")


//log(compareload[1].num)

//files.close