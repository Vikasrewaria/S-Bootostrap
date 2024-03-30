Task.1:- 
Problem statment:-
You have to create a case card which should contain the thumbnail image, title and description with a call to action button.
Solution:-

   <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Bootstrap Card</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9"
      crossorigin="anonymous" />

  </head>
  <body class="d-flex justify-content-center align-items-center vh-100">
    <div class="card" style="width: 18rem">
      <img
        src="https://cdn.pwskills.com/assets/uploads/thumbnails/64a514966977cc6e87e27504.png"
        class="card-img-top"
        alt="thumbnail"/>
      <div class="card-body">
        <h5 class="card-title">Full Stack Web Development</h5>
        <p class="card-text">
          Learn MERN stack: MongoDB, Express.js, React.js, Node.js. Build
          dynamic web apps. Gain hands-on full-stack skills.
        </p>
        <a href="#" class="btn btn-primary w-100">Enroll Now</a>
      </div>
    </div>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
      crossorigin="anonymous"> </script>
  </body>
</html>

Task.2:-  
Problem Statment
In the assignment yo have to create a simple carousel consisting of three slides with a controller and indicator on it to make ot easy for the user navigate to other slides easily.
Also for all these slides, you have to gather the image from the pw skills website (https://pwskills.com).
Any three recent course images can be used in it.
Answer:-
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Bootstrap </title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9"
      crossorigin="anonymous"/>
  </head>
  <body class="d-flex justify-content-center align-items-center vh-100">
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      style="width: 600px">
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="https://cdn.pwskills.com/assets/uploads/
thumbnails/64a514966977cc6e87e27504.png"
            class="d-block w-100"
            alt="web development"/>
        </div>
        <div class="carousel-item">
          <img
            src="https://cdn.pwskills.com/assets/uploads/
thumbnails/64c787ac228e13bbe7db67ee.png"
            class="d-block w-100"/>
        </div>
        <div class="carousel-item">
          <img
            src="https://cdn.pwskills.com/assets/uploads/
thumbnails/64a264076977ccc0a0e20c13.png"
            class="d-block w-100"
            alt="..."/>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>

      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleCaptions"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
      crossorigin="anonymous"></script>
  </body>
</html>
