# CSS hacks or conditional comments
CSS hacks or conditional comments, for all IE including IE10, IE11 and all versions of EDGE

<strong>ALL IE VERSIONS</strong>
```css
			<!--[if IE]>
				<link rel="stylesheet" type="text/css" href="css/estilos2.css" />
			<![endif]-->
```
<strong>ALL NON-IE VERSIONS</strong>
```css
			<!--[if !IE]><!-->
				<link rel="stylesheet" type="text/css" href="css/estilos1.css" />
			<!--<![endif]-->
```		
<strong>IE 10 without hacks, using USER-AGENT sniffing</strong>
```css
			html[data-useragent*='MSIE 10.0'] p {
			  color: green;
			}
```			
<strong>IE 11 without hacks, using UE sniffing</strong>
```css
			html[data-useragent*='rv:11.0'] p {
			  color: pink;
			}
```
<strong>ALL Edge versions using @supports -ms-ime-align </strong>
```css
			@supports (-ms-ime-align:auto) p {
				color:yellow; 
			}
```
<hr/>
				
<br/>
<strong>Some proofs</strong><br/><br/>
<strong>Google Chrome</strong><br/>
![Alt text](https://user-images.githubusercontent.com/14861253/27251224-03e6e2ea-5343-11e7-9b76-1f6a06bb5763.png)
<br/><br/><hr/>

<strong>Internet explorer 8 </strong><br/>![Alt text](https://user-images.githubusercontent.com/14861253/27251226-0b15f09c-5343-11e7-8c60-20329ab2beba.png)<br/><br/><hr/>

<strong>Internet explorer 11</strong><br/>![Alt text](https://user-images.githubusercontent.com/14861253/27251228-10b8acb0-5343-11e7-8ceb-a62d98fcc75d.png)<br/><br/><hr/>
