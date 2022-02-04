What I have learned in this project:
- JS Properties
	1. parentElement: return the parent element of the specific element.
	2. nodeName: return the current element's name.
	3.*className: add class tag into a specific tag or label.

-JS Methods
	1. addEvenListener: this is a useful method that cna triger even automatically. 
		For example, if you want to triger something while submitting a form, you can use:
		form.addEventListener('submit', e => { myfunction() });

		also, if you want to varify a form field while the cursor is moved away:
		email.addEvenListener('focusout', e => { myfunction() });

-CSS Units
	1. vh: vh means viewport height, 1 vh occupies 1% of totally viewport height. This is same to the wh which represents viewport width;
	2. box-sizing: border-box: a safe and wise way to make the width/height same as they're actually set regardless of border and padding that will be added additionally if not set.

-HTML properties
	1. onfocusout: this is another event that can inset in some tag such as 'input' to execute a function/event while the cursor moves away.
	2. getElementById/querySelector: the main difference between these two is that the former is limited to the id while the latter can be a html tag, id(#), or class(.).