# leetcode2016-12-1
begin at 2016-12-1 0:00


--1--
two sum
// 刚刚做完了第一题 Two Sum 虽然easy到爆了但是在阅读英文题目的过程中还是很开心的，还看了解释，我个人使用的是暴力破解，复杂度肯定喳喳了，

//先把vector拷贝到一个n＊2的矩阵，复杂度N，空间复杂度N，第二维是记录index
//然后快速排序NlogN，复杂度，然后左右逼近，复杂度N
//从左开始如果最小的加最大的小于target，就继续从左移动，如果大于tatget，就从右移动，如果等于target，还是左移。

--2--
Add Two Numbers
（1）
 第一次做的我用的脑残的嗯两个list想加，但是木有考虑到list长度不一样,后来又加上了如果截止了咋整的方法。
 其中学到了很多啦，比如carry是英文进位，我每次next先用carry初始化，然后记录最后一位前一个，判断下最后一个是不是0，决定保存不。
 嘻嘻嘻。熟悉了list操作和赋值 是否重复指定。     
（2）
 学长教了我法二，先都转化为十进制，想加，再十进制解码大雾，他说用了傅里叶变换的启发？？！！分别变换！！？？ （并没有写）
（3）
写了个根据答案启发版本的
（4） 
 至于答案，依旧如此精彩，我终于补完了心得，一会去改github 并加上md@杨炫越 感谢提醒
 
