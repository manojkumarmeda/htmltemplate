<html>
<head>
<link rel="stylesheet" href="https://getbootstrap.com/docs/4.1/dist/css/bootstrap.min.css" />
<link href="https://cdn.datatables.net/1.10.20/css/jquery.dataTables.min.css" rel="stylesheet"/>
<link href="https://cdn.datatables.net/rowgroup/1.1.1/css/rowGroup.dataTables.min.css" rel="stylesheet" />
<link href="https://getbootstrap.com/docs/4.1/examples/starter-template/starter-template.css" rel="stylesheet"/>
<link rel="stylesheet" href="https://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
<style>
.bg-green {
  background-color: #006637 !important;
}

a.bg-green:hover, a.bg-green:focus,
button.bg-green:hover,
button.bg-green:focus {
  background-color: #0062cc !important;
}
</style>
</head>
<body>
<nav class="navbar navbar-expand-md navbar-dark bg-green fixed-top">
  <a class="navbar-brand" href="#"><img src="https://jqueryui.com/jquery-wp-content/themes/jquery/images/logo-jquery-ui.png" height="40px" /></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
	<span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarsExampleDefault">
	<ul class="navbar-nav mr-auto">
	  <li class="nav-item active">
		<a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
	  </li>
	  <li class="nav-item">
		<a class="nav-link" href="#">Link</a>
	  </li>
	  <li class="nav-item">
		<a class="nav-link disabled" href="#">Disabled</a>
	  </li>
	  <li class="nav-item dropdown">
		<a class="nav-link dropdown-toggle" href="https://example.com" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</a>
		<div class="dropdown-menu" aria-labelledby="dropdown01">
		  <a class="dropdown-item" href="#">Action</a>
		  <a class="dropdown-item" href="#">Another action</a>
		  <a class="dropdown-item" href="#">Something else here</a>
		</div>
	  </li>
	</ul>
	<form class="form-inline my-2 my-lg-0">
	  <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
	  <button class="btn btn-outline-default my-2 my-sm-0" type="submit">Search</button>
	</form>
  </div>
</nav>
<div class="container">
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%22800%22%20height%3D%22400%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20800%20400%22%20preserveAspectRatio%3D%22none%22%3E%3Cdefs%3E%3Cstyle%20type%3D%22text%2Fcss%22%3E%23holder_16fcd992977%20text%20%7B%20fill%3A%23555%3Bfont-weight%3Anormal%3Bfont-family%3AHelvetica%2C%20monospace%3Bfont-size%3A40pt%20%7D%20%3C%2Fstyle%3E%3C%2Fdefs%3E%3Cg%20id%3D%22holder_16fcd992977%22%3E%3Crect%20width%3D%22800%22%20height%3D%22400%22%20fill%3D%22%23777%22%3E%3C%2Frect%3E%3Cg%3E%3Ctext%20x%3D%22285.9140625%22%20y%3D%22217.7%22%3EFirst%20slide%3C%2Ftext%3E%3C%2Fg%3E%3C%2Fg%3E%3C%2Fsvg%3E" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%22800%22%20height%3D%22400%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20800%20400%22%20preserveAspectRatio%3D%22none%22%3E%3Cdefs%3E%3Cstyle%20type%3D%22text%2Fcss%22%3E%23holder_16fcd992978%20text%20%7B%20fill%3A%23444%3Bfont-weight%3Anormal%3Bfont-family%3AHelvetica%2C%20monospace%3Bfont-size%3A40pt%20%7D%20%3C%2Fstyle%3E%3C%2Fdefs%3E%3Cg%20id%3D%22holder_16fcd992978%22%3E%3Crect%20width%3D%22800%22%20height%3D%22400%22%20fill%3D%22%23666%22%3E%3C%2Frect%3E%3Cg%3E%3Ctext%20x%3D%22247.3125%22%20y%3D%22217.7%22%3ESecond%20slide%3C%2Ftext%3E%3C%2Fg%3E%3C%2Fg%3E%3C%2Fsvg%3E" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%22800%22%20height%3D%22400%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20800%20400%22%20preserveAspectRatio%3D%22none%22%3E%3Cdefs%3E%3Cstyle%20type%3D%22text%2Fcss%22%3E%23holder_16fcd992979%20text%20%7B%20fill%3A%23333%3Bfont-weight%3Anormal%3Bfont-family%3AHelvetica%2C%20monospace%3Bfont-size%3A40pt%20%7D%20%3C%2Fstyle%3E%3C%2Fdefs%3E%3Cg%20id%3D%22holder_16fcd992979%22%3E%3Crect%20width%3D%22800%22%20height%3D%22400%22%20fill%3D%22%23555%22%3E%3C%2Frect%3E%3Cg%3E%3Ctext%20x%3D%22276.9921875%22%20y%3D%22217.7%22%3EThird%20slide%3C%2Ftext%3E%3C%2Fg%3E%3C%2Fg%3E%3C%2Fsvg%3E" alt="Third slide">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>
<main role="main" class="container-fluid">
<div class="row">
<div class="col-10">
<div id="dialog" title="Basic dialog">
  <table id="example" class="table table-striped table-bordered table-hover"></table>
</div>
</div>
</div>
</main>

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://getbootstrap.com/docs/4.1/assets/js/vendor/popper.min.js"></script>
<script src="https://getbootstrap.com/docs/4.1/dist/js/bootstrap.min.js"></script>
<script src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script src="https://cdn.datatables.net/1.10.20/js/jquery.dataTables.min.js" ></script>
<script src="https://cdn.datatables.net/rowgroup/1.1.1/js/dataTables.rowGroup.min.js" ></script>
<script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
<script type="text/javascript">
$(document).ready(function() {
	$( "#dialog" ).dialog();
    $('#example').DataTable( {
        data: aDemoItems,
		scrollY: 300,
        //paging:  false,
		columns : [
            { data : "patientId",title:"PatientId" },
            { data : "otherId",title : "OtherId" },
            { data : "firstName",title : "FirstName" },
            { data : "lastName",title : "LastName" },
            { data : "gender", title : "Gender" },
            { data : "dob",title : "DOB" },
            { data : "race",title : "Race" }
        ]
    } );
} );
var aDemoItems = [
    {
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":1,
        "otherId":"LanTest101",
        "firstName":"x1",
        "lastName":"yLanTest101",
        "gender":"M",
        "dob":"10/16/1941",
        "race":"Caucasian/White"
    },
    {
        "patientId":2,
        "otherId":"LanTest102",
        "firstName":"x2",
        "lastName":"yLanTest102",
        "gender":"M",
        "dob":"08/10/2005",
        "race":"Caucasian/White"
    },
    {
        "patientId":3,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    },{
        "patientId":4,
        "otherId":"Test1111",
        "firstName":"x2",
        "lastName":"yTest1111",
        "gender":"F",
        "dob":"08/13/2015",
        "race":"Native Hawaian/Pacific Islander"
    }
]
</script>
</body>
</html>
