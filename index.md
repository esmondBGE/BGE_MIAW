<html>
	MIAW Iteration 28. 31/07/2024
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "405fd596-0991-46b0-accd-2964c723bf54", "IP_Address" : "255.255.255.255", "Origin_Page" : "Github" } );
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
