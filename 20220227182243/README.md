# Never Use Markdown Inline Links: 

* **What is Markdown?**

Markdown is one of the most popular way to **Document your Project /
Programs**. There are many different flavours of Markdown but I prefer
to use **Common Mark** for it's *simplicity* and *industry-like*
standards. 

* **Why should not use Inline Links in Your Markdown?**

Inline Links are great but are they? Because it nice that you can put a
link where ever you like directly but **they reduce the readability**.
Now, you might how come isn't Markdown suppose to improve the
readability of the documentation? This problem is specifically faced by
CLI users as it makes things ambiguous.

Let me show you some the difference: 

```markdown

🙂 Hi there !!, Whats up ? Hope everything is going well. Here is
my [Github](https://github.com/dharmit009) page. Sadly I am not
available on [Twitch](https://www.twitch.com) or [Youtube]
(https://youtube.com/). Hope you like my
[Github](https://github.com/dharmit009) page. 

While writing this Paragraph I just realize I cannot reference the an
Inline Link 😂. It's time to switch to Relative Links. Let us rewrite
the same paragraph below and see the difference.

Plus I only need to update link in one place for relative links. 

```

```markdown

🙂 Hi there !!, Whats up ? Hope everything is going well. Here is
my [Github][1] page. Sadly I am not available on [Twitch][2] or on
[Youtube][3]. Hope you like my [Github][1] page. 

While writing this Paragraph I just realize I cannot reference the an
Inline Link 😂. It's time to switch to Relative Links. Let us rewrite
the same paragraph below and see the difference.

Plus I only need to update link in one place for relative links. 

[1]: https://github.com/dharmit009 "Github"
[2]: https://twitch.com/
[3]: https://www.youtube.com/

```

Tags: 

    #markdown #commonmark #links #relativelinks
