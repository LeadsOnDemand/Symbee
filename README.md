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
2. [ ] Setup inbound phone numbers
    - www.itbr.com website number.
    - 15 additional numbers used for outbound marketing asking to call in.
    - Call in strategy for routing is:
        - If inbound call is from a contact and the contact is owned by an Agen route to agent.
        - If inbound call is not owned by and agent, then ring all available phones (if ring all is not available round robin).
        - if inbound call is from a lead or unknown, then reing all available pones (if ring all is not available round robin).
3. [ ] Setup Screen pop strategy.
    - If inbound number is associated with a contact, then screen pop the contact.
    - If inbound number is associated with a lead, then screen pop the lead.
    - if inbound number is associaged with an account, then screen pop the account.