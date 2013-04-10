SwitchButtons
============
###A simple set of toggle buttons for faster prototyping in code
###Coded with love by Catt Small in 2013
###http://www.cattsmall.com
###Twitter: @cattsmall
###Github: cattsmall

SwitchButtons are a simple set of jQuery-based toggle buttons for faster prototyping in code. I built them for use in my work when I couldn't find a quick, lightweight, easy-to-use plugin. I ended up referencing the files so often that I began to think it could be useful to other people.

Feel free to fork this project and make it your own; I hope this will make prototyping interactions faster by removing the extra time spent on coding for toggle buttons. The SwitchButtons styles are in a separate CSS file, so it's quick and easy to create your own look. If you're a backend developer, you can also hook SwitchButtons up to code that interacts with a server. The possibilities are endless!

For examples, check out the demo site: http://cattsmall.github.io/SwitchButtons/


* Using SwitchButtons *
-----------------------
Using Switchbuttons is very simple.

1. Get jQuery

2. Add switchbuttons.js to your main JavaScript file or folder; link JavaScript before the closing body tag

3. Add switchbutton.css to your main CSS file or folder

4. Attach Switchbuttons.js to any pages on which toggle buttons are needed

5. Copy and paste the SwitchButton you need from the demo site or this readme!

6. *Optional* - Download an icon font library like Symbolset, Foundation Icons (included), Entypo, or Font Awesome.

7. *Optional* - change the <i> tag class & content to match your preferred icon font.


* List of SwitchButtons + code *
--------------------------------

1. Star - Use for favoriting or rating</h5>

*Basic favorite button:*

	<button class="switch-button star"><i class="foundicon-star"></i></button>


*Favorite all button:*

Add the "star-all" class to the button, then add "switch-button-target" to the other buttons you wish to trigger.

	<button class="switch-button star star-all"><i class="foundicon-star"></i></button>

Example of target:	

	<div class="example">
		<button class="switch-button switch-button-target star"><i class="foundicon-star"></i></button>
		<button class="switch-button switch-button-target star"><i class="foundicon-star"></i></button>
		<button class="switch-button switch-button-target star"><i class="foundicon-star"></i></button>
		<button class="switch-button switch-button-target star"><i class="foundicon-star"></i></button>
	</div>

Feel free to duplicate & edit the JavaScript if you ever need more than one set of targeted favorite buttons on a page.


*Rating stars:*	

	<div class="switch-button-group rating">
		<button class="switch-button star"><i class="foundicon-star"></i></button>
		<button class="switch-button star"><i class="foundicon-star"></i></button>
		<button class="switch-button star"><i class="foundicon-star"></i></button>
		<button class="switch-button star"><i class="foundicon-star"></i></button>
	</div>
	
	

2. Heart - Use to show appreciation

	<button class="switch-button heart"><i class="foundicon-heart"></i></button>


3. Thumbsup - Use for liking content

	<button class="switch-button thumbsup"><i class="foundicon-social-thumb-up"></i></button>


4. Delete/Ban - Signify deletion or banning

	<button class="switch-button ban"><i class="foundicon-remove"></i></button>


5. Checkbox - Can be used to check one option or check & uncheck all targeted checkboxes

*Bacic checkbox button:*

	<button class="switch-button checkbox"><i class="foundicon-checkmark"></i></button>


*Check all button:*

	<button class="switch-button checkbox check-all"><i class="foundicon-checkmark"></i></button>
	<div class="example">
		<input type="checkbox" class="switch-button-target checkbox">
		<input type="checkbox" class="switch-button-target checkbox">
		<input type="checkbox" class="switch-button-target checkbox">
		<input type="checkbox" class="switch-button-target checkbox">
		<input type="checkbox" class="switch-button-target checkbox">
	</div>


6. Alert bell/flag - Can be used to toggle alerts or an alarm for a later date

	<button class="switch-button alert"><i class="foundicon-flag"></i></button>


7. Lock - Can be used to signify that something is secured on click

	<button class="switch-button lock"><i class="foundicon-lock"></i></button>


------------------------------------------------------------------------------------

Thanks! If you have any questions, tweet me @CattSmall.