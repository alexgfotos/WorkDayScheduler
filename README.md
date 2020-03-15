Work day scheduler:

For this assignment we had to creat a website that would:

1. utilize the Moment JS API to set time and create events that respond to the current time.

2. Each block represents an hour of a 9-5 work day.  The user can input their planned activity for the hour and it will be saved to local storage.

I think that is the gist of the site?

It took some time to figure out how to make all the components not break each other, for example getting blocks to respond to the current time broke my localstorage. 

I created a for loop to to compare current time to each time block.  To do these I gave each block a data-value of their corresponding 24hr time and made it run through 3 if statements. I pulled the separate values with this variable:
        
        var descriptionTime = $("#" + i).attr("data-value");

I used $("#" + i) and data-values as a workaround to treat blocks separaetly a few times, I would love to know the cleaner solution.

Overall this assignment went smoother and faster than the last.