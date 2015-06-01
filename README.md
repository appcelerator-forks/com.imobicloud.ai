# Titanium UI - Activity Indicator

xml
	<Widget id="vAI" src="com.imobicloud.ai" visible="true" message="Please wait..."/>
	
js
	// show AI with default message
	$.vAI.toggle(true);
	
	// show AI with custom message
	$.vAI.toggle(true, 'Loading...');
	
	// show AI, auto hide after 5 seconds
	$.vAI.toggle(true, null, 5000);
	
	// hide AI
	$.vAI.toggle(false);