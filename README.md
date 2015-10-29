# velocity-download-portal

*It requires jQuery (1.8.1)* to make the accordion work.
The accordion works by using jQuery to add and remove an “.open” class to the .accordion-toggle and .accordion-content tags.

The css was written mobile first so in older browsers or narrow windows the view is simplified.
#### Tested in:
* IE5 – (NO) accordion doesn’t work,
*	IE7 – functional,
*	IE8 – functional,
*	IE9 – better layout and buttons ,
*	IE10 and Edge – fully featured animated transitions and
*	Chrome 44 – fully featured

#### The first three accordion items (bellows???) contain a showcase of the different partial states for a “specific environment” object/download :
1.	The empty/initial state (if a user sees this, something has gone a bit wrong) <div class="download_empty">
2.	Loading (would be nice to get ellipsis dots to animate) <div class="download_loading">
3.	Error (hopefully no one will see this) <div class="download_error">

#### The ideal fully loaded state is shown under the first Velocity 2.0 > UAT item and is open by default. <div class="download_ideal">


## What is missing:
*	Top bar needs some work (possibly get rid of it?)
*	Background image (Felix Chilvers is working on this but has had other priorities)
*	Meta information in the head
*	Favicon (red Velocity chevron?)
