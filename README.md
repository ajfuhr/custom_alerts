Custom Alerts for StreamElements
================================

These basic alerts will send you on your way to coding custom alerts for your live-streaming broadcasts. I have tested this with StreamElements exclusively. It should work for Stream Labs as well, though it has not been tested as of this writing.

Setup
-----

In the alerts.html file, you will find each alert type in it's own section:

    <!-- FOLLOWER ALERT -->
    <div class="alert">      
      <div class="alert-type">NEW FOLLOWER</div>

      <div class="alert-information">
        <span id="username-container"></span>
      </div>      
    </div>
    <!-- END FOLLOWER ALERT -->

Ignoring anything between the <!-- and --> tags (these are comments, ignored by the browser when rendering HTML elements), copy the HTML and go to your StreamElements overlay. From here, select the AlertBox widget, or create one if you do not have one present. 

- Under "Position, size, and style", set it to have a 1920px width and a 1080px height.
- Under "Settings", click the gear icon next to the alert type you'd like to configure. We'll continue with the Follower alert.
- Remove any images or videos that are set for the alert and set up the sound you'd like to be played.
- Set the Alert duration to 5s.
- Toggle the "Enable custom CSS" selector to on.
- Click "Open CSS Editor".
- There are four tabs in this view: HTML, CSS, JS, and Fields. 
- Click on the HTML tab.
- Paste the HTML you copied from alerts.html (you can ignore everything except what's between your desired alert type's block).
- Click on the CSS tab.
- Open the assets/css/alerts.css stylesheet.
- Select all and copy.
- In the StreamElements CSS editor, select all and delete, then paste the CSS from this repo.
- Close the CSS Editor and test your new alert.
- Repeat for all other alert types and variations (eg. re-subs, gift subs, community gifts).

Conclusion
----------

That's all you need to get these basic alerts running in StreamElements. Tinker with the HTML/CSS, make it your own, dive into CSS animations and come up with something great!