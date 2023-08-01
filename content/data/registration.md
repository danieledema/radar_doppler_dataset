---
title: 'Registration'
date: 2023-03-30
weight: 1
summary: "Use your academic email address to register and obtain the download link."
---


Registration is not available yet, please check out this website in a few days.


## Registration

Please use your **university academic email address** (e.g. .ac / .edu) to register, if we cannot verify this address we will get in touch with you personally.
Please make sure you can receive emails from the following address to receive the verification email from **radardopplerdataset@robots.ox.ac.uk**.

###### Timeline
Please only register once below per user.
Once you have registered please wait for a verification email to your academic address which should take up to 1hr to arrive depending on the volume of registrations.
After your email is verified we are required to manually approve your academic credentials which may take up to 24hr during the working week.
When this is done you will be sent a welcome email and downloads will be enabled.

###### Oxford Robotics Institute
If you are a member of the Oxford Robotics Institute please consider using the internal mirror to avoid duplication.

### Registration Form

<form method="post"> <!-- action="https://forms.un-static.com/forms/YOUR_ENDPOINT_REFERENCE"-->
  <div class="form-group row">
    <label for="name" class="col-4 col-form-label">Name</label>
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon">
          <i class="fa fa-user"></i>
        </div>
        <input id="name" name="name" placeholder="Please enter your name" type="text" required="required" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="email" class="col-4 col-form-label">E-mail address</label>
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-addon">
          <i class="fa fa-envelope"></i>
        </div>
        <input id="email" name="email" placeholder="Your e-mail address" type="text" required="required" class="form-control">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="message" class="col-4 col-form-label">Message (optional)</label>
    <div class="col-8">
      <textarea id="message" name="message" cols="40" rows="10" class="form-control"></textarea>
    </div>
  </div>
  <div class="form-group row">
    <label class="col-10 col-form-label" for="accept">
        By checking, I agree that:
        <ol>
        <li>The data are only to be processed for the purposes of robotics research.</li>
        <li>No attempt to profile or de-anonymise the individuals in the data set will be made.</li>
        <li>The data must not be shared with any other parties.</li>
        <li>The data should be stored in GDPR secure systems.</li>
        <li>All efforts to avoid the data being leaked to a third party must be made.</li>
        <li>We may require that you delete the data at any time.</li>
        <li>We may require that you update the data from our servers at any time.</li>
        </ol>
        I agree to the terms and conditions and acknowledge that the data and files are distributed under the CC BY-NC-SA 4.0 license. I agree that the dataset is to be used for academic and non-commercial purposes. I understand that the owner (University of Oxford) reserves the right to withdraw access for any reason.
    </label>
    <div class="col-2">
        <input type="checkbox" id="accept" required="required" name="accept" value="true">
    </div>
  </div>
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button name="submit" type="submit" class="btn btn-primary">Send</button>
    </div>
  </div>
</form>
