+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "The Waitress"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-19T17:03:04-07:00 #the date the file was created
    
    shortDescription = "A music video I made using traditional animation techniques"
    projectVideo = "305628501"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "traditional.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 
+++
<div class=text-align>
An animated music video for the song "The Waitress" by Atmosphere, the song touches on broken relationships and how it affects children as their older. I was extremely inspired by the lyrics and immediately saw the entire song in my mind. I animated the video using a mix of techniques such as tweening, traditiona keyframing, and rotoscoping. I designed all the characters as well as the backgrounds. 
</div>