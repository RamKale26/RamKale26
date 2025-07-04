##  👋 Hi there  Ramnath Kale

## 🚀 Technologies Used
- Java
- MySQL
- HTML/CSS
- JavaScript
- Spring Boot (optional)

## 🛠️ Features
- Admin Interface
- Add/Edit/Delete Products
- Inventory Report Generation
- Exception Handling
- Unit Testing



## Contact me

  
📧 kaleramnth2003@gmail.com  
📍 Pune, Maharashtra  
📄 [Resume PDF](link-to-your-resume-on-Google-Drive-or-another-repo)





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Inventory Dashboard</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Animate.css -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

  <!-- AOS -->
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">

  <style>
    .btn-animate {
      transition: 0.3s ease;
    }
    .btn-animate:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

<div class="container text-center mt-5">
  <h1 class="animate__animated animate__fadeInDown">Inventory System</h1>

  <div class="row mt-4">
    <div class="col-md-4" data-aos="fade-up">
      <div class="card p-3 shadow">
        <h4>Add Product</h4>
        <button class="btn btn-outline-primary btn-animate mt-3">Add</button>
      </div>
    </div>
    <div class="col-md-4" data-aos="fade-up" data-aos-delay="100">
      <div class="card p-3 shadow">
        <h4>View Products</h4>
        <button class="btn btn-outline-success btn-animate mt-3">View</button>
      </div>
    </div>
    <div class="col-md-4" data-aos="fade-up" data-aos-delay="200">
      <div class="card p-3 shadow">
        <h4>Generate Report</h4>
        <button class="btn btn-outline-dark btn-animate mt-3">Generate</button>
      </div>
    </div>
  </div>
</div>

<!-- Bootstrap + JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<!-- AOS JS -->
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
<script>
  AOS.init();
</script>

</body>
</html>

