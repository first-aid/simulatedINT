# simulatedINT
利用signal和kill实现一个中断系统

模拟键盘按键作为中断信号，每次获取一个字母将其加入到队列中；
每次收到的字母会保存到链表中等待其处理
收到一个字母则发送一次用户信号，
信号处理函数会依次处理收到的按键信号




