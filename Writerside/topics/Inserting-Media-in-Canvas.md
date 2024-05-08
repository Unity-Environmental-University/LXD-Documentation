# Inserting Media in Canvas

The Learning Materials page typically has some sort of media incorporated. There will often be a “Weekly Lecture” from the SME (unless this appears on the Overview page) or an appropriate YouTube video curated by the SME. 

#### Steps for adding an internal (instructor made) YouTube video to Canvas:
- Go to the Learning Materials.
- To insert a video, click “Edit”.
- Your video may be sourced from YouTube or Canvas studio, so there are two possible workflows.
  1. For a YouTube video:
     - Click “HTML Editor”. 
     - Find the iframe code: ```<iframe src="https://www.youtube.com/embed/my9ED04Z4oc" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"></iframe>```
       - Replace this whole code (from ```<iframe> to </iframe>```) with the new iframe code, which can be found by copying the code from the “share” button of YouTube.
     - You can preview by clicking “Rich Text Editor”.
  2. For a Canvas Studio Video:
     - In editing mode, click your cursor underneath the “Weekly Overview Video” text line. In the rich text editor menu bar, select Canvas studio (the blue icon), then locate the video you would like to add. Select it, and select “do not show media options”.
     - Insert this video, then delete the placeholder video.
- For a class with no lectures (i.e. legacy) any singular YouTube video for that week can be removed from the learning materials and embedded in the black media box.
- When adding a YouTube link in other locations, remove the “inline preview” from how the link displays by adding the code class="inline_disabled" . 
  - Example: ```<li aria-level="2"><a class="inline_disabled" href="https://www.youtube.com/watch?v=xR9r38mZjK4" target="_blank" rel="noopener"><span>Interpreting linear graphs word problems example 1 | Algebra I | Khan Academy</span></a></li>```
- Directions to add this code:
  - Find the YouTube link in the html by clicking the “< / >” icon under the text editor in Canvas.
  - Look for “YouTube” or “youtu.be” in the code. The portion you are looking for is between “<a” and “/a>”
  - Add the code class="inline_disabled" between <a and href=

#### Inserting Audio/Podcasts
- Click the Upload/Record media button in the RTE.
- Select your audio file.
- Adjust the display settings to show a playable option for the audio file (not just a downloadable file).
- Be sure to also request a transcript for the audio!

#### YouTube

Most videos are now housed and/or created in Canvas Studio. You may not need to work within YouTube during a course build.

To work within YouTube you need access to the Unity institutional account. This will be added by IT. When you open YouTube in your browser, click the top right account “circle” and switch to the Unity account from your personal Unity email account.

Steps for adding a video to the Unity College channel:

- Download the video from Google Drive to your computer.
- Switch to the Unity College Distance Education account in the top right corner of Youtube.
- Click on the “+ camera icon (create)”, “upload a video” (you can add videos all at once).
- Keep the course code and number at the beginning of the line, for example “EMGT 307 - Week 1 Overview”.
- Add the Unity Environmental University Distance Education Logo as the thumbnail image. You’ll want to download a copy of this image to your computer and keep it for video uploads.
- Create a playlist for the video with the course’s title, eg title “EMGT 307” which will eventually hold all course videos.  
  - This needs to be unlisted (visibility). It is important to leave it unlisted so that it’s not searchable, and only available with a link.
- Select “No, it’s not made for kids” for the audience. 
- Save or publish, again make sure it’s “unlisted”.
- If the SME has made multiple mini-lectures for a week, you should create a playlist for that week and save the videos to it. This will mean the video is on two playlists, i.e. “EMGT 307” and EMGT 307 - Week 1. Make sure the new playlist is unlisted. Then that playlist should be embedded on the right in Canvas. 
- Copy the code below and replace the text after playlist?list= (highlighted in yellow) with the playlist ID from your video playlist. The playlist ID is the url text after list=
- Label the right column in Canvas as “Weekly Lecture Playlist” as opposed to “video” to indicate multiple videos are assigned for that week. 
- Switch back to your personal account in YouTube.

Embedding code for a playlist in Canvas: 
```<iframe width="560" height="315" src="https://www.youtube.com/embed/playlist?list=PLZCz70q-Ni-acnRC4uJhh-v_y_Gv8LJY7" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>```

       


 