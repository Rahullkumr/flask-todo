<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Todo List</title>
  <link rel="shortcut icon" type="image/jpg" href="https://icon-library.com/images/todo-icon/todo-icon-14.jpg">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
</head>
<body>
      
  <div class="container my-3" style="margin-left: 27rem; max-width: 30rem;">  
    <div class="card border-black mb-3 text-center" style="max-width: 30rem;">
      <div class="card-header"><h2>Add a Todo</h2></div>
      <div class="card-body">
        <form action="/" method="POST">
          <div class="mb-3">
            <label for="title" class="form-label">Title</label>
            <input type="text" class="form-control" name="title" id="title" aria-describedby="emailHelp">
          </div>
          <div class="mb-3">
            <label for="desc" class="form-label">Description</label>
            <input type="text" class="form-control" name="desc" id="desc">
          </div>
          <button type="submit" class="btn btn-dark">Submit</button>
        </form>
      </div>
    </div>
  </div>

  <div class="container my-4" style="margin-left: 11rem;">
    <div class="card border-black mb-3" style="max-width: 60rem;">
      <div class="card-header text-center"><h2>All Todos</h2></div>
      <div class="card-body">
        
      <table class="table">
          <thead>
            <tr>
              <th scope="col">SNo</th>
              <th scope="col">Title</th>
              <th scope="col">Description</th>
              <th scope="col">Priority</th>
              <th scope="col">Actions</th>
            </tr>
          </thead>
          <tbody>        
            
            <tr>
              <th scope="row">1</th>
              <td>Flask</td>
              <td>Install Flask </td>
              <td>2023-06-12 21:18:28.508750</td>
              <td>
                <a href="/update/1" type="button" class="btn btn-outline-dark btn-sm mx-1">Update</button>
                <a href="/delete/1" type="button" class="btn btn-outline-danger btn-sm mx-1">Delete</button>
              </td>
            </tr>
            
            <tr>
              <th scope="row">2</th>
              <td>hello</td>
              <td>world</td>
              <td>2023-06-12 22:25:59.967153</td>
              <td>
                <a href="/update/3" type="button" class="btn btn-outline-dark btn-sm mx-1">Update</button>
                <a href="/delete/3" type="button" class="btn btn-outline-danger btn-sm mx-1">Delete</button>
              </td>
            </tr>
            
          </tbody>
        </table>
        
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>        

</body>
</html>
