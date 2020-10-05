# Event/activity organizers

Events are where community members get together. Examples are GUADEC and KDE Akademy

Activities can include Hackfests.


## Goal: Retaining and attracting contributors



1. Question: How long do new people who attend events stay with the community?
    1. Metric: Length of time of attendee’s membership
        1. Data: Correlate registrations with existing data on participation, e.g. for GNOME, Foundation membership renewal. 
        1. Data: Compare membership length for attendees vs. non-attendees.
    1. Metric: Time since first contribution for event attendees
        1. Data: Cross-reference GitLab or GitHub contribution data with event attendees to see when someone attending an event first contributed
    1. Metric: Time since event to last contribution (retro-spective metric)
        1. Data: Cross-reference GitLab or GitHub contribution data with event attendees to see when someone attending an event last contributed
1. Question: Given a person who is new to the project and not a member, how much more likely are they to become more involved and stay longer in the project?
    1. Metric: Statistical test for comparing two groups (maybe T-Test?)
        1. Data: (1) baseline of how long people stay in the community if they didn’t attend an event. (2) how long do people stay in the community if they attended an event. Data might come from surveying community members or asking for community handles during event registration.
        1. Survival Analysis: After how many weeks of first contribution, how many people continue to be active in the community? 
1. Question: What role do events have in engaging contributors? _Operationalized as: What is the level of contribution of people over time before or after attending an event? Do we see a spike of contributions from attendee members after an event? OR Did contributions as a whole spike after an event? (Keep in mind other factors for spikes, e.g., release schedule_)
    1. Metric: Number of contributions of attendees
        1. Data: Cross-reference the list of attendees with project contributors. Requires a metric platform that tracks contributions
        1. NOTE: Need to make sure that we capture all types of contributions, not just software development contributions.
    1. Metric: Contributions to a particular segment of a project, for example during hackathons and BoFs (e.g. Docs hackathon. Were there more Docs contributions after event?)
        1. Data: have project leads measure contributions before and after the event.
1. Question: How many attendees are also contributors to the project?
    1. Metric: Number of attendees who contributed to the project before the event
        1. Data: ask in registration form if they are contributors
        1. Data: Cross-reference the list of attendees with project contributors. Requires a metric platform that tracks contributions
1. Question: How do the people at an event feel about the project?
    1. Metric: Count emojis (positive and negative) as a way to gauge sentiment.
        1. Data: Ask participants to submit an emoji response to the question how they felt about the project.
    1. Metric: Sentiment analysis around event hashtags on social media
        1. Data: Social media feed for the event hashtag
1. Question: How engaging was an event?
    1. Metric: Number of messages on social media with event hashtag
        1. Data: Social media feed for the event hashtag
    1. Metric: Number of messages on conference specific messaging platform
        1. Data: Conference specific messages platform, e.g., Slack
1. Question: How many people return to our events?
    1. Metric: Number of people who have attended previous events
        1. Data: Registration survey (ask: have you attended this event before?)
        1. Data: Registration data from previous events
1. Question: What is the turnover at our event
    1. Metric: Ratio of returning and new participants in the events
        1. Data: Registration survey (ask: have you attended this event before?)
        1. Data: Registration data from previous events
    1. Metric: Number of events over time -- if event is growing, then larger number of new participants is good
        1. Data: Registration data
1. Question: How many attendees are attending for the first time?
    1. Metric: Number of people who have not attended previous events
        1. Data: Registration survey (ask: have you attended this event before?)
        1. Data: Registration data from previous events
1. Question: How many people started contributing at one of our events?
    1. Metric: Number of people who contribute for the first time during an event.
        1. Data: Ask in a post-conference survey or maybe ask BoFs to record newcomers
        1. Data: Ask in a community survey how they made their first contribution


## Goal: Understanding company contributions to event



1. Question: How many event attendees come from companies vs. volunteer contributors.
    1. Metric: Ratio of attendees that have an organizational affiliation versus those that are volunteers
        1. Data: Event registration form
            1. Question on registration: Is a company sponsoring in some way (e.g. flight/accomodation/ticket/time-off) your attendance?
            1. Question on registration: Which company would you like to recognize for supporting your attendance?
        1. Data: If an event has different levels of tickets, we can use that data to know who is a “hobbyist” or “academic” or “sponsored by company” -- it’s an honor system.
1. Question: What companies are attending our event?
    1. Metric: List of organizations attendees affiliate with [target org]
        1. Data: Event registration form
1. Questions: What companies are involved in the event beyond sending employees?
    1. Metric: List of companies represented by speakers
        1. Data: The schedule of the event
    1. Metric: List of companies who directly sponsor the event
        1. Data: Ask the event organizers
        1. Data: Event website
    1. Metric: List of companies who are in other ways involved in the event
        1. Data: Ask the organizers
            1. Note: This may include companies contracted in executing the event.
            1. Note: This may include side-events that are not officially part of your event.
1. Question: How many companies are repeat sponsors? How many only sponsored once?
    1. Metric: List of sponsors with their number of times sponsoring
        1. Data: Event organizers
        1. Data: Event website from past events
    1. Metric: Amount sponsored by organizations and by year
        1. Data: Event organizers
        1. Data: Event website with list of sponsors + Sponsor prospectus to know how much different levels are
    1. Metric: List of sponsors with the last time they sponsored an event
        1. Data: Event organizers
        1. Data: Event website from past events
1. Question: How competitive it is to get sponsorship for our event?
    1. Metric: List of similar events that are looking for sponsorship
        1. Data: Search the internet
        1. Data: Ask others in the ecosystem


## Goal: Ensure events contribute towards diversity and skill gaps in the community



1. Question: What skill programs do we have at our events?
    1. Metric: List of skill programs
        1. Data: Event organizer provides this overview (might also be available on event website).
            1. Note: Skill programs can be: Tutorials, classes, workshops, hackathons, certification events, speed mentorings
1. Question: What is the diversity of initiatives we have at our events?
    1. Metric: # of tracks
        1. Data: The conference schedule: How many tracks are being held at the conference? (for different industries, for different roles, for different skill levels, etc)
    1. Metric: # of different activities
        1. Data: The conference schedule: How many other activities besides talks are planned? (hackathons, coding for good, charity work, specialized workshops, etc)
1. Question: What are the different skills we have represented in our events?
    1. Metric: List of skills (maybe word cloud)
        1. Data: Survey, possibly during registration for event
1. Question: Do we represent at the event the skills we need in the project/community?
    1. Metric: List of skills that we need in the project community
        1. Data: Project leads
        1. Data: Onboarding team
    1. Metric: List of skills covered by talks, programs, initiatives, etc. at the event
        1. Data: Event schedule

