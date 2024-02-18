---
layout: layouts/base.njk
title: Contact
eleventyNavigation:
  key: Contact
  order: 3
---
<h1> {{title}} </h1>

<fieldset>
<legend> Please fill in to contact the webmaster </legend>
<form name = 'contact' method = 'post' data-netlify='true'>
<div class="row">
  <div class="col">
    <input type="text" class="form-control" placeholder="First name" aria-label="First name" required=“required”>
  </div>
  <div class="col">
    <input type="text" class="form-control" placeholder="Last name" aria-label="Last name" required=“required”>
  </div>
</div>
<div class="col-12">
    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
    <input type="email" class="form-control" id="inputEmail" required=“required”>
  </div>
<div class="col-12">
    <label for="exampleFormControlTextarea1" class="form-label">Message</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"> Enter nice message here </textarea>
  </div>
</div>

Checking this box means you accept the Terms and Conditions 
<input type="checkbox" name="T&C" value="yes" required=“required” /> 
<br>
<div>
<button type="submit" class="btn btn-primary">Submit</button>
</div>
</form>
</fieldset>