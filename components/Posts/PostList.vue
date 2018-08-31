<template>
    <section class="post-list">
      <PostPreview 
        id="1"
        thumbnail="https://www.cmo.com/content/dam/CMO_Other/articles/1046x616_Tech_Meeting.jpg"
        title="Hello there!"
        previewText="This is my first post!" />
      <PostPreview 
        id="2"
        thumbnail="https://www.cmo.com/content/dam/CMO_Other/articles/1046x616_Tech_Meeting.jpg"
        title="Hello there - the second time"
        previewText="This is my second post!" />
        <PostPreview 
        id="3"
        thumbnail="https://www.cmo.com/content/dam/CMO_Other/articles/1046x616_Tech_Meeting.jpg"
        title="Hi!"
        previewText="This is my third post!" />
    </section>
</template>

<script>
  import PostPreview from "@/components/Posts/PostPreview";
  export default {
    components : {
      PostPreview
    }
  }
</script>

<style scoped>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>

