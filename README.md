# ecommerce_mock_data_generator
A tutorial to help users develop mock streaming data using the Mockingbird Streaming generator developed by Tinybird.


## Using the Web UI

1. Go to https://mockingbird.tinybird.co/
2. Sign up for a tinybird account. I found it easier to get data via the tinybird events API.
3. Copy and paste the admin privileges API key in your account portal. This connects your data source stream to your specific account. I used the wrong API key and could not find the streamed dataset.
4. Return to https://mockingbird.tinybird.co and select cloud host region, tinybird events API. Paste the API token, and specify data source name and the events/second.
5. Use one of the default schemas or modify the schema to your preference. mockingbird is built on the Faker.js library so modifications will need to reference the libraries docs.
6. Generate your data!
7. Go back to your account and create a pipe and there will be python code readily provided to request the data generated for your project.

