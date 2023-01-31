# TVC_Songlist_Website
Songlist Web App Project


# History
This is a website that I had created for "TVC" to create an "Approved" Songlist with some search functionality for stream moderators to quickly identify and screen songs and leave comments

# Goal
I would like to turn this into a full Web Based Application with Twitch API Integration for Authentication and Chat Interaction, and to turn this into a full replacement for the current method used in her stream for Song Queue Screening.

# Initial Starting Points

-Remove paid JS codelets for search Functionality and rewrite those functions to be native to reduce project costs.

-Remove all references to the Webflow CMS and rewrite those references using the Database API currently being used for content management (Currently using Airtable, looking at cheaper options for that as well)

-Remove the Webflow References for User Management and begin utilizing Twitch Authentication and/or Firebase Authentication

# Intended Paramaters of Webapp Functionality

    -General Requirements

        -Must strictly remain a Web Based Application
        -Have multiple Queues (Now Playing, Priority, General, Song Pool, Needs Screened)
        -Drag and drop re-ordering between all queues for Admins/Moderators
        -2 web interfaces and/or dashboards (Client View Only Side / Admin-Mod Edit Side)
        -allow the streamer to see the youtube video embed

    - Web Interface Requirements

        -Twitch Login Authentication (Allow the Channel Owner to edit permissions and give people Admin/Mod Rights)
        -Limit who can request songs by "Subsriber Level" (everyone, subscriber, VIP, Moderator, Owner)
        -Request songs via Youtube Links
        -Limit the number of active requests per user to a configurable number (Ideally customizable per access level)
        -Allow Admins/Mods to disable/enable queues, and/or add/delete queues

    - Chatbot Requirements

        -Ability to Connect the Bot to the Owners Twitch Channel 
        -Listen for commands in the Chat Channel
        -Ability to Customize commands
        -Post Feedback Messages when a command is recognized (Success/Fail)
        -Allow the chatbot to take a direct youtube link, youtube short link, or vod ID, and Search String as well
        -Have !currentsong command post the current song playing in chat. 
        -Allow the chatbot to automatically reject submissions based on length of song/video, and cross reference a pre-defined list of "Blacklist" items.
         




