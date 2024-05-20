# Introduction

LearnGPT is a free project, created by ShadowRocket227, for helping students at middle and high school level in studying, searching and generally, learning. LearnGPT Is avaible as "1-click prompt" on MaxAI.

The only requirement Is one of the two official MaxAI extensions, "WebChatGPT" and "MaxAI.me", both available to download for any modern browser like Chrome, Edge and Firefox, from their official stores.

You can find the setup and use tutorials below.

Why is LearnGPT is better than ChatGPT ? For a lot of reasons:

1) It can search on the web. 
2) It uses the informations taken on the internet for checking the generated contents. 
3) It leaves a complete source mapping, for checking the web pages visited by ChatGPT. 
4) Is focused on the school, so he can adapt to various subjects and topic using the most correct vocabulary, tone, writing style etc. based on the selected subject. 
5) You can customize a lot of options, like banned web addresses, writing style and output language, directly from the prompt bar of WebChatGPT/MaxAI.me, after selecting the prompt.

And so on.

You can find the raw prompt in the "LearnGPT-prompt.txt" file.

DISCLAIMER: DON'T USE THE PROMPTS CONTAINED ON BRANCH "dev". THEY ARE BETA PROMPTS AND IS NOT GUARANTEED A SMOOTH EXECUTION AND EXPERIENCE. ONLY LOOK ON BRANCH "main".

The following text explains how to use the prompt, so please, read this file carefully.

# Requirements

Modern browser, like:

1) Google Chrome 
2) Mozilla Firefox 
3) Microsoft Edge 
4) Opera 
5) Brave

WebChatGPT or MaxAI.me official extensions. If you use Google Chrome, you can download it from the official store of your browser by typing the extension name and clicking "install" or something similar.

# Setup

Because of the difficulty that I had in publishing the prompt on the platform, i reccomend you manually set up the prompt and adding it to your "Own" area. You can do this following these instructions.

1) WebChatGPT

First, download the extension WebChatGPT.

This extension Is a web AI service: it can, for example, allow you to search on the web with ChatGPT (a crucial feature for LearnGPT).

Now go on chat.openai.com, login with your OpenAI account and make sure that the buttons "1-click prompts" and "Web access" are both turned on. You can find these buttons in the lowest area of the page.

Then, in the 1-click prompts window select "Own", click "Login",  and create (or login, if already have an account) a MaxAI.me account. To do this, it will also ask you to install the MaxAI.me extension because, MaxAI owns both WebChatGPT and MaxAI.me. It's completely safe, and after creating and login into the MaxAI account,  you can remove it without any problem.

Now, click on "Add new prompt template" and in the "Template" area paste the prompt that you find in the LearnGPT-prompt.txt file. Then go on "Add new variable" add this variable names:

"Blocked" "Subject" "Topic"

Please, make sure you have written the variable names as me (of course, don't insert the marks "").

These variables will be the prompt fields for blocked URLs, the subject for LearnGPT and the topic. After setting up the prompt, you will see these fields displayed in the prompt bar (which will be a bit different respect to the normal ChatGPT prompt bar).

When you add a new variable, you can also add a "hint", that is a description that you will see as a grey text in the variable spaces in the prompt area if in that moment they're empty. You can use this to better remember what a determinate prompt bar's field does.

The other datas aren't important, like the "Title". Complete them just for a better experience, they won't change the prompt's work flow.

Lastly, click save and then click on the prompt you just created in the "Own" area. Now you will be able to see the prompt bar, and you're good to go !

# MaxAI.me

MaxAI.me is a better choice if, for example, you also want to use AI for assisted writing when you're on your browser, or for having a small ChatGPT bar always ready to be used by pressing Alt+j. By the way, it also has a "1-click prompts" area where you can set up LearnGPT exactly like on WebChatGPT. I think it has too many useless features compared to the first alternative I mentioned, but it's your choice.

First, click on the extension icon from your extensions bar. If a sort of ChatGPT sidebar open ups on the right side of the screen, look for the "Immersive chat" button and click it. If MaxAI.me already shows up in full view, you're ok yet.

Now click on "1-click prompts" and then "Own".

Click on "Add new prompt template" and in the "Template" area paste the prompt that you can find in the "LearnGPT-prompt.txt" file. Then go on "Add new variable" and add this variable names:

"Blocked" "Subject" "Topic"

Please, make sure you have written the variable names like me (of course, don't insert the marks "").

These variables will be the prompt fields for blocked URLs, the subject for LearnGPT, and the topic. After setting up the prompt, you will see these fields displayed in the prompt bar (which will be a bit different respect to the normal ChatGPT prompt bar).

When you add a new variable, you can also add a "hint", that is a description that you will see as a grey text in the variable spaces in the prompt area if you didn't type anything already in that area. You can use this to remind better what a determinate prompt bar's field does.

The other datas aren't important, like the "Title". Complete them just for a better experience, they won't change the prompt's work flow.

Lastly, click save and then click on the prompt you just created in the "Own" area. Now you will be able to see the prompt bar,  and you're good to go !

# Other use instructions.

To use in the most efficient way the prompt, you should follow these guidelines:

The prompt has a space called "Blocked", in the input bar. Here you can insert all the web URLs that you don't want are used by LearnGPT for his responses. You have to write the banned addresses separated by a ";", like this:

www.facebook.com; www.tikok.com; www.wikipedia.org

IMPORTANT: THE ADDRESSES PROVIDED HERE ARE ONLY EXAMPLES FOR EXPLAINING HOW THE PROMPT WORKS.

Always insert clearly the subject and the topic that you want to search with LearnGPT. You have these two informations in the spaces in the prompt windows, called "Subject" and "Topic".

If the LearnGPT output isn't good for you and you want to quickly say "Do this again, but in a better way.", you can type in the chat (after the first LearnGPT response) the keyword "/REDO". This command will force LearnGPT to read again your guidelines and make his work better. If the answer still hasn't the desired quality, formulate a more articulated request for task regeneration or just start a new chat with LearnGPT and explain better the task.

# General ChatGPT tips

In general, always remember that you're talking to an AI, so avoid complex language and expressions, always be clear and don't include useless terms like "Please, do...", "Can you please..." and also exclude direct questions. This's because ChatGPT works better with "commands": for example, if you want to know how to say a "hi" in spanish, don't type "How can I say hi in spanish ?" but instead say "Tell me how to say hi in spanish."

Another good thing is to use delimiters. At example, if you want a translation of a text, you can write your request like this:

"Translate the following text in spanish:"

(Avoid type the marks here, I used them to separate my text from the example).

As you can see, I typed a command request, not a question, and I also inserted the ":" character; this helps ChatGPT to recognize that the text before the ":" is your request, and after the ":" there's the text that ChatGPT actually has to translate.

Talking about this, the third good habit is to use some characters to "contain" the text. If you have to include a second text after your request, you can use determinate character to say "My secondary text starts here and ends there".

Here for example, to divide better the text to translate to our request we can use delimiters like marks (""), brackets (like "[]" and the "{}". I don't reccomend using the round brackets, because ChatGPT usually confuse them with the actual text) and other characters at your own choice. In my opinion, the best characters are simple marks (""), but sometimes you will want to insert them in the text; in that case, you can use these two "<>". These are really good, because the various languages usually don't have this letters in their syntax, and ChatGPT will automatically detect them as text delimiters.

Your delimiters are your choice, select them basing on the situation, if you need to insert a character in the text or something else.

# For the new developers of "LearnGPT"

LearnGPT is started as a school project; because of this, it will not developed forever by his first creator (me). But, as you can read in the "LICENSE.txt" file, the project is released in MIT License: everyone can continue his developing, cloning, forking and generally do everything with this project.

I completley agree with this condition: if this project can be useful and it will continue his evolution, i can only be happy !

There's only one thing that i quest to all hypotetical future developers of LearnGPT: please, put a reference to the original project (this one): in this way, the original creator (me) will not be forgot by future users !
