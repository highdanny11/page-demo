<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/0.21.1/axios.min.js"></script>
    <title>Document</title>

</head>

<body>
    <div class="container">
        <div class="row ">
            <form id="form">
                <div class="col-3  position-absolute top-50 start-50 translate-middle  border-bottom ">
                    <div class="h1 text-center my-3">請先登入</div>
                    <div class="form-floating mb-3">
                        <input type="email" class="form-control" id="email" placeholder="name@example.com" autofocus
                            required>
                        <label for="email">Email address</label>
                    </div>
                    <div class="form-floating ">
                        <input type="password" class="form-control" id="password" placeholder="Password" autofocus
                            required>
                        <label for="password">Password</label>
                    </div>
                    <div class="d-flex justify-content-center my-3 ">
                        <button class="btn btn-primary btn-lg" type="submit">登入</button>
                    </div>
                </div>
            </form>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
        crossorigin="anonymous"></script>
    <script src="javascripts/loginVue3.js"></script>
</body>

</html>
