<template lang="pug">
  //Vue 的背景圖要用 public 資料夾的圖片的話要這樣寫
  #main(:style="{backgroundImage: 'url(./images/0101.jpg)'}")
    //- Vue 的 img src 用 v-bind 時 ./ 代表 public 資料夾
    //- 沒有用 v-bind 的話會找 src

    img(src="@/assets/0104.jpg")
    br
    br
    p
      | 嗨！歡迎加入國立科技高中。
      br
      | 參加社團不僅可以豐富自己的人生、寬闊自己的視野，
      br
      | 也能砥礪技能、磨練人際、培養第二專長。
      br
      | 選擇一項您喜歡的社團，積極的參與和投入，
      br
      | 您會獲得一陣陣的驚喜！
</template>

<script>
export default {
  name: 'Main'
}
</script>
