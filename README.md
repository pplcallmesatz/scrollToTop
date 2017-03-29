# scrollToTop
This is an plugin to the beginners. Here we can customise the  scroll top content. Now it is in initial stage.


# Insatallation Guide:

Basic Setup:
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="scrollToTop.js"></script>

HTML Mocup:
<div class="scroll"></div>

Jquery:
```javascript
$('.scroll').scrollToTop();

Jquery Settings:
	$('.scroll').scrollToTop({
		color: "yellow",
		backgroundColor:"#fff",
		svg: {
		      fill: "#C80C17"
	       },
		animation: {
			          scrollPosition: "150",
		            speed: "speed"
		          }
	});
```
Jquery settings properties:
1. color
2. backgroundColor
3. svg:
      - fill
4. animation:
      - scrollPosition
      - speed
      


working in progress, you may expect more customization sooner. 

Thank you,
