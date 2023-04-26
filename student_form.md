<!DOCTYPE html>
<html>
<head>
	<title>Student Registration Form</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
	<style>
		.container {
			margin-top: 50px;
		}
        div{
           
            width:100%;
             
        }
       
	</style>
</head>
<body>
	<div class="container">  
		<h1 style="text-align:center ;">Student Registration Form</h1>
		<form action="" method="post">
         <div class="row">
		 
		 <div class="form-group col-md-6">
				<label for="STD">  ADMISSION STD :</label>
				<select class="form-control" id="STD" name="STD">
					<option value="CLASS:9">CLASS:9</option>
					<option value="">class:10</option>
					<option value="class:10">CLASS:11 ARTS</option>
					<option value="CLASS:11 COMMERCE">CLASS:11 COMMERCE</option>
					<option value="CLASS:11 SCIENCE">CLASS:11 SCIENCE</option>
					<option value="CLASS:12 ARTS">CLASS:12 ARTS</option>
					<option value="CLASS:12 COMMERCE">CLASS:12 COMMERCE</option>
					<option value="CLASS:12 SCIENCE">CLASS:12 SCIENCE</option>
				</select>
			</div>
		 
		 <div class="form-group col-md-6" >
				<label> </label>
				<span> <h2 style="text-align:center">ADMISSION YEAR<h2></span>
			</div>
		
		 
			<div class="form-group col-md-6" >
				<label for="name"> Student Name:</label>
				<input type="text" class="form-control" id="name" name="name" placeholder=" Student Name:" required>
			</div>

			<div class="form-group col-md-6">
				<label for="fatherName">Father's Name:</label>
				<input type="text" class="form-control" id="fatherName" name="fatherName" placeholder="Father's Name:" required>
			</div>

			<div class="form-group col-md-6">
				<label for="motherName">Mother's Name:</label>
				<input type="text" class="form-control" id="motherName" name="motherName"placeholder="Mother's Name:" required>
			</div>

			<div class="form-group col-md-6">
				<label for="surname">Surname:</label>
				<input type="text" class="form-control" id="surname" name="surname"placeholder="Surname:" required>
			</div>

			<div class="form-group col-md-6">
				<label for="dob">Date of Birth:</label>
				<input type="date" class="form-control" id="dob" name="dob" required>
			</div>
			
			<div class="form-group col-md-6">
				<label>Gender:</label><br>
				<div class="form-check-inline">
					<label class="form-check-label">
						<input type="radio" class="form-check-input" name="gender" value="male" required>Male
					</label>
				</div>

                <div class="form-check-inline col-md-6">
					<label class="form-check-label">
						<input type="radio" class="form-check-input" name="gender" value="female" required>Female
					</label>
				</div>
            </div>

			<div class="form-group col-md-6">
				<label for="address">Address:</label>
				<textarea class="form-control" id="address" name="address" rows="4" placeholder="Address:" required></textarea>
			</div>

			<div class="form-group col-md-6">
				<label for="village">Village:</label>
				<input type="text" class="form-control" id="village" name="village"placeholder="Village:" required>
			</div>


			<div class="form-group col-md-6">
				<label for="caste">Caste:</label>
				<select class="form-control" id="caste" name="caste">
					<option value="general">General</option>
					<option value="obc">OBC</option>
					<option value="sc">SC</option>
					<option value="st">ST</option>
				</select>
			</div>

			<div class="form-group col-md-6">
				<label for="Sub_Cast">SUB CAST:</label>
				<input type="text" class="form-control" id="Sub_Cast" name="Sub_Cast"placeholder="SUB CAST:" required>
			</div>
			

       
			
			<div class="form-group col-md-6">
				<label for="whatsapp">WhatsApp Number:</label>
				<input type="number" class="form-control" id="whatsapp" name="whatsapp" size="10"   placeholder="WhatsApp Number:" required>
			</div>

			<div class="form-group col-md-6">
               <label for="mobile">Mobile Number:</label>
				<input type="number" class="form-control" id="mobile"  name="mobile"placeholder="Mobile Number:"  required>
			</div>

			

                <div class="form-group col-md-6">
                    <label class="form-check-label">previous school Name:</label>
                    <input type="text" class="form-control" id="pre_school" name="Qualification" placeholder="previous school:" required>
                </div>
				
                <div class="form-group" style="text-align: center;">
                    <button type="submit" class="btn btn-primary">Submit</button>
                    <button type="reset" class="btn btn-secondary">Reset</button>
                </div>

            </div> 
			</form>	
	</div>			
