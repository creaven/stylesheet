Stylesheet
==========
js stylesheet


How to use
----------

	#js
	var sheet = new Stylesheet();
	
	sheet.addRules({
		'div.test': {
			width: 100,
			height: 100,
			background: 'red'
		},
		'html, body': {
			width: '100%',
			height: '100%'
		},
		'*': {
			margin: 0,
			padding: 0
		}
	});
