# This is a tool for getting an info of a youtube video.\

## Quick Start
*First, you need to make a profile for Google Developer, and create a project using Google Cloud Console.*
**Make sure you have your API_KEY and an OAuth 2.0 Client ID**
Then clone this repo, and edit the [dets.html](./dets.html) file. In the file, find these placeholders: {YOUR API KEY}, {YOUR VIDEO ID}, and {YOUR OAuth 2.0 CLIENT ID}, and replace with the respectible keys and ids.
NOTE: To find the id, copy a Youtube video link and copy the id. The format of a youtube video is like this: https://youtube.com/watch?v={VIDEO_ID}
Finally, execute the run.sh file.
(You need python3 to run the run.sh file)


## How to use?
Once you run the run.sh file, go to your browser of choice (preferrably chrome or brave), then type localhost:8000 to the URL bar, then navigate to the [dets.html](./dets.html) then 2 buttons will show up, Then toggle the Developer Mode (press F12).
Next, click the 'Authorize and load' button then login to your google account (Make sure that your account is connected to your Google Developer project), if successful, click the 'Execute' button, then details will show up.
