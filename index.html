<?php
  require_once('recaptchalib.php');
  $privatekey = "6Lez5dESAAAAAEdBWtLQrz85B3jRTPp9ajx3m4vM";
  
  $resp = null;
  if(!empty($_POST)){
  
  $resp = recaptcha_check_answer ($privatekey,
                                $_SERVER["REMOTE_ADDR"],
                                $_POST["recaptcha_challenge_field"],
                                $_POST["recaptcha_response_field"]);  
  
  }
?>
<?php
	// Set email variables
	$email_to = 'lindashek1@gmail.com';
	$email_subject = 'Lindastic: Form Submission';

	// Set required fields
	$required_fields = array('fullname','email','comment');

	// set error messages
	$error_messages = array(
		'fullname' => 'Please enter a Name to continue.',
		'email' => 'Please enter a valid Email Address to continue.',
		'comment' => 'Please enter your Message to continue.',
		'security' => 'Please enter your valid Security Code to continue.'
	);

	// Set form status
	$form_complete = FALSE;

	// configure validation array
	$validation = array();

	// check form submittal
	if(!empty($_POST)) {
		// Sanitise POST array
		foreach($_POST as $key => $value) $_POST[$key] = remove_email_injection(trim($value));
		
		// Loop into required fields and make sure they match our needs
		foreach($required_fields as $field) {		
			// the field has been submitted?
			if(!array_key_exists($field, $_POST)) array_push($validation, $field);
			
			// check there is information in the field?
			if($_POST[$field] == '') array_push($validation, $field);
			
			// validate the email address supplied
			if($field == 'email') if(!validate_email_address($_POST[$field])) array_push($validation, $field);
		}
		
		// basic validation result
		if(count($validation) == 0) {
			// Prepare our content string
			$email_content = 'New Website Comment: ' . "\n\n";
			
			// simple email content
			foreach($_POST as $key => $value) {
				if($key != 'submit') $email_content .= $key . ': ' . $value . "\n";
			}
			
			// if validation passed ok then send the email
			mail($email_to, $email_subject, $email_content);
			
			// Update form switch
			$form_complete = TRUE;
		}
	}

	function validate_email_address($email = FALSE) {
		return (preg_match('/^[^@\s]+@([-a-z0-9]+\.)+[a-z]{2,}$/i', $email))? TRUE : FALSE;
	}

	function remove_email_injection($field = FALSE) {
	   return (str_ireplace(array("\r", "\n", "%0a", "%0d", "Content-Type:", "bcc:","to:","cc:"), '', $field));
	}

?>

<!DOCTYPE html>
<html lang="en">
<head> 
    <title>Lindastic - Online Portfolio of Linda Shek</title>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" /> 	
	<meta name="keywords" content="Relational Databases, Data Analysis, Web Development, Web Design" />
	<meta name="description" content="I'm Linda Shek. I specialize in relational databases, data analysis, web development, and user interface design." />
    <!--[if IE]>
    	<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    
    <!--[if IE 7]>
    	<link rel="stylesheet" href="ie7.css" type="text/css" media="screen" />
    <![endif]-->  
    <link rel="stylesheet" href="style.css" type="text/css" media="screen" />
	<link rel="stylesheet" href="colorbox.css" />
	<link rel="icon"  type="image/png" href="favicon.ico">
    
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.0/jquery.min.js" type="text/javascript"></script>
    <script src="js/jquery.anchor.js" type="text/javascript"></script>
    <script src="js/jquery.fancybox-1.2.6.pack.js" type="text/javascript"></script>
	
	<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/mootools/1.3.0/mootools-yui-compressed.js"></script>
    <script type="text/javascript" src="js/validation.js"></script>
	<script type="text/javascript">
	  
		var nameError = '<?php echo $error_messages['fullname']; ?>';
		var emailError = '<?php echo $error_messages['email']; ?>';
		var commentError = '<?php echo $error_messages['comment']; ?>';
		var securityError = '<?php echo $error_messages['security']; ?>;
		function MM_preloadImages() { //v3.0
			var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
			var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
			if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
		}
		
		jQuery(document).ready(function () {
			
			jQuery('.inline').colorbox({inline:true, width:"50%"});
        });
	</script>
	
	
	<script type="text/javascript">

	  var _gaq = _gaq || [];
	  _gaq.push(['_setAccount', 'UA-27829772-1']);
	  _gaq.push(['_trackPageview']);

	  (function() {
		var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
		ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
		var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
	  })();

	</script>
    
</head>

<body>

	<script type="text/javascript">
		 var RecaptchaOptions = {
			theme : 'custom',
			custom_theme_widget: 'recaptcha_widget'
		 };
	</script>

    <header> <!-- HTML5 header tag -->
    
    	<div id="headercontainer">
    
    		<h1><a class="introlink anchorLink" href="#intro">The Lindastic Collection</a></h1>
    		
    		<nav> <!-- HTML5 navigation tag -->
    			<ul>
    				<li><a class="introlink anchorLink" href="#intro">Intro</a></li>
    				<li><a class="portfoliolink anchorLink" href="#portfolio">Portfolio</a></li>
    				<li><a class="aboutlink anchorLink" href="#about">About</a></li>
    				<li><a class="contactlink anchorLink" href="#contact">Contact</a></li>
    			</ul>				
    		</nav>
    	
    	</div>
    
    </header>

    <section id="contentcontainer"> <!-- HTML5 section tag for the content 'section' -->
    
    	<section id="intro">
    	
    		<h2 class="intro">Welcome to the Lindastic Collection. <span class="sub">Hello. My name is Linda Shek. I specialize in <em>relational databases</em>, <em>data analysis</em>, <em>web development</em>, and <em>user interface design<em>. </span></h2>
    		
    		<!--<a class="featured" href="http://inspectelement.com"><img src="images/featured.gif" alt="Inspect Element large preview" /></a>
    		
    		<p>Featured Project: <a href="#">Inspect Element</a></p>-->
    				
    	</section>

    	<section id="portfolio"> <!-- HTML5 section tag for the portfolio 'section' -->
    	
    		<h2 class="work">My Portfolio</h2>
    			
    		<ul class="work">
    			
				<li>
					<a class='inline' href="#inline_content1"><img src="images/RMH.jpg" alt="RMH preview" /></a>
					    <!-- This contains the hidden content for inline calls -->
					    
						<div style='display:none'>
							<div id='inline_content1'>
							<p class='maintitle'>Ronald McDonald House</p>
							<p class='subtitle'>What I Did:</p>
							<p>Worked with Ronald McDonald House New York, to produce a room-reservation-maker system. 
								This system would allow social workers from pediatric cancer treatment hospitals to provide housing 
								for pediatric  patients at the Ronald McDonald House New York, which is the largest facility of its kind in the world.<p>
								
							<p>Having the room-reservation-maker system in place will eliminate paper work (e.g. forms), reduce response time to approve or deny a room-reservation date, and allow families to instantly know if a room has been reserved for them at the Ronald McDonald House. </p>

							<p>The database and domain object subsystem directly manages the storage, manipulation, and deletion of data used within the system. The database classes contain the functions necessary to create, update, or delete the records within the tables, as well as to retrieve the records from the database by connecting to it, querying it, and closing it. The domain objects classes represent the chief entities of the system and contain their attributes, identifiers, and getter and setter methods for them. They are accessed from the database classes to form and retain objects utilized throughout the entire system.</p>
								
							<ul>
								<li>Interfaced with Business Clients to gather requirements in order to produce a Requirements Document.</li>
								<li>Responsible for creating the ERD (Entity Relationship Diagram), database script, test database, unit test script for core database functions.</li>
								<li>Worked closely with other developers to find out specific database functions that were needed.</li>
								<li>Produced the majority of the database functions so that front-end users could interact with the database.</li>
								<li>Development environment included the utilization of PHP (a server-side scripting language), MySQL (a DBMS), SQL (query language), and Apache (a web server).</li>
								<li>Utilized project management tools which consists of Subversion (version control system), NetBeans (programming environment), and Visio (diagramming tool).</li>
								<li>Software was hosted on Google Code, were there is a code repository, a wiki, and an issue tracker.</li>
							</ul>
							<p><a href="http://publications.rmdh.org/reserve/rmh-reservation-maker/login.php" target=new>Visit the RMH Room Reservation Maker</a></p>
							

								<!--<ul>
									
									<li>Analyzed Business Requirements from Clients</li>
									<li>Created a working relational database schema</li>
									<li>Utilized SQL Queries to Manipulate Data for Testing and Reports</li>
									<li>Worked closely with other developers to create database functions</li>
									<li>Tools: PHP, SQL, MySQL, Apache, NetBeans, Subversion, Visio, Google Code</li>
								</ul>-->
							
									
							</div>
						</div>
				</li>
				
				<li>
    				<!--<a href="http://publications.rmdh.org/reserve/rmh-reservation-maker/login.php" target=new><img src="images/inspectelementSmall.jpg" alt="Inspect Element preview" /></a>-->
					<a class='inline' href="#inline_content2"><img src="images/PCH.jpg" alt="PCH preview" /></a>
						<!-- This contains the hidden content for inline calls -->
	
						<div style='display:none'>
							<div id='inline_content2'>
							<p class='maintitle'>Publishers Clearing House</p>
							<p class='subtitle'>What I Did</p>
							<p>Created Technical Design Documents based on the various subject areas that were involved. 
							Some of the subject areas that I worked with included: Online/Offline Entries, Prize Engine, Transactions, and PCH Games.</p>
							<p>Publishers Clearing House runs various sweepstakes and has multiple microsites or properties to run these sweepstakes as well as giveaways. Some of these sites include:
							<a href="http://search.pch.com/" target=new>PCHSearch&Win.com</a><a href="http://lotto.pch.com/" target=new>PCHLotto.com</a>
							<a href="http://www.pchgames.com/" target=new>PCHGames.com</a></p>
							<p>The Data Warehouse Team meets with Business Users to figure out the type of Data that needs to be implemented in the Data Warehouse. 
							In order to better understand the Business Requirements as well as the Technical Requirements.</p>
							<p>I learned about the ETL process (Extract, Transform, and Load), the functionalities of the Data Warehouse, 
							how the Data Warehouse is used as a data mining tool, met with Business Users and Technical Users to understand the 
							specific requirements and steps for implementation into the Data Warehouse. </p>
							<p>In the end, the data is used to provide a 360 view of its members (the customers), provide behavioral targeting methods, 
							monetize data, and segmentation.</p>
							<p>Utilized SQL (query language), Microsoft SQL Server 2008 (a DBMS), SSIS (SQL Server Integration Services), Visio (a diagramming tool),
							Excel (for importing data from flat files, filtering data, and creating metadata), Word (for creating documentations - meeting recaps and 
							technical design documents).</p>
							
								<ul>
									<li>Created and Updated Technical Design Documents</li>
									<li>Gathered Business Requirements from Clients</li>
									<li>Utilized SQL Queries to Manipulate Data for Testing and Reports</li>
									<li>Researched Software Packages</li>
									<li>Prepared Meeting Minutes</li>
								</ul>
							</div>
						</div>
				</li>
				
    			<li>
    				<a class='inline' href="#inline_content3"><img src="images/OPD.jpg" alt="One Prime Design preview" /></a>
						<!-- This contains the hidden content for inline calls -->
	
						<div style='display:none'>
							<div id='inline_content3'>
							<p class='maintitle'>One Prime Design</p>
							<p class='subtitle'>What I Did</p>
							<p>Worked on a furniture site for a business client. Collaborated with other web developers to figure out the right color scheme for the website.
							Utilized photoshop to crop and resize images of furniture. Utilized PHP to insert images into the main site for the homepage as well as the gallery collection page.</p>
							<p><a href="http://www.jhornfurniture.com/" target=new>Visit J. Horn Furniture</a><p>
							
							<p>One Prime Design offers business solutions to clients through web design, site architecture, site hosting, custom application development, and more.</p>
							<p>Utilized Adobe Photoshop (a graphics editing program), PHP (a server-side scripting language), SQL (query language), Apache (a Web Server), and Microsoft SQL Server 2008 (a DBMS).</p>
								<ul>
									<li>Responsible for supporting and maintaining websites</li>
									<li>Direct customer support and SQL server database troubleshooting</li>
								</ul>
							</div>
						</div>
				</li>
    			</li>
			</ul>
    				
    	</section>
    			
    	<section id="about"> <!-- HTML5 section tag for the about 'section' -->
    	
    		<h2 class="about">About Me</h2>
    		
    		<p>Hello. My name is Linda Shek. I'm a recent college graduate from St. John's University, with a Bachelor of Science Degree in Computer Science concentrating in Business Administration. I'm a dedicated computer science professional who is pursuing opportunities for growth and advancement in the computer science discipline. Currently I would like to network with IT and Business Professionals. I plan to develop skills in Business Analytics, utilizing both Business and Technical skills. I look forward towards speaking with you and working with you in the future.</p>
    	
    	</section>
		

    		
    	<section id="contact"> <!-- HTML5 section tag for the contact 'section' -->
    	
    		<h2 class="contact">Contact Me</h2>
    		
    		<p>If you love my work, please feel free to send me a message. I will get back to you as soon as I can.</p>
    		
				
			<?php
			if($form_complete === FALSE):?>
			
			
				
			<form action="index.php#contact" method="POST" id="contactform"> 
				
    			<p><label for="name">Name</label></p> 
				<input type="text" id="fullname" class="detail" placeholder="First and last name" name="fullname" value="<?php echo isset($_POST['fullname'])? $_POST['fullname'] : ''; ?>"/><?php if(in_array('fullname', $validation)): ?><span class="error"><?php echo $error_messages['fullname']; ?></span><?php endif; ?>
    			 
    			<p><label for="email">Email</label></p> 
    			<input type="text" id="email" class="detail" placeholder="example@domain.com" name="email" value="<?php echo isset($_POST['email'])? $_POST['email'] : ''; ?>"/><?php if(in_array('email', $validation)): ?><span class="error"><?php echo $error_messages['email']; ?></span><?php endif; ?> 
				
    			<p><label for="comment">Message</label></p> 
    			<textarea id="comment" placeholder="What would you like to say?" name="comment" class="mess"><?php echo isset($_POST['comment'])? $_POST['comment'] : ''; ?></textarea><?php if(in_array('comment', $validation)): ?><span class="error"><?php echo $error_messages['comment']; ?></span><?php endif; ?>
    			<p><label for="security">Security Code</label></p>
				
				<div id="recaptcha_widget" style="display:none;">
					<table>
					<tr>
					   <td>
							<div id="recaptcha_image" style="border: 5px solid #000;"></div>
					   </td>
					     <td>
							<div class="button"><a href="javascript:Recaptcha.reload()"><img src="images/refresh.png"/></a></div>
					   </td> 
						<td>
						&nbsp;&nbsp;&nbsp;&nbsp;
						</td>
						<td>
							<div class="recaptcha_only_if_image"><a href="javascript:Recaptcha.switch_type('audio')"><img src="images/audio.png"/></a></div>
							<div class="recaptcha_only_if_audio"><a href="javascript:Recaptcha.switch_type('image')"><img src="images/text_img.png"/></a></div>
						</td>	
						<td>
						&nbsp;&nbsp;&nbsp;&nbsp;
						</td>
						<td>
						  <div class="help"><a href="javascript:Recaptcha.showhelp()"><img src="images/help.png"/></a></div>
						</td>
					</tr>
					
					<tr>
						<td>
							
						   <input type="text" id="recaptcha_response_field" style="margin-top: 20px;" placeholder="Enter the security code with no spaces" 
						   name="recaptcha_response_field" value="<?php echo isset($_POST['security']) ? $_POST['security'] : ''; ?>"/><?php if($resp != null && !$resp->is_valid && in_array('comment', $validation)): ?><span class="error"><?php echo $error_messages['security']; ?></span><?php endif; ?>
						</td>
					  
					
						
					</tr>
					<!-- recaptacha validation red color-->
					
					</table>
				 </div>

				 <script type="text/javascript"
					src="http://www.google.com/recaptcha/api/challenge?k=6Lez5dESAAAAAFyjjL50BeBwTJxuQXsg-DGiJOU2">
				 </script>
				 <noscript>
				   <iframe src="http://www.google.com/recaptcha/api/noscript?k=6Lez5dESAAAAAFyjjL50BeBwTJxuQXsg-DGiJOU2"
						height="300" width="500" frameborder="0"></iframe><br>
				   <textarea name="recaptcha_challenge_field" rows="3" cols="40">
				   </textarea>
				   <input type="hidden" name="recaptcha_response_field"
						value="manual_challenge">
				 </noscript>
				
				<br/><br/>
    			<input name="submit" type="submit" id="submit" tabindex="5" value="Send Message" /> 	
    			 
    		</form> 
			
				<?php else: ?>
				<p style="font-size: 48px; float: left; color: #4b4b4b;">Thank you for your Message!</p>
				<!--<script type="text/javascript">
				setTimeout('ourRedirect()', 5000)
				function outRedirect(){
					location.href='index.php'
				}
				</script>-->

				<?php endif; ?>
    	
    	</section>
    			
    	<footer> <!-- HTML5 footer tag -->
    		<ul>
    			<li><img src="images/linkedin.png" alt="linkedin"/><a href="http://www.linkedin.com/in/lindashek" target=new>Connect with me on LinkedIn</a></li>	
    		</ul>
			<p>Made with Awesome Stuff such as PHP, HTML5, CSS3, JavaScript, JQuery, and Ajax</p>
			<p>LINDASTIC &#169; 2012</p>
    	</footer>	
    
    </section>
	
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
		<script src="colorbox/jquery.colorbox-min.js"></script>
		<script type="text/javascript">
			jQuery.noConflict();
			jQuery(document).ready(function () {
				
				jQuery('.inline').colorbox({inline:true, width:"50%"});
				});
		</script>
    
	</body>

</html>