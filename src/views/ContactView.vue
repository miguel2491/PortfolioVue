<link src="../../public/css/timeline.css" />
<template>
<div id="main" class="site-main">
    <div class="single-page-content">
        <div id="primary" class="content-area">
            <div class="page-title">
            <h1>Contact</h1>
            <div class="page-subtitle">
                <h4> Get in Touch</h4>
            </div>
            </div>

            <div id="content" class="page-content site-content single-post" role="main">

            <div class="row mapa">
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d9230.969051208152!2d-98.24153061923147!3d19.07886654838979!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1ses-419!2smx!4v1679264383886!5m2!1ses-419!2smx" width="600" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>

            <div class="row mt-3">
                <div class=" col-xs-12 col-sm-4 ">
                <div id="info_list_1" class="info-list-w-icon">
                    <div class="info-block-w-icon">
                    <div class="ci-icon">
                        <i class="linecons linecons-phone"></i>
                    </div>
                    <div class="ci-text">
                        <h4>(+52) 221-436-8482</h4>
                        <p>.</p>
                    </div>
                    </div>

                    <div class="info-block-w-icon">
                    <div class="ci-icon">
                        <i class="linecons linecons-location"></i>
                    </div>
                    <div class="ci-text">
                        <h4>Puebla,México</h4>
                        <p>Colonia Ignacio Romero Vargas, 72120, Puebla,México.</p>
                    </div>
                    </div>
                    
                    <div class="info-block-w-icon">
                    <div class="ci-icon">
                        <i class="linecons linecons-mail"></i>
                    </div>
                    <div class="ci-text">
                        <h4><a href="#" class="__cf_email__" data-cfemail="80e8e5ececefc0e5f8e1edf0ece5aee3efed">miguel.angel.dominguez.serrano@gmail.com</a></h4>
                        
                    </div>
                    </div>
                </div>

                </div>


                <div class=" col-xs-12 col-sm-8 ">

                <div class="block-title">
                    <h2>How Can I Help You?</h2>
                </div>

                <form id="contact_form" class="contact-form" action="contact_form/contact_form.php" method="post">

                    <div class="messages"></div>

                    <div class="controls two-columns">
                    <div class="fields clearfix">
                        <div class="left-column">
                        <div class="form-group form-group-with-icon">
                            <input id="form_name" type="text" name="name" class="form-control" placeholder="Full Name" required="required" data-error="Name is required.">
                            <div class="form-control-border"></div>
                            <div class="help-block with-errors"></div>
                        </div>

                        <div class="form-group form-group-with-icon">
                            <input id="form_email" type="email" name="email" class="form-control" placeholder="Email Address" required="required" data-error="Valid email is required.">
                            <div class="form-control-border"></div>
                            <div class="help-block with-errors"></div>
                        </div>

                        <div class="form-group form-group-with-icon">
                            <input id="form_name" type="text" name="subject" class="form-control" placeholder="Subject" required="required" data-error="Subject is required.">
                            <div class="form-control-border"></div>
                            <div class="help-block with-errors"></div>
                        </div>
                        </div>
                        <div class="right-column">
                        <div class="form-group form-group-with-icon" style="margin-right:20px">
                            <textarea id="form_message" name="message" class="form-control" placeholder="Message" rows="7" required="required" data-error="Please, leave me a message."></textarea>
                            <div class="form-control-border"></div>
                            <div class="help-block with-errors"></div>
                        </div>
                        </div>
                    </div>

                    <div class="g-recaptcha" data-sitekey="6LdqmCAUAAAAAMMNEZvn6g4W5e0or2sZmAVpxVqI" data-theme="dark"></div>

                    <input type="submit" class="button btn-send disabled" value="Send message">
                    </div>
                </form>

                </div>


            </div>

            </div>
        </div>
    </div>
</div>
</template>
<style>
    .mapa{
        width: 90%;
        margin-left: 5%;
    }
</style>