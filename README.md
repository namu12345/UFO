# UFO
## Overview of Project:
  ### Purpose
The purpose of this project is to build a dynamic web-page that displays UFOs sightings information for upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon. There is a lot of data to display so adding filters to the table which let users to refine their search on more than one level is absolutely necessary.
The web-page contains the following:

- Interactive filters for searching criteria on date, city, country and shape.
- Brief article and its summary.
- An attention-grabbing header with a refresh-page button.
- Visually appealing design of overall presentation of the data.

### Resources
- **Data Source:** JavaScript list [data.js](https://github.com/namu12345/UFO/blob/main/static/js/data.js)
- **Software:** VS Code and Chrome Developer Tools 
- **Languages:** JavaScript, HTML, CSS and Bootstrap 3. [app.js](https://github.com/namu12345/UFO/blob/main/static/js/app.js) & [style.css](https://github.com/namu12345/UFO/blob/main/static/css/style.css)
- **Dependencies:** D3

## Results

The webpage [UFO Sightings - The Truth is Out There]( https://namu12345.github.io/UFO/) has been created. Upon entering, visitors embarking on their **"first encounter"** will see:

![image](https://user-images.githubusercontent.com/92283185/149230605-d500e0bd-4069-4072-b6e5-a8c90790f68c.png)

You will notice that a **"Filter Search"** section has been added.

![image](https://user-images.githubusercontent.com/92283185/149233404-3a78318b-492d-4249-b960-a90750aa1aeb.png)

You can filter by one or all of the search criteria shown. For example, if you search by **"City"**, you will see that the table updated to show the reported sightings that was recorded for that specific city.

![image](https://user-images.githubusercontent.com/92283185/149234502-4ab9a1a8-5099-4acb-b326-44feca5f5926.png)

If you add a **shape**, the table will update filtering further to only display the information containing that shape.

![image](https://user-images.githubusercontent.com/92283185/149234791-05ceda51-9dc5-413b-9fbe-febe16027407.png)

## Summary
### Drawbacks:

Unfortunately, the page has several drawbacks. They include:

The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown.

There is no button to click, wording or action that tells the user that the table will update after you hit "enter".

The data is limited and outdated since it is not linked to a "live" source.

### Recommendations for further development:

With the following enhancements, it can greatly improve the user's experience.

Add additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help "guide" the user and make the page more interactive.

Add functionality to pull the data from a live source that includes current and archived data not limited to only the United States, but globally.

Add a "Latest News" section that will highlight an article showing the most recent reported sighting.










