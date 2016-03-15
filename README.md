# baidutext_4
百度第一场第四题  水平垂直居中

#### 法一：父容器填充屏幕   子容器设置position:relative; top:50%;margin-top:-100px;
#### 法二：margin-top:-100px;改成transform:translateY(-50%);
####　法三：flex布局 设置body display:flex;
####　                        align-items:center;//body内元素垂直居中
####　                        justify-content:center;//body内元素水平居中
