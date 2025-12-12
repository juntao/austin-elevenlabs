# Austin culture guide

> Submission to ElevenLabs Worldwide Hackathon in Austin

By [Michael Yuan](https://github.com/juntao) and Tony Yuan

[Watch the 2 minute demo](https://youtu.be/sv6WIgaV_c8)

An open-source smart hardware device configured to chat to people about Austin in voice. Perfect for new comers or anyone who wants to move to Austin. There are over 150 people moving to Austin everyday, and they all want to chat about the culture, life and weather in Austin! Utilizing a Texas-accented voice on ElevenLabs, this device can chat about

* History
* Culture
* Local politics
* Housing
* Schools
* Neighborhoods
* Current weather
* Current events

## Quick start with an EchoKit device

This utilizes a server we already set up. It will be taken down after the hackathon. You should start and run your own server.

* Power up your [EchoKit device](https://echokit.dev/echokit_box.html)
* Point your browser to https://echokit.dev/setup/
* Add your Wifi network and password (2.4GHz ONLY)
* Enter **server URL**: `ws://45.33.125.24:8051/ws/`
* Click on **Save changes**

## Quick start with browser-only

This utilizes a server we already set up. It will be taken down after the hackathon. You should start and run your own server.

* **Download** the [austin.html](austin.html) file from this repo
* Double click on your local copy of `austin.html' to open it in a browser
* Enter **server URL**: `ws://45.33.125.24:8051/ws/`
* Click on **Listen ...** to start chatting!

## Tech stack

* [ElevenLabs](https://elevenlabs.io/)
* [Groq](https://groq.com/) (or [xAI](https://x.ai/api) or any OpenAI compatible API service)
* [Tavily](https://www.tavily.com/)
* [Docker](https://www.docker.com/)
* [LlamaEdge](https://llamaedge.com/docs/ai-models/) (if running locally)
* [EchoKit server](https://github.com/second-state/echokit_server)
* Open source hardware: [EchoKit device](https://echokit.dev/echokit_box.html) (or web client -- see [austin.html](austin.html) above)

![](tech_stack.png)

## Complete guide to run your own server

### 0 

### 1 Start the EchoKit server

### 2 Start the MCP server

### 3 Figure out the IP address



