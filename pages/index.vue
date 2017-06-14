<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        Nuxt News
      </h1>
      
      <p class="subtitle">
        Periodic Newsletters about everything and anything Nuxt. <br>Fresh content delivered to your mailbox.
      </p>
      <div class="links">
      <!-- Begin MailChimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; width:100%;}
	/* Add your own MailChimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="//site.us16.list-manage.com/subscribe/post?u=6ff33cd556a8d5dea316f6d46&amp;id=d1d999b218" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<label for="mce-EMAIL">Subscribe to our mailing list</label>
	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_6ff33cd556a8d5dea316f6d46_d1d999b218" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
    
</form>
</div>
<p class="subtitle">You wrote a blog post about nuxt?<br>You want to submit a new resource?<br><br><a href="https://github.com/rap2hpoutre/nuxt-news">Send us a PR on Github</a></p>
<br><br>
<p>Made with 👣 by <a href="https://twitter.com/rap2h">rap2h</a></p>
</div>

<!--End mc_embed_signup-->
    </div>
  </section>
</template>

<script>
import Logo from '~components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-left: 15px;
  margin-right: 15px;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 64px;
  margin-top: 20px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 20px;
  color: #526488;
  padding-bottom: 15px;
  padding-top: 35px;
}
.links
{
  padding-top: 15px;
}
</style>
