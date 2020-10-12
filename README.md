!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Diya Shine</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600&display=swap" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" />
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" />
    <link rel="stylesheet" href="./style.css" />
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.bundle.min.js"></script>
    <script src="https://rawcdn.githack.com/albburtsev/jquery.typist/f4f429fad5bab374b1cf01da52ce4e469758afe6/dist/jquery.typist.min.js"></script>
    <script src="./script.js"></script>
  </head>
  <body>
    <nav class="navbar fixed-top navbar-dark bg-dark">
      <a class="navbar-brand" href="">Diya Shine</a>
    </nav>
    <section id="intro">
      <img src="./banner.png" alt="Diya Shine" />
      <div class="content">
        <h3>Hello, I am</h3>
        <h1>Diya Shine</h1>
        <h2>I am a <span></span></h2>
        <div class="socials">
          <a target="_blank" href=""><i class="fa fa-facebook"></i></a>
          <a target="_blank" href=""><i class="fa fa-twitter"></i></a>
          <a target="_blank" href=""><i class="fa fa-linkedin"></i></a>
          <a target="_blank" href=""><i class="fa fa-stack-overflow"></i></a>
          <a target="_blank" href=""><i class="fa fa-stack-exchange"></i></a>
          <a target="_blank" href=""><i class="fa fa-github"></i></a>
          <a target="_blank" href=""><i class="fa fa-gitlab"></i></a>
        </div>
      </div>
      <div class="go-down">
        <a href="#about" class="mouse"></a>
      </div>
    </section>
    <section id="about">
      <div class="container-fluid">
        <div class="row">
          <div class="col-12">
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam. Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam. Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
          </div>
        </div>
      </div>
    </section>
    <section id="experience">
      <div class="container-fluid">
        <div class="row">
          <div class="col-12 col-md-6">
            <h2>Experience I have</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
          </div>
          <div class="col-12 col-md-6">
            <h2>Projects I did</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo quia veritatis dolorum, ad est ipsam ut quod rerum reiciendis maxime harum ab? Delectus, aspernatur. Sint sit neque necessitatibus magnam veniam.</p>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-md-5">
            <h2>Contacting Me</h2>
            <p class="text-center p-3">
              <i class="fa fa-3x fa-clock-o mr-3"></i>
              <i class="fa fa-3x fa-comments-o"></i>
            </p>
            <p>Feel free to talk to me about anything that bothers you. If you need a helping hand, please don't hesitate to contact me. Got a question on the services that I provide? I am just a click away. I live in the England's time zone, if this helps.</p>
          </div>
          <div class="col-12 col-md-7">
            <h2 class="mb-3">Say Hi to Me</h2>
            <p>Please write me a nice message and I'll reply you ASAP!</p>
            <form>
              <div class="row">
                <div class="col-6">
                  <div class="form-group">
                    <input type="text" name="Name" placeholder="What's your name?" class="form-control" required />
                  </div>
                </div>
                <div class="col-6">
                  <div class="form-group">
                    <input type="email" name="Email" placeholder="Give me your email..." class="form-control" required />
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-9">
                  <div class="form-group">
                    <input type="text" name="Subject" placeholder="What's it about?" class="form-control" required />
                  </div>
                </div>
                <div class="col-3">
                  <div class="form-group">
                    <input type="datetime-local" name="Appointment" placeholder="When?" class="form-control" />
                  </div>
                </div>
                <div class="col-12">
                  <div class="form-group">
                    <textarea name="Message" placeholder="Tell me about it in detail..." class="form-control" required></textarea>
                  </div>
                  <button type="submit" class="btn btn-success">Send</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>

