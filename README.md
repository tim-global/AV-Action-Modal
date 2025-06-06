# AV Action Modal
A modal window that pops up if it detects that a user is located in a state with pending age-verification legislation.


## How To Add It To Your Site

1. Copy this:
`<script src="https://assets.freespeechcoalition.com/code/avActionModal.min.js"></script>`

2. Paste it before the `</body>` tag of your website's code.


## How It Works

When a user visits your website, the script checks to see whether they have a cookie indicating that they have already seen the pop up. If not, it checks whether they are  in a state with a pending age-verification bill. If they are, it displays a pop up window asking them to oppose the bill:

![Screenshot of the AV Action Modal on a dark website.](https://assets.freespeechcoalition.com/code/modalDark.png)

Any links clicked will open in a new window/tab. Clicking anywhere on the page (including the links) will close the pop up.

Whether or not the user clicks the links, the cookie is set, ensuring that they do not see the message again.



## FAQs
### Why did FSC create this?
Politicians' number one priority is reelection, so they care far more about what the voters in their district think than what the porn industry thinks. We were able to defeat Arizona's law in 2024 by mobilizing constituents to pressure the governor into vetoing a bill that the legislature had passed. We think we can do it again this year in more states.

### Which states will see the pop up?
Arizona, Colorado, Hawaii, Illinois, Iowa, Maryland, Minnesota, Missouri, Nevada, New York, North Dakota, Ohio, Oregon, West Virginia, and Wisconsin.

### What happens when the user clicks the link to contact their representatives?
They are taken to a form where they can send a message to their elected officials. (Example: [Illinois](https://www.defendonlineprivacy.com/il/action.php))

### What if the user isn't in the state associated with their IP address?
Under the button urging them to take action, we link to a [page](https://defendonlineprivacy.com/geolocation.php) explaining that geotargeting is imperfect and that they could still be affected by the law even if they don't live in that state.

### Do I have to pay to use this?
No. FSC is providing access to this code (including the geolocation service) free of charge so that websites can mobilize their customers to stop the spread of bad age-verification laws. In the event that the number of API requests surpasses FSC's budget, the pop up will simply not appear.

### What if I have a problem adding the code or the pop up looks wrong?
Let Alison know!
