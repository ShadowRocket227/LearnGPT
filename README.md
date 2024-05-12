# Introduction

LearnGPT is a free project, created by ShadowRocket227, for helping students at middle and high school level in studyng, searching and generally, learning.
LearnGPT Is avaible as "1-click prompt" on the MaxAI

The only requirment Is one of the two official MaxAI extension, "WebChatGPT" and "MaxAI.me", both downloadble for any modern browser like Chrome, Edge and Firefox, from their official stores.

You can find the setup and use tutorials below.

Why LearnGPT is better then ChatGPT ? For a lot of reasons:

-It can search on the web.
-It use the informations taken on the internet for checking the generated contents.
-It leave a complete source mapping, for checking the web pages visited by ChatGPT.
-Is focus on the school, so he can adapt to various subjects and topic using the most correct vocabulary, tone, writing style etc. based on the selected subject.
-You can customize a lot of options, like banned web addresses, writing style and output language, directly from the prompt bar of WebChatGPT/MaxAI.me, after selecting the prompt.

And so on.

You can find the raw prompt in the "LearnGPT-prompt.md" file. 

DISCLAIMER: DON'T USE THE PROMPTS CONTAINED ON BRANCH "dev". THEY ARE BETA PROMPTS AND IS NOT GURANTEED A SMOOTH EXECUTION AND EXPERIENCE. ONLY LOOK ON BRANCH "main".

The following text explain how to use the prompt, so please, read this file carefully.

# Requirments

1) Modern browser, like:

    -Google Chrome
    -Mozilla Firefox
    -Microsoft Edge
    -Opera
    -Brave

2) WebChatGPT or MaxAI.me official extensions. If you use Google Chrome, you can download it from the official store of your browser by typing the extension name and clicking "install" or something similiar.


# Setup

Becuase of the difficult that i had in publishing the prompt on the platform, i reccomend you to setup manually the prompt and adding it to your "Own 1-click prompts" area. You can do this following these instructions.

1) WebChatGPT

First, download the extension WebChatGPT or MaxAI.me. Both extension are managed by the same producer and they have similar fetuares, but i reccomend you uising WebChatGPT becuase it's lighter and i think is also more useful.

These two extensions are web AI services: they can, at example, allow you to search on the web with ChatGPT (a crucial fetuare for LearnGPT).

Now go on chat.openai.com, login with your OpenAI account and make sure that the buttons "1-click prompts" and "Web access" are both turned on. 
You can find this buttons in the downest area of the page.

Then, in the 1-click prompts window select "Own", click "Login" and create (or login, if alredy have an account) a MaxAI.me account. For do this, it will also ask you to
install the MaxAI.me extension (becuase, as i said before, MaxAI owns WebChatGPT and MaxAI.me). It's completley safe and after creating and login into the MaxAI account you can remove it without any problem.

Now, click on "Add new prompt template" and in the "Template" area paste the prompt that you find in the LearnGPT-prompt.txt file.
Then go on "Add new variable" add this variable names:

"Blocked"
"Subject"
"Topic"

Please, make sure you written the variable names as me (of course, don't insert the marks "").

These variables will be the prompt fields for blocked URLs, the subject for LearnGPT and the topic. After setting up the prompt, you will see these fields displayed in the prompt bar (that will be a bit different respect to the normal ChatGPT prompt bar).

When you add a new variable, you can also add an "hint", that is a description that you will se as a grey text in the variable spaces in the prompt area if you didn't typed nothing alredy in that area. You can use this for remind better what a determinate prompt bar's field does.

The other datas aren't important, like the "Title". Complete them just for a better experience, they won't change the prompt's work flow.

Lastly, click save and then click on the prompt you just created in the "Own" area. Now you will able to see the prompt bar and you're good to go !

2) MaxAI.me

MaxAI.me is a better choice if, at example, you also want to use AI for assisted writing when you're on your browser, or for having a small ChatGPT bar always ready to be used by pressing Alt+j. By the way, it also have a "1-click prompts" area where you can setup LearnGPT exactly like on WebChatGPT. I think it has too much useless fetuares respect to the first alternative i mentioned, but it's your choice.

First, click on the extension icon from your extensions bar. If a sort of ChatGPT side bar open ups on the right side of the screen, look for the "Immersive chat" button and click it. If MaxAI.me alredy shows up in full view, you're alredy ok.

Now click on "1-click prompts" and then "Own".

Click on "Add new prompt template" and in the "Template" area paste the prompt that you find in the LearnGPT-prompt.txt file.
Then go on "Add new variable" and add this variable names:

"Blocked"
"Subject"
"Topic"

Please, make sure you written the variable names like me (of course, don't insert the marks "").

These variables will be the prompt fields for blocked URLs, the subject for LearnGPT and the topic. After setting up the prompt, you will see these fields displayed in the prompt bar (that will be a bit different respect to the normal ChatGPT prompt bar).

When you add a new variable, you can also add an "hint", that is a description that you will se as a grey text in the variable spaces in the prompt area if you didn't typed nothing alredy in that area. You can use this for remind better what a determinate prompt bar's field does.

The other datas aren't important, like the "Title". Complete them just for a better experience, they won't change the prompt's work flow.

Lastly, click save and then click on the prompt you just created in the "Own" area. Now you will able to see the prompt bar and you're good to go !

# Other use instructions.

To use in the most efficient way the prompt, you should follow thes guidelines:

1) The prompt has a space called "Blocked", in the input bar. Here you can insert all the web URLs that you don't want are used by    LearnGPT for his responses. You have to write the banned addresses separated by a ";", like this:

    www.facebook.com; www.tikok.com; www.wikipedia.org

IMPORTANT: THE ADDRESSES PROVIDED HERE ARE ONLY EXAMPLES FOR EXPLAINING HOW THE PROMPT WORKS.

2) Always insert clearly the subject and the topic that you want to search with LearnGPT. You have these two informations in the spaces in the prompt windows, called "Subject" and "Topic".

3) If the LearnGPT output isn't good for you and you want to fastly say "Do this again, but in a better way.", you can type in the chat (after the first LearnGPT response) the keyword "/REDO". This command will force LearnGPT to follow your guidelines and make his work better. If the answer still hasn't the desired quality, formulate a more articulated request for task regeneration os just start a new chat with LearnGPT and explain better the task.


# General ChatGPT tips

In general, always remeber that you're talking to an AI, so avoid complex language and expressions, always be clear and don't include useless terms like "Please, do...", "Can you please..." and also exclude direct questions. This's becuase ChatGPT works better with "commands": at example, if you want to know how to say a "hi" in spanish, don't type "How can i say hi in spanish ?" but instead say "Tell me how to say hi in spanish."

Another good thing is to use delimiters. At example, if you want a translations of a text, you can write your request like this:

"Translate he following text in spanish:"

(Avoid type the marks here, i used them to separate my text from the example).

As you can see, i typed a command request, not a question, and i also inserted the ":" charachter; this helps ChatGPT to recognize that the text before the ":" is your request, and after the ":" there's the text that ChatGPT actually has to translate.

Talkig about this, the third good habit is to use some characters to "contain" the text. If you have to include a second text after your request, you can use determinate character to say "My secondary text starts here and ends there". 

Here at example, to divide better the text to translate to our request we can use delimiters like marks (""), brackets (like "[]" and the "{}". I don't reccomed using the round brackets, becuase ChatGPT usually confuse them with the actual text) and other characters at your own choice. In my opinion, the best characters are simple marks (""), but sometimes you will want to insert them in the text; in that case, you can use these two "<>". These ones are really good, becuase the various languages usually don't have this letters in their syntax and ChatGPT will automatically detect them as text delimiters.

Your delimiters are your choice, select them basing on the situation, if you need to insert a character in the text or something else.