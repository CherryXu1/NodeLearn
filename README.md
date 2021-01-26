<!--
 * @Descripttion: 
 * @Author: Fiona.xu
 * @version: 
 * @Date: 2021-01-26 12:40:32
 * @LastEditors: Fiona.xu
 * @LastEditTime: 2021-01-26 13:19:31
-->
# NodeLearn
Node运行于后台服务和浏览器前端之间的中间层,服务端渲染SSR（ServerSideRending）来提高搜索引擎抓取网页效果,以及网页展现首屏速度。
问题：
1.Node.js程序运行不稳定，经常出现服务不可用情况
2.Node.js运行效率低，每秒处理的请求数维持在一个很低水平
3.Node.js 前端对服务端不熟悉，日常开发中难以推广，强行推广作出了难以维护老代码
根据网站特点，内容型网站进行具体分析，为这种场景定制全新的Node.js框架，大大提高了开发效率程序稳定性以及性能。
在这个过程中，让我对
开发调试
架构设计
性能优化
灾备方案等方面有了深入了解。
Node.js被广泛用于Web服务，开发工作流，客户端应用等,在Web服务开发这个领域业界对Node.js接受程度最高。通常会被用来做一个BFF层即Backend For Frontend（服务于前端的后端）通俗的说就是一个为前端业务提供数据的后端程序。特点：不需要太强大的服务器运算能力，对程序灵活性有较高要求。
好处：
1.对于Web业务本身来说，Node.js是一个最适合用来做BFF层的一门技术，有一个Node.js BFF层能让前端有能力自由组装后台数据，减少大量的业务沟通成本，加快迭代速度，同时，前端工程师能自主决定前端与后台通讯方式，让前端工程师有更多能力着手性能优化。
2.对于后端和运维工程师来说，Node.js BFF层的搭建不是光靠前端工程师就能完成事情，搭建过程遇到的RPC调用，系统运维等场景都需要后端和运维紧密配合。通过大家BFF层除了能大幅度减少自己在繁重业务中的工作量以外，大大提升在架构领域的知识经验。
3.对于前端工程师自身来说，Node.js虽然是一门非浏览器端的技术，但基于javascript的环境能让前端工程师快速上手。可以涉及到数据库、操作系统、人工自能等技术领域。让前端不在局限于浏览器端的技术壁垒。
