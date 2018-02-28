# instagram-api
A simple app using instagram's api to pull a users most recent photos taken at their current location.





# Instagram Current Location Photo Stream - Proof of Concept
This simple application uses Instagram's API to allow users to view their most recent photos taken at their current location.

<!-- **Link to project:** http://recruiters-love-seeing-live-demos.com/ -->

![instagram photo stream app preview](https://github.com/lpercivalDEV/instagram-api/blob/master/insta-api-preview.png)

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, jQuery

Using HTML, CSS, and jQuery, I created a simple app where a user can log into their Instagram account, authorize their location being used, and then see a stream of photos from their account that were taken at their current location. Users can also view a count of how many likes each of their photos has under each image in the photo stream.

For example, if you are currently located at the Boston Public Library, any photos you've taken at that location will appear in your stream (as long as those photos have location information added to them on Instagram).

This project involves directing the user to my app where they can click on a button. The button redirects them to Instagram's login page. Once the user logs in to their account they also gain an OAuth access token from Instagram. The user is then directed back to my app where they are prompted by their browser to allow their current location to be used. Once the user approves to have their location used, a stream of photos from their Instagram account is produced containing photos that were taken at their current location.

If no photos were taken at the user's current location, then no photos will appear on the application's stream.

The specific photos and number of likes were targeted by selecting the "images" and "likes" properties within the JSON file that Instagram's API returned. The information was then displayed in the DOM by using jQuery to target the specific HTML elements where they would be placed.

## Optimizations
As it is right now, my app is more like a proof of concept. It works, but it's not the slickest looking application.

If I had more time to work on this project, I would love to play more with the CSS to make the app more appealing. I would make the stream align as a grid instead of a vertical list of images. I also would have liked to add an event listener so that when a user hovers over an image, the location is displayed.

I think the last most important thing I would've liked to add if I had more time is a message/alert for users.  This message/alert would pop up to let users know that no photos could be found when they are in a location where they have not taken any photos. I think as it is now, it may be confusing for first time users to realize that the app is not broken when no photos show up and that it simply means they have not taken any photos at that location. So adding some kind of alert or message would greatly improve the UX/UI of my app.


## Lessons Learned:

Setting up a local server in my terminal to run the application and working with the Instagram API was a fairly straightforward process. Once I understood that I had to provide my client ID for a user to be able to get their OAuth token, everything else kind of fell into place.

I also learned that teamwork makes the dream work! A mentor helped me understand that I wasn't clearing local storage and this helped me understand why some of my changes were not initially showing up. Lesson learned!

## Examples:
Take a look at these couple examples that I have in my own portfolio:

coming soon....
