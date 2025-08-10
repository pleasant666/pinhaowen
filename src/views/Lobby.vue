<template>
  <div class="lobby">
    <div class="room-choice">
      <a href="#">1230000</a>
      <div class="information">小明的故事</div>
      <div class="number-of-ppl">5/10</div>
    </div>
    <div class="room-choice">
      <a href="#">1231124</a>
      <div class="information">小明的神奇故事</div>
      <div class="number-of-ppl">10/700</div>
    </div>
    <div class="room-choice">
      <a href="#">1279483</a>
      <div class="information">小明的奇奇妙妙故事</div>
      <div class="number-of-ppl">5/10</div>
    </div>
    <div class="page-choice">
      <a id="to-left" href="#">上一页</a>
      <p>·第1页/共3页·</p>
      <a id="to-right" href="#">下一页</a>
    </div>
  </div>
</template>

<style scoped>
.lobby {
  margin: 20px auto;
  background-color: var(--bg);
  padding: 10px 10px;
  border-radius: 6px;
}

.room-choice {
  margin: 20px auto;
  background-color: var(--t);
  color: #613d6a;
  padding: 10px 10px;
  border-radius: 6px;
  display: grid;
  grid-template-columns: 150px 1fr 120px;
  align-items: center;
}

.room-choice a {
  color: #613d6a;
  text-decoration: none;
  text-align: left;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.room-choice .information {
  text-align: left;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.room-choice .number-of-ppl {
  text-align: right;
  white-space: nowrap;
}

.page-choice {
  display: flex;
  justify-content: center;
  align-items: center;
}

.page-choice a {
  font-size: 0.8rem;
  color: var(--t);
  text-decoration: none;
}

.page-choice p{
  font-size: 0.8rem;
}
</style>
