<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <img src="../assets/logo15.png" style="width: 50px; height: 50px" alt="logo-smkn-15-bandung" />
      <a class="navbar-brand" href="#">SMKN 15 Bandung</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link mod" href="#carouselExampleFade">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item dropdown dropp">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-expanded="false"> Profil </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item" href="#">Visi & Misi</a>
              <a class="dropdown-item" href="#">Kurikulum</a>
              <a class="dropdown-item" href="#">Kesiswaan</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link mod" href="#about">Info</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mod" href="#gallery">Gallery</a>
          </li>
          <li class="nav-item">
            <a class="nav-link mod" href="#contact">Kontak</a>
          </li>
        </ul>
      </div>
    </nav>
    <div id="carouselExampleFade" class="carousel slide carousel-fade" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="../assets/8.png" class="d-block w-100 car" alt="..." />
          <div class="carousel-caption d-none d-md-block bck">
            <h5>First slide label</h5>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corrupti quia sed illum consectetur perferendis, veritatis doloremque odio explicabo dolore rerum nihil nisi odit necessitatibus tempora aperiam ullam. Incidunt,
              pariatur aspernatur.
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/9.png" class="d-block w-100 car" alt="..." />
          <div class="carousel-caption d-none d-md-block bck">
            <h5>Second slide label</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel sit nesciunt ducimus obcaecati reprehenderit nostrum, eveniet nulla error illo sapiente sint nemo aperiam suscipit voluptatibus recusandae soluta asperiores id
              exercitationem?
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/10.png" class="d-block w-100 car" alt="..." />
          <div class="carousel-caption d-none d-md-block bck">
            <h5>Third slide label</h5>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. At debitis, veritatis cum, quis quasi praesentium ad cupiditate recusandae, laboriosam et animi necessitatibus. Id numquam dolores nesciunt enim accusamus assumenda
              quidem.
            </p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-target="#carouselExampleFade" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-target="#carouselExampleFade" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </button>
    </div>
    <div class="container" style="margin: 85px">
      <h1 class="display-4 text-center gal">SMK Terbaik di Bandung</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad laboriosam mollitia reiciendis sed obcaecati, laborum pariatur placeat necessitatibus impedit ut voluptates, deleniti perspiciatis! Dolor, tempore rerum laboriosam
        distinctio aut ratione. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam rem vero ad consequuntur error inventore iure expedita, impedit assumenda. Modi velit, excepturi nemo veritatis voluptas cum libero a. Quia,
        sed. Lorem ipsum dolor sit amet consectetur adipisicing elit. A blanditiis est nulla exercitationem similique incidunt placeat non accusamus, aspernatur sapiente eligendi! Veritatis, quam obcaecati. Quaerat quasi repellendus
        obcaecati accusantium velit. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae quas minus iste enim. Enim perspiciatis dolorem voluptatem eius sapiente sunt aut itaque ex, recusandae reprehenderit explicabo pariatur!
        Assumenda, id vel! Lorem ipsum dolor, sit amet consectetur adipisicing elit. Architecto iste, officiis doloremque aut eaque ratione natus dolores sed? Eaque dolor minima explicabo eius temporibus inventore voluptatibus ipsam
        eligendi dolores vel.
      </p>
    </div>
    <section style="background-color: #2c272e">
      <div class="container boxbody" id="about">
        <img src="../assets/me.jpeg" alt="my photo" style="width: 300px; border-radius: 100%; padding: 30px" />
        <div class="text-box" style="background-color: white; border-radius: 10px; color: black; padding: 10px">
          <h5>Hello</h5>
          <p>
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora soluta voluptate excepturi illum dolorum sint officia dicta recusandae eveniet, totam ipsam praesentium voluptates minima ullam cum debitis, perferendis nostrum
            tempore.
          </p>
        </div>
      </div>
    </section>
    <div class="container" id="gallery">
      <h1 class="display-4 text-center gal">Gallery</h1>
    </div>
    <section>
      <div style="display: flex; flex-direction: row; justify-content: space-evenly; align-items: center; width: 100%; margin-bottom: 30px">
        <div class="card" style="width: 18rem">
          <img src="../assets/PHOTO/21.jpg" class="card-img-top" alt="..." />
        </div>
        <div class="card" style="width: 18rem">
          <img src="../assets/PHOTO/2.jpg" class="card-img-top" alt="..." />
        </div>
        <div class="card" style="width: 18rem">
          <img src="../assets/PHOTO/10.jpg" class="card-img-top" alt="..." />
        </div>
      </div>
    </section>
    <div class="upper-op">
      <div class="op" id="contact">
        <h1 class="display-4 text-center">Contact Us</h1>
        <form class="form-contact">
          <div class="form-row">
            <div class="form-group col-md-6">
              <label for="firstname">First Name</label>
              <input type="email" class="form-control" id="inputEmail4" />
            </div>
            <div class="form-group col-md-6">
              <label for="lastname">Last Name</label>
              <input type="password" class="form-control" id="inputPassword4" />
            </div>
          </div>
          <div class="form-group">
            <label for="inputemail4">Email</label>
            <input type="text" class="form-control" id="inputAddress" placeholder="Example@gmail.com" />
          </div>
          <div>
            <label for="subject">Message</label>
          </div>
          <div style="margin-bottom: 16px">
            <input id="subject" name="subject" style="height: 200px; width: 452px; border-radius: 10px" />
          </div>
          <button type="submit" class="btn btn-primary">submit</button>
        </form>
      </div>
      <div class="outside-contact-inf">
        <div class="contact-inf">
          <div class="inside-contact-inf">
            <div class="wp-block-group is-style-shadow-box has-white-background-color has-background">
              <div class="wp-block-group__inner-container">
                <div style="height: 20px" aria-hidden="true" class="wp-block-spacer"></div>

                <h4 style="margin-bottom: 30px">Contact Information</h4>
              </div>
            </div>
            <div class="wp-block-group is-style-shadow-box has-white-background-color has-background">
              <div class="wp-block-group__inner-container">
                <div class="wp-block-columns are-vertically-aligned-top">
                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 5%">
                    <figure class="wp-block-image size-large">
                      <img
                        style="margin-right: 10px"
                        width="20"
                        height="20"
                        src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Pin-2.svg"
                        alt="Pin 2"
                        class="wp-image-107546 entered lazyloaded"
                        data-lazy-src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Pin-2.svg"
                        data-ll-status="loaded"
                      />Location<noscript><img width="20" height="20" src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Pin-2.svg" alt="Pin 2" class="wp-image-107546" /></noscript>
                    </figure>
                  </div>

                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 80%">
                    <p class="inf">
                      Jl. Gatot Subroto No.4, Burangrang, Kec. Lengkong,<br />
                      Kota Bandung, Jawa Barat 40262
                    </p>
                  </div>
                </div>

                <div class="wp-block-columns are-vertically-aligned-top">
                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 5%">
                    <figure class="wp-block-image size-large">
                      <img
                        style="margin-right: 10px"
                        width="20"
                        height="20"
                        src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Phone-2.svg"
                        alt="Phone 2"
                        class="wp-image-107550 entered lazyloaded"
                        data-lazy-src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Phone-2.svg"
                        data-ll-status="loaded"
                      />Phone<noscript><img width="20" height="20" src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Phone-2.svg" alt="Phone 2" class="wp-image-107550" /></noscript>
                    </figure>
                  </div>

                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 80%">
                    <p class="inf">+45 71 99 77 07</p>
                  </div>
                </div>

                <div class="wp-block-columns are-vertically-aligned-top">
                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 5%">
                    <figure class="wp-block-image size-large">
                      <img
                        style="margin-right: 10px"
                        width="20"
                        height="20"
                        src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Mail.svg"
                        alt="Mail"
                        class="wp-image-107554 entered lazyloaded"
                        data-lazy-src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Mail.svg"
                        data-ll-status="loaded"
                      />Email
                      <noscript><img width="20" height="20" src="https://n7nqziuw1z4b1r6k2adhav10-wpengine.netdna-ssl.com/wp-content/uploads/2020/10/Mail.svg" alt="Mail" class="wp-image-107554" /></noscript>
                    </figure>
                  </div>
                  <div class="wp-block-column is-vertically-aligned-top" style="flex-basis: 80%">
                    <p><a target="_blank" rel="noreferrer noopener">rayhan.dhika9@gmail.com</a></p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <p>Copyright 2021 by Rayhandhika. All Rights Reserved.<br />This website powered by Visual Code Studio.</p>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.car {
  filter: drop-shadow(100px);
  width: 100vw;
}
.carousel-item h5 p {
  position: absolute; /* Position the background text */
  bottom: 0; /* At the bottom. Use top:0 to append it to the top */
  background: rgb(0, 0, 0); /* Fallback color */
  background: rgba(0, 0, 0, 0.5); /* Black background with 0.5 opacity */
  color: #f1f1f1; /* Grey text */
  padding: 20px; /* Some padding */
}
.carousel {
  position: relative;
  max-width: 100vw; /* Maximum width */
  margin: 0 auto; /* Center it */
}
.bck {
  background-color: rgba(0, 0, 0, 0.5);
  width: auto;
}
.cow {
  color: white;
  width: fit-content;
}
.boxbody {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  width: 100%;
}
.gal {
  padding: 20px;
}
.text-box {
  color: #f1f1f1;
  text-align: left;
}
.form-contact {
  background-color: #2c272e;
  color: white;
  padding: 30px;
}
.upper-op {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  background-color: #2c272e;
}
.op {
  background-color: #2c272e;
  padding-top: 6px;
  color: white;
  margin-top: 4px;
}
.btn {
  background-color: grey;
  border-color: grey;
}
.footer {
  background-color: #181d31;
  color: #e6ddc4;
  font-family: monospace;
  text-align: center;
}
p {
  margin: unset;
}
nav {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.contact-inf {
  background-color: white;
  padding: 53px;
  justify-content: center;
}
.inside-contact-inf {
  padding: 91px;
}
.inf {
  margin-bottom: 0.5rem;
}
div#contact.op {
  margin-left: 45px;
  margin-top: 25px;
}
</style>
