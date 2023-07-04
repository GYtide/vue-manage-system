<template>
  <div class="hello-container">
    <h1 class="hello-title">你好，欢迎来到“爸爸再也不用担心我的学习！”</h1>
    <p class="hello-description">感谢您的访问。让我们向您介绍我们的功能：</p>
    <ul class="hello-features">
      <li class="hello-feature">功能 1：===================================.</li>
      <li class="hello-feature">功能 2：=====================================.</li>
      <li class="hello-feature">功能 3：=====================================</li>
      <!-- 添加更多功能 -->
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Hello',
};
</script>

<style scoped>
.hello-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
  background-image: url(../assets/img/home.jpg);
}

.hello-title {
  font-size: 32px;
  font-weight: bold;
  color: #333;
  margin-bottom: 20px;
  background-color: #89d57b;
}

.hello-description {
  font-size: 20px;
  color: #666;
  margin-bottom: 30px;
}

.hello-features {
  list-style-type: none;
  padding: 0;
  margin: 0;
  background-color: #89d57b;
}

.hello-feature {
  font-size: 18px;
  color: #888;
  margin-bottom: 10px;
  text-align: left;
}
</style>
