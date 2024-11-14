# WindBorneCodingChallenge

# How to submit

Make a POST request to `https://windbornesystems.com/career_applications.json` with the following body:
```json
{
  "career_application": {
    "name": "Your name",
    "email": "Your email",
    "role": "Web Dev Intern",
    "resume_url": "A publicly accessible URL pointing to your resume",
    "notes": "Optional -- anything you'd like to say about yourself",
    "submission_url": "A publicly accessible URL pointing to your coding challenge -- see below"
  }
}
```

Make sure this gives a status code of 200! Any other status means it wasn't accepted; check the response body for more.

# The coding challenge
Your task is to render a line in webgl. A few requirements:
1. You are NOT allowed to use any libraries. Vanilla javascript only.
2. The user should be able to configure the width (in pixels)
3. The user should be able to dynamically add more line segments to the existing line. I don't care about the interface, but some examples that I'd happily accept include (a) a button to generate a random coordinate to add to the line (b) a text input in which the user enters an x,y coordinate (c) clicking on the page and drawing a line to that point

Host this on a publicly accessible url. Bonus points if you style it nicely!

![image](https://gist.github.com/user-attachments/assets/b0424f76-1153-48fe-ba85-1d46150e5b3a)

NB: if for some reason you absolutely hate this assignment, you can submit saying so and find another creative way to convince me that you have the requisite kinds of skills here.

# More about the role
Hopefully you came across this gist from our careers page, but if not, here's the summary!
- [WindBorne Systems](http://windbornesystems.com/) designs, builds, and launches a new kind of smart weather balloon, then plugs this unique data into our own AI-based weather models. Our mission is to build a planetary nervous system. In the process, we can both save a huge amount of carbon emissions and help humanity adapt to extreme weather
- This role is for a web dev intern. You'll get to work on our mission control suite to fly balloons and our products so our customers can benefit from our high accuracy weather forecasts. 
- This is for you if you like deranged web development and pushing the limits of what's possible. This is not for you if you want a chill job selling ads.
- If you do the coding challenge, I promise you'll hear back (usually within a day or two, but could be up to a week)
