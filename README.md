### Hi 👋, I'm Alpha-1729

<!-- My profile pic -->

## <img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/profile.jpg" width="300px" height="300px">

<!-- Contact form -->

## <u>Contact Me</u>

<!-- Ajax library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Adding style to form -->
<style>

div
{
  width:70%;
  height:300px
}

#container
{
  background-color:  black;
  align-content: center;
  padding: 20px;
}

.data
{
  margin-bottom: 5px;
  text-align: left;
  width: 100%;
  height:40px;
  font-size: 18px;
}

textarea
{
  margin-bottom: 5px;
  text-align: left;
  width: 100%;
  height:100px;
  font-size: 18px;
}

#button {
  background-color: cyan;
  text-align: center;
  color: white;
  width: 30%;
  height:40px;
  font-size: 18px;
}

</style>

<!-- Html file -->
<div id="container">
  <form id="submit-form" action="">
    <input class="data" name="name" placeholder="Name" type="text" required /><br />
    <input class="data" name="email"placeholder="Email" type="email" required /><br />
    <input class="data" name="subject"placeholder="Subject" type="text" required /><br />
    <textarea placeholder="Message" name="message" type="text" required /></textarea><br />
    <button id="button" name="submit" type="submit" id="submit-form">Submit</button>
  </form>
</div>

<!-- Success Message -->
<script>
  $("#submit-form").submit((e)=>
  {
    e.preventDefault()
    $.ajax(
      {
        url:"https://script.google.com/macros/s/AKfycbwD_GxGs4keltPJfRabwMv_DGrTL11EMLs1PB4gZVq947hHIqoW/exec",
        data:$("#submit-form").serialize(),
        method:"post",
        success:function (response){
          alert("Message sent successfully")
          window.location.reload()
        },
        error:function (err){
          alert("Message not sent")
        }
      })
  })
</script>

---

<!-- Languages -->

## <u>Languages Used</u>

<img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/python.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/c.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/cpp.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/csharp.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/go.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/perl.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/ruby.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/html.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/css.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/javascript.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/php.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/arduino.jpg" height="64px" width="64px">

<hr>

<!-- Software -->

## <u>Favourite Software</u>

<img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/kdenlive.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/libreoffice.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/github.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/sublime.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/arduino.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/vscode.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/vlc.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/chrome.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/brave.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/mozilla.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/tor.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/sphere.jpg" height="64px" width="64px">

<hr>

<!--  Os Used-->

## <u>Favourite OS</u>

<img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/win7.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/win8.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/win10.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/ubuntu.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/kali.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/parrot.jpg" height="64px" width="64px"><img src="https://raw.githubusercontent.com/Alpha-1729/Alpha-1729/master/images/raspberry.jpg" height="64px" width="64px">

<hr>

<!--My Github Stats-->

## <u>My GitHub Stats</u>

<a href="https://github.com/Alpha-1729/Alpha-1729">
  <img align="center"  src="https://github-readme-stats.alpha-1729.vercel.app/api?username=Alpha-1729&theme=radical&show_icons=true&line_height=27&count_private=true&alt="Alpha-1729 GitHub Stats" />
</a>
<hr>

<!-- Top Languages Used -->
<!-- Themes supported ->dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula. -->

## <u>Top Languages Used</u>

<a href="https://github.com/Alpha-1729/Alpha-1729">
  <img align="center" src="https://github-readme-stats.alpha-1729.vercel.app/api/top-langs/?username=Alpha-1729&theme=radical" />
</a>

<!-- Pinned card -->

#### Pinned

<a href="https://github.com/Alpha-1729/Name_The_Certificate/">
  <img align="center"  src="https://github-readme-stats.vercel.app/api/pin/?username=Alpha-1729&repo=Name_The_Certificate&show_owner=true&theme=radical" />
</a>
<br><br>
<a href="https://github.com/Alpha-1729/ESP_WiFi_Captive_Portal/">
  <img align="center"  src="https://github-readme-stats.vercel.app/api/pin/?username=Alpha-1729&repo=ESP_WiFi_Captive_Portal&show_owner=true&theme=radical" />
</a>
<br><br>
<a href="https://github.com/Alpha-1729/Python_Simple_File_Classifier/">
  <img   align="center"  src="https://github-readme-stats.vercel.app/api/pin/?username=Alpha-1729&repo=Python_Simple_File_Classifier&show_owner=true&theme=radical" />
</a>
