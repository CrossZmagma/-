<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      用户指引<br>
      用户指引
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">超链接1</a>.
    </p>
    <ul>
    <h3>您需要联系快递公司？</h3>
    </ul>
      <p>
        <a href="http://www.zto.com">
          <img border="0" src="./../../public/img/1.jpg" />
        </a>
      </p>
      <p>
        <a href="http://www.sto.cn">
          <img border="0" src="./../../public/img/2.jpg" />
        </a>
      </p>
      <p>
        <a href="http://800bestex.com">
          <img border="0" src="./../../public/img/3.jpg" />
        </a>
      </p>
      <p>
        <a href="http://http://www.sf-express.com/cn/sc/">
          <img border="0" src="./../../public/img/4.jpg" />
        </a>
      </p>
      <p>
        <a href="http://http://www.deppon.com/newwebsite">
          <img border="0" src="./../../public/img/5.jpg" />
        </a>
      </p>
    <ul>
    <h3>您的权益受到了侵害？</h3>
    </ul>
      <li><a href="http://www.315.gov.cn/" target="_blank" rel="noopener">中国消费者权益保护网</a></li>
      <li><a href="https://jubao.taobao.com/t" target="_blank" rel="noopener">淘宝网举报中心</a></li>
      <li><a href="https://myjd.jd.com/afs/indexNew.action?entry=2" target="_blank" rel="noopener">京东售后服务</a></li>
      <li><a href="https://help.suning.com/page/id-469.htm" target="_blank" rel="noopener">苏宁联系客服</a></li>

    <h3>有什么可以帮到您？</h3>
    <ul>
      <li><a href="http://www.baidu。com/" target="_blank" rel="noopener">个人账户</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">联系客服</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">关于我们</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">投诉或意见</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
