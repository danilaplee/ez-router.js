##Ez-Router v.0.1.0
=========

##Super-easy AJAX routing solution for all your nerdly needs

Build Ajax and Jquery powered web apps using only css selectors in 5 minutes

## 0 - don't forget to include some jquery and <a href="https://github.com/browserstate/history.js/">history.js</a>

Ok, we are set to go

##First define the options(somewhere in your head):

	<script type="text/javascript">
	var $EzNav = $('whatever your header is or the part of your page you don't wish to reload')
	var $EzContainer = $('whatever you want to be totally dynamic and uploading dynamically with the url')
	var $EzModal =  $('whatever container you wish to define as your modal window')
	</script>

##Second include the script

Now all your links are used as targets for a simple AJAX-GET request on the designated url

Finally just add some classnames to your basic link tags

	<a href="/shop" class="basicMe"> - Defines your basic needs to convert the request to non-ajax

	<a href="/cart" class="modalMe"> - Loads content into your modal window
	
