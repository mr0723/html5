html标签：
1.预定义文本标签pre（保留空格和换行）
    <pre>
        123123312132321
        1321321231
        lkj l   lkj lk 
    </pre>
    输出的格式和pre标签里的格式都一致
2.对html转义（在浏览器界面输出html的标签）
    &lt;body&gt;
3.缩写说明（对一个文字的内容进行解释）
    <abbr title='Hyper text Markup language'>Html</abbr>
    鼠标移入到html上面的时候，就会出现一串解释说明文字。
4.table里面的合并：
    colspan='2'横坐标两格的合并
    rowspan='3'一列里面三格的合并
5.a链接新窗口的跳转:target='_blank'
    <a href='http://www.baidu.com' target='_blank'>百度</a>
6.select如何进行多项选择（multiple='multiple'）
    <select multiple='multiple'>
        <option>---请选择---</option>
        <option>红色</option>
        <option>黄色</option>
        <option>蓝色</option>
    </select>
    按住ctrl，就可以选择多个了
7.单项选择
<1>name值一致的时候，就可以进行单项选择。
    <input type='radio' name='sex'>男</input>
    <input type='radio' name='sex'>女</input>
<2>点击文字的时候，也可以获取到选择（设置id）
    <input type='radio' name='sex' id='man'> <label for='man'>男</label></input>
    <input type='radio' name='sex' id='woman'> <label for='woman'>女</label></input>
<3>input的重置和提交 ：
    <input type='reset'>重置</input>   <input type='submit'>提交</input>
8.两个多媒体标签：audio video
    <1>.<audio src='xxx.mp3' controls='controls' autoplay='autoplay'></audio>
        ##autoplay自动播放
        ##有的浏览器不支持mp3的格式，所以需要对它进行转化。或者直接写两个格式：MP3或者ogg.  eg:
        <audio src='xxx.mp3' controls='controls' autoplay='autoplay'>
            <source src='xxx.mp3' type='audio/mpeq'></source>
            <source src='xxx.ogg' type='audio/ogg'></source>
        </audio>
    <2>.<video src='xxx.mp4' ontrols='controls' autoplay='autoplay' loop='3'></video>
        ##loop循环播放。
        
        
  9.<header></header>内容的头部都可以用
    <nav></nav>导航栏
    <article>文章，评论标签。
    <section></section>章节段落
    <aside></aside>文章旁边的一些推荐内容。
    <footer></footer>底部的信息
    <hgroup></hgroup>主副标题
10.<details></details>定义文档细节
        <details>
            <summary>你可能对这些感兴趣</summary>
            <p>怎么学习？</p>
            <p>需要使用什么开发工具</p>
        </details>
11.<input>标签
    