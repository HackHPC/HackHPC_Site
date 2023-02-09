+++
fragment = "content"
#disabled = true
date = "2021-3-29"
weight = 300
background = "dark"

#title = "code of conduct"
#subtitle = "Mentors are the people who make this  possiple!"
+++
<!DOCTYPE html>
<head>
<title>Form submission</title>
</head>
<body>
<center><h3>Alumni Email</h3>
<h5>If you are an Alumni please join the community mailing list by signing up below!</h5></center>
<form action="https://formspree.io/f/meqvjbka" method="post">
<center>
  <label>
  	<input type="text" name="name", placeholder="Name" style="width: 300px;", required>
  </label>
  <label>
    <input type="text" name="_replyto", placeholder="Email" style="width: 300px;", required>
  </label><br>
    <label>
    <input type="text" name="hackathon", placeholder="Hackathon" style="width: 300px;", required>
  </label>
  <label>
    <input type="text" name="year", placeholder="Year" style="width: 300px;", required>
  </label><br>
  <label>
    <textarea name="message", placeholder="I would like to sign up for the Hackathon Alumni Email!" style="height: 100px; width: 600px", required></textarea>
  </label>
  <!-- your other form fields go here -->
  <br>
  <button type="submit" style="color: #ffffff; background-color: #00838f; border-radius: 16px; width: 35%">Send</button></center>
</form>

</body>
</html>