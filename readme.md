JavaScript ICAL Parser
---------------------
A proof of concept script to process .ics (Icalendar) files using JavaScript.

Warning: This code is expermental and still rather hacky. 

**Usage Example:**

		obj = new ical_parser("my_ical_file.ics", function(events){
			//do somthing with the events.
		});