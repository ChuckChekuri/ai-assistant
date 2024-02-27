
<h1 style="display: flex; align-items: center;">

  <img src="imgs/favicon.jpg" alt="Axiomatic logo" width="50"
       style="border-radius: 10px;">
  <span style="color: lightblue; margin-left: 10px;">Axiomatic's HR Assistant</span>
</h1>

<p align="center">
  <img src="imgs/logo.png" alt="Streamly image"
    width="300" style="border-radius: 45px;"/>
</p>

AI Assistant designed to help you resolve human resources or people issues.
It could be presonal or professional. It an expert suggesting the perfect
communication needed to make the relationship more valuable.

## Features ##

- Secure and Private : Your data is never stored or shared with anyone.

- Interactive Chat Interface : Expect a serious professional interaction
   as if you are talking to an expert.

- Data Driven : Assistant relies on a data model that captures the state of
  the relationship and does a SWOT analysis to suggest the best communication.

- Actionable : Improves on it's suggestions until the suggestions are actionable.

- Personalized : Every relationship and every situation is unique and must be analyzed
  and treated differently.

## Methodology ##

At the heart of Assistant lies a sophisticated Data Model and prompting logic that
evaluates the state of the relationship based on the interactiive question and answer
session with the users. Once the state is captured, the assistant does a SWOT
analysis and suggests the best communication to make the relationship more
valuable.

The assistant uses the session state management, enough memory for a consistently
coherent conversation for all your employee or customer challenges..

Built in caching mechanisms under the hood for performance optimization, and has
a robust error handling protocol.

Founder, professionals and Sr. Executives interact with customers, investors,
employees and vendors all with different agendas and priorities. The AI assistant
is you way to think through those interactions in a way to find win-win solutions.

## Instructions ##

This will be run on AWS under a secure environment. The assistant will be
deployed in a custom EC2 that you own.

## Technolgy ##

- Python
- Huggingface
- OpenAI
- GeminiPip package manager

### API Keys ###

You will need to get the API keys from OpenAI and Huggingface to use the assistant.
It can be stored safely in the environment variables.

### Installation ###

Create an EC2 instance from the AWS console using a prebuilt AMI. The AMI will have
all the necessary software installed and configured.

You need to open the following ports in the security group: 8645, 8501, 22, 80, 443