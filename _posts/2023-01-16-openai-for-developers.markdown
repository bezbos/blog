---
layout: post
title:  "ChatGPT for Developers"
date:   2023-01-06 20:00:00 +0200
categories: openai
---
#### Available on YouTube:
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/nJ5hJgKcXFQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{% include heading2.html text="1. Introduction" fragment="introduction" %}
Welcome to my ChatGPT guide for developers, where I’m going to explain to you what ChatGPT is, how it works and how you can practically use it. In this guide I will show you how to practically use ChatGPT as a developer.

ChatGPT is an AI powered tool that can help you unlock your imagination and boost your productivity. It has the ability to understand human text which allows us to ask it questions and receive accurate and relevant responses.

![ChatGPT is an AI powered tool which boosts productivity, understands human text, generates answers and relevant responses.](/assets/openai/chatgpt_openai_tool.webp)

ChatGPT is an important technology that is quickly becoming a vital tool in many industries. Its ability to understand and generate human-like text is making it an increasingly popular choice for tasks such as customer service, creative writing, and content generation.

As a matter of fact ChatGPT is already being used for copywriting, blogging, generating product descriptions, writing code, writing documentation, data analysis, and so on.

![ChatGPT is already being used for copywriting, blogging, generating product descriptions, writing code, writing documentation, data analysis, and so on.](/assets/openai/chatgpt_openai_tool_usecases.webp)

As more and more businesses and organizations adopt ChatGPT, it is becoming an essential skill for professionals in many fields. Understanding how to use ChatGPT and fine-tune it for specific tasks can give you a competitive edge in the job market and open up new opportunities.

Additionally, ChatGPT is continuously improving, with new and advanced capabilities being added regularly. Keeping up with the latest developments and learning how to use them can help you stay ahead of the curve and stay relevant in your field.

As a testament to its importance, ChatGPT exploded in popularity the moment it was released. Popular indexes have recorded that ChatGPT gathered 1 million users in just about 5 days since launch, which is mindblowing! In comparison, it took Instagram about 75 days to gather that many users, or Spotify which took about 150 days to get to 1 million users. The Google search index for ChatGPT has also skyrocketed and the number of Reddit subscribers on r/chatgpt has grown by over 10 thousand in just about 7 days which is incredible for a reddit board.

![ChatGPT gathered 1 million users in just 5 days!](/assets/openai/chatgpt_dataviz_popularity_index_chart.webp)

ChatGPT is based on the Generative Pre-training Transformer 3, or just GPT-3. It uses many of the same techniques and technologies as GPT-3 and it has about 175 billion parameters. The GPT-3 model was trained on a colossal dataset gathered from the internet, which allows it to learn patterns and relationships in human language. ChatGPT uses this pre-trained knowledge to generate human-like responses when given a prompt.

![GPT-3 language model was built on a colossal data set scraped from the internet, has about 175 billion parameters and has the ability to recognize human language patterns and relationships.](/assets/openai/gpt3_language_model.webp)

The key difference between ChatGPT and GPT-3 is that ChatGPT is fine-tuned on specific-tasks, such as answering questions or generating data, code and other types of writing. This fine-tuning allows ChatGPT to generate more accurate and relevant responses for specific tasks.

At the moment of this recording, ChatGPT has been trained on data up until 2021, so most of the information that has appeared on the internet after 2021 is not available to ChatGPT, although there may be edge cases.

![ChatGPT is based on GPT-3 model architecture and is fine tuned on specific tasks for answering questions, generating data, generating code, etc. It's been trained on data up unit 2021.](/assets/openai/chatgpt_based_on_gpt3_with_fine_tuning.webp)

Keep in mind that despite being a revolutionary tool, ChatGPT is not perfect. Sometimes it will respond with reasonable-sounding, but incorrect answers. Oftentimes the answers it provides will look reasonable but they won’t provide any value. It’s also sensitive to input phrasing, meaning that for some questions it may claim to not know the answer, but after slight rephrasing it will give you an anwer.

ChatGPT is also sometimes biased and might flat out refuse to answer your question if it deems it to be offensive to certain groups of people or you’re asking it to provide you with harmful instructions. You will also notice that it often reuses the same phrases, explaining how it’s a language model trained by OpenAI.

![ChatGPT known issues are: reasonable sounding but incorrect answers, occasinally provides useless answers, sensitive to input phrasing, biased, refuses to answer questions with harmful instructions, often reuses same phrases explaining it's an OpenAI model.](/assets/openai/chatgpt_know_issues.webp)

ChatGPT is often compared with Google, however this is not a fair comparison since ChatGPT is only a text-based AI interpreter capable of human-like communication and it cannot actually access the internet. It also cannot tell you where it learned its information from, so if you ask it to tell you the source of the information, it won’t be able to. On the other hand, Google is a search engine associated with various other services that allow you to do reverse image search, see the information source, validate information against other sources, utilizes SEO optimization to provide relevant information, can tell you the time and the weather, and so on.

![ChatGPT is not a Google replacement and it's an unfair comparison.](/assets/openai/chatgpt_is_not_a_google_replacement.webp)

So ChatGPT is not a replacement for Google, since it works completely differently and serves a different purpose. Also ChatGPT is highly unlikley to remain free in the future because the costs of running it are eyewatering, while Google likely costs a mere fraction of that cost to run it’s services.

![ChatGPT generates text, data and answers questions. It is exclusively a text-based AI interpreter capable of human communication, trained on web scraped data. It cannot access the internet, it cannot tell you information sources, extremely expensive to host and it's highly unlikely to remain free. Google has text, voice and image search. Provides various services like cloud storage, email, maps, photo sync, play store, etc. Continuosly updated search index with most recent information. Tells you information sources. It probably costs just a fraction of the ChatGPT costs (if comparing them on the same scale). It will remain free (probably forever).](/assets/openai/chatgpt_vs_google.webp)

Getting started with ChatGPT is very easy. Simply go to **<a href="https://chat.openai.com/">chat.openai.com</a>** and sign-up for an account. You can use your existing Google or Microsoft accounts as well. Once you login you can start writing prompts.

{% include heading2.html text="2. Writing Prompts" fragment="writing-prompts" %}
{% include heading3.html text="2.1 Word Counter" fragment="word-counter" %}
Let’s start with something simple:
>Generate a Java method that counts word occurrences in a string.

I’m going to take this code and paste it to IntelliJ. Create a new class `WordCounter`, paste the code. Back in the `main` method, I’m going to print out the results:
{% highlight java %}
wordCount.forEach((k, v) -> System.out.printf("%8s: %2d\n", k, v));
{% endhighlight %}

And we got the words counted!

{% include heading3.html text="2.2 Simple HTTP Client" fragment="simple-http-client" %}
We can also ask it to generate code for sending HTTP requests:
>Generate code for sending HTTP requests in Java using the built-in Java HTTP client.

As you can see it generated a very basic method for sending HTTP requests. However this client is too simply and it wouldn't prove very practical. 

We can rephrase our request and provide additional information and ChatGPT will generate a better solution:
>Generate Java code for sending HTTP requests. I want you to name the class CustomHttpClient and I want it to have a method for sending GET, POST, PUT and DELETE requests. Make sure to use the legacy HTTP classes for sending these requests. Also make sure that request and response body is encoded as UTF-8.

Now this will generate a better HTTP client, but ChatGPT may stop halfway with the answer. If this happens, simply tell it to continue:
>continue
 
Now that it finished, we have a much better HTTP client. Let’s test it out. I’m going to create the class `CustomHttpClient` and copy/paste the code from ChatGPT. Then in the main method I will call the HTTP client methods. I will send HTTP requests to the popular **<a href="https://jsonplaceholder.typicode.com/">jsonplaceholder.typicode.com</a>**:
{% highlight java %}
var http = new CustomHttpClient();
http.sendGet("https://jsonplaceholder.typicode.com/posts/1");
http.sendPost("https://jsonplaceholder.typicode.com/posts", """
        {
          "userId": 1,
          "id": 1,
          "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
          "body": "quia et suscipitsuscipit recusandae consequuntur expedita et cumreprehenderit molestiae ut ut quas totamnostrum rerum est autem sunt rem eveniet architecto"
        }
        """);
http.sendPut("https://jsonplaceholder.typicode.com/posts/1", """
        {
          "userId": 1,
          "id": 1,
          "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
          "body": "quia et suscipitsuscipit recusandae consequuntur expedita et cumreprehenderit molestiae ut ut quas totamnostrum rerum est autem sunt rem eveniet architecto"
        }
        """);
http.sendDelete("https://jsonplaceholder.typicode.com/posts/1");
{% endhighlight %}

Alright, so that works nicely! 

{% include heading3.html text="2.3 Unit Tests" fragment="unit-tests" %}
We should definitely write unit-tests for our new HTTP client. Let’s ask ChatGPT to do it for us:
>Can you write me unit tests for the previously generate HTTP client?

So it wrote some basic unit tests. Let’s add them to our code. Open the tests directory and add a new class `CustomHttpClientTest`. Paste the generated code. 

Hmm, our project doesn’t seem to the JUnit dependency. Since this is a Maven project I need to go to pom.xml and add the JUnit dependency. Let’s ask ChatGPT to generate the dependency snippet for us:
>Generate me the snippet for adding the JUnit dependency to my Maven project.

Nice! So I’m just going to add this to my pom.xml file and refresh Maven. And there we go, that fixed the issue. Now let’s run the unit tests.

Our tests are failing because the test API returned a different response. So I’m just going to place a breakpoint on our GET test and see what the response is and copy that and make sure that we’re comparing against that string.

Run again... and it seems to work now. To be fair, ChatGPT could not have known what kind of response would be returned so it tried its best guess. It’s a mistake anyone could have made.

{% include heading3.html text="2.4 PlantUML Diagrams" fragment="plantuml-diagrams" %}
Now I would like to write documentation for my `CustomHttpClient`. I want to create a sequence diagram explaining how it works. I can ask ChatGPT to do that for me:
>Generate me a PlantUML code that explains how the CustomHttpClient works by using a sequence diagram with examples.

If ChatGPT stops, make sure to tell it to continue:
>continue

Very nice! You can visualize the diagram by giving the PUML markup to a PlantUML interpreter. For example you can try **<a href="https://plantuml-editor.kkeisuke.dev/">plantuml-editor.kkeisuke.dev</a>**.

Now that we have the diagram, I would also like to have some written documentation with examples:
>Generate documentation for the CustomHttpClient with pretty formatting and examples.

Now isn’t that incredible!

{% include heading3.html text="2.5 Programming Language Conversion" fragment="programming-language-conversion" %}
We can also ask ChatGPT to convert code from one language from another. Let’s convert our `CustomHttpClient` into C#:
>Convert the CustomHttpClient code into C#.

Very nice.

{% include heading3.html text="2.6 Generating Data" fragment="generating-data" %}
Other than ask ChatGPT to generate code and documentation for us, we can also ask it to generate data:
>Generate me a CSV table with belivable data with the following format:
ID, FirstName, LastName, BirthDate, Country, Address, Average Monthly Spending, Occupation

{% include heading3.html text="2.7 Data Format Conversion" fragment="data-format-conversion" %}
We can ask it to convert this data into a different format, for example JSON:
>Convert this example into JSON.

{% include heading3.html text="2.8 Data Summarization" fragment="data-summarization" %}
ChatGPT is also great at analyzing data. Let’s ask it to summarize some logs from the Linux kernel boot process:
>Summarize these logs:
>```
>[    0.295836] clocksource: Switched to clocksource tsc-early
>[    0.304043] VFS: Disk quotas dquot_6.6.0
>[    0.304056] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
>[    0.304154] AppArmor: AppArmor Filesystem Enabled
>[    0.304187] pnp: PnP ACPI init
>[    0.304483] system 00:00: [io  0x0290-0x029f] has been reserved
>[    0.304912] pnp 00:01: [dma 0 disabled]
>[    0.305238] system 00:02: [io  0x0680-0x069f] has been reserved
>[    0.305240] system 00:02: [io  0xffff] has been reserved
>[    0.305242] system 00:02: [io  0xffff] has been reserved
>[    0.305243] system 00:02: [io  0xffff] has been reserved
>[    0.305244] system 00:02: [io  0x1800-0x18fe] has been reserved
>[    0.305246] system 00:02: [io  0x164e-0x164f] has been reserved
>[    0.305343] system 00:03: [io  0x0800-0x087f] has been reserved
>[    0.305405] system 00:05: [io  0x1854-0x1857] has been reserved
>[    0.305796] system 00:06: [mem 0xfed10000-0xfed17fff] has been reserved
>[    0.305799] system 00:06: [mem 0xfed18000-0xfed18fff] has been reserved
>[    0.305800] system 00:06: [mem 0xfed19000-0xfed19fff] has been reserved
>[    0.305802] system 00:06: [mem 0xf8000000-0xfbffffff] has been reserved
>[    0.305803] system 00:06: [mem 0xfed20000-0xfed3ffff] has been reserved
>[    0.305805] system 00:06: [mem 0xfed90000-0xfed93fff] could not be reserved
>[    0.305806] system 00:06: [mem 0xfed45000-0xfed8ffff] has been reserved
>[    0.305808] system 00:06: [mem 0xff000000-0xffffffff] has been reserved
>[    0.305810] system 00:06: [mem 0xfee00000-0xfeefffff] could not be reserved
>[    0.305811] system 00:06: [mem 0xf7fc0000-0xf7fdffff] has been reserved
>[    0.305813] system 00:06: [mem 0xc7c00000-0xc7fffffe] has been reserved
>[    0.305861] system 00:07: [mem 0xfd000000-0xfdabffff] has been reserved
>[    0.305863] system 00:07: [mem 0xfdad0000-0xfdadffff] has been reserved
>[    0.305864] system 00:07: [mem 0xfdb00000-0xfdffffff] has been reserved
>[    0.305866] system 00:07: [mem 0xfe000000-0xfe01ffff] could not be reserved
>[    0.305867] system 00:07: [mem 0xfe036000-0xfe03bfff] has been reserved
>[    0.305869] system 00:07: [mem 0xfe03d000-0xfe3fffff] has been reserved
>[    0.305870] system 00:07: [mem 0xfe410000-0xfe7fffff] has been reserved
>[    0.306227] system 00:08: [io  0xfe00-0xfefe] has been reserved
>[    0.307851] system 00:09: [mem 0xfdaf0000-0xfdafffff] has been reserved
>[    0.307853] system 00:09: [mem 0xfdae0000-0xfdaeffff] has been reserved
>[    0.307854] system 00:09: [mem 0xfdac0000-0xfdacffff] has been reserved
>[    0.309088] pnp: PnP ACPI: found 10 devices
>[    0.314649] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
>[    0.314700] NET: Registered PF_INET protocol family
>[    0.314783] IP idents hash table entries: 131072 (order: 8, 1048576 bytes, linear)
>```

So as you can see it tries it's best to explain the data.

{% include heading3.html text="2.9 Explaining Code" fragment="explaining-code" %}
Let’s ask it to explain an SQL query:
>Explain this SQL query:
>```sql
>select row_number () over (order by value) as row_order,
>       value,
>       avg(value) over w1 as avg_rows,
>       avg(value) over w2 as avg_groups,
>       avg(value) over w3 as avg_range
>from   t1
>window w1 as (order by value rows between 1 preceding and current row),
>       w2 as (order by value groups between 1 preceding and current row),
>       w3 as (order by value range between 1 preceding and current row);
>```

And we get a very nice explanation here.

{% include heading3.html text="2.10 Generating a Landing Page" fragment="generating-a-landing-page" %}
Most of these examples have been back-end related. Let’s see some front-end action with ChatGPT. I’m going to ask it to generate a landing page for a company that sells software development services:
>Generate HTML for a landing page for a company named "bezbos." that sells software development services. Use Bootstrap for styling.

Since there is a lot of code that needs to be generated, ChatGPT will stop quite a few times. Just make sure to tell it to continue:
>continue 

You can also try telling it to continue without breaking formatting, but it's quite inconsistent:
>continue without breaking formatting

I’m going to create a file called “index.html” and copy/paste code there. Open it in the browser, and look at that. We have a somewhat decent landing page. Of course you can rephrase your prompt to generate a better landing page and whatnot, but considering we haven’t written a single line of code, this is great!

{% include heading3.html text="2.11 Generating Copy" fragment="generating-copy" %}
Sometimes we have a template for a website but we don’t have the content. We can ask ChatGPT to generate it for us as well:
>Generate copy for a website of a company that sells software development services.

Very nice!

{% include heading3.html text="2.12 Open-source Development Advice" fragment="open-source-development-advice" %}
We can ask ChatGPT for advice on how to join an open-source project:
>How do I start contributing to Linux kernel development.

So as you can see, it gives us a step by step guide on how to get started.

{% include heading3.html text="2.13 Explaining Project Domains" fragment="explaining-project-domains" %}
We can also ask it to explain certain domains to us as software developers. Let’s say we’ve been tasked to make a fleet management application, but we don’t understand the domain. We can ask ChatGPT to explain it to us:
>I am a software developer. Can you explain to me the domain of fleet management.

{% include heading3.html text="2.14 Generating Technical Specifications" fragment="generating-technical-specifications" %}
We can ask it to generate a technical specification for this project:
>Generate me a technical specification for a fleet management web application.

{% include heading2.html text="3. Conclusion" fragment="conclusion" %}
I’ve shown you some examples of how you can practically apply ChatGPT as a software developer. It’s truly an amazing tool and it can help you become more productive.

However, keep in mind that **ChatGPT is not an oracle. It’s a tool that uses advanced sophisticated statistical algorithims on a colossal data set. You can use it for assistance, but you should never use it as a definitive solution to your problems**.