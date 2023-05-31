<template>
        <div class="tab">
        <ul>
        <li>
          <a href="https://www.lazada.co.th/"
            ><img
              src="https://laz-img-cdn.alicdn.com/images/ims-web/TB1KB2laMFY.1VjSZFnXXcFHXXa.png"
              alt="lazada" class="tab1"
          /></a>
        </li>
        <li class="tabex">
          <input
            type="text"
            v-model="input"
            placeholder="ค้นหาในลาซาด้า"
          /><button><i class="material-icons">search</i></button>
        </li>
        <div class="cart">
        <li>
          <a
            href="https://member.lazada.co.th/user/login?lzdmflt=p&redirect=http%3A%2F%2Fcart.lazada.co.th%2Fcart%3Fspm%3Da2o4m.home.header.dcart.11252a80ZHnr3S%26scm%3D1003.4.icms-zebra-5001427-2591761.OTHER_5196131821_2267435"
            ><i class="material-icons">shopping_cart</i></a
          >
        </li>
        </div>
        <li>
          <a
            href="https://ali.lazada.co.th/wow/i/th/THCampaign/appbenefit?spm=a2o4m.home.header.dewallet.11252a80ZHnr3S&hybrid=1"
            ><img
              src="https://laz-img-cdn.alicdn.com/images/ims-web/TB1DcZESBr0gK0jSZFnXXbRRXXa.jpg"
              alt="couponfirst" class="tab2"
          /></a>
        </li>
      </ul>
    </div>
</template>

<script>
export default {
name:'tabLaz',
}
</script>

<style scoped>
.tab{
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  
  
}
.tab ul {
  display: flex;
  justify-content: center;
  align-items: center;
  align-items: flex-end;
  list-style: none;
  padding: 0;
  margin: 0;
}
.tab ul li {
  margin-right: 10px;
}
.tabex{
    display: flex;
  align-items: center;
}
.tab1{
    width: 127px;
    height: 40px;
}
.tab2{
    width: 188px;
    height: 45px;
}
input{
    width: 688px;
    height: 39px;
    background-color: #eff0f5;
    border: 1px solid #eff0f5;
}
button{
    border: 1px solid white;
    background-color:#f57224 ;
    width: 45px;
    height: 47px;
    display: flex;
  align-items: center;
  justify-content: center;
}
.cart{
    width: 40px;
    height: 38px;
}
</style>