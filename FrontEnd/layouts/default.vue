<template>
  <div>
    <VmHeader></VmHeader>
    <main >
      <nuxt/>
      <VmLoginModal></VmLoginModal>
      <VmRegistrationModal></VmRegistrationModal>
      <VmCheckoutModal></VmCheckoutModal>
    </main>
    <VmFooter></VmFooter>
  </div>
</template>

<script>
import VmHeader from '@/components/header/Header';
import VmFooter from '@/components/footer/Footer';
import VmLoginModal from '@/components/modal/Login';
import VmRegistrationModal from '@/components/modal/Registration';
import VmCheckoutModal from '@/components/modal/Checkout';

export default {
  components: {
    VmHeader,
    VmFooter,
    VmLoginModal,
    VmRegistrationModal,
    VmCheckoutModal
  }
}
</script>

<style>
html, body {
  width: auto;
  height:auto;
}

body {
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
}

@keyframes gradient {
    100% {
        background-position: 0% 50%;
    }
    100% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}
  .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }

  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }

  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }

  /* body > .el-container {
    margin-bottom: 40px;
  }

  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }

  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  } */
</style>
