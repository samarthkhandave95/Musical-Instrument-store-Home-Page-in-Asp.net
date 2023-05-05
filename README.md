# Musical-Instrument-store-Home-Page-in-Asp.net Using Bootstrap
# You have to write this code  in master page.
<%@ Master Language="C#" AutoEventWireup="true" CodeBehind="Site1.master.cs" Inherits="WebApplication1.Site1" %>

<!DOCTYPE html>

<html>
<head runat="server">
    <link href="StyleSheet1.css" rel="stylesheet" />
    <title>Online MUSICAL STORE</title>
    <%--<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
     
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>--%>



  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>


    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>





    
   
        <style>
            body {
                /*background-image: url('images/tabla.jpg');
                background-repeat: no-repeat;
                style = "height:300px; width:400px";
             */
            }
            h3 {
                color:orange;
            }
            middle{
                color:white;
            }
            p{
                color:white;
            }
            header{
                color:white;
                font-size:xx-large;
            }
             footer {
             position:fixed;
             bottom:0;
             width: 100%;
             height: 30px; /* adjust the height as needed */
             background-color: orange;
             color: #fff;
			  
             text-align: center;
             padding-top: 10px;
			

				   color:orange;
				   font:100;
			   }
        </style>




    <asp:ContentPlaceHolder ID="head" runat="server">
    </asp:ContentPlaceHolder>
    <style>
        .customClassForDropdown{
            height:100px;
            overflow-y:auto;

            
        }
    </style>









</head>
<body>
    <style>
        .header {
   display: flex;
   justify-content: flex-end;
}

    </style>

    <form id="form1" runat="server">
        <nav class="navbar navbar-inverse navbar-fixed-top">
            <div class="container-fluid">
                <div class="navbar-header">
                    <a class="navbar-brand" href="#">Musical Store</a>
                </div>

            </div>

            <ul class="nav navbar-nav">
                <li class="active"><a href="homepage.aspx">Home</a></li>
                

                <li class="active"><a href="aboutus.aspx">About Us</a></li>
                
               
                
                
                <li class="active"><a href="userregistration.aspx" class="right">Register</a></li>
                <%--<li class="active"><a href="userlogin1.aspx" class="right">Login</a></li>
                --%>
                <li class="dropdown">
                    <a href="#" class="dropdown-toggle" data-toggle="dropdown">Login<b class="caret"></b></a>
                    <ul class="dropdown-menu">
                   
                        
                            
                                <li><a href="adminlogin.aspx">ADMIN</a>
                            <li role="separator" class ="divider"></li>
                        <li><a href="userlogin1.aspx">USER</a></li>
                        </ul>

                                </li>
                


           
                <li class="dropdown">
                    <a href="product.aspx" class="dropdown-toggle" data-toggle="dropdown">product<b class="caret"></b></a>
                   
                        <ul class="dropdown-menu">
                            <ul class="vertical-menu">
                            <li class="dropdown-header"style="text-decoration-thickness:revert;">String Instrument</li>
                            <li role="separator" class ="divider"></li>
                            <li> <a href="violin1.aspx">Violin</a></li >
                              <li> <a href="Guitar1.aspx">Guitar</a></li >
                              <li> <a href="sitar1.aspx">Sitar</a></li >
                              <li> <a href="veenaaspx.aspx">veena</a></li >

                                <li role="separator" class ="divider"></li>
                            <li class="dropdown-header">Percussion Instrument</li>
                            <li role="separator" class ="divider"></li>
                            <li> <a href="timpani.aspx">Timpani</a></li >
                              <li> <a href="tabla.aspx">Tabla</a></li >
                              <li> <a href="#">Cymbals</a></li >
                              <li> <a href="#">Snare Drum</a></li >

                                <li role="separator" class ="divider"></li>
                           <li class="dropdown-header">Wood Instrument</li>
                            <li role="separator" class ="divider"></li>
                            <li> <a href="flute.aspx">Flute</a></li >
                              <li> <a href="piccolo.aspx">Piccolo</a></li >
                              <li> <a href="recorder.aspx">Recorder</a></li >
                              <li> <a href="saxophone.aspx">Saxophone</a></li >

                                <li role="separator" class ="divider"></li>
                              <li class="dropdown-header">Keyboard Instrument</li>
                            <li role="separator" class ="divider"></li>
                            <li> <a href="product.aspx">Piano</a></li >
                              <li> <a href="Guitar.aspx">Accordion</a></li >
                              <li> <a href="#">Harmonium</a></li >
                              <li> <a href="#">Harpsichord</a></li >
                                
                            
                                </li>
                    
                                
                                
                            


                              
                
              
                
               
<%--                            <a href="product.aspx">All Product</a></li>--%>
                        
<ul>
    </div>




                </li>
  
                    
           
                </div>
            </div>
                   
          
       
       

               
         
               
      
   





        </u1>
                

  





        
  
         
        </li>
       
      </u1>
       
           
               
   
        </u1>
      
       
    </div>
  </div>
</nav>
        </br>
        </br >
        </br>
        </br>
        </br>
        </br>
        </br>
        </br>
                     
 </div>
            



 </nav>


    
   <footer>
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-8 text-center">
                    <center>
                        <p>
                            Copyright &copy; 2023 Your Musical System   |Terms of Use| 
                        </p>
                    </center>
                </div>
            </div>
        </div>
    </footer>


        <asp:ContentPlaceHolder ID="ContentPlaceHolder1" runat="server">
        </asp:ContentPlaceHolder>

    </form>
</body>
</html>
