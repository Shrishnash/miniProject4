<!DOCTYPE html>
<html>
    <head>
    </head>
        <body style="text-align:center">
            <h1 style="font-size:50px;color:whitesmoke"><i><u>Cruise Booking Form</u></i></h1>
            <form action="/form.php" target="_blank" method="GET">
                <fieldset>
                <legend><h2>Deposit <span style="color:#9e97c9">(or additional payment)<span></h2></legend>
                <p>Make a <span style="color:white">Deposit/Payment</span></p>
                <input type="text" name="paymentAmount" value="" class="makethispurple" id="box">
                </fieldset>
                <br>
                <fieldset>
                <legend><h2>Travel Insurance</h2></legend>
                <p>Purchase Travel Insurance?</p>
                <input type="radio" name="Insurance" value=""> Yes
                <br><br>
                <input type="radio" name="Insurance" value=""> No
                <br>
                </fieldset>
                <br>
                <fieldset>
                <legend><h2>Personal Information</h2></legend>
                <p>Name</p>
                <input type="text" name="firstName" value="" class="makethispurple">
                <input type="text" name="lastName" value="" class="makethispurple">
                <br>
                <p>Email</p>
                <input type="text" name="email" value="" class="makethispurple" id="box">

                <p>Phone Number</p>
                <input type="number" name="phoneNumber" value="" class="makethispurple" id="box">
                </fieldset>
                <br>
                <fieldset>
                <legend><h2>Addresses</h2></legend>
                <p>Street Address</p><input type="text" name="address1" value="" class="makethispurple" id="box">
                <p>Street Address 2</p><input type="text" name="address2" value="" class="makethispurple" id="box">
                <p>City</p><input type="text" name="city" value="" class="makethispurple" id="box">
                <p>Region</p><input type="text" name="region" value="" class="makethispurple" id="box">
                <p>Postal/Zip Code</p><input type="text" name="zipCode" value="" class="makethispurple" id="box">
                </fieldset>
                <br>
                <fieldset>
                <legend><h2>Date of Birth</h2></legend>
                <input type="date" name="dateOfBirth" value="" class="makethispurple">
                </fieldset>
                <br>
                
                <fieldset>
                <legend><h2>Citizenship</h2></legend>
                <input type="text" name="citizenship" value="" class="makethispurple">
                </fieldset>
                <br>
                <input type="submit" name="Submit" value="Book Your Cruise!" class="makethispurple">

            </form>
        </body>
</html>

