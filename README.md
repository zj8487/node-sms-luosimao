# node-sms-luosimao

http://luosimao.com/docs/api/20#send_msg


## demo
 
```
var sms = require("./index");

sms.key = process.env.LSM_KEY

sms.send('18612189317', '测试1~~【小斑马货栈】', function(error, res, body){
  console.log(body);
});
``` 