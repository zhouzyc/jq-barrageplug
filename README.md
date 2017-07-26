#jq 弹幕插件
1.支持随机滚动|序列无覆盖滚动
2.支持弹幕循环重复滚动
//        top: '0',
//        left: '0',
//        right: '0',
//        bottom: '0',
//        width: '100%',
//        height: '50%',
//        background:'rgba(0,0,0,0.5)',
//        data:['111','33333'],//type == data  必须 json 数据格式['a','b']
//        paddingNumber: 30,//弹幕上下边距距离
//        sleep:20,//弹幕速度系数 越大越慢
//        pattern:'random',//弹幕模式 random 随机 sequence 队列模式
//        sequenceSpaceTime:4000,// sequence 队列模式 每个弹幕之前间隙时间 决定了两个弹幕距离不重复
//        tops:[{'top':1}, {'top':36}, {'top':71}, {'top':106}],//sequence 队列模式  设置 每列的top
//        loopNumber:false//是否循环弹幕,默认关闭,设置数组为循环弹幕数量