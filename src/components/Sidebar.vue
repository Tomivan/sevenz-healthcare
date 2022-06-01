<template>
 <nav>
   <router-link to="/">
     <img src="../assets/dashboard.png" alt="" />
     Dashboard
   </router-link>
   <router-link to="/#">
     <img src="../assets/profile.png" alt="" />
     Profile
   </router-link>
   <router-link to="/#">
     <img src="../assets/services.png" alt="" />
     Services
   </router-link>
   <router-link to="/#">
     <img src="../assets/medical.png" alt="" />
     Medical Records
   </router-link>
   <router-link to="/#">
     <img src="../assets/wallet.png" alt="" />
     Care Wallet
   </router-link>
   <router-link to="/#">
     <img src="../assets/messages.png" alt="" />
     Messages
   </router-link>
   <router-link to="/#">
     <img src="../assets/resources.png" alt="" />
     Resources
   </router-link>
    <hr />
   <router-link to="/#">
     <img src="../assets/account.png" alt="" />
     Account Settings
   </router-link>
   <router-link to="/#">
     <img src="../assets/contact.png" alt="" />
     Contact Support
   </router-link>
   <router-link to="/#">
     <img src="../assets/logout.png" alt="" />
     Logout
   </router-link>
 </nav>
</template>

<script>

export default {
  name: 'Sidebar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
nav{
  display: flex;
  flex-direction: column;
  border-right: 1px solid #0000001e;
  height: 85vh;
  width: 15vw;
  padding-top: 4em;
  padding-left: 1em;
}
img{
  margin-right: 5%;
  height: 2vh;
  width: 1vw;
}
router-link{
  margin-bottom: 7%;
}
</style>
