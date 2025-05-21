### Sriharsha Kavuri, [skavuri@ucsd.edu](mailto:skavuri@ucsd.edu), A17926793


1. Within a Github action because this can be setup to run whenever something is pushed to a preset branch. Manual
testing should still be done locally but automated testing can be pushed over to Github because it is like a last
frontier before stuff gets pushed to prod. 

2. No end to end tests as the name implies are end to end. For a single function unit tests would be better.

3. **Navigation mode** measures how fast the page loads when a user first opens it. 

   **Snapshot mode** doesn't care about the navigation and it instead just takes a snapshot of the page elements like DOM and CSS and does some analysis on it to determine things like accessibility and SEO.

4. The html tag doesn't have a lang attribute which is very important for screen readers and accessibility in general.

   The meta tag is missing which is important for responsive design. It eliminates a 300ms blocking time for touch events on mobile devices.

   The images are higher res than displayed which is a waste of bandwidth and can slow down the page load time. 
