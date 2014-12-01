#Sprocket

A class based CSS Animation library containing commonly used UI animations

##LESS Documentation


###Defintions
`@animation-fast: 0.5s;`

`@animation-medium: 1s;`

`@animation-slow: 2s;`

###Classes

`animate`

Defaults an animation at medium speed with linear timing function

`animate-fast`

Defaults an animation at fast speed with linear timing function

`animate-slow`

Defaults an animation at slow speed with linear timing function

`animate-alternate`

Sets animaiton-direction to alternate

`animate-repeat`

Sets animation iteration count to infinite


###Mixins

| Mixin | Param | Description 	|
| ------------ | ------------- | ------------ |
| animation() 					| @animation	| Vendor prefix for animation property |
| animation-name() 				| @name 		| Vendor prefix for animation-name property |
| animation-duration() 			| @duration 	| Vendor prefix for animation-duration property |
| animation-fill-mode()			| @mode 		| Vendor prefix for animation-fill-mode property |
| animation-timing-function() 	| @timing-function | Vendor prefix for animation-timing-function property |
| animation-delay() 			| @delay 		| Vendor prefix for animation-delay property |
| animation-iteration-count() 	| @iteration-count | Vendor prefix for animation-iteration-count property |
| animation-direction() 		| @direction	| Vendor prefix for animation-direction property |