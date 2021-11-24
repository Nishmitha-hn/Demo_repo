1) URL for Register-
	Method-> POST
	Link-> https://zgritn03j0.execute-api.us-east-2.amazonaws.com/prod/register
	Content-> {
  		    "username": "xyz@gmail.com",
                    "age": 23,
                    "password": "xyz"
		  }	
	Response->"Status": "User Registered Successfully"


2) URL for Login-
	Method-> POST
	Link-> https://zgritn03j0.execute-api.us-east-2.amazonaws.com/prod/login?email=nishu@gmail.com&password=lmn
	Response-> Status: Access Granted

3) URL for get all users-
	Method-> GET
	Link-> https://zgritn03j0.execute-api.us-east-2.amazonaws.com/prod/getallrecords
	Response-> List of all records

4) URL for Age Filter-
	Method-> GET
	Link-> https://zgritn03j0.execute-api.us-east-2.amazonaws.com/prod/getagerecords?age=23
	Response-> List of users whose age=23

 