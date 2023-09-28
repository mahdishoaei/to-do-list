<template>
  <nav class=" navbar navbar-expand-lg bg-primary " data-bs-theme="dark">
    <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
<br/>




<div class="border border-info-subtle rounded w-50 container text-center">
  <table class="table table-hover   " >
  <thead>
    <tr  scope="row">
      <th class="col-2" scope="col">Number</th>
      <th class="col-6" scope="col">Subject</th>
      <th class="col-2" scope="col">Status</th>
      <th class="col-2" scope="col">Advance</th>

    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>done something yeterday</td>
      <td><input class="form-check-input mt-0" type="checkbox" value="" aria-label="Checkbox for following text input"></td>
      <td>
        <div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
         <button type="button" class="btn btn-secondary">Edit</button>
         <button type="button" class="btn btn-danger">Delete</button>
        </div>
      </td> 
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>do something else for now</td>
      <td><input class="form-check-input mt-0" type="checkbox" value="" aria-label="Checkbox for following text input"></td> 
      <td>
        <div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
         <button type="button" class="btn btn-secondary">Edit</button>
         <button type="button" class="btn btn-danger">Delete</button>
        </div>
      </td> 
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>doing something for next week</td>
      <td><input class="form-check-input mt-0" type="checkbox" value="" aria-label="Checkbox for following text input"></td> 
      <td>
        <div class="btn-group btn-group-sm" role="group" aria-label="Basic mixed styles example">
         <button type="button" class="btn btn-secondary">Edit</button>
         <button type="button" class="btn btn-danger">Delete</button>
        </div>
      </td> 
    </tr>
  </tbody>
</table>
</div>

<br/>

<div class="input-group w-50 container ">
  <input type="text" class="form-control" placeholder="Your future list" aria-label="Recipient's username with two button addons">
  <button class="btn btn-primary" type="button">Submit</button>
</div>



</template>

<script>


</script>

<style>

</style>
