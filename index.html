<?php


if(isset($_POST['submit']))
{
	
	 $contact = $_POST["contact"];
	 $msg = $_POST["textbox"];

	$fields = array(
					    "sender_id" => "TXTIND",
					    "message" => "$msg",
					    "route" => "v3",
					    "numbers" => "$contact",
					);

	$curl = curl_init();

	curl_setopt_array($curl, array(
	  CURLOPT_URL => "https://www.fast2sms.com/dev/bulkV2",
	  CURLOPT_RETURNTRANSFER => true,
	  CURLOPT_ENCODING => "",
	  CURLOPT_MAXREDIRS => 10,
	  CURLOPT_TIMEOUT => 30,
	  CURLOPT_SSL_VERIFYHOST => 0,
	  CURLOPT_SSL_VERIFYPEER => 0,
	  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
	  CURLOPT_CUSTOMREQUEST => "POST",
	  CURLOPT_POSTFIELDS => json_encode($fields),
	  CURLOPT_HTTPHEADER => array(
	    "authorization: R8opX7lUMeDFP2AGjLicak5fmnbH4QTIu0szEBZKtSr13vY6CVwjTeByFhRicG7xuar1o2ns8M9YmbqE",
	    "accept: */*",
	    "cache-control: no-cache",
	    "content-type: application/json"
	  ),
	));

	$response = curl_exec($curl);
	$err = curl_error($curl);

	curl_close($curl);

	if ($err) 
	{
	  //echo "cURL Error #:" . $err;
	   echo "<script>alert('Something Went Wrong..');</script>";
	} 
	else
	{
	    // echo $response;
	    echo "<script>alert('SMS Sent Successfully..');</script>";
	}
	
}





?>
<!DOCTYPE html>
<html>
<head>
	<title>SMS APP</title>
	<link rel="stylesheet" type="text/css" href="s3.css">
</head>
<body>
	<div class="header">
		<h1>SMS APPLICATION</h1>
	</div>


	<div class="content">
		<form method="post" style="margin-top: 90px;">
			<table  align="center" cellpadding="10" cellspacing="0">
				
				<tr>
					<td>Mobile Number:</td>
					<td><input type="text" id="contact" name="contact"></td>
				</tr>

				<tr>
					<td>Message:</td>
					<td><textarea type="textarea" rows="4" cols="50" id="textbox" name="textbox"></textarea></td>
				</tr>
				
				
				<tr>
					<td colspan="2" align="center">
						<input type="submit" id="submit" name="submit" value="Send SMS"></td>
				</tr>
			</table>
	</form>
	</div>


	<div class="footer">
		<h3>by DIVYA HEMNANI</h3>
	</div>
</body>
</html>