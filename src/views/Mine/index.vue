<template>
  <div>
    <Header title="我的喵喵" />
    <LoginIn />
    <TabBar />
  </div>
</template>
<script>
import Header from '@/components/Header';
import TabBar from '@/components/TabBar';
import LoginIn from '@/components/LoginIn'
export default {
  name: 'Mine',
  components: {
    Header,
    TabBar,
    LoginIn
  }
}
</script>
<style></style>
