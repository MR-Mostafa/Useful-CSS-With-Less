# Useful CSS With Less Mixins
`Useful CSS` is a snippets of reusable CSS by less mixins to develop faster and keep code readable.

___
## For more information: [http://usefulcss.ir](http://usefulcss.ir/)
___

## How to Use
Download `UsefulCSS.less` OR `UsefulCSS.min.less` and then copy the following code:
```CSS
/* place it into your <head> tag */
<link rel="stylesheet/less" href="UsefulCSS.min.less">

/* OR use it @import from your less file */
@import "../UsefulCSS.min.less";
```
___

## How it works:
As a rule, you can use the CSS properties you would expect just by adding a `.` to start them and putting arguments afterwards.
Whatever... let's say you want a elliptical border radius for an element, here you go:

#### Example:
```Less
div.radius{
	.border-radius(150px 150px 150px 150px, 75px 75px 75px 75px);
}
```

#### Output:
```CSS
div.radius {
	-webkit-border-radius: 150px 150px 150px 150px / 75px 75px 75px 75px;
	-moz-border-radius: 150px 150px 150px 150px / 75px 75px 75px 75px;
	border-radius: 150px 150px 150px 150px / 75px 75px 75px 75px;
}
```
___

## Mixin Names:
| ?CSS property & Value |
|--------------------|
| .opacity(@opacity); |
| .border-radius(@radius; @elliptical); |
| .border-image(...); |
| .box-sizing(@value); |
| .text-shadow(...); |
| .box-shadow(...); |
| .font-face(@font-family-name; @font-name; @font-style; @font-weight; @woff; @woff2; @ttf; @eot; @svg); |
| .transform(@rotate; @scale; @skew; @translate); |
| .transform-origin(@value); |
| .transform-style(@style); |
| .translate(@x; @y); |
| .translate3d(@x; @y; @z); |
| .translateX(@x); |
| .translateY(@y); |
| .translateZ(@z); |
| .rotate(@deg); |
| .rotate3d(@x; @y; @z; @deg); |
| .rotateX(@deg); |
| .rotateY(@deg); |
| .rotateZ(@deg); |
| .scale(@x; @y); |
| .scale3d(@x; @y; @z); |
| .scaleX(@x); |
| .scaleY(@y); |
| .scaleZ(@z); |
| .skew(@deg; @deg2); |
| .skewX(@deg); |
| .skewY(@deg); |
| .matrix(...); |
| .backface-visibility(@value); |
| .perspective(@value); |
| .perspective-origin(@value); |
| .keyframes(@name; @arguments); |
| .animation(@arguments); |
| .animation-name(@name); |
| .animation-duration(@time); |
| .animation-timing-function(@args); |
| .animation-delay(@delay); |
| .animation-iteration-count(@count); |
| .animation-direction(@direction); |
| .animation-fill-mode(@mode); |
| .animation-play-state(@args); |
| .media-max(@maxWidth; @rules); |
| .media-min(@minWidth; @rules); |
| .mobile(@rules); |
| .tablet(@rules); |
| .desktop(@rules); |
| .desktop-wide(@rules); |
| .mobile-small-bs(@rules); |
| .mobile-bs(@rules); |
| .tablet-bs(@rules); |
| .desktop-bs(@rules); |
|  .desktop-wide-bs(@rules); |
| .filter(@args); |
| .placeholder(@ruleset); |
| .selection(@ruleset); |

**For more information, visit [http://usefulcss.ir](http://usefulcss.ir/)**

___

## Contributing:
There are no special conditions, we look forward to working with you.

___

## License
`Useful CSS` released under the [MIT License](https://opensource.org/licenses/MIT)