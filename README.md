# Symbee

Leads on Demand contact center solution.

## Purpose

The purpose of this repository is to house and documentation, configuraiton and code Leads On Demand want needs to maintain.

## Requested Features
### Phase 1.
#### Outbound.

1. [ ] Create unique number per agent.
    - We would like new numbers for our agents, but when we are ready to cut over we will request that our numbers be transfered from our current provider over to connect.
    - Can an agent have multiple numbers? If so, can they choose what number they call out as.
2. [ ] Allow the agent to cerate a "voicemail drop"
3. [ ] Set up outbound dispositions.
    - Attempted
    - Booked
    - Company Too Small
    - No Campaigns Available
    - No Influence
    - No Longer At Company
    - No Upcomming Projects
    - Rescheduled
    - Unqualified
    - Unsubscribed
    - Wrong Number
    - Left Voicemail
    - Customer Service
    - More Information
    - Follow Up

#### Inbound
1. [ ] Setup direct dial for all agents.
2. [ ] Setup inbound dispositions.
    - Booked
    - Company Too Small
    - No Campaigns Available
    - No Influence
    - No Longer at Company
    - No Upcoming Projects
    - Rescheduled
    - Unqualified
    - Customer Service
    - More Information
    - Follow Up
3. [ ] Setup inbound phone numbers
    - www.itbr.com website number.
    - 15 additional numbers used for outbound marketing asking to call in.
    - Call in strategy for routing is:
        - If inbound call is from a contact and the contact is owned by an Agen route to agent.
        - If inbound call is not owned by and agent, then ring all available phones (if ring all is not available round robin) Note: ring all is not available.
        - if inbound call is from a lead or unknown, then reing all available pones (if ring all is not available round robin) Note: ring all is not available.
4. [ ] Setup Screen pop strategy.
    - If inbound number is associated with a contact, then screen pop the contact.
    - If inbound number is associated with a lead, then screen pop the lead.
    - if inbound number is associaged with an account, then screen pop the account.

#### Features
1. [ ] Recored all calls
2. [ ] Transcribe all calls
3. [ ] Enable click to dial
    - Most call center solutions allow click to dial on Contact/Lead/Account. Does Symbee allow click to dial from any phone field? If yes, do we have the ability to associate that call however we sith via lambda?
4. [ ] Build custom reports and/or views that allow us to call through.

### Phase 2.
1. [ ] Web enable associate phone numbers in order to text with contacts.
2. [ ] Setup webchat on www.itbr.com. Symbee to provide documentation.


## General Questions
1. Can an agent see there call history from the dialer? Yes
2. Can an agent vew call recordings form the dialer? Not today feature was requested and accepted. Link to record from record go to recording
3. Can we restrict an agent to see all calls, but only listen to their calls, with the exception of team leads and managers? You can listen to all recordings or none. This feature has been requested.
4. When using click to dial do I have access to the context of that click? Example what custom object was used when dialed.
