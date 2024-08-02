<html>
	MIAW Iteration 33. 02/08/2024
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "05474239-119c-4a6d-badf-544a529a1537", "IP_Address" : "255.255.255.255", "Origin_Page" : "Github" } );
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
