一个mmo游戏，底层基于自写C#框架lbGame
可以很好的和Unity3d整合搭配使用

这套代码
改了一些ngui
和底层框架

###还是老问题，框架看起来很美，实际上人一多做起来很乱的
例如：Iselfplayer,Iplayer,Ientity几个类，名字上看是接口（实际上是实体类），一个Move动作的实现，写了很多个方法，这几个类互相继承，代码互相交互，很难调试
###还有，很多实现都基于服务器（服务器写的真稳定）
所以，先不管框架，要做到客户端和服务器分离
###客户端和服务器解耦后，才能再理清框架
1.FSM
2.MVC
3.BattleGame
4.其他工具
