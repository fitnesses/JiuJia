## 申明：技术无罪，请勿用于盈利，如有冒犯请联系本人删除此项目
## 由于女朋友变前女友了(下家都找到了，我很是生气，所以一直没上传代码),这段时间看有人要，就上传了，你们自行修改吧，我不再维护了，谢谢，实在是抱歉

### 本项目用于抢购九价疫苗的预约号
- 抢购疫苗来源  
 - [X] 约苗  
 - [X] 成都市金牛区妇幼保健院服务号
 - [ ] 知苗易约  

### 本项目用golang编写，如果bug/建议请提issue或pr，如需本地运行，请自行交叉编译(右转谷歌/百度，有方法，这里不再赘述)

### 运行说明
```
1:请认真填写JiuJia/config/config.yml文件中的配置，如果不知道具体数据，请勿修改。这个配置是用yaml语法写的，注意缩进问题。

- 如果是运行 查看约苗有哪些城市有秒杀信息
命令：JiuJia seckill --config=/path/to/your/config.yml

- 如果是运行 从成都市金牛区妇幼保健院服务号中抢购
命令：JiuJia jinniu --config=/path/to/your/config.yml

- 如果是运行 从约苗中抢购
命令：JiuJia yuemiao --config=/path/to/your/config.yml

```
### 这还有一个java项目可以参考 https://github.com/lyrric/seckill
