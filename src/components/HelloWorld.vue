<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Portofolio</a>
            <a class="nav-link disabled">Contact</a>
          </div>
        </div>
      </div>
    </nav>
    <div class="jumbotron jumbotron-fluid">
      <div class="container text-center">
        <img src="../assets/fallout.jpg" alt="me" />
        <h1 class="display-4">Rayhandhika yusuf</h1>
        <p class="lead">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odit a expedita itaque hic voluptatem nisi suscipit dolor corrupti odio eligendi at velit earum, autem quaerat fuga esse, sapiente consequuntur eius?</p>
      </div>
    </div>
    <div class="container">
      <form>
        <div class="form-row">
          <div class="form-group col-md-6">
            <label for="inputEmail4">First name</label>
            <input type="email" class="form-control" id="inputEmail4" />
          </div>
          <div class="form-group col-md-6">
            <label for="inputPassword4">Last name</label>
            <input type="password" class="form-control" id="inputPassword4" />
          </div>
        </div>
        <div class="form-group">
          <label for="inputAddress">Address</label>
          <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St" />
        </div>
        <div class="form-group">
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck" />
            <label class="form-check-label" for="gridCheck"> Check me out </label>
          </div>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
      </form>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped></style>
