# Porfolio-Page
<!DOCTYPE html>
<html>
<title>Kristen Pham Portfolio</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<style type="text/css">
#background-color-grid1 {
  background-color: #E1ABA4;
}
#swingby {
  background-color: #A3726C;
}
</style>
<body class="w3-content" style="max-width:1300px">

<!-- First Block: Logo & About -->
<div class="w3-row">
  <div class="w3-half w3-white w3-container w3-center" style="height:650px">
    <div class="w3-padding-16">
      <img src="kristenpham.jpg" class="w3-image" style="height:10px width:10px">
    </div>
    <div class="w3-padding-64">
      <a href="#" class="w3-button w3-white w3-block w3-hover-blue-grey w3-padding-16">Home</a>
      <a href="#work" class="w3-button w3-white w3-block w3-hover-teal w3-padding-16">My Work</a>
      <a href="#work" class="w3-button w3-white w3-block w3-hover-dark-grey w3-padding-16">Resume</a>
      <a href="#contact" class="w3-button w3-white w3-block w3-hover-brown w3-padding-16">Contact</a>
    </div>
  </div>
  <div class="w3-half w3-container" style="height:700px" id="background-color-grid1">
    <div class="w3-padding-64 w3-center">
      <h1>About Me</h1>
      <div class="w3-left-align w3-padding-large">
        <p>Kristen Pham, an aspiring web developer. </p>
        <p>love visual arts and photography</p>
      </div>
    </div>
  </div>
</div>

<!-- Second block: Work & Resume -->
<div class="w3-row">
  <div class="w3-half w3-black w3-center" style="min-height:800px" id="work">
    <div class="w3-padding-64">
      <h2>My Work</h2>
      <p>Some of my latest projects.</p>
    </div>
    <div class="w3-row">
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
    </div>
    <div class="w3-row w3-hide-small">
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
    </div>

    <div class="w3-row w3-hide-small">
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="" style="width:100%">
      </div>
    </div><br>
    <p></p>
  </div>
  <div class="w3-half w3-indigo w3-container" style="min-height:800px">
    <div class="w3-padding-64 w3-center">
      <h2>Resume</h2>
      <p>A draft from my CV</p>
      <div class="w3-container w3-responsive">
        <table class="w3-table">
          <tr>
            <th>Year</th>
            <th>Title</th>
            <th>Where</th>
          </tr>
          <tr class="w3-white">
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr class="w3-white">
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr>
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr class="w3-white">
            <td></td>
            <td></td>
            <td></td>
          </tr>
          <tr class="w3-hide-medium">
            <td></td>
            <td></td>
            <td></td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</div>

<!-- Third Grid: Swing By & Contact -->
<div class="w3-row" id="contact">
  <div class="w3-half w3-khaki w3-container w3-center" style="height:700px">
    <div class="w3-padding-64">
      <h1>Swing By</h1>
    </div>
    <div class="w3-padding-64">
      <p>....</p>
      <p>Sydney, Australia</p>
      <p>+61 1515151515</p>
      <p>kristen@kristenpham.me</p>
    </div>
  </div>
  <div class="w3-half w3-teal w3-container" style="height:700px">
    <div class="w3-padding-64 w3-padding-large">
      <h1>Contact</h1>
      <p class="w3-opacity">GET IN TOUCH</p>
      <form class="w3-container w3-card w3-padding-32 w3-white" action="/action_page.php" target="_blank">
        <div class="w3-section">
          <label>Name</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Name">
        </div>
        <div class="w3-section">
          <label>Email</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Email">
        </div>
        <div class="w3-section">
          <label>Message</label>
          <input class="w3-input" style="width:100%;" type="text" required name="Message">
        </div>
        <button type="submit" class="w3-button w3-teal w3-right">Send</button>
      </form>
    </div>
  </div>
</div>

<!-- Footer -->
<footer class="w3-container w3-black w3-padding-16">
  <p>Kristen Pham</p>
</footer>

</body>
</html>
