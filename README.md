# PHOTO_APP
The objective of this project is to write a React Photo App that meet the following:

Requirements

Wireframe 
A proper Readme.md file 
Navigation Bar
Home (Photo-Grid)
User Profile (Maximum of 3 ppl.)
Bookmarks (Saved Images)
User is logged in or user is logged out
Hint
This is hard-coded user information inside of state
User Profile
Profile Image
Username
Grid Photos
Use a node library (SASS/Bootstrap/etc.)
 
*Minimum of 80 GitHub commits*

**Pseudocode must be included for every part of your process/files**

User Details

When viewing the details of a user, the user detail page should include the following: 

The entire user account. If the user chooses to delete her/his/their account, there should be a final warning prompt, followed by the user being logged out and all the details of his/her/their account destroyed. This means that, in addition to the User object being destroyed, you should also handle the deleting of all photos and comments created by this user. Essentially, we will treat the user as never having existed in the first place. Other things added for other stories implemented (e.g. activities, visibility, mentions, etc) should also be covered.
Hints:
When a user deletes various objects, you need to consider any associated information that must also be deleted. This will be done on the server and you may have to do some research into how to properly destroy objects with associations. 
Make sure a user can’t delete anything that he or she does not own.
 

User Story
Implement a like button for each photo to allow the user to like the photo. It can be a button, icon or whatever you like.
Clicking on the like button makes the user like the photo (and visually changes the like button to an unlike button). Clicking the unlike button on a photo that has already been liked by the same user should unlike the photo.
The number of likes of a photo should never be greater than the total number of users.
If a user has already liked a photo, there should be some sort of visual indication on the page that the user has already liked the photo. This visual indication should be removed if the user unlikes the photo.
Next to the like button, it should display the number of likes for that photo. This count should be updated (visually) immediately upon liking or unliking the photo.
A user’s photos page should be sorted by the number of likes in descending order (most liked photos at the top). If photos have the same number of likes, sort by the timestamp in reverse chronological order (most recent first). This doesn’t need to change immediately when a user likes / unlikes a photo - you are allowed to wait until the page refreshes.
 
