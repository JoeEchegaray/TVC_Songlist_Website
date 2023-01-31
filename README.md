# TVC_Songlist_Website
Songlist Web App Project


# History
This is a website that I had created for "TVC" to create an "Approved" Songlist with some search functionality for stream moderators to quickly identify and screen songs and leave comments

# Goal
I would like to turn this into a full Web Based Application with Twitch API Integration for Authentication and Chat Interaction, and to turn this into a full replacement for the current method used in her stream for Song Queue Screening.

# Initial Starting Points

-Remove paid JS codelets for search functionality and rewrite those functions to be native to reduce project costs.

-Remove all references to the Webflow CMS and rewrite those references using the Database API currently being used for content management (Currently using Airtable, looking at cheaper options for that as well)

-Remove the Webflow References for User Management and begin utilizing Twitch Authentication and/or Firebase Authentication

# Paramaters of Webapp functionality

-Utilize Twitch.tv API for User Authentication, and Chat Interaction, Receive Commands from Twitch Chat (Potentially chatty API as well)

-Allow twitch users to add items to a "Queue" based on Subscriber Status received through the Twitch API

-Allow Moderators and Above to manage said queue, and re-order the items utilizing a drag/drop functionality


