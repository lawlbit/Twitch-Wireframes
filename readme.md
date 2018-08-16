# Twitch Rework Wireframes
This basic rework of Twitch demonstrates a baseline for integrating esports gambling with the existing web app. While working on the redesign small changes were made on existing pain points of the application. Each of the screens touched in this repository is labeled accordingly as seen on the image name.

## Existing Pain Points
* Cluttered Logged in landing page
* Redundent elements
* Extented use can irritate eyes due to exessive brightness of the screens

# Wireframe Walkthroughs
## Home Screen (Logged in)
Existing site had irrelevant feeds streamed to a user. The featured streamers are deteremined through randomization from a list of sponsored streamers. The information clutters up the screen and can potentially turn off a user. Majority of users who are returning to Twitch use Twitch to watch very specific streamers. The reimagining of the page focuses on bring desired content to the user.

The header was also decluttered and seperated into two parts. The explore option takes you to the Explore page screen. 

The Side navigation bar is now starts off closed to open up more real estate for the rest of the app.

## Home Screen (Large Sponsored Events)
The main focus of this screen is to drag in viewership to large public events such as Ninjs's Fortnite Tournament or the LCS. This page will be dynamicall activated to avoid certain users who dislike the game or subject.

## Footer
The footer abstract uncommonly used links by the average user to the bottom. This design focuses on the audience experience in order to maximize the audience return rate. 

## Sidebars (Open)
This screen demonstrates the space usage of the side navigation bar on the home screen. The layout for the navigation is to clean up the existing redundent links as well as give a more personal experience to the user. Giving them the focused view on followed channels and friends. The signifiers beside each external account name signifies their status. Green means online, red means live and streaming and gray means offline. This colour scheme follows closely to the current twitch scheme as to keep the experience consistent if a transfer were to happen.

## Explore Page
This page is designed to replace the existing screens dedicated to browsing games as categories as well as the featured streams from the existing homepage. The focus of this page is create a dedicated space in which a user can find potential sources of entertainment. On the backend the carousel should on select specific streams given a certain relevance to the user. Following this foot in the door tactic viewer retention should be higher.

## Video Stream
The base video stream screen is where majority of the time a user will be spent. The base format is very similar to the current layout. Some changes done is the retractable side navigation bar as well as the more pronouced border surrounding the actual video display. This screen is also the first place the wager system can be seen. The intent behind the button is to give tournament streams as well as individual streamers a new way to interact with their respective communities. Clicking the button leades to the betting confirmation screen. The button should be optional and up to the streams discretion. The functionality should also be age gated based on regional laws based on ip addresses.

## Video Stream (Bet Confirmation)
The betting confirmation is meant to be simple and quick. The column on the right should be a list of people who or teams who are currently participating. The middle column are the odds for each team and the far right column is the amount to be placed on the wager. Once done a user goes to the button and clicks to submit the purchase. 

## Technology Strategy
The full stack for Twitch can be found here: <br/>
`https://blog.twitch.tv/twitch-engineering-an-introduction-and-overview-a23917b71a25` 
<br />
Most modifications will be done the face level of the system. The rework mainly focuses on reworking the organization of the site rather complete overhaul of the backend.

## Design Strategy
The focus behind the design was to streamline and focus the user experience. Another consideration was information overload a current user will face when logging on to the site. Clean design allows the site to better control teh user story.

## Betting Strategy
For twitch betting is a little difficult to integrate. The final solution will probably incorporate the pre-existing twitch currency, bits. This currency is used to encourage community involvment between streamers and their audience. The prototype system should focus on using bits as the platform in introduce gambling to esports. In this way the transition can be smooth as well as reactive to user wants.
