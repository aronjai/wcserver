<template>
    <form>
        <div class="container" >
            <div class="row h-100 justify-content-center align-items-center">
                <div class="col-md-5">
                    <h2>Login</h2>
                    <div class="form-group text-left" id='email'>
                        <label for="email_add">Email</label>
                        <input type="text" class="form-control" name="email_add" id="email" placeholder="Enter your Email" v-model="email_add"/>
                    </div>
                    <div class="form-group text-left ">
                        <label for="password">Password</label>
                        <input type="password" class="form-control" name="password" id="pass" placeholder="Enter your Password" v-model="password"/>
                    </div>
                    <button class="btn btn-lg btn-warning m-4 pb-2" type="submit" id='login'>Login</button>
                    <button class="btn btn-lg btn-warning  pb-2" type="submit" id='cancel'>Cancel</button>
                </div>
            </div>
        </div>
    </form>
</template>


<script>
export default{
  data() {
    return {
      uname: '',
      pass: ''

    }
  },
  methods:{
      loginUser(){
        if (this.uname === '') {
          alert('Please enter your  Username.')
        }
      }
  }
}
</script>