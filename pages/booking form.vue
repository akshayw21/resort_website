<template>
  <div class="container  three">
      <navbar/>
      <h1>Book Ticket</h1>
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

        <label for="source"><h3>Source : </h3></label>
        <input id="source" type="text" placeholder="Enter your source"/><br>
        <br>

        <label for="dest"><h3>Destination : </h3></label>
        <input id="dest" type="text" placeholder="Enter your destination"/><br>
        <br>


        <button type="submit" class="btn btn-primary">Submit</button>







    </fieldset>
      </form>
      <br>
      <br>
      <br>
      
  </div>
</template>

<script>
export default {

}
</script>

<style>
.three{
    
    border-radius: 30px;
    text-align:center;
    /*background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0rU1iY82EHD_hf5hVF9P-HMfJ7L2kPLCGRQ&usqp=CAU');
    background-size: 100%;*/
    background-color:cornflowerblue;
    
    
}
h1{
    color:blue;
}
h3{
    color:red;
}
input{
    
    background-color: white;
}
</style>