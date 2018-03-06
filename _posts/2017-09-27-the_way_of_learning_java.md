---
ID: 30
post_title: Java如何入门及提高
post_name: the_way_of_learning_java
post_date: 2017-09-27 21:59:25
layout: post
link: >
  http://www.233lab.com/the_way_of_learning_java/
published: true
tags:
  - Java
  - 折腾技术
categories:
  - Java
---
<div class="pure-u-1 pure-u-md-3-4">
<div class="content_container">
<div class="post">
<div class="post-content">
<h3 id="不走弯路，就是捷径" style="text-align: left;"><span style="font-size: 18pt;">不走弯路，就是捷径</span></h3>
<span style="font-size: 14pt;">做任何事情，最好都要有计划，学习Java也是，什么时候开始学习Servlet，JSP，什么时候开始玩框架，有了规划，就可以稳扎稳打，多实践，多练习，多Coding，自然就会有提升。</span>

<span style="font-size: 14pt;">本文也是给我做了一个学习规划，我将会在Java学习之路中，逐步更新每个阶段的学习心得以及遇到的问题，欢迎大家斧正。</span>
<h3 id="明确方向-坚定信心" style="text-align: left;"><span style="font-size: 18pt;">明确方向 坚定信心</span></h3>
首先，要有 <strong><em>兴趣 </em></strong>。兴趣是坚持下去的动力。不要浮躁，不要想着今天学会了<code>if else</code>，明天就去学多线程。要明确，学习编程没有想象的那么简单，必须要 <strong><em>多Coding，多思考，多Google </em></strong>。
<h3 id="软件开发学习路线"><span style="font-size: 18pt;">软件开发学习路线</span></h3>
<span style="font-size: 14pt;">从软件开发人员的生涯规划来看，可以大致分为三个阶段：</span>
<blockquote><span style="font-size: 14pt;">软件工程师—&gt;软件设计师—&gt;架构设计师</span></blockquote>
<span style="font-size: 14pt;">当然，每个人的职业发展规划都不相同，你可以根据自己感兴趣的方向发展。</span>
<span style="font-size: 14pt;"> 让我们整理一下需要学习的主要技术：</span>
<ul>
 	<li><span style="font-size: 14pt;">A.基础理论知识，如操作系统，编译原理，数据结构与算法，计算机原理等，这些内容并非不重要，如果不想成为计算机科学家，可以采取“用到的时候再学”的原则。当然，基础的数据结构和算法知识还是必备的，后面会专门介绍。</span></li>
 	<li><span style="font-size: 14pt;">B.一门编程语言，现在基本上都是面向对象的，这里我们用的是JAVA。</span></li>
 	<li><span style="font-size: 14pt;">C.一种思想：面向对象的思想，这个很重要。</span></li>
 	<li><span style="font-size: 14pt;">D.一种关系型数据库，Oracle/SqlServer/DB2/MySQL等，我学的是MySQL。</span></li>
 	<li><span style="font-size: 14pt;">E.一种提高生产率的IDE（集成开发环境），Java我用的是IntelliJ IDEA。</span></li>
 	<li><span style="font-size: 14pt;">F.一种UML建模工具，一般用Visio，笔进行建模。</span></li>
 	<li><span style="font-size: 14pt;">G.一种软件过程。RUP/XP/CMM等。通过软件过程来组织软件开发的众多活动，使得开发流程专业化，规范化。我还没接触过。</span></li>
 	<li><span style="font-size: 14pt;">H.项目管理、体系结构、框架知识。这块的书籍豆瓣上找找看，经典蛮多的。</span></li>
</ul>
<span style="font-size: 14pt;">路线可以是<code>B---&gt;C---&gt;E---&gt;F---&gt;G---&gt;H</code></span>
<blockquote>
<ul>
 	<li><span style="font-size: 14pt;">A和C是在不断的实践中逐步领悟编程理论与编程思想的。新技术虽然不断涌现，更新速度令人眼花缭乱，雾里看花，但是万变不离其宗，编程理论与编程思想的变化却很慢。掌握编程理论和编程思想就会有拨云见日之感。</span></li>
 	<li><span style="font-size: 14pt;">D.数据库可以在学习Java的时候一起学习，MySQL买本<a href="https://book.douban.com/subject/3354490/" target="_blank" rel="external noopener">《MySQL必知必会》</a>来上手就好。</span></li>
 	<li><span style="font-size: 14pt;">软件工程师注重<code>B、C、E、D</code>，软件设计师注重<code>B、C、D、E、F</code>，架构师注重<code>C、F、H</code>。</span></li>
</ul>
</blockquote>
<h4 id="Java学习路线"><span style="font-size: 18pt;">Java学习路线</span></h4>
<span style="font-size: 14pt;">首先说下我所接触到的Java应用场景：</span>
<ul>
 	<li><span style="font-size: 14pt;">Java Web 开发</span></li>
 	<li><span style="font-size: 14pt;">大数据方向(Hadoop)</span></li>
 	<li><span style="font-size: 14pt;"><a href="http://stormzhang.com/android/2014/07/07/learn-android-from-rookie/" target="_blank" rel="external noopener">Android</a></span>
<span style="font-size: 14pt;"> 大家根据自己喜欢的方向，学习相关内容就好。由于我对Hadoop方向也在摸索中，所以不进行推荐，大家可自行Google。</span></li>
</ul>
<h4 id="第一阶段：Java基础"><span style="font-size: 14pt;">第一阶段：Java基础</span></h4>
<span style="font-size: 14pt;">牢记：<strong><em> 基础不牢靠，如同沙地上建摩天大厦，一触即倒</em></strong></span>
<ul>
 	<li><span style="font-size: 14pt;">这个阶段主要学习:</span>
<ul>
 	<li><span style="font-size: 14pt;">Java基础语法</span></li>
 	<li><span style="font-size: 14pt;">面向对象思想：对象与类、继承与多态</span></li>
 	<li><span style="font-size: 14pt;">集合、泛型</span></li>
 	<li><span style="font-size: 14pt;">异常处理</span></li>
 	<li><span style="font-size: 14pt;">IO</span></li>
 	<li><span style="font-size: 14pt;">多线程</span></li>
 	<li><span style="font-size: 14pt;">网络编程</span></li>
 	<li><span style="font-size: 14pt;">JDBC</span></li>
</ul>
</li>
 	<li><span style="font-size: 14pt;">多Coding，多思考，多Google</span></li>
 	<li><span style="font-size: 14pt;">可以开始数据库的学习，学习Java累了，可以看看数据库。MySQL<a href="https://book.douban.com/subject/3354490/" target="_blank" rel="external noopener">《MySQL必知必会》</a>。</span></li>
 	<li><span style="font-size: 14pt;">推荐书籍：<a href="https://book.douban.com/subject/6529833/" target="_blank" rel="external noopener">《Java语言程序设计（基础篇）》</a>,我个人看过<a href="https://book.douban.com/subject/25762168/" target="_blank" rel="external noopener">《Java核心技术》</a>以及<a href="https://book.douban.com/subject/25959184/" target="_blank" rel="external noopener">《疯狂Java讲义》</a>还有<a href="https://book.douban.com/subject/2607402/" target="_blank" rel="external noopener">《Head First Java》</a>，最终还是选了Java语言程序设计。</span>
<span style="font-size: 14pt;"> 原因是疯狂Java讲义书厚字小，实在让人提不起兴趣，Java核心技术个人不喜欢它的代码块，太小，看着累。Head First Java 这本书看着蛮有趣的，但是可能我觉得太中二了，所以入门书籍看自己喜好，随便选一本就好，不用过多的纠结于此事。</span>
<span style="font-size: 14pt;"> 然后想看视频的可以配合视频讲解，这里推荐马士兵老师的视频，我是先看了书再去看视频的，算是知识加固吧。最重要的是，把书上的习题每个敲代码实现一遍。《Java语言程序设计》的编程题答案可向我咨询。</span></li>
</ul>
<h4 id="第二阶段：实战项目"><span style="font-size: 14pt;">第二阶段：实战项目</span></h4>
<span style="font-size: 14pt;">在学习语言的时候，最纠结的事情就是找项目了，去Google找项目或者自己想实现一个爬虫，一个BBS都可以，把第一阶段所学到的东西试着应用进去，后续会更新我的练手项目上来。</span>
<span style="font-size: 14pt;"> 这个阶段可以继续深入学习数据结构和算法知识。</span>
<span style="font-size: 14pt;"> 推荐书籍：<a href="https://book.douban.com/subject/6424904/" target="_blank" rel="external noopener">《大话数据结构》</a>以及<a href="https://book.douban.com/subject/10432347/" target="_blank" rel="external noopener">《算法(第四版)》</a>。</span>
<span style="font-size: 14pt;"> Java继续深造书籍：<a href="https://book.douban.com/subject/2130190/" target="_blank" rel="external noopener">《Java编程思想》</a>，<a href="https://book.douban.com/subject/3360807/" target="_blank" rel="external noopener">《Effective Java》</a>，至于先看后看的问题，看自己的选择，我是先阅读Java编程思想。</span>
<span style="font-size: 14pt;"> 另外，关于多线程的书，推荐：<a href="https://book.douban.com/subject/10484692/" target="_blank" rel="external noopener">《Java并发编程实战》</a>，这本书讲解并发编程十分详细，可根据基础书籍延伸阅读，主要是在做项目中应用，慢慢上手。</span>
<ul>
 	<li>
<h6 id="Android方向"><span style="font-size: 14pt;">Android方向</span></h6>
<span style="font-size: 14pt;">可以在这里进行下一步学习，推荐阅读<a href="http://stormzhang.com/android/2014/07/07/learn-android-from-rookie/" target="_blank" rel="external noopener">Android学习之路</a>,书籍推荐：<a href="https://book.douban.com/subject/25942191/" target="_blank" rel="external noopener">《第一行代码》</a>，Linux基础要开始修炼：<a href="https://book.douban.com/subject/4889838/" target="_blank" rel="external noopener">《鸟哥的Linux私房菜.基础学习篇（第三版）》</a></span></li>
</ul>
<h4 id="第三阶段：Java-Web基础"><span style="font-size: 14pt;">第三阶段：Java Web基础</span></h4>
<span style="font-size: 14pt;">这个阶段学习HTML、CSS、JavaScript的基础语法，学习Dom编程基础。可以看<a href="https://book.douban.com/subject/6038371/" target="_blank" rel="external noopener">《JavaScript DOM编程艺术》</a>。咨询了前端的小伙伴，HTML/CSS入门可以看看Head First系列，<a href="https://book.douban.com/subject/3040870/" target="_blank" rel="external noopener">《Head First HTML与CSS（第2版）》</a></span>
<h4 id="第四阶段：Servlet-amp-JSP"><span style="font-size: 14pt;">第四阶段：Servlet &amp; JSP</span></h4>
<span style="font-size: 14pt;">这个阶段主要学习tomcat基础、servlet基础、web.xml配置基础、web application的结构、servlet生命周期、request response等常用方法、ServletContext类、HTTP协议基础（GET POST）、Cookie Session Application、JSP的几种语法（包括JSTL等）。</span>
<span style="font-size: 14pt;"> 推荐书籍：<a href="https://book.douban.com/subject/1942934/" target="_blank" rel="external noopener">《Head First Servlets &amp; JSP》</a></span>
<h4 id="第五阶段：实战项目"><span style="font-size: 14pt;">第五阶段：实战项目</span></h4>
<span style="font-size: 14pt;">学了这么多，一定要项目实战巩固巩固。</span>
<span style="font-size: 14pt;"> 推荐书籍：<a href="https://book.douban.com/subject/19965586/" target="_blank" rel="external noopener">《深入分析Java Web技术内幕》</a>,<a href="https://book.douban.com/subject/24722612/" target="_blank" rel="external noopener">《深入理解java虚拟机》</a>。</span>
<h4 id="第六阶段：框架学习：Struts-Hibernate-Spring">第六阶段：框架学习：Struts/Hibernate/Spring</h4>
<span style="font-size: 14pt;">框架的学习就此开始~可以配套视频学习</span>
<span style="font-size: 14pt;"> 书籍推荐：<a href="https://book.douban.com/subject/1943128/" target="_blank" rel="external noopener">《How Tomcat Works》</a>,<a href="https://book.douban.com/subject/7154446/" target="_blank" rel="external noopener">《Struts2技术内幕》</a>,<a href="https://book.douban.com/subject/4199483/" target="_blank" rel="external noopener">《Spring技术内幕》</a>。</span>
<h4 id="第七阶段：设计模式学习">第七阶段：设计模式学习</h4>
<span style="font-size: 14pt;">推荐书籍：<a href="https://book.douban.com/subject/2334288/" target="_blank" rel="external noopener">《大话设计模式》</a>。</span>
<h4 id="其他方面"><span style="font-size: 14pt;">其他方面</span></h4>
<ul>
 	<li>
<h5 id="勤查API文档"><span style="font-size: 14pt;">勤查API文档</span></h5>
</li>
 	<li>
<h5 id="多Google"><span style="font-size: 14pt;">多Google</span></h5>
</li>
 	<li>
<h5 id="学习开源软件的设计思想"><span style="font-size: 14pt;">学习开源软件的设计思想</span></h5>
</li>
</ul>
<span style="font-size: 14pt;">编程的学习是贵在坚持，有了规划就应该一步一步的打牢基础，多实战，多Google，多思考，这样才会有进步，与君共勉。</span>

</div>
</div>
</div>
</div>
&nbsp;