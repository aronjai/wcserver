<template> 
<form>
    <div class='container'>
        <div class='row h-90 justify-content-right align-items-center'>  
            <div class='col-md-8' id='tableto'> 
                <h2>Create an account </h2>
                <div class='form-group text-left'>
                    <label for ='firstname'>First Name </label>
                    <input width="10" maxlength="5" type='text' class='form-control' name="firstname" id="name" placeholder="Enter your Firstname" v-model= "firstname"/>
                </div>
                <div class='form-group text-left' id='mini'>
                    <label for ='middleinitial'>Middle Initial </label>
                    <input type='text' class='form-control' name="middleinitial" id="mi" placeholder="Enter your Middle Initial" v-model= "middleinitial"/>
                </div>
                <div class='form-group text-left'>
                    <label for ='lastname'>Last Name </label>
                    <input type='text' class='form-control' name="lastname" id="name" placeholder="Enter your Lastname" v-model= "lastname"/>
                </div>
                <div class='form-group text-left'>
                    <label for ='address'>Address</label>
                    <textarea type='text' class='form-control' name="address" id="add" placeholder="Enter your Address" v-model= "address"></textarea>
                </div>
                <div class='form-group text-left' id='birth'>
                    <label for ='birthdate'>Birthdate</label>
                    <input type='text' class='form-control' name="birthdate" id="mi" placeholder="Enter your Birthdate" v-model= "birthdate"/>
                </div>
                <div class='form-group text-left'>
                    <label for ='contact'>Contact No.</label>
                    <input type='text' class='form-control' name="contact" id="name" placeholder="Enter your Contact No." v-model= "contact"/>
                </div>
                <div class='form-group text-left'>
                    <label for ='email_add'>Email Address</label>
                    <input type='text' class='form-control' name="email_add" id="name" placeholder="Enter your Email Address" v-model= "email_add"/>
                </div>
                <div class='form-group text-left' id='pass'>
                    <label for ='password'>Password</label>
                    <input type='password' class='form-control' name="password" id="name" placeholder="Enter your Password" v-model= "password"/>
                </div>
                <div class='form-group text-left'>
                    <label for ='confirm_pass'>Confirm Password</label>
                    <input type='text' class='form-control' name="confirm_pass" id="name" placeholder="Confirm your Password" v-model= "confirm_pass"/>
                </div>
                <button class='btn btn-lg btn-warning mr-5 pb-2 ' type="submit">Register</button>
                <button class='btn btn-lg btn-warning pb-2' type="button">Cancel</button>
            </div>
        </div>
    </div>
</form>
</template>
<script>
import axios from 'axios'
import router from '../router'
export default{
    data(){
        return{
            firstname:'',
            middleinitial:'',
            lastname:'',
            address:'',
            birthdate:'',
            sex:'',
            email_add:'',
            username:'',
            password:'',
            confirm_pass:''
        }
    },
    methods: {
        register (){
            axios.post('app/signup',{
                firstname:this.firstname,
                middleinitial:this.middleinitial,
                lastname:this.lastname,
                address:this.address,
                birthdate:this.birthdate,
                sex:this.sex,
                email_add:this.email_add,
                username:this.username,
                password:this.password   
            }).then(res => {
                if (res.data){
                alert('You have successfully registered...')
                router.push({name:'Home'})
                }
            }).catch(err => {
                console.log(err)
            })
        }
    }
}
</script>

<style>
div.container{
     width:auto;
 }

 h2{
     font-family: fantasy;
 }
form{
     background-image: url('../assets/signup.jpg');
     background-repeat: no-repeat;
     background-size: cover;
     font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
 }
div#tableto{
     
     width:100%;
     height: 100%;
     left:380px;
     border-radius: 4px;
     background-color: white;
 }
 div#tableto > div#mini{
     position:absolute;
     left:400px;
     top:78px;
     width: 800px;
 }
  div#tableto > div#birth{
     position:absolute;
     left:400px;
     top:163.8px;
     width: 800px;
 }
   div#tableto > div#pass{
     position:absolute;
     left:400px;
     top:445.9px;
     width: 500px;
 }
 input[type=text]{
     width: 80%;
     
 }
 input[type=password]{
     width: 80%;
 }
 input[id=mi]{
     width: 30%;
 }
  input[id=name]{
     width: 50%;
 }
   textarea[id=add]{
     width: 70%;
 }

 
</style>