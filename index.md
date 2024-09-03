<html>
	MIAW Iteration 72. 03/09/2024
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
				embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields( { "Access_Token" : "29154ab7-5d60-4b64-9119-5449342949e5", "Origin_Page" : "/home/my-accounts", "Session_Token" : "87e10251-3892-4add-8fce-c1af9aed77b3" });
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
