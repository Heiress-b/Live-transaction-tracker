Live Transaction Tracker is a fully automated 
end-to-end financial accountability system that 
monitors bank transfer emails in real time, 
extracts structured transaction data using custom 
JavaScript, logs every transaction into a live 
database, and delivers instant account summary 
reports to users on demand.

Built entirely without writing a backend server — 
powered by Gmail, Zapier, Airtable, and JavaScript.


## Problem It Solves

Most people send money frequently but have no 
structured way to track:
- Who they've sent money to
- How much they've sent to each person in total
- How many times they've transacted with each account
- Their full transfer history in one place

This system solves all of that — automatically, 
in real time, with zero manual input required.

## Tech Stack
 **Gmail** | Email trigger — detects OPay transfer confirmations 
**Zapier** | Automation engine — orchestrates the entire pipeline
**JavaScript** | Custom parser — extracts fields from raw email text
**Airtable** | Database — stores transactions and account summaries
