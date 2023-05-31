<template>
            <div class="btn">
            <button><img src="https://icms-image.slatic.net/images/ims-web/9d78cd14-05ee-43ba-a360-61f895a70aef.png" alt="lazred" class="btn-icon">LazMall</button>&nbsp;
            <button><img src="https://laz-img-cdn.alicdn.com/images/ims-web/TB12wVshUT1gK0jSZFhXXaAtVXa.png" class="btn-icon">Vouchers</button>&nbsp;
            <button><img src="https://laz-img-cdn.alicdn.com/images/ims-web/TB11DFthO_1gK0jSZFqXXcpaXXa.png" alt="lazred" class="btn-icon">Top-Up,Bills&Food</button>&nbsp;
            <button><img src="https://icms-image.slatic.net/images/ims-web/a13d12e1-91d1-4240-b22f-46233a012e89.png" alt="lazred" class="btn-icon">LazBlog</button>&nbsp;
            <button><img src="https://img.alicdn.com/imgextra/i1/O1CN01yvjCS71LsB10MJoJt_!!6000000001354-2-tps-150-150.png" alt="lazred" class="btn-icon">LazPick</button>
        </div>

</template>

<script>
export default {
    name: 'buttonLaz',
}
</script>

<style scoped>
.btn{
    padding-top: 10px ;
    text-align: center;
}
button{
    
    position: relative;
    border-radius: 15px;
  font: inherit;
  font-size: 18px;
  cursor: pointer;
  border: 1px solid white;
  background: white;
  color: black;
  width: 220px;
  height: 40px;
}
.btn-icon {
  position: absolute;
  left: 8px; 
  top: 50%; 
  transform: translateY(-50%); 
  width: 32px; 
  height: 32px;
}
.btn-text {
  font-weight: bold;
}
</style>