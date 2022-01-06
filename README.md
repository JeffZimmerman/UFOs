# UFOs

## Project Overview
This aim of this project was to create an interactive webpage allowing for user inputs into various search criteria to access data on reported UFO sightings. Javascript, HTML, CSS, and Bootstrap elements were brought together to create a visually appealing and user-friendly interface.

### Results
Familar website elements are brought together, including a navigation bar, main header, description of the site, and text entry boxes that affect the main content portion of the page. Background formatting provides a visually appealing color scheme relevent to the subject, including use of NASA imagery and light-colored text on a dark background, like one might experience when encountering unidentifed bright lights in a night sky. Flexible containers were used to hold textual elements, and each portion of the page was organized according to a storyboard-format, allowing users of different sized-screens to still enjoy the intended design presentation.

> The initial page offers multiple entry points: The user can begin by reading the overview paragraph, browse the default data presented, or by filtering a search: 
<img width="1243" alt="Screen Shot 2022-01-05 at 11 27 46 PM" src="https://user-images.githubusercontent.com/91562577/148328307-36e891ab-6824-4a4b-9029-d30e98823cd0.png">

The webpage acheieved its primary aim of dynamic responsiveness to user inputs. The user can search for reported UFO sightings in the dataset by date, city, state, country, and the "shape" of the unidentified object that was seen. The main content portion of the page responds and rapidly filters based on each individual input, allowing the user to quickly backtrack or alter their search criteria based on the results shown. 

> A search for the US state of Oregon returns a relatively small number of results, but allows for a fine-grained view of their differences:
<img width="1237" alt="Screen Shot 2022-01-05 at 11 29 15 PM" src="https://user-images.githubusercontent.com/91562577/148328346-646aed83-3744-4156-9617-0af342bf9760.png">


### Summary
The project achieves the goal of providing easily accessible and dynamically searchable information on reported UFO sightings. The table filters allow the user to quickly move from a broad search to one that is more focused, and to easily alter the parameters.

* One notable drawback of the design of the webpage is that any text entered into a search box must precisely match the text as it is structured in the data. This may not cause much trouble if a user wants to search by date or country, but the options for the "shape" parameter are not as obvious, and there is no way provided to see all the available options or find a close match. 

- One recommendation for further development would be to retain the recommended formatting provided for entries in each text box, but to also introduce a drop-down menu or list of close matches. This would help, for example, if a user were to enter "circular" in the "shape" field, which presently is only coded to allow for "circle" as a match. 
- A second recommendation is to expand the dataset, potentially using more up-to-date information drawn from webscraping or links to outside resources. 
- Lastly, a more sophisticated design would expand on the interactive character of the site, giving the user a broader sense of how to discover information they were not already looking for. Example search results could be provided to show patterns that emerge from the data, or interesting examples that might encourage the user to explore further. These additions are in key with the theme of the page, making mystery and exploration part of the greater user experience.  

