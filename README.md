# Case Study: Using Customer Data to Predict Application Success

Problem description One aspect of our business involves calling potential customers (leads) who inquire about our products. In the best-case scenario, these customers work with our licensed sales agents to submit an application for a new policy (we consider this a sale). The typical structure this process takes is:

We create a prediction score for all available uncontacted leads at the time of a match.
The agent will match with the “best” uncontacted lead and call that lead.
If the customer is not available, we put the lead back in the inventory of available leads for later consideration.
If the customer is available, the agent engages in a conversation; this is a contact.
Agent assesses the customer’s interest and eligibility in our products.
If applicable, the agent provides custom pricing information; this is a quote.
If the customer is interested, the agent helps the customer submit an application.
Problem: How do we use available data to improve our prediction score (1) to maximize sales?
