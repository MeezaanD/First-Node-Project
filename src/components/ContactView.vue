<template>
    <body>
        <div class="contact">
            <div class="container">
                <form form action="https://formspree.io/f/mbjbywlp" method="post">
                  <label for="fname">First Name</label>
                  <input type="text" id="fname" name="firstname" placeholder="Your name..">
              
                  <label for="lname">Last Name</label>
                  <input type="text" id="lname" name="lastname" placeholder="Your last name..">
              
                  <label for="country">Job title</label>
                  <select id="Job title" name="Job title">
                    <option value="Front-end Developer">Front-end Developer</option>
                    <option value="Back-end Developer">Back-end Developer</option>
                    <option value="Fullstack Developer">Fullstack Developer</option>
                  </select>
              
                  <label for="subject">Subject</label>
                  <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
              
                  <input type="submit" value="Submit">
                </form>
              </div>
        </div>
    </body>
</template>
<script>
</script>

<style>

input[type=text], select, textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
  }
  
  input[type=submit] {
    background-color: aqua;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  input[type=submit]:hover {
    background-color: yellow;
  }
  
  .container {
    border-radius: 5px;
    background-color: beige;
    padding: 20px;
  }


  
</style>