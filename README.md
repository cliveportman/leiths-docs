# Leiths documentation

## Professional Courses

### Splash image
This is the large image that greets users when they arrive on the page. It should have a dark top so that white text can be clearly visible, something for people to look at in the middle and fade to a white background at the bottom. It's tricky to produce. Follow these steps in the order described:
- Start with the large image provided by Scott. Resample so it's 72dpi. Resize the image so the height is 1640px. Then crop the result to a width of 2560px. You should now have an image measuring 2560px by 1640px. Save it with the the filename `name-of-course-2560x1640.jpg`.
- Now resize the image so the height is 1280px. Crop the result to a width of 1920px, so the image measures 1920px by 1280px. Save it as `name-of-course-1920x1280.jpg`.
- Crop that image to a width of 1366px. Save it as `name-of-course-1366x1280.jpg`.
- Resize to a height of 1080px. Then crop the width to 768px. Save it as `name-of-course-768x1080.jpg`.
Upload these to the relevant fields within the CMS.

### Putting a 2020 Design course live
To avoid issues with Google linking to older Professional Course pages, we need the URL of new Professional Course pages to match the older course. This can't be actioned until the new page goes live.

Here's what to do:
- When ready to put the new page live, go to the old entry.
- Find the old entry's slug and copy it. Now add `-old` to the end of it. That changes the address the old page sits at. We have to do this because two entries cannot have the same address.
- Disable the old entry and save it.
- Go to the new entry and replace the new entry's slug with the one you copied from the old entry.
- Enable the new entry. Save it.
