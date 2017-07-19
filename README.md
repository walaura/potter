# Potter
CLI tool that fetches strings from a json file and turns them into a .po file

* well, it gives you the copypasteable contents

<div align="center"> <img src='http://i.imgur.com/4Gt6OUt.png'/> </div>

## Usage

	npm install potter -g
  
you can also import it as a library and feed it json strings

	const potter = require('potter');

	const strings = potter({
		"hello": "Welcome to App™",
		"body": "⚡️ Please have fun using App 🌈"
	})
	console.log(strings);
