# myUtils
1、getbitmapbytearray
这是一个工具类，它可以异步下载网络图片资源，最后转化成bytearray，方便存储在sqlite中，调用setData（）方法，对方法中的参数进行设置，
 setData(String url,int Quality,RequestCallBack callBack)；
 url 请求地址； 
 Quality 为请求到的图片质量 最大值为100；
 callBack 回调借口 有两个方法；
 2、UpdateTime
 这是一个动态更新时间的类，getUpdateTime(long time,boolean isToSecond)这个方法中的两个参数分别代表（time）过去时期的毫秒数，（isToSecond）是否精确到秒级别，比如几秒前更新。
 
