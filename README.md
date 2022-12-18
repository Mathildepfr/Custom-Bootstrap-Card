# Custom-Bootstrap-Card
UI/UX Design

### Prerequisites

<li>SASS/SCSS preprocessor</li>

<li>Bootstrap v4.3 (or higher)</li>

<li>Github account</li>

## The Default Boostrap Card - Objective A
In its final form, it consists on a main `<div>` using a `.card`class and 3 sub-sections:
An card-header containing a navigation tab
A card-body containing 3 tabs bodies
A static footer

Tab1: A title and a subtitle followed by a two columns block. Clicking an entry on the left must toggle the corresponding image on the right.

Tab2: A centered “Loading..” block. The animated shape must be an inline SVG.

Tab3: Static content

![Boostrap Card](https://user-images.githubusercontent.com/86634734/208239140-a971f0e2-b5ee-48d2-9e9f-0150cd09e664.png)

## Responsiveness
Provide the component with simple responsive behaviors triggered when  screen size < 768px.

![Boostrap Card Responsive](https://user-images.githubusercontent.com/86634734/208289524-980cb31c-0519-485e-a5f7-e1a14da30597.png)


## The Custom Boostrap Card - Objective B & C
Improve the design as you wish.

Create a SCSS mixin defining design variations for each bootstrap contextual class (primary, secondary, success, danger, warning, info, light, dark).
Classes should be applied on the component’s main `<div>` and trigger the style for all inner elements.
