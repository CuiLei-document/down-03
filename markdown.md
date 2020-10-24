# 学习的内容

1. 内容标签

* ul+li(ordered list + list item) 无序列表
* ol+li(unordered list + list item) 有序列表
* dl+dt+dd(description list + termfdata) 描述列表
* pre(previem 的缩写) 保留文字中的空格
* hr 分割线
* br 换行
* a(anchor) 链接
* em(emphasis) 倾斜 强调
* strong 加粗 重点
* code 让标签里面的文字一样宽
* quote 表示内联
* blockquote 表示 块级引用 


# 英语小课堂     翻译         助记  
1. hyper        超级         害怕
2. target       目标         她给他
3. reference    引用         refer+ence
4. frame        边框、框架   夫瑞么
5. error        错误         爱惹
6. blank        空白         不烂可儿
7. parent       父母之一     盼望他
8. self         自己         嗖夫
9. load         加载         露的
10. canvas      画布         看喂思

## a 标签的属性
1. herf 
2. target
3. download
4. rel=noopener
   
### a标签的作用
1. 作用跳转外部页面
2. 跳转内部锚点
3. 跳转邮箱或者打电话等！

#### a 标签的代码格式
    <a href="//baidu.com">百度</a>
    伪协议
    <a href="javascript:;">伪协议</a>
    锚链接
    <p id=xxx>跳转锚点Id</p>
    <a href="xxx">定义锚链接</a>
   ### a链接的取值
   1.   targer="_blank" 打开新页面
   2.   target="_top" 在最上级打开
   3.   target="parent" 当前页面打开
   4.   target="_self"  当前页面打开

### iframe标签
*   内置窗口-- 已经很少使用

## table 表格标签
*  代码格式
1. table表格
2. thend 头部
3. tbody 主体
4. tfoot 底部
5. tr 行
6. th 头
7. td 列

### 代码格式
    <table>
        <thead>
            <tr>
                <th></th>
                <td></td>
            </tr>
        </thead>
        <tbody></tbody>
        <tfoot></tfoot>
    </table>

## 相关样式
    <style>
        table {
            table-layout: auto fixed;
            auto 根据文字内容分配宽度，文字越多宽度越宽
            fixed 根据文字的内容平均分配

            border-spacing:0; 表格之间的距离为0
            border-collapse: collapse; 合并表格
        }
    </style>