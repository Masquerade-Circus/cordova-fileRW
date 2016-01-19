# cordova-fileRW
Write and read files helper for cordova apps

## Example:

```javascript
Ready(function(){
	setTimeout(function(){
		fileWR.save2file('hola.txt', 'mundo', function(){
			fileWR.readFile('hola.txt', function(){
				document.body.innerHTML = this.result;
			});
		}, false);
	},2000);
});
```
