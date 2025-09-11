<html>
	MIAW Iteration 131. 11/09/2025
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "b01812c0-210c-4b12-afaf-cb9e8cd458ae", "Origin_Page" : "/home/my-accounts", "Session_Token" : "" });
			});
			embeddedservice_bootstrap.init(
				'00DUB00000069dJ',
				'MIAW_EsmondDev4',
				'https://bordgaisenergyeandu--esmonddev.sandbox.my.site.com/ESWMIAWEsmondDev41703172693512',
				{
					scrt2URL: 'https://bordgaisenergyeandu--esmonddev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
	</script>
	<script type='text/javascript' src='https://bordgaisenergyeandu--esmonddev.sandbox.my.site.com/ESWMIAWEsmondDev41703172693512/assets/js/bootstrap.min.js' 	onload='initEmbeddedMessaging()'></script>
 	 </body>
</html>
