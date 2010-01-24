Stylesheet
==========
js stylesheet


How to use
----------

	#js
	var sheet = new Stylesheet();
	
	sheet.addRules({

		'div.pushbutton': {
			'cursor': 'default',
			'overflow': 'hidden',
			'height': '22px',
			'min-width': '60px',
			'display': 'inline-block',
			'text-align': 'center',
			'font-size': '12px',
			'position': 'relative',
			'font-family': '"Lucida Grande", "Helvetica", Arial, sans-serif',
			'white-space': 'nowrap',
			'padding': '0 5px',
			'background-image': 'button-right.png',
			'background-repeat': 'no-repeat',
			'background-position': 'right 0'
		},

		'div.pushbutton div.bg': {
			'background-image': 'button-left.png',
			'background-repeat': 'no-repeat',
			'width': '50px',
			'display': 'inline-block',
			'height': '22px',
			'position': 'absolute',
			'left': '0px',
			'top': '0'
		},

		'div.pushbutton.hover': {
			'background-image': 'button-hover-right.png'
		}
		
	});
