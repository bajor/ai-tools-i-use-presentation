# copilot:
I don't like code completions. It requires to be detail-oriented and write very precise function names - then it will generate likely what you need. For me it's distracting long-term so I have it disabled.

Selecting parts of code and asking copilot what does it do:
<example>

Askig how would you write this simpler/more optimal:
<example>

General conversation about subject I don't understand:
general question -> more focused -> example in code

Generate dummy data:
<give this prompt, note that ``` because they oftern use markdown for reply>

Copilot to review PR:
https://docs.github.com/en/copilot
```
premium feature, available with the Copilot Pro, Copilot Pro+, Copilot Business, and Copilot Enterprise plans
```
In vs-code you can choose model it will use to answer.
In jetbrains products this option is disabled (I think) but it as these agents of `\explain` <add what else is avaliable> 
https://www.jetbrains.com/junie/


# chat gpt
I have it as a default website in my private computer, I use it daily instead of a google.
- 4o model for trivial questions - how to boil egg
- o3 for more reseach oriented - chain of thought model which evaluates it's own answers
- 15 deep reseach option for non-trivial tasks
- I use it for reseach mostly and to learn myself rathern than from books or youtube videos. I usually code something and ask it for help or to explain some subject when I am stuck.


# codex - from June 3 for ChatGPT Plus users
https://openai.com/index/introducing-codex/

- cloud-based software engineering agent taht can work on many task in parallel.
- used it to continue long-abandoned project of writing spark features in go.
- I have very defined, specific tasks for him and this is when it shines I believe. It won't work when you give it very general task - "write me replica of core spark funcitonalities in go". But it will when you ask him to do one very well defined "small" task. 
- It will evaluate his 

here is PR it created:
https://github.com/bajor/spark-go-core/pull/1/files

# cursor
- news from 5th of June on techcrunch:
Anysphere, the maker of AI coding assistant Cursor, has raised $900 million at a $9.9 billion valuation, Bloomberg reported.

based on vscodium - open-sourced versin of vscode. One for best if not best AI-first IDE now. They had agents at least from over year, I've generated entire front-end for some hobby project while ago now knowing js at all:
https://www.youtube.com/watch?v=3F9TdbzjDdE
- I've tried it again this month after a while. It got way better. Now if you are that crazy you can let it execute terminal commands and let it test what it generated. Codex is safer in this regard as it does everything in isolated cloud environment. But I thought yolo and let it run these commands in my terminal but after me approving by hand each of them.
- I was able to generate game in 3-4h with C which again I don't use these days:
https://github.com/bajor/c-raylib-playground

Bugbot - other cursor feature for reviewing PR requests in beta. Similar to what copilot has for premium users.
https://docs.cursor.com/bugbot


# zed
another very fast GPU accelerated, AI-First IDE. I've used it for few months but I prefer other tools.


# local-hosted LLMs
as LLMs are more and more censoured and more and more available to run them locally I've setup not so long ago ollama uncensoured llm model. Have it in my local network, connect to it via ssh. Works well but the one I have it's gpt 3.5 level - so it's not censourded but not super strong either.


# should you use them? does it make sense for you to use them the way I do?
Idk, depends who you are. Maybe you can cope some of these techniques and will work for you but everyone is different so you'd need to tweak it for you way of work.

Be very sceptical of everything AI generated and don't trust anything it says. Often what it will generate would be valuable but assume that it's bullshit and work your way from there.



