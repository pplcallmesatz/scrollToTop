# scrollToTop
Everyday scrolling on long pages can be a tiring experience specially on those sites which provides infinite scrolling (like facebook, twitter, Google+, etc). You will keep scrolling using your mouse to see more and more updates and then when you want to go up to the top of the page, you might move your hand from your mouse to keyboard to search for Home key or you will drag the scroll bar to the top.

# Insatallation Guide:

### Basic Setup:
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="scrollToTop.js"></script>
```

### HTML Mocup:
```
<div class="scroll"></div>
```

### Jquery:
```javascript
$('.scroll').scrollToTop();
```

### Jquery Settings:
```javascript
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
### Jquery settings properties:
1. color
2. backgroundColor
3. svg:
      - fill
4. animation:
      - scrollPosition
      - speed
      


working in progress, you may expect more customization sooner. 

## Thank you,
