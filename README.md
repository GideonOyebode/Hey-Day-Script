# Hey-Day-Script
Script and a README for Hey Day assignment
This script explains how to make a fun program that prompts you to enter you name and you get a personalized greeting (with your name) and "HEY"
To learn more about Auburn's "Hey Day" please click on the link to read more about this Auburn tradition here: http://sga.auburn.edu/hey-day/
"Dating all the way back to 1947, students who served in WWII were returning back to normalcy here at Auburn University, but upon their return, they felt unseen and unheard here on campus. In response, Auburn University’s student body and members of the Student Government Association pushed for a day that would unite the Auburn Family and promote a friendly atmosphere known as Hey Day – a day where every student got the opportunity to wear a name tag, helping everyone feel a sense of belonging.

Each year, we carry on this tradition by handing out name tags and encouraging students, faculty, and the rest of the Auburn Family to greet one another, bringing all members of Auburn closer together. Hey Day has become one of Auburn University’s longest, most cherished traditions and is a day the student body has grown to love and look forward to each year.

This year’s Hey Day will be hosted on October 18, 2023 all around campus! We look forward to engaging the Auburn Family by distributing name tags and handing out Hey Day-branded promotional items. Furthermore, we will also be hosting a festive event on the Campus Green for all to enjoy, so we invite everyone to join us for a free, catered meal, a pep-rally performed by the Auburn Cheerleaders, an inflatable obstacle course, and many special guests. We can’t wait to see you all there!"

# Now the script
#!/bin/bash 
echo "Please enter your name"
read name
echo "Hey, $name!"

#!/bin/bash #this first line is called a shebang and it tells the computer that the script should be interpreted and executed using the Bash shell.
When you run a script (e.g., ./script.sh), the system reads the shebang and uses the specified interpreter to execute the script.

# For the provided script, here's a breakdown of what it does: Commands are boldened in dark black.

**echo "Please enter your name:"**: Prints the message "Please enter your name:" to the standard output, prompting the user to enter their name.

**read name**: Waits for the user to input their name and stores it in a variable called name.

**echo "Hey, $name!"**: Prints a greeting message that includes the provided name using variable substitution. The $name is replaced with the actual name the user entered.

So, the script first asks the user for their name, reads their input, and then greets them using the entered name: Now try and have fun
