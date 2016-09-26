# mygit
这是一个工具类，它可以异步下载网络图片资源，最后转化成bytearray，方便存储在sqlite中，调用setData（）方法，对方法中的参数进行设置，
 setData(String url,int Quality,RequestCallBack callBack)；
 url 请求地址； 
 Quality 为请求到的图片质量 最大值为100；
 callBack 回调借口 有两个方法；
 
