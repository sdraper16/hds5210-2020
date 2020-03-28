# Midterm Feedback

## Overall Score: 
45 / 50

Generally, you had all the right ideas. When it came to the work of reading the file off of the internet and comparing against known scores, there's more that could be done there. Nice work!


## Part 1: Creating a JSON Rules File
Comments - Nice work.  They all look great.  I'm not sure how you're going to pick between A-a Gradient and PaO2, though.

## Part 2: Functions to evaluate rules
Comments - These all look great in general.  The one thing you miight notice, though, is that you're writing a lot of the kind of code over and over -- the range comparison.  When I suggested that you should be able to do this without writing quite as much code, I was suggesting that you could write a generic function that would do any range lookup given the configuration file, the value, and which section to look in.  (-1)

Your organ failure logic should have gone in the JSON.  (-1)

Your FiO2 section doesn't really do anything to distinguish between which rule to use.  I don't think it will behave as epected. (-1)


## Part 3: Put it all together
Comments - Nice and simple except for creatinine and PaO2.  On creatinine, you could have simplified that by calling config[acute_renal_failure] and you've hard coded the range rules for FiO2.  (-1)

## Part 4: Accessing and processing the patient file
Comments - I liked where you were going with these ideas.  You were getting pretty close to a solution, but didn't quite get it all complete.  (-2)