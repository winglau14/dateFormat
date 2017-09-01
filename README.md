# dateFormat
### 参数描述
## 
var option ={
        time: '2017-08-31 16:31:02',
        type: ['/', '/'],
        formatYear: false,
        formatDate: true
     }
##
     time为需要转换的时间，格式可以是时间戳or时间字符串
     type为需要转换的格式类型，需是array，如需显示2017年08月01日格式，则传['年','月','日']，如需显示2017-08-01格式，则传['-','-','-']，如需显示2017/08/01格式，则传['/','/']
     formatYear为是否显示年月日，需是bool，true显示，false不显示
     formatDate为是否显示时分秒，需是bool，true显示，false不显示
     formatYear && formatYear 同时为true，则显示年月日 时分秒
     默认这两个值可以不传
