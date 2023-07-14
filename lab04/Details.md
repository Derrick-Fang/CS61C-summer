# 过程细节

## 变量

a0: 链表头指针

a1: 函数指针

struct{
int _ arr;
int size;
struct node_ next;
}

t1: 当前头指针
t2: 循环次数

t0: 统计循环次数

## 易错点

- 注意 lw 和 add 区别 一个是加载，一个仅仅是地址复制
- 注意数组循环访问的偏移量
