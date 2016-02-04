am-i-responsive
===============

A high fidelity preview of your responsive design across Desktop, Laptop, Tablet and Mobile.

I take a lot of screen shots of the various device breakpoints for responsive design and it takes a while to prepare them. This tools allows me to get what I need quickly, and hopefully it can be helpful for showing your more visual clients what you mean by responsive design when a suite of products isn't at the ready.

This is not a tool for testing, it is really important that you do that on real devices. This instead is a tool for quick screenshots (for me) and to visually allow people to “get” what you mean in client meetings.

# How it works

Add your URL to the input field and press GO! to see how your website looks across a few different viewports.

## Viewports

- Desktop
 - 1600x992px scaled down to scale(0.3181)
- Laptop
 - 1280x802px scaled down to scale(0.277)
- Tablet
 - 767x1024px scaled down to scale(0.219)
- Mobile
 - 320x480px scaled down to scale(0.219)

## A note on the viewports

The viewports I have chosen are based on the devices that were a part of the responsive PSD layout I previously bought. Apologies to all the Adroid fans out there, you can save the “Adroid has a bigger market share” because although you're right I just don't care. Plus if you're going to use this to sell RWD to new clients they're likely to be more familiar and wow'd by Apple stuff anyway.

# Updates
- 10/02/13 Updated so that pressing enter after adding a url will use the ?url get variable to update the iframes. This also means that you could share a link like http://ami.responsivedesign.is?url=http://www.thegreatdiscontent.com and it will load it up, helpful for emailing clients.
- 09/02/13 Added jQuery UI for the ability to drag the elements around the page. Remember that the <div>'s are more than the visible image so you might need to play around a bit with where you can click. Thanks Tim.
- 09/02/13 update the layout to be responsive across devices (even though it was just a tool for screenshots), although the iframes are WAY taller on tablet and iphone then they should be, still need to fix that... thanks @silentritual & @amberweinberg.
- 09/02/13 Scroll bars removed from tablet and mobile, cheers @benbrignall.
