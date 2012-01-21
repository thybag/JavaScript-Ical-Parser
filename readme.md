JavaScript ICAL Parser
---------------------
A proof of concept script to process .ics (Icalendar) files using JavaScript.

Warning: This code is expermental and still rather hacky. 

**Usage Example:**

		new ical_parser("my_ical_file.ics", function(cal){
			events = cal.getEvents();
			//do somthing with the events.
		});