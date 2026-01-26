<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DBm000004Ug5x',
				'Agentforce',
				'https://marion--comfull.sandbox.my.site.com/ESWAgentforce1769383889845',
				{
					scrt2URL: 'https://marion--comfull.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://marion--comfull.sandbox.my.site.com/ESWAgentforce1769383889845/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
