
# Testing Assessment

This assessment requires the completion of 3 different tasks, one analytical approach, a jmeter task, and a functional one



## Tasks


### Approach
We have 285 Codeception tests in Magento2 which uses test data. We started using Cypress for graphql, some API and frontend tests.

    1. What would be your approach to put this all together in a best possible way?

    2. It is challenging to add test data on test environments where sanitised production data already exists. What would be your approach to fix this and how?

    3. How can you make Cypress flexible to perform integration tests with third party vendors?







### Jmeter 
Use jMeter v5.0 Scripting, write a front end automated script, targeting www.harveynorman.com.au where you;

1. go to homepage,
2. navigate to any product page,
3. and then press add to cart.
4. select a delivery postode, proceed to chechout and enter all customer details, including shipping
4. checkout using invalid credit card and validate the response


## Additional items

* The script properties should contain 2 users, with a 5 second constant time sampler between each request.
* This script should finish after 3 iterations and validate the error messaging received on invalid payment
* Describe what additional details you would need, to implement the exact same test to be run via Blazemeter


## Required output

Once complete, commit your tests, along with any instructions and create a Pull request for it back to this repo







### Cypress  
Setup Cypress framework and write a front end automated script targeting www.harveynorman.com.au where you;

##TASK A
1. Go to product page(for example https://www.harveynorman.com.au/google-nest-cam-outdoor-with-floodlights.html )
2. Verify the estimated delivery cost for postcode 2140
3. Verify the tabs (for example Description, Specifications, Returns, Reviews etc are present on the page) 

##TASK B
1. Go to gift card product page (for example https://www.harveynorman.com.au/harvey-norman-e-gift-card.html)
2. Fill the form, add the gift card to the cart and go to checkout page.

Do the basic assertions while performing both Task A and Task B

## Required output
Create a report and upload the report in GitHub



