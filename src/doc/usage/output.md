### lib/bower.json

```json
{
	"registry": {
		"publish": "http://localhost:8000",
		"register": "http://localhost:8000",
		"search": [
			"http://localhost:8000"
		]
	},
	"storage": {
		"cache": "~/.bower/cache",
		"registry": "~/.bower/registry"
	},
	"analytics": true,
	"ca": "/etc/ssl/cert.pem",
	"color": "true",
	"cwd": "~/my-project",
	"directory": "~/my-project/vendor",
	"https-proxy": "https://localhost:8081",
	"interactive": true,
	"proxy": "http://localhost:8080",
	"shorthand-resolver": "git://example.com/{{shorthand}}.git",
	"timeout": 40000,
	"tmp": "~/.bower/tmp",
	"user-agent": "Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36"
}
```