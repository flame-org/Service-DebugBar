#ServicePanel

**[DEPRECATED] Panel for Nette 2.0 which shows list of all available services**

##Installation:
Insert the following code into config.neon

	nette:
		debugger:
			bar:
				- Flame\Diagnostics\ServicePanel\ServicePanel

**NETTE has got own session debug bar**
###Activation
In config.neon
	
	nette:
		session:
			debugger: true
			expiration: 14 days
			autoStart: smart
			...