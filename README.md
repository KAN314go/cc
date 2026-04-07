本地包文件举例，下载群文件纯福利，密码看置顶。手机文件夹解压到手机根目录，打卡影视，点文件选路径里的 纯福利.json确定开看呗。

群里写好的一般是三种，看到第一时间下载到手机

某某.py
用mt管理器，编辑纯福利.json
        {
            "key": "某某", 
            "name": "某某",
            "type": 3,
            "searchable": 1,
            "quickSearch": 1,
            "filterable": 1,
            "api": "./PY1/某某.py",
            "order_num": 5,
            "ext": ""
        },   
 保存开看

第二种 xbpq，一大串文本。

    {
      "key": "某某",
      "name": "某某",
      "type": 3,
      "quickSearch": 1,
      "searchable": 1,
      "changeable": 0,
      "filterable": 1,
      "jar": "./jar/XBPQ.jar",        
      "timeout": 60,
      "style": {
        "type": "rect",
        "ratio": 1.78
      },
      "api": "csp_XBPQ",
      "ext": {把人家发的内容放这里}
},


第三种 txt、m3u8、json等直播文件放纯福利里对应的文件夹里呗

注意文件夹，不要乱改名，乱放位置，编辑json要核对好英文符号，文件路径



"jar": "./XBPQ.jar",
代表意思是一级目录，如果你用纯福利包，就得该为
"jar": "./jar/XBPQ.jar",
代表的意思是，调用的是纯福利[文件夹]里的jar[文件夹]里的XBPQ.jar
