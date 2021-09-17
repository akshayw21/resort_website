<template>
  <div class="container col-12  ">
      <h1>Contact Us</h1>
      <form >
          <fieldset>
        <label for='fname'><h3>First Name :</h3> </label>
        <input id="fname" type:='text' name='fname'  placeholder='Enter your first name' required /><br>
        <br>
        <label for='lname'><h3>Last Name : </h3></label>
        <input  id='lname' type='text' name='lname' placeholder='Enter your last name' required/>
        <br>
        <br>

        <label for='mbn'><h3>Mobile Number :</h3> </label>
        <input id='mbn' type='text' name='mbn'  placeholder='Enter your Mobile Number' required/>
        <br>
        <br>

        <label for='email'><h3>Email Id : </h3></label>
        <input id='email' type='email' name='email'  placeholder='Enter your Email' required/>
        <br>
        <br>

        <label for="addre"><h3>Address :</h3></label>
        <input id="addre" type="text" placeholder="Enter your Address"/>
        <br>
        <br>

        <label for="query"><h3>Enquiry : </h3></label>
        <input id="query" type="text" placeholder="Enter your query"/><br>
        <br>


        <button type="submit" class="btn btn-success">Submit</button>







    </fieldset>
      </form>
  </div>
</template>

<script>
export default {

}
</script>

<style>


h1{
    color:blue;
}
h3{
    color:red;
}
input{
    border-radius: 20px;
    background-color: white;
}
</style>