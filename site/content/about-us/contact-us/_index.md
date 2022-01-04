---
author:
  name: SmartWinnr
  email: smartwinnr@mobillionlabs.com
title: Contact Us | SmartWinnr
og_title: Contact Us | SmartWinnr
description: Contact SmartWinnr
description: Contact SmartWinnr
keywords: ["smartwinnr"]
license: '[CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0)'
published: 2017-04-14
type: ml_layout
layout: ml_layout
---

<section>
  <div class="ml-background-white padding30">
    <div class="row ml_div_contents_in_center">
      <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 text-center">
        <h1>How can we help you?</h1>
        <h3>Write to us and we will respond immediately.</h3>
      </div>
      <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 padding80">
        <form class="ml_request_demo_signup" action="https://bu4y0vkrwi.execute-api.us-west-2.amazonaws.com/prod" method="post" id="webform-client-form-11" accept-charset="UTF-8">
        <h2 class="ml-title-adjustable">Get in Touch</h2>
        <input name="_honeypot" style="display:none" type="text">
            <input type="hidden" name="_to" value="94867cb7283ac9911fadb73040c85fbe11aeafbffb09">
            <input type="hidden" name="_redirect" value="https://smartwinnr.com/form-successful">
          <div>
            <div  class="form-item">
              <label class="element-invisible" for="edit-submitted-name">Name <span class="form-required" title="This field is required.">*</span></label>
              <input required="required" placeholder="Name" type="text" id="edit-submitted-name" name="submitted[name]" value="" size="60" maxlength="128" class="form-text required" />
            </div>
            <div  class="form-item">
              <label class="element-invisible" for="edit-submitted-email">Company Business Email <span class="form-required" title="This field is required.">*</span></label>
              <input required="required" class="email form-text form-email required" placeholder="Company Business Email" type="email" id="edit-submitted-email" name="submitted[email]" size="60" />
            </div>
            <div  class="form-item">
              <label class="element-invisible" for="edit-submitted-phone-number">Phone Number<span class="form-required" title="This field is required.">*</span></label>
              <input required="required" placeholder="Phone Number" type="text" id="edit-submitted-phone-number" name="submitted[phone_number]" value="" size="60" maxlength="128" class="form-text" />
            </div>
            <div  class="form-item">
              <label class="element-invisible" for="edit-submitted-company-name">Company Name <span class="form-required" title="This field is required.">*</span></label>
              <input required="required" placeholder="Company Name" type="text" id="edit-submitted-company-name" name="submitted[company_name]" value="" size="60" maxlength="128" class="form-text required" />
            </div>
            <div  class="form-item">
              <label class="element-invisible" for="edit-submitted-message">Message </label>
              <textarea placeholder="Give us a brief outline of your requirements, to create a customised demo for you" id="edit-submitted-message" id="edit-submitted-message" name="submitted[message]" cols="60" rows="3" class="form-textarea"></textarea>
            </div>
            <input type="hidden" name="details[sid]" />
            <input type="hidden" name="details[page_num]" value="1" />
            <input type="hidden" name="details[page_count]" value="1" />
            <input type="hidden" name="details[finished]" value="0" />
            <input type="hidden" name="form_build_id" value="form-tF8e92Q7jjjIwQLZpoEP76p1bd1_SSsc_ysKTTOhfMw" />
            <input type="hidden" name="form_id" value="webform_client_form_11" />
            <div class="form-actions text-center"><input class="webform-submit form-submit" type="submit" name="op" value="Get in Touch" />
            </div>
          </div>
        </form>
        <!-- <form action="https://bu4y0vkrwi.execute-api.us-west-2.amazonaws.com/prod"
         method="post"><input name="_honeypot" style="display:none" type="text">
             <input type="hidden" name="_to" value="94867cb7283ac9911fadb73040c85fbe11aeafbffb09"> -->
         <!-- <div class="input-group"><label>Email</label><input name="_to" type="email"></div> -->
         <!-- <div class="input-group"><label>Message</label><textarea name="message"></textarea></div>
           <div class="input-group"><label>Name</label><textarea name="Name"></textarea></div>
           <div class="input-group"><label>Company</label><textarea name="Company"></textarea></div>
         <div class="input-group"><input class="button" value="Send message" type="submit"></div>
       </form> -->
      </div>
    </div>
  </div>
</section>

<script>
$(document).ready(function() {
  $(':input[type="submit"]').prop('disabled', true);
  $('input[type="text"]').keyup(function() {
    if($(this).val() != '') {
      $(':input[type="submit"]').prop('disabled', false);
    }
  });
});
$(function() {
  $( ".ml-loading-button" ).click(function() {
    $( ".ml-loading-button" ).addClass( "onclic", 250, validate);
  });

  function validate() {
    setTimeout(function() {
      $( ".ml-loading-button" ).removeClass( "onclic" );
      $( ".ml-loading-button" ).addClass( "ml-validate", 450, callback );
    }, 2250 );
  }
  function callback() {
    setTimeout(function() {
      $( ".ml-loading-button" ).removeClass( "ml-validate" );
    }, 1250 );
  }
});
</script>