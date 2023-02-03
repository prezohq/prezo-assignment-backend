# prezo-assignment-backend

Hi there, thanks for your interest in [Prezo](https://prezo.ai). We are excited to work with builders and hackers to help us shape Prezo.

A common need when hacking on Prezo is to setup endpoints for querying AI models. Your mission, should you choose to accept it, is to create a working version of one such endpoint.

## Requirements

You are building an API endpoint that can summarize text sent to it.

- Create an API endpoint that accepts text input, wraps it in a full prompt and queries an Open AI model.

- It should query for text completion. (https://platform.openai.com/docs/guides/completion) You can create a free account on OpenAI and get free credits to use. You will need an API key from them.

- Your API should return a JSON response of the result returned by OpenAI.

- How will you make this fault tolerant? Think about all the ways in which this simple endpoint can fail and write your ideas on how we can handle failures. If you code up mitigating solutions as part of the endpoint, even better.

For instance:
- OpenAI's servers could throw 500s
- The input text could take a long time to summarize

What about rate limits? What else should we consider?

We work in python and javascript so prefer solutions in those languages, but you're free to use whichever language/framework you're most comfortable with.

## Deliverables

- Create a repo with your code in it. 

- Host it on render/railway/heroku/or any other service with free tier.

- Record a short video walking us through how you crushed this

- Share the repo, the video and the hosted app with us

If you are out of OpenAI credits, contact us for a key.

## Resources

- [OpenAI docs](https://platform.openai.com/docs/introduction)
